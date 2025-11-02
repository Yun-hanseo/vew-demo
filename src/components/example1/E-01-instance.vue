<template>
  <div>Hello, {{ message }}</div>
</template>

<script>
export default {
  name: "E01Instance",
  data() {
    return {
      message: "Vue!"
    };
  }
};
</script>

<style scoped>
div {
  color: blue;
  font-weight: bold;
}
</style>
