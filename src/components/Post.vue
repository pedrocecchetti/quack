<template>
  <v-card class="post">
    <v-card-title outline>{{ post.title }} </v-card-title>
    <v-img :src="post.image" alt="IMAGEM DO POST" />
    <v-card-text>
      {{ post.content }}
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  props: {
    post: {
      type: Object,
      required: true
    }
  }
};
</script>

<style>
.post {
  margin-bottom: 3%;
}
</style>
