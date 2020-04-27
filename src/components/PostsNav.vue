<template>
  <div>
    <ul class="uau">
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

<style>
.uat {
  margin: 0%;
  padding: 0%;
}

ul {
  list-style-type: none;
  margin-bottom: 5%;
  padding: 0%;
  align-items: left;
  text-align: left;
}
</style>
