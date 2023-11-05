<script>
import img from '../assets/jeegSD.jpg';

export default {
  data() {
    return {
      message: 'Jumbotron',
      img,
    };
  },
};
</script>

<template>
  <h1>{{ message }}</h1>
  <img src="/jeegSD.jpg" alt="" />
  <img :src="img" alt="" />
</template>

<style scoped>
img {
  width: 100%;
}
</style>
