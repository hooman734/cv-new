<template>
  <div class="flex flex-row align-middle">
    <div class="flex flex-row m-2 p-2 content-center">
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar1"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar2"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar3"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar4"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar5"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar6"></div>
      <div class="bars w-8 h-3 border-solid rounded-tl-3xl rounded-br-3xl mr-0.5" v-bind:class="bar7"></div>
    </div>
    <div class="flex flex-row font-black text-green-900 pl-1 md:pl-4 self-center">
<!--      {{percent}}%-->
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
      if (this.percent < 15) {
        return { "bg-green-400" : true }
      } else {
        return { "bg-green-800" : true }
      }
    },
    bar2: function () {
      if (this.percent < 29) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar3: function () {
      if (this.percent < 43) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar4: function () {
      if (this.percent < 58) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar5: function () {
      if (this.percent < 72) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar6: function () {
      if (this.percent < 86) {
        return "bg-green-400"
      } else {
        return "bg-green-800"
      }
    },
    bar7: function () {
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
