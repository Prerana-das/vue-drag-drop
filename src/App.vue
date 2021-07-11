<template>
  <div id="app">
    <main class="flexbox">
      <Board id="board-1">
         <Card id="card-1" draggable="true">
           <p>Card One</p>
         </Card>
      </Board>
      <Board id="board-2">
         <Card id="card-2" draggable="true">
           <p>Card Two</p>
         </Card>
      </Board>
    </main>
  </div>
</template>

<script>
import Board from './components/Board';
import Card from './components/Card';

export default {
  name: 'App',
  components: {
    Board,
    Card
  }
}
</script>

<style>
.board{
  width:300px;
  height:500px;
  background-color:rgb(226, 208, 208);
}
.card{
  height:100px;
  background-color: #000;
  color:#fff;
}
</style>
