<script>
export default {
    name: 'AppCardMain',
    props: {
        thumb: String,
        price: String,
        series: String,
        type: String
    }

};
</script>

<template>
    <div class="cards">
        <div class="thumb"><img :src="thumb" :alt="series"></div>
        <h3>{{ series }}</h3>
    </div>
</template>

<style scoped>
.cards {
    padding: 10px;
}

.thumb {
    width: 160px;
    height: 160px;
}

img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center top;
    margin: 10px 0;
}
</style>