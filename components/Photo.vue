<template>
  <div class="image rounded-full h-60 w-60 xl:h-80 xl:w-80 flex items-center justify-center shadow-lg self-center p-6 transition duration-500 ease-in-out bg-blue-600 hover:bg-red-600 transform hover:-translate-y-1 hover:scale-110"></div>
</template>

<script>
export default {
  name: "Photo"
}
</script>

<style scoped>
.image {
  /*background-image: url("../assets/hooman.png");*/
  /*background-image: url("../assets/brad-pitt .jpg");*/
  background-image: url("../assets/hmn2.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
