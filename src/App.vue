<script>
  import InfoStudent from './components/InfoStudent.vue';
  import LikeCounter from './components/LikeCounter.vue';
  import Generator from './components/Generator.vue';

  export default {
    components: {
      InfoStudent,
      LikeCounter,
      Generator,
    }
  }
</script>

<template>
  <div>
    <InfoStudent/>
    <LikeCounter/>
    <Generator/>
  </div>
</template>

<style scoped>

</style>
