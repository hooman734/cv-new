<template>
  <div class="container mx-auto my-auto">
    <div class="flex flex-row flex-wrap justify-items-center mt-6 md:mt-20">
      <div class="flex-initial mx-4 border-4 ">
        <photo></photo>
      </div>
      <div class="flex flex-1 mx-4 border-4 justify-center">
        <name class="self-end"></name>
      </div>
    </div>
<!--    -->
    <div class="flex flex-row flex-wrap justify-items-center mt-6 md:mt-20">
      <div class="flex-initial mx-4 border-4 ">
        <side-panel></side-panel>
      </div>
      <div class="flex-1 mx-4 border-4">
        <main-panel></main-panel>
      </div>
    </div>
  </div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
