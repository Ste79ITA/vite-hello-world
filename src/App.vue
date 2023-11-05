<script>
import AppHero from './components/AppHero.vue';

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!',
    };
  },
  components: {
    AppHero,
  },
};
</script>

<template>
  <div>{{ message }}</div>
  <AppHero />
</template>

<style scoped></style>
