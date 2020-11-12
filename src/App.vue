<template>
  <the-header title="Resource Center"></the-header>
  <div class="px-4 md:px-0">
    <the-resources></the-resources>
    <the-footer></the-footer>
  </div>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';
import TheFooter from './components/layouts/TheFooter'

export default {
  components: {
    TheHeader,
    TheResources,
    TheFooter
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

html {
  font-family: 'Roboto', sans-serif;
}

body {
  background: rgb(35 35 35);
  color: whitesmoke;
}
</style>
