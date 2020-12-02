<template>
  <div class="" id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>
<script>
import "tailwindcss/tailwind.css";
export default {
  name: "App"
};
</script>
<style lang="scss">
body {
  @apply w-full h-full bg-gray-400;
}

#nav {
  @apply bg-blue-800;
}
</style>
