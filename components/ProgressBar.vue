<template>
  <div class="flex flex-row align-middle">
    <div class="flex flex-row m-2 p-2 content-center">
      <div class="bars w-12 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-1" v-bind:class="bar1"></div>
      <div class="bars w-12 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-1" v-bind:class="bar2"></div>
      <div class="bars w-12 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-1" v-bind:class="bar3"></div>
      <div class="bars w-12 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-1" v-bind:class="bar4"></div>
      <div class="bars w-12 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-1" v-bind:class="bar5"></div>
    </div>
    <div class="flex flex-row text-xl font-black text-green-900 pl-4 font-serif self-center">
      {{percent}}%
      <slot></slot>
    </div>
  </div>


</template>

<script>
export default {
  name: "ProgressBar",
  props: {
    percent: Number
  },
  computed: {
    bar1: function () {
      if (this.percent < 20) {
        return { "bg-green-400" : true }
      } else {
        return { "bg-green-800" : true }
      }
    },
    bar2: function () {
      if (this.percent < 40) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar3: function () {
      if (this.percent < 60) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar4: function () {
      if (this.percent < 80) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar5: function () {
      if (this.percent < 100) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    }
  }
}
</script>

<style scoped>
.bars {

}
</style>
