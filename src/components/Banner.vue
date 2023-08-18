<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner"
}
</script>

<style scoped>

  #main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -450px;
    background-size: cover;
    display: flex;
    height: 400px;
    align-items: center;
    justify-content: flex-start;
  }

</style>