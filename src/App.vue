<script lang="ts">
export default {
  name: 'App'
}
</script>

<template>
  <header class="header">
    <img src="./assets/logo.svg" alt="logo" class="header-logo">
    <h2>My favorites books</h2>
  </header>
  <div class="movies"></div>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
}

.header-logo {
  max-width: 50px;
  margin-right: 10px;
}

.btn {
  border: none;
  width: 100px;
  height: 40px;
  font-size: 14px;
  margin: 0 10px;
  border-radius: 10px;
  cursor: pointer;
  background: #efefef;
}

.btn:hover {
  opacity: 0.7;
}

.btn_green {
  background: #37df5c;
}

.tabs {
  display: flex;
  justify-content: center;
  margin-bottom: 30px;
}
</style>
