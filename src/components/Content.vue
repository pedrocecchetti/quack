<template>
  <div class="container">
    <Post v-for="post in posts" :key="post.id" :post="post" />
  </div>
</template>

<script>
import Post from '@/components/Post.vue';
export default {
  components: { Post },
  data() {
    return {
      posts: [
        {
          id: 1,
          title: 'Sejam Bem vindos a Nárnia',
          content: 'Aqui jaz o texto da publicacao',
          image:
            'https://images.unsplash.com/photo-1587058680684-e0a315822a84?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'
        },
        {
          id: 1,
          title: 'Sejam Bem vindos a Nárnia',
          content: 'Aqui jaz o texto da publicacao',
          image:
            'https://images.unsplash.com/photo-1587058680684-e0a315822a84?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'
        },
        {
          id: 1,
          title: 'Sejam Bem vindos a Nárnia',
          content: 'Aqui jaz o texto da publicacao',
          image:
            'https://images.unsplash.com/photo-1587058680684-e0a315822a84?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'
        },
        {
          id: 1,
          title: 'Sejam Bem vindos a Nárnia',
          content: 'Aqui jaz o texto da publicacao',
          image:
            'https://images.unsplash.com/photo-1587058680684-e0a315822a84?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=750&q=80'
        }
      ]
    };
  }
};
</script>

<style>
v-sheet {
  margin: 0;
}
</style>
