<script setup>

</script>

<template>
    <div class="about">
        <h2 class="about__title"> About </h2>
        <section class="about__info">
            <p class="about__info-text">
                At the age of 16 I started studying web development, at first I was interested in making good money in this area, but as soon as I got to know development better, I fell in love with web development
            </p>
            <p class="about__info-text">
                I have been in development for 4 years, during which time I worked in various companies, worked in a training center, developed a platform with 2D games, a site for recruiting users, crm systems, telegram bots and simple express servers
            </p>
        </section>
    </div>
</template>

<style lang="scss">
.about {
    &__title {
        color: white;
        font-size: 35px;

        &::after {
            content: "";
            width: 120px;
            height: 5px;
            background: orange;
            border-radius: 5px;
            display: block;
            margin-top: 10px;
        }
    }

    &__info {
        margin-top: 20px;
        
        &-text {
            color: hsla(0, 0%, 84%, 0.7);
            line-height: 25px;

            &:not(:last-child) {
                margin-bottom: 20px;
            }
        }
    }
}
</style>