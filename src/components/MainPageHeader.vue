<script setup>
import MyButton from "./MyButton.vue";

const logMama = () => {
  console.log("mama");
};

const logPapa = () => {
  console.log("fsdfsdfds");
};

const logBrother = () => {
  console.log("brother");
};
</script>

<template>
  <MyButton
    text="mama"
    @click="logMama"
    @mouseover="logPapa"
    @mouseleave="logBrother"
  />
  <header>
    <ul class="list">
      <li>Палка</li>
      <li>О нас</li>
      <li>Попка</li>
      <li>Какашечка</li>
      <li>Ещё лишечка</li>
      <li>Танюшка</li>
    </ul>
  </header>
</template>

<style scoped>
header {
  width: 100%;
  padding: 8px 16px;
}

.list {
  list-style-type: disc;
}
</style>
