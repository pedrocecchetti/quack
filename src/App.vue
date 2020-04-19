<template>
  <v-app>
    <NavBar />
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar.vue';
export default {
  name: 'App',

  components: { NavBar },

  data: () => ({
    //
  })
};
</script>

<style>
#app {
  font-family: 'Baloo Bhaina 2', cursive;
}
</style>
