<template>
  <div id="Category">
    <nav-bar class="Category-nav">
      <div slot="left">left</div>
      <div slot="center">购物街</div>
      <div slot="right">right</div>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from "../../components/navbar/NavBar"

export default {
  name: "Category",
  components: {
    NavBar
  }
}
</script>

<style scoped>
.Category-nav {
  background-color: var(--color-tint);
  color: #fff;
}
</style>