<script>
export default {
    name: 'AppComicCard',
    props: {
        thumb: String,
        title: String
    }

}
</script>


<template>
    <div class="card">
        <img :src="thumb" :alt="title + 'image'" alt="">
        <h5>{{ title }}</h5>
    </div>
</template>


<style scoped>
.card {

    &>img {
        aspect-ratio: 1;
        object-fit: cover;
        object-position: top;
    }
}
</style>