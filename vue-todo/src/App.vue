<template>
  <div id="app">
    <h1 class="title">Todos</h1>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
  }
}
</script>

<style scoped>
* {
  margin-top: 0;
}

#app {
  margin: auto;
  width: 40%;
}

.title {
  text-align: center;
  font-size: 5rem;
  margin-top: 1rem;
  color: rgba(170, 55, 55, 0.192);
  text-transform: lowercase;
}
</style>
