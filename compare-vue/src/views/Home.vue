<template>
  <div class="home">
    <Sample />
  </div>
</template>

<script>
import Sample from '@/components/Sample.vue'

export default {
  name: 'Home',
  components: {
    Sample
  }
}
</script>

<style>
  @import '../mq.scss';
</style>
