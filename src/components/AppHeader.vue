<script>
export default {
    name: 'AppHeader'
}
</script>


<template>
    <header>

        <nav class="container">

            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>

            <ul class="main_menu">
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
.container {
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: space-around;


    & .main_menu {
        list-style: none;
        display: flex;
        gap: 50px;
    }

    & .logo {
        padding-top: 20px;
        padding-bottom: 20px;
    }

    & a {
        text-decoration: none;
        color: black;
        font-size: 12px;
        padding: 2rem 0;

    }


    & a:hover {
        border-bottom: 4px solid var(--soft-blue);
        color: var(--soft-blue);
    }


}
</style>