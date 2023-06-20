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
                            <img src="../img/buy-comics-digital-comics.png" alt="Digital-Comics">
                            <span>DIGITAL COMICS</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../img/buy-comics-merchandise.png" alt="Dc-Merchandise">
                            <span>DC MERCHANDISE</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../img/buy-comics-subscriptions.png" alt="Subscription">
                            <span>SUBSCRIPTION</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img id="locator" src="../img/buy-comics-shop-locator.png" alt="Shop-Locator">
                            <span>COMIC SHOP LOCATOR</span>
                        </div>
                    </li>
                    <li>
                        <div>
                            <img src="../img/buy-dc-power-visa.svg" alt="Power-Visa">
                            <span>DC POWER VISA</span>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
        <section>
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
            <div>
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
            </div>
            <div>
                <li><strong>SITES</strong></li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </div>
        </section>
        <section>
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div>
                <span>
                    FOLLOW US
                </span>
                <span>
                    <img src="../img/footer-facebook.png" alt="Facebook">
                    <img src="../img/footer-twitter.png" alt="Twitter">
                    <img src="../img/footer-youtube.png" alt="Youtube">
                    <img src="../img/footer-pinterest.png" alt="Pinterest">
                    <img src="../img/footer-periscope.png" alt="Periscope">
                </span>
            </div>
        </section>
    </div>
</template>

<style lang="scss">
@use '../styles/partials/variables' as *;

.container {
    background-color: #027DEF;

    .sub-container {
        width: 60%;
        height: 100px;
        margin: 0 auto;

        li {
            display: inline-block;
            margin-right: 5px;
            margin-top: 20px;

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
</style>