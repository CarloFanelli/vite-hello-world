<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return {
      message: "Hello Vite!",
    }
  },
  components: {
    AppTitle,
    AppHero
  },

}

</script>

<template>
  <h1 class="text-success">{{ message }}</h1>
  <AppTitle title="La mia prima app con Vite!"></AppTitle>
  <AppHero></AppHero>
</template>

<style>
.jumbotron {
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background-color: #e9ecef;
  border-radius: 0.3rem;
}
</style>