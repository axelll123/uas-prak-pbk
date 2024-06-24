<template>
  <div class="homeview">
    <Weather />
  </div>
</template>

<script>
import Weather from '../components/Cuaca.vue';

  export default {
    name: 'HomeView',
    components: {
      Weather,
    }
  };
</script>

<style>
.homeview {
  text-align: center;
}
</style>
