<script>
export default {
    name: 'Appheader',
}
</script>

<template>
    <header>
        <div class="logo">
            <img src="../../public/img/construction_logo.png" alt="avada logo">
        </div>

        <div class="nav">
            <a href="#" aria-disabled="true">HOME</a>
            <a href="#" aria-disabled="true">ABOUT</a>
            <a href="#" aria-disabled="true">SERVICES</a>
            <a href="#" aria-disabled="true">WORK</a>
            <a href="#" aria-disabled="true">ARTICLES</a>
            <button>GET QUOTE</button>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: #F5F5F5;
    height: 130px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .logo {
        margin-left: 100px;
    }

    .nav {
        margin-right: 100px;
        display: flex;
        gap: 45px;

        a {
            position: relative;
            font-size: 10px;
            align-self: center;
            text-decoration: none;
            color: #333333;
        }

        a:hover::before {
            content: '';
            position: absolute;
            top: 60px;
            left: 50%;
            transform: translateX(-50%);
            border-width: 6px 6px 0 6px;
            border-style: solid;
            border-color: #F5F5F5 transparent transparent transparent;
        }

        button {
            font-size: 10px;
            border: none;
            background-color: #fed03d;
            padding: 15px 25px;

        }

        button:hover {
            background-color: #333333;
            color: #F5F5F5;
        }
    }
}
</style>