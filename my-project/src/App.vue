<template>
  <h1>chào</h1>
  <h3>{{ title }}</h3>
  <button class="rounded-full p-3 border-inherit bg-slate-600 " @click="addNumber">+</button>
  <b class="font-bold">{{ count }}</b>
</template>

<script>
export default {
  data() {
    return {
      title: "Hello world", // added comma here
      count: 0,
    };
  },
  methods: { // corrected from methods() to methods:
    addNumber() {
      this.count--
    },
  },
};
</script>
