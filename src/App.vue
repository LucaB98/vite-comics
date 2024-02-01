
<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  name: 'Comics',
  components: { AppHeader, AppMain }
};
</script>

<template>
  <AppHeader />
  <AppMain />
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