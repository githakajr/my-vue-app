<template>
  <div class="my-component">
    <h1>{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: 'MyComponent',
  data() {
    return {
      message: 'Single-File Components In Vue.js'
    };
  }
};
</script>

<style scoped>
.my-component {
  text-align: center;
  color: #42b983;
}
</style>
