<template>
  <div id="app">
    <Header />
    <div class="gameList">
      <div>
        <img src="./assets/pong.png" alt="ping pong game screenshot" />
        <h2 class="name">Ping Pong</h2>
        <a href="https://pong-game-js14.netlify.app" target="_blank" rel="noopener noreferrer">play</a>
      </div>
      <div>
        <img src="./assets/falling_bricks.png" alt="falling bricks game screenshot" />
        <h2 class="name">Falling Bricks</h2>
        <a href="https://falling-bricks-game.netlify.app/" target="_blank" >play</a>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style>
body{
  margin:0;
  padding:0;
  background-color: whitesmoke;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

.gameList{
  display: flex;
  flex-flow: row wrap;
  align-items: center;
  justify-content: space-evenly;
  margin-top: 6rem;
}

.gameList div {
  width: 400px;
  display: flex;
  flex-direction: column;
  background: white;
  border-radius: 8px;
  padding: 4px;
  box-shadow: 0 2px 6px grey;
}

.gameList img {
  width: 100%;
}

a {
  flex: 1;
  text-decoration: none;
  background-color: aquamarine;
  border: none;
  border-radius: 16px;
  color: white;
  font-size: x-large;
  padding: 1.2rem;
  text-transform: uppercase;
}
</style>
