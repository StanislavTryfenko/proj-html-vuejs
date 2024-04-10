<script>
export default {
    name: 'FooterJumbotron'
}
</script>

<template>

    <div class="jumbotron">
        <div class="container">
            <div class="left">
                <h3>Building Inspiring Spaces</h3>
                <hr>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Necessitatibus quis eligendi ipsum
                    maximetemporibus, cumque voluptas voluptatum quae libero iure.</p>
            </div>

            <div class="right">
                <button class="quote">GET A FREE QUOTE</button>
                <h5>Only Takes a few seconds!</h5>
            </div>
        </div>
    </div>

</template>

<style scoped>
.jumbotron {
    height: 428px;
    width: 1913px;
    background-image: url(../../../public/img/footer_jumbotron_background.jpg);
    background-size: 1913px 428px;
    background-repeat: no-repeat;

    .container {
        width: 1164px;
        height: 100%;
        margin: 0 auto;
        display: flex;

        .left {
            h3 {
                font-size: 32px;
                font-weight: 400;
                margin-top: 150px;
                color: #ffffff;
            }

            hr {
                background-color: #FED03D;
                width: 200px;
                margin: 36px 0;
            }

            p {
                font-size: 16px;
                width: 760px;
                color: #ffffff;
                margin: 0 auto;
            }
        }

        .right {
            justify-self: ;
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-left: 200px;
            gap: 20px;

            .quote {
                font-size: 15px;
                border: none;
                background-color: #fed03d;
                padding: 15px 32px;
                color: #333333;
            }

            .quote:hover {
                color: #ffffff;
                background-color: #333333;
            }

            h5{
                color: #ffffff;
                font-weight: 500;
                text-align: center;
            }
        }
    }
}
</style>