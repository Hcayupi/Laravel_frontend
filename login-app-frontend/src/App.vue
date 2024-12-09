<script lang="ts">
import { defineComponent } from "vue";
import TheWelcome from "./components/TheWelcome.vue";

export default defineComponent({
  name: "App",
  components: {
    TheWelcome,
  },
  setup() {
    return {};
  },
});
</script>


<template>
  <header>
    <div id="app">
      <h1>¡Hola, Vue con TypeScript!</h1>
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
h1 {
  color: teal;
}
</style>
