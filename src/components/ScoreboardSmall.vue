<template>
  <div class="ScoreboardSmall">
    <h1>Scoreboard</h1>
    <div v-for ="(scoreboard,id)" class="scoreboardclass">
  </div>
</template>

<script>
export default {
  name: 'ScoreboardSmall',
  props:[scoreboard],
}
</script>

<style scoped>

</style>
