<template>
  <button>
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props: ["text"],
};
</script>

<style scoped>
button {
  border: 0.4rem solid #fff;
  color: #fff;
  padding: 0.5rem 1rem;
}
</style>
