<template>
  <header>
    <h1 class="font-semibold">{{ title }}</h1>
  </header>
</template>

<script>
export default {
  props: ['title']
}
</script>

<style scoped>
header {
  width: 100%;
  height: 56px;
  background-color: #6e6e56;
  display: flex;
  font-size: 2.5rem;
  justify-content: center;
  align-items: center;
}

header h1 {
  color: white;
  margin: 0;
}
</style>