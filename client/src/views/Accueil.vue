<template>
  <div class="home">
    <div class="flex justify-center h-60">
      <img alt="Vue logo" src="../assets/logo.png" />
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
  methods: {},
};
</script>
