<template>
<div class="container rounded-3xl h-auto w-max md:w-1/3 xl:w-1/4 h-auto p-3 m-3">
  <div class="flex flex-col flex-wrap">
    <a target="_blank" v-bind:href="link">
      <p class="font-bold font-sans">{{topic}}</p>
      <p class="text-xs text-gray-400 mb-2.5">{{date}}</p>
      <div class="text-justify text-sm">
        <slot></slot>
      </div>
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
  }
}
</script>

<style scoped>

</style>
