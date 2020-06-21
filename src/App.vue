<template>
  <div id="app">
    <Header/>
    <WelcomeBanner
      class='mt-4 mb-4 font-weight-bold'
      msg="Bienvenue Enigmagates, le portail français des énigmes en ligne !"/>
    <div class="container-fluid">
      <div class="row">
        <div class="col">
          <WebcamHeader/>
        </div>
      </div>
        <div class="row">
          <div class="col-9 pr-1">
            <Board/>
          </div>
          <div class="col-3 pl-1">
            <ChatBox/>
          </div>
        </div>
    </div>
  </div>
</template>

<script>
import Header from './components/layout/Header.vue';
import Board from './components/layout/Board.vue';
import WelcomeBanner from './components/layout/WelcomeBanner.vue';
import WebcamHeader from './components/layout/WebcamHeader.vue';
import ChatBox from './components/layout/ChatBox.vue';

export default {
  name: 'App',
  components: {
    Header,
    Board,
    WelcomeBanner,
    WebcamHeader,
    ChatBox,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
#app {
  font-family: Montserrat, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.col {
    max-width: 100%;
}
</style>
