<template>
  <div class="image rounded-full h-60 w-60 flex items-center justify-center shadow-lg self-center p-6"></div>
</template>

<script>
export default {
  name: "Photo"
}
</script>

<style scoped>
.image {
  background-image: url("../assets/hooman.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
