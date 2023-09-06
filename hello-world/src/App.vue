<template>
  <h1>hoi</h1>
  <section class="game-board">
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
  </section>
</template>

<script>
import Card from './components/Card'
export default {
  name: 'App',
  components: {
    Card
  },
  data() {
    
  }
}
</script>

<style>
#app {

}

.card {
  border: 5px solid #ccc
}

.game-board {
  display: grid;
  grid-template-columns: repeat(4, 100px);
  grid-template-rows: repeat(4, 100px);
  grid-column-gap: 30px;
  grid-row-gap: 30px;
  justify-content: center;
}
</style>
