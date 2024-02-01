<script>
export default {
    name: 'AppFooter'
}
</script>


<template>
    <footer>
        <div class="dc_footer">

        </div>
        <div class="nav_footer">
            <button>SIGN-UP! NOW</button>
            <div class="follow">
                <h4>FOLLOW US</h4>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>

        </div>
    </footer>
</template>

<style scoped>
.dc_footer {
    min-height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);
}

.nav_footer {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100px;
    background-color: var(--soft-grey);
}

button {

    border-color: var(--soft-blue);
    background-color: transparent;
    color: white;
    width: 150px;
    height: 50px;
}

h4 {
    color: var(--soft-blue);
}

.follow {
    display: flex;
    align-items: center;
    gap: 20px;
}
</style>