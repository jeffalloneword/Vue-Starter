<template>
  <div>
    <h1>{{ header }}</h1>
    <input type='text' v-model='header' />
  </div>
</template>

<script>
export default {
  name: "inputTest",
  data() {
    return {
      header: "Here's some Vue data!"
    };
  }
};
</script>
