<script setup>

</script>

<template>
    <nav class="navbar">
        <ul class="navbar__list">
            <li class="navbar__list-item">
                <NuxtLink to="/"> About </NuxtLink>
            </li>
            <li class="navbar__list-item">
                <NuxtLink to="/"> Resume </NuxtLink>
            </li>
            <li class="navbar__list-item">
                <NuxtLink to="/"> Portfolio </NuxtLink>
            </li>
            <li class="navbar__list-item">
                <NuxtLink to="/"> Github </NuxtLink>
            </li>
        </ul>
    </nav>    
</template>

<style lang="scss">
.navbar {
    background: white;
    display: inline-block;
    padding: 10px;
    position: absolute;
    left: auto;
    top: 0;
    right: 0;
    border-radius: 0 20px 0 20px;
    padding: 20px 40px;
    background: rgba(43, 43, 44, .75);
    backdrop-filter: blur(10px);
    border: 1px solid #383838;
    &__list {
        display: flex;
        gap: 50px;

        & a {
            color: white;
        }
    }
}
</style>
