<template>
  <div>
<<<<<<< HEAD
    <ul id="link-list">
=======
    <ul class="uau">
>>>>>>> da628b017ff63a8516311631821ce7bfd0baff1f
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

<<<<<<< HEAD
<style scoped>
#link-list {
  list-style-type: none;
  margin-bottom: 5%;
  padding-left: 0;
=======
<style>
.uat {
  margin: 0%;
  padding: 0%;
}

ul {
  list-style-type: none;
  margin-bottom: 5%;
  padding: 0%;
>>>>>>> da628b017ff63a8516311631821ce7bfd0baff1f
  align-items: left;
  text-align: left;
}
</style>
