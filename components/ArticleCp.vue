<template>
<div class="container border-2 rounded-3xl md:w-1/3 xl:w-1/4 h-auto p-3 m-3">
  <div class="flex flex-col flex-wrap">
    <a target="_blank" v-bind:href="link">
      <p class="font-bold font-sans">{{topic}}</p>
      <p class="text-xs text-gray-400 mb-2.5">{{date}}</p>
      <p class="text-justify text-sm">{{description}}</p>
    </a>
     </div>
</div>
</template>

<script>
export default {
  name: "Article",
  props: {
    topic: String,
    date: String,
    link : String,
    description: String
  }
}
</script>

<style scoped>

</style>
