<template>
  <div class="app">
    <!-- APP你 -->
    <h2>你你你</h2>
    <button onclick="changeName">123</button>
    <button onclick="changeAge">456</button>
  </div>
</template>

<script lang="ts">
export default {
  name: "App1",
};
</script>

<script lang="ts">
function changeName() {}
function changeAge() {}
</script>

<style>
.app {
  background-color: aqua;
  padding: 10px;
  box-shadow: 1 1 6px;
  border-radius: 2px;
}
</style>
