<template>
  <v-container>
    <v-layout text-xs-center wrap>
      <v-flex xs12>
        <v-img :src="require('../assets/index.jpg')" class="my-3" contain height="200"></v-img>
      </v-flex>

      <v-flex mb-4>
        <h1 class="display-2 font-weight-bold mb-3">Welcome to Vuetify</h1>
        <p class="subheading font-weight-regular">Todo List</p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: "Todo",
  props: {
    Todos: Array
  }
};
</script>

<style></style>
