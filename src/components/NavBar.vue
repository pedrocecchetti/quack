<template>
  <v-app-bar class="navbar" app dark>
    <div class="d-flex align-left">
      <v-btn :to="{ name: 'Home' }" text x-large fab>Quack</v-btn>
    </div>

    <v-spacer></v-spacer>
    <v-btn text :to="{ name: 'Home' }">Home</v-btn>
    <v-btn disabled text>Posts Recentes </v-btn>
    <v-btn text :to="{ name: 'Creators' }">
      Criadores
      <v-icon>mdi-account-multiple</v-icon>
    </v-btn>
    <v-btn href="https://youtube.com/c/quackbr" text target="_blank">
      Nosso Canal
      <v-icon>mdi-youtube</v-icon>
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {};
</script>
