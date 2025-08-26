<script setup>
/* eslint-disable */
const props = defineProps({
  text: {
    type: String,
    default: "Нажми на меня",
  },
});
</script>

<template>
  <button>
    {{ props.text }}
    <span>mama</span>
  </button>
</template>

<style scoped lang="scss">
button {
  outline: none;
  border: none;
  background-color: rgb(0, 156, 47);
  color: white;
  padding: 8px 12px;
  border-radius: 8px;

  &:hover {
    cursor: pointer;
    background-color: rgb(0, 133, 40);
    transition: 0.3s ease-in-out;
  }

  span {
    background-color: black;
  }
}
</style>
