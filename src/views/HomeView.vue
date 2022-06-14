<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Creator />
  </div>
</template>

<script>
// @ is an alias to /src
import Creator from '@/components/Creator.vue'

export default {
  name: 'HomeView',
  components: {
    Creator
  }
}
</script>
