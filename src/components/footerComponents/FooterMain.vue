<script>
export default {
    name: 'FooterMain'
}
</script>

<template>
    <div>
        <div class="container">
            <div class="row">
                <div class="card">
                    <img src="../../../public/img/footer_main_logo.png">
                    <p class="us">We are specialists in the cnstruction of uniques and exclusive propraties. Our work
                        inspires. We
                        pride ourselves on delivering outstanding quality and design for leading clients across the
                        world</p>
                    <button>LEARN MORE</button>
                </div>
                <div class="card">
                    <h4>LATEST TWEETS</h4>
                    <div class="theme_fusion">
                        <img class="rounded" src="../../../public/img/footer_main_logo_2.png">
                        <div>
                            <h3>ThemeFusion</h3>
                            <h5>@Theme_Fusion</h5>
                        </div>
                        <img class="twitter" src="../../../public/img/twitter.svg" alt="">
                    </div>
                    <p class="post">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam atque voluptates
                        numquam maxime enim cumque, eos inventore explicabo itaque laudantium ex iusto ducimus non
                        voluptatibus</p>
                    <img class="promo" src="../../../public/img/footer_promo.jpeg" alt="">
                </div>
                <div class="card">
                    <h4>CONTACT US TODAY</h4>
                    <ul>
                        <li>
                            <i class="fa-solid fa-globe"></i>
                            <div>
                                Corporate Location 1600 Amphitheatre Parkway London WC1 1BA
                            </div>
                        </li>
                        <li>
                            <i class="fa-solid fa-house"></i>
                            <div>
                                Residential Location 9521 Broadsberry Avenue Paddington RC7 9ZA
                            </div>
                        </li>
                        <li>
                            <i class="fa-solid fa-phone"></i>
                            <div>
                                1.800.458.556 / 1.800.532.2112
                            </div>
                        </li>
                        <li>
                            <i class="fa-solid fa-envelope"></i>
                            <div>
                                info@your-domain.com
                            </div>
                        </li>
                        <li>
                            <i class="fa-regular fa-clock"></i>
                            <div>
                                Monday - Friday: 9:00 AM - 6:00 PM
                            </div>
                        </li>
                        <li>
                            <i class="fa-regular fa-clock"></i>
                            <div>
                                Saturday - Sunday: 9:00 AM - 12:00 PM
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="card">
                    <h4>FIND US</h4>
                    <img class="map" src="../../../public/img/construction_map_pin.png-Notti">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    width: 1913px;
    height: 636px;
    background-color: #333333;
    padding-top: 75px;

    .row {
        width: 1632px;
        display: flex;
        justify-content: space-between;
        margin: 0 auto;

        .card {
            width: 396px;

            .theme_fusion {
                display: flex;

                h3 {
                    color: #ffffff;
                }

                h5 {
                    color: #ffffff;
                }

                .twitter {
                    aspect-ratio: 1;
                    width: 24px;
                    margin-left: 200px;
                }

                .rounded {
                    border-radius: 50%;
                    aspect-ratio: 1;
                    width: 32px;
                }
            }

            .post {
                color: #ffffff;
                font-weight: 200;
                margin-left: 28px;
            }

            .promo {
                width: 354px;
                margin-left: 24px;
            }

            h4 {
                font-size: 15px;
                color: #fed03d;
                font-weight: 600;
                margin-bottom: 24px;
            }

            .us {
                margin: 32px 0;
                line-height: 24px;
                font-size: 12px;
                color: gray;
            }

            button {
                font-size: 15px;
                border: none;
                background-color: #fed03d;
                padding: 15px 32px;
                color: #333333;
            }

            button:hover {
                color: #ffffff;
                background-color: #333333;
            }

            ul {
                list-style: none;

                li {
                    display: flex;
                    gap: 1rem;
                    padding-bottom: 1rem;
                    color: gray;
                }
            }

            .map{
                width: 330px;
                height: 277px;
            }
        }
    }
}
</style>