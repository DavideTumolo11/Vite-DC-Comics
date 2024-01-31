<script>
export default {
    name: 'AppMain'
}
</script>


<template>
    <main>
        <div class="components_space"> --Content goes here--</div>
        <div class="buy_space">
            <img class="img_buy" src="../assets/img/buy-comics-digital-comics.png" alt="">DIGITAL COMICS
            <img class="img_buy" src="../assets/img/buy-comics-merchandise.png" alt="">DC MERCHANDISE
            <img class="img_buy" src="../assets/img/buy-comics-subscriptions.png" alt="">SUBSCRIPTION
            <img class="img_buy" src="../assets/img/buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR
            <img class="img_buy" src="../assets/img/buy-dc-power-visa.svg" alt="">DC POWER VISA
        </div>
    </main>
</template>

<style scoped>
.components_space {
    background-color: var(--soft-black);
    height: 200px;
    color: white;
    display: flex;
    align-items: center;
    font-size: 30px;
    padding-left: 200px;
}

.buy_space {
    background-color: var(--soft-blue);
    height: 200px;
    display: flex;
    align-items: center;
    justify-content: center;
    justify-content: space-evenly;
    color: white;
}

.img_buy {
    height: 60px;

}
</style>