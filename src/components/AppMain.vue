
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
        <div class="container card-container">
            <AppCardMain v-for="comic in comics" :key="comic.id" v-bind="comic" />
        </div>
    </main>
</template>

<style scoped>
.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 2rem;
}

.cards {
    flex-basis: calc(100% / 6);

}
</style>