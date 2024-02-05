<script>
import AppComicCard from './AppComicCard.vue';
export default {
    name: 'AppComicsList',
    components: {
        AppComicCard
    },
    data() {
        return {
        }
    }
}

</script>


<template>
    <section class="comics">
        <div class="container">
            <h3>Current Series</h3>
            <div class="row">
                <div class="col-12 col-md-4 col-lg-2" v-for="comic in comics" :key="'index_' + comic.title">
                    <AppComicCard :title="comic.title" :thumb="comic.thumb"></AppComicCard>

                </div>
            </div>

            <div class="loadmore">
                <button>Load More</button>
            </div>
        </div>

    </section>
</template>

<style scoped>
.comics {
    background-color: var(--soft-black);
    color: white;


    & h3 {
        display: inline-block;
        padding: 20px 30px;
        background-color: var(--soft-blue);
        margin: -20px 30px 2px;
    }

    .loadmore {

        text-align: center;
        margin: 0 30px;

        & button {
            background-color: var(--soft-blue);
            color: white;
            padding: 15px 30px;
            border-style: none;
            margin-bottom: 30px;
            margin-left: 30px;
        }
    }
}
</style>