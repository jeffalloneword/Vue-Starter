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
      header: "Edit the text box to change this!"
    };
  }
};
</script>

<style scoped>
input {
  width: 80%;
  max-width: 300px;
}
</style>