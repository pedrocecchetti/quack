<template>
  <div>
    <Carousel />
    <v-container>
      <v-row>
        <v-col :cols="2" class="nav">
          <h1>oi</h1>
        </v-col>
        <v-col :cols="6" class="content">
          <h1>oi2</h1>
        </v-col>

        <v-col :cols="4" class="creators">
          <h1><CreatorsSidebar /></h1>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import CreatorsSidebar from '@/components/CreatorsSidebar.vue';
import Carousel from '@/components/Carousel.vue';
export default {
  components: {
    Carousel,
    CreatorsSidebar
  }
};
</script>

<style>
.creators {
  background: #232323;
  border-radius: 20px;
}
</style>
