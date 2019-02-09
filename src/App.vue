<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Todo App</span>
        <span class="font-weight-light">-- Vue 3.0</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://github.com/byoung730" target="_blank">
        <span class="mr-2">My Github</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import Todo from "./components/Todo";

export default {
  name: "App",
  components: {
    Todo
  }
};
</script>
