<template>
  <div id="app">
    <NavBar />
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";
import Index from "@/components/Index";

export default {
  name: "App",
  components: {
    NavBar
    Index
  }
};
</script>

<style>
.navbar nav {
  padding: 0 20px;
}
</style>
