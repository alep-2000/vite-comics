<script>
export default {

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
                        <li><a href="#"> CHARACTERS </a></li>
                        <li><a href="#"> COMICS </a></li>
                        <li><a href="#"> MOVIES </a></li>
                        <li><a href="#"> TV </a></li>
                        <li><a href="#"> GAMES </a></li>
                        <li><a href="#"> COLLECTIBLES </a></li>
                        <li><a href="#"> VIDEOS </a></li>
                        <li><a href="#"> FANS </a></li>
                        <li><a href="#"> NEWS </a></li>
                        <li><a href="#"> SHOP </a></li>
                    </ul>
                </div>
            </div>
        </header>
    </div>
</template>

<style lang="scss">
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
                margin: 30px 5px;

                a {
                    text-decoration: $text_decoration;
                    color: black;

                    &:hover {
                        color: #0C7CEC;
                        border-bottom: 3px solid #0C7CEC;
                        padding-bottom: 40px;
                    }
                }
            }
        }
    }
}
</style>