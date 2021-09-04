<template>
<div>
  <p>I'm a Counter! My value is {{ count }}</p>
  <button v-on:click="count -= 1">Decrease by 1</button>
  <button v-on:click="count += 1">Increase by 1</button>
</div>
</template>

<script>
export default {
  name: "App",
  data() {
    return { count: 0 };
  },
};
</script>

<style>
</style>

