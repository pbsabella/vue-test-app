<script lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

import { defineComponent } from '@vue/composition-api';

export default defineComponent({
  name: 'Home',

  components: {
    HelloWorld,
  },
});
</script>

<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<style lang="scss" scoped>

</style>
