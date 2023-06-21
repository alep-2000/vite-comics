<script>
export default {
    data() {
        return {
            links: [
                {
                    name: 'CHARACTERS'
                },
                {
                    name: 'COMICS'
                },
                {
                    name: 'MOVIES'
                },
                {
                    name: 'TV'
                },
                {
                    name: 'GAMES'
                },
                {
                    name: 'COLLECTIBLES'
                },
                {
                    name: 'VIDEOS'
                },
                {
                    name: 'FANS'
                },
                {
                    name: 'NEWS'
                },
                {
                    name: 'SHOP'
                },
            ]
        }
    }

}
</script>

<template lang="">
    <div>
        <header>
            <div class="flex">
                <div>
                    <img src="../../public/dc-logo.png" alt="Logo-bg">
                </div>
                <div>
                    <ul>
                        <li v-for="(link,index) in links" :key="index"><a href="#"> {{link.name}} </a></li>
                    </ul>
                </div>
            </div>
        </header>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/./partials/variables' as *;

header {
    width: 100%;
    background-color: white;

    .flex {
        display: flex;
        justify-content: space-between;
        width: 60%;
        margin: 0 auto;

        img {
            width: 60px;
            margin: 10px 0;
        }

        ul {

            li {
                display: inline-block;
                margin: 5px;
                font-size: 10px;
                margin: 35px 5px;

                a {
                    text-decoration: $text_decoration;
                    color: black;

                    &:hover {
                        color: $blue;
                        border-bottom: 3px solid $blue;
                        padding-bottom: 35px;
                    }
                }
            }
        }
    }
}
</style>