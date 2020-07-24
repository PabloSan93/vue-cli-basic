<template>
  <div id="app">
    <TopMenu/>
    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
import TopMenu from '@/components/general/TopMenu.vue';

export default {
  name: 'Global',
  components: {
    TopMenu,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Blinker;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
