<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <button class="btn btn-primary" @click="goToDaybook">Primary</button
    ><button class="btn btn-secondary" @click="goToDaybook">Secondary</button
    ><button class="btn btn-success" @click="goToDaybook">Success</button>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  methods: {
    goToDaybook() {
      this.$router.push({ name: "no-entry" });
    },
  },
};
</script>
