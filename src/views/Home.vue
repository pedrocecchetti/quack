<template>
  <div>
    <Carousel />
    <v-container>
      <v-row>
        <v-col :cols="2" class="nav">
          <h1>oi</h1>
        </v-col>
        <v-col sm="12" md="7" :xs="7" class="content">
          <v-sheet color="#ffabcd">
            <Content />
          </v-sheet>
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
import Content from '@/components/Content.vue';
export default {
  components: {
    Carousel,
    CreatorsSidebar,
    Content
  }
};
</script>

<style></style>
