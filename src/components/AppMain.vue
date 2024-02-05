<script>
import AppJumbotron from './AppJumbotron.vue';
import AppComicsList from './AppComicsList.vue';

export default {
    name: 'AppMain',
    components: {
        AppJumbotron,
        AppComicsList
    },
    data() {
        return {

        }
    }

}
</script>


<template>
    <main>
        <AppJumbotron></AppJumbotron>
        <AppComicsList></AppComicsList>

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
.buy_space {
    background-color: var(--soft-blue);
    height: 150px;
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