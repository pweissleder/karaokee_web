<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ScoreboardSmall/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import ScoreboardSmall from '@/components/ScoreboardSmall'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    ScoreboardSmall{

    }
  }
}
</script>
