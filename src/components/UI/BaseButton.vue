<template>
  <button :type="type" :class="mode">
    <slot></slot>
  </button>
</template>

<script>
export default {
  props: ['type', 'mode']
}
</script>

<style scoped>
button {
  padding: 0.75rem 1.5rem;
  font-family: inherit;
  background-color: #414141;
  color: white;
  cursor: pointer;
  font-size: 1rem;
  border-radius: 8px;
}

button:hover,
button:active {
  background-color: #41414160;
}

.flat {
  background-color: transparent;
  color: whitesmoke;
  border: none;
}

.flat:hover,
.flat:active {
  background-color: #bebebe;
  color: black;
}
</style>