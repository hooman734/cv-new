<template>
  <div>{{ topic }}</div>
  <div v-for="item in items">{{ item }}</div>
</template>

<script>
export default {
  name: "Skill",
  props: {
    topic: String,
    items: Array,
  },
};
</script>
