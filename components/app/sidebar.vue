<script setup>

</script>

<template>
    <aside class="sidebar">
        <div class="sidebar__info">
            <figure class="sidebar__info-avatar">
                <img src="@/assets/images/developer.png" alt="Ismail Kherkheulidze">
            </figure>

            <div class="sidebar__info-content">
                <h1 class="sidebar__info-name" title="Ismail Kherkheulidze"> Ismail Kherkheulidze </h1>
                <p class="sidebar__info-speciality"> Web Developer </p>
            </div>
        
            <ul class="sidebar__info-list">
                <li class="sidebar__info-item">
                    <div class="sidebar__info-icon">
                        <Icon name="material-symbols:mail-outline" />
                    </div>
                    <div class="sidebar__info-contact">
                        <p> Email </p>
                        <a href="mailto:ismailkherkheulidze@gmail.com" class="contact-link">ismailkherkheulidze@gmail.com</a>
                    </div>
                </li>
                <li class="sidebar__info-item">
                    <div class="sidebar__info-icon">
                        <Icon name="iconoir:github-circle" />
                    </div>
                    <div class="sidebar__info-contact">
                        <p> Github </p>
                        <a href="https://github.com/Ismail-1004" class="contact-link">Ismail-1004</a>
                    </div>
                </li>
                <li class="sidebar__info-item">
                    <div class="sidebar__info-icon">
                        <Icon name="material-symbols:location-on-outline" />
                    </div>
                    <div class="sidebar__info-contact">
                        <p> Location </p>
                        <a href="https://github.com/Ismail-1004" class="contact-link">Uzbekistan, Tashkent</a>
                    </div>
                </li>
            </ul>

            <ul class="sidebar__info-social">
                <li>
                    <a href="https://www.instagram.com/kherkheulidze_01/">
                        <Icon name="mdi:instagram" />
                    </a>
                </li>
                <li>
                    <a href="https://t.me/idev_01">
                        <Icon name="mdi:telegram" />
                    </a>
                </li>
            </ul>
        </div>
    </aside>    
</template>

<style lang="scss">
.sidebar {
    background: #1e1e1f;
    border: 1px solid #383838;
    border-radius: 20px;
    padding: 25px;

    &__info {
        display: flex;
        flex-direction: column;
        align-items: center;

        &-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            &::after {
                content: '';
                display: block;
                width: 100%;
                height: 1px;
                background: white;
                margin: 20px 0;
                border-radius: 5px;
            }
        }

        &-avatar {
            width: 200px;
            & img {
                width: 100%;
                border-radius: 10px;
            }
        }

        &-name {
            text-align: center;
            color: white;
            margin: 20px 0;
        }

        &-speciality {
            text-align: center;
            color: white;
            background: #22262a;
            display: inline-block;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        &-item {
            display: flex;
            align-items: center;
            gap: 20px;

            &:not(:last-child) {
                margin-bottom: 20px;
            }
        }

        &-icon {
            color: white;
            font-size: 25px;
        }

        &-contact {
            & p {
                color: hsla(0,0%,84%,.7);
                font-size: 18px;
                margin-bottom: 10px;
            }

            & a {
                color: white;
            }
        }

        &-social {
            display: flex;
            gap: 20px;
            margin-top: 20px;

            & a {
                font-size: 30px;
                color: white;
            }
        }
    }
}
</style>
