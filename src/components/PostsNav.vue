<template>
  <div>
    <ul id="link-list">
      <li v-for="route in routes" :key="route.path">
        <v-btn v-if="route.component" text>{{ route.name }}</v-btn>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {
    routes: {
      type: Array,
      required: true
    }
  }
};
</script>

<style scoped>
#link-list {
  list-style-type: none;
  margin-bottom: 5%;
  padding-left: 0;
  align-items: left;
  text-align: left;
}
</style>
