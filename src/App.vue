
<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooterUp from './components/AppFooterUp.vue';
import AppFooterDown from './components/AppFooterDown.vue';

export default {
  name: 'Comics',
  components: { AppHeader, AppMain, AppFooterUp, AppFooterDown }
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooterUp />
  <AppFooterDown />
</template>

<style>
/* reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* generics */

img {
  max-width: 100%;
  height: auto;
}

a {
  color: black;
  text-decoration: none;
}

body {
  min-height: 100vh;
  background-color: black;
  color: white;
  font-family: 'Open Sans', sans-serif;
}

/* utils */

.container {
  margin: 0 auto;
  max-width: 1200px;

}

.flex {
  display: flex;
}
</style>