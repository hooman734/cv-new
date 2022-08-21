<template>
    <div ref="body2" class="ml-2 md:ml-9">
        <div class="flex flex-row flex-wrap justify-between">
        <p class="text-green-900 font-bold">
            <font-awesome-icon class="text-xs" icon="dot-circle"/>
            {{topic}}
        </p>
        <p class="text-green-900 font-bold">{{date}}</p>
        </div>
        <div class="border-l-4 pl-5 pb-4 text-justify break-all">
        <p class="text-gray-400 text-sm mb-1.5">{{subTopic}}</p>
        <p class="">{{description1}}</p>
        <p class="">{{description2}}</p>
        </div>
        <ul class="list-inside list-disc">
            <li v-for="(item, idx) in items" :key="idx">{{item}}</li>
        </ul>
    </div>
</template>

<script>
export default {
  name: "Experience",
  props: {
    topic: String,
    subTopic: String,
    description1: String,
    description2: String,
    items: Array,
    date: String,
  },
};
</script>
