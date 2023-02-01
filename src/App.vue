<script>
import AppTitle from './components/AppTitle.vue';
import AppImg from './components/AppImg.vue';

export default {
  components: {
    AppTitle,
    AppImg
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
  <AppTitle />
  <AppImg />

</template>

<style scoped>
button {
  font-weight: bold;
}
</style>