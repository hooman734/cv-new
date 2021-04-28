<template>
  <div class="container mx-auto my-auto flex-wrap">
    <div class="flex flex-row flex-wrap justify-items-center mt-6 md:mt-20">
      <div class="flex-initial mx-4 md:mx-10 md:pl-10 lg:w-1/5">
        <photo></photo>
      </div>
      <div class="flex flex-1 mx-4 justify-center md:w-4/5">
        <name class="self-center"></name>
      </div>
    </div>
<!--    -->
    <div class="flex flex-row flex-wrap justify-items-center mt-6 md:mt-10">
      <div class="flex-initial mx-4 md:mx-10 lg:w-1/6">
        <side-panel></side-panel>
      </div>
      <div class="flex-1 w-screen mx-4 md:w-5/6">
        <main-panel></main-panel>
      </div>
    </div>
  </div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
