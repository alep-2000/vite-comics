<script>
export default {

}
</script>

<template lang="">
    <div>
        <div class="container">
            <div class="sub-container">
                <ul>
                    <li>
                        <div>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital-Comics">
                            <span>DIGITAL COMICS</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="Dc-Merchandise">
                            <span>DC MERCHANDISE</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
                            <span>SUBSCRIPTION</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img id="locator" src="../assets/img/buy-comics-shop-locator.png" alt="Shop-Locator">
                            <span>COMIC SHOP LOCATOR</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="Power-Visa">
                            <span>DC POWER VISA</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
        <section class="background">
            <div class="options-list">
                <div class="flex">
                    <div>
                        <ul>
                            <li><strong>DC COMICS</strong></li>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <ul>
                            <li><strong>SHOP</strong></li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <ul>
                        <li><strong>DC</strong></li>
                        <li>Terms of Use</li>
                        <li>Privacy Policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                    <ul>
                        <li><strong>SITES</strong></li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                    <img src="../../public/dc-logo-bg.png" alt="Logo-BG">
                </div>
            </div>
        </section>
        <section class="back">
            <div class="options-list">
                <div class="flex">
                    <button>SIGN-UP NOW!</button>
                    <span>
                        FOLLOW US
                        <img src="../assets/img/footer-facebook.png" alt="Facebook">
                        <img src="../assets/img/footer-twitter.png" alt="Twitter">
                        <img src="../assets/img/footer-youtube.png" alt="Youtube">
                        <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                        <img src="../assets/img/footer-periscope.png" alt="Periscope">
                    </span>
                </div>
            </div>
        </section>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

.container {
    background-color: #027DEF;



    .sub-container {
        width: 60%;
        margin: 0 auto;

        li {
            display: inline-block;
            margin: 30px 5px 30px 0;

            div {
                margin-right: 2.5rem;

                img {
                    width: 35px;
                    margin: 8px;
                    vertical-align: middle;
                }

                #locator {
                    width: 25px;
                }

                span {
                    font-size: 10px;
                    color: white;
                }
            }
        }
    }

}

.background {
    width: 100%;
    background-image: url('../assets/img/footer-bg.jpg');

    .options-list {
        width: 60%;
        margin: 0 auto;
        position: relative;

        .flex {
            display: flex;

            ul {
                margin: 25px 15px 35px 0;
                padding: 15px 0 5px;
                list-style-type: $list_s_type;

                li {
                    padding-top: 5px;
                    font-size: 10px;
                    color: rgb(166, 163, 163);

                    strong {
                        font-size: 16px;
                        color: white;
                    }
                }
            }

            img {
                position: absolute;
                z-index: 1;
                right: 0%;
                top: 40%;
                transform: translate(-0%, -40%);
                width: 450px;
                object-fit: fill;

            }
        }
    }

}

.back {
    width: 100%;
    background-color: #303030;
    position: relative;
    z-index: 3;

    .options-list {
        width: 60%;
        margin: 0 auto;

        .flex {
            display: flex;
            justify-content: space-between;

            button {
                background-color: transparent;
                border: 1px solid #027DEF;
                padding: 8px;
                color: white;
                margin: 32px 0;
            }

            span {
                color: #027DEF;
                margin: 38px 0;
            }

            img {
                vertical-align: middle;
                width: 22px;
                margin: 0 5px;
            }
        }
    }
}
</style>