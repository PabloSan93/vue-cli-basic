<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Banner/>
  </div>
</template>

<script>
// @ is an alias to /src
import Banner from '@/components/general/Banner.vue';

export default {
  name: 'Contact',
  components: {
    Banner,
  },
};
</script>
