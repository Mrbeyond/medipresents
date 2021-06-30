<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="te">Test Variables</div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style lang="scss" scoped>
 .te{
 color: $pBlue;
 }
</style>
