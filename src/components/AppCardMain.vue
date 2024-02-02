<script>
export default {
    name: 'AppCardMain',
    promp: {
        thumb: String,
        price: String,
        series: String,
        type: String
    }

};
</script>

<template>
    <div class="cards">
        <img :src="thumb" :alt="series">
        <h3>{{ series }}</h3>
    </div>
</template>

<style scoped>
.cards {
    padding: 20px;
}

img {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 10px 0;
}
</style>