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
    <h1>Home page</h1>
  </div>
</template>

<style lang="scss" scoped>

</style>
