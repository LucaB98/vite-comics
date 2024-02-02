
<script>
import AppJumbo from './AppJumbo.vue';
import AppCardMain from './AppCardMain.vue';


export default {
    name: 'AppMain',
    components: { AppJumbo, AppCardMain, AppCardMain },
    props: {
        comics: Array,
    }
};
</script>

<template>
    <main id="main">
        <AppJumbo />
        <div class="container">
            <a href="#" class="title-series bg-blue">CURRENT SERIES</a>
        </div>
        <div class="container card-container">
            <AppCardMain v-for="comic in comics" :key="comic.id" v-bind="comic" />
        </div>
        <div class="container load-more">
            <a href="#" class="bg-blue btn-load">LOAD MORE</a>
        </div>
    </main>
</template>

<style scoped>
.card-container {
    display: flex;
    flex-wrap: wrap;
}

.bg-blue {
    background-color: #0C7CEC;
    color: white;
}

.title-series {
    padding: 10px;
    font-size: 25px;

    position: relative;
    bottom: 15px;
}

.load-more {
    display: flex;
    justify-content: center;
    margin: 20px auto;
    font-size: 12px;
}

.btn-load {
    padding: 10px 40px;
}

.cards {
    flex-basis: calc(100% / 6);

}
</style>