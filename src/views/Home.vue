<template>
  <div>
    <Carousel />
    <v-container>
      <v-row>
        <v-col sm="12" md="2" xs="2" fluid class="nav">
          <PostsNav :routes="routes" />
        </v-col>
        <v-col sm="12" md="7" :xs="7" class="content">
          <v-sheet color="#efefef">
            <Content />
          </v-sheet>
        </v-col>

        <v-col sm="12" md="3" :xs="3" class="creators">
          <v-sheet color="#232323" class="creators-content">
            <CreatorsSidebar />
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import CreatorsSidebar from '@/components/CreatorsSidebar.vue';
import Carousel from '@/components/Carousel.vue';
import Content from '@/components/Content.vue';
import PostsNav from '@/components/PostsNav.vue';
export default {
  components: {
    Carousel,
    CreatorsSidebar,
    Content,
    PostsNav
  },
  data() {
    return {
      routes: this.$router.options.routes
    };
  }
};
</script>

<style></style>
