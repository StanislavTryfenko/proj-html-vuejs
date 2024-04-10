<script>
export default {
    name: 'AppJumbotron',
}
</script>

<template>
    <div class="top">
        <h1>BUILDING INSPIRING SPACES</h1>
        <h3>We Build Inspiring Residential & Commercial Spaces</h3>
        <div class="buttons">
            <button class="explore">EXPLORE RECENT WORK</button>
            <button class="quote">GET A QUOTE TODAY</button>
        </div>
    </div>

    <div class="bottom">
        <h2>Do You Have A Constructor Project We Can Help With?</h2>
        <button>GET A FREE QUOTE</button>
    </div>
</template>

<style scoped>
.top {
    height: 850px;
    background-image: url(../../public/img/jumbotron_background.jpg);
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    gap: 40px;

    h1 {
        color: #ffffff;
        font-size: 48px;
    }

    h3 {
        color: #FED03D;
        font-size: 24px;
        font-weight: 200;
    }

    .buttons {
        display: flex;
        gap: 20px;

        .explore {
            font-size: 15px;
            border: none;
            background-color: #333333;
            padding: 15px 20px;
            color: #ffffff;
        }

        .explore:hover {
            color: #333333;
            background-color: #fed03d;
        }

        .quote {
            font-size: 15px;
            border: none;
            background-color: #fed03d;
            padding: 15px 20px;
            color: #333333;
        }

        .quote:hover {
            color: #ffffff;
            background-color: #333333;
        }
    }
}

.bottom {
    height: 160px;
    background-color: #FED03D;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;

    h2 {
        font-size: 24px;
        font-weight: 350;
    }

    button {
        position: absolute;
        bottom: -25px;
        font-size: 10px;
        padding: 15px 25px;
        font-size: 12px;
        background-color: #1f1f1f;
        color: #fed03d;
        border: none;
        outline: 4px solid #f5f5f5;
    }

    button:hover {
        background-color: #ffffff;
        outline: 2px solid #1f1f1f;
        color: #1f1f1f;
    }

}
</style>