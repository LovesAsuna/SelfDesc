<template>
  <div id="container">
    <Header></Header>
    <Me></Me>
    <Game></Game>
    <Host></Host>
    <CopyRight></CopyRight>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Me from './components/Me.vue'
import Game from './components/Game.vue'
import Host from './components/Host.vue'
import CopyRight from './components/CopyRight.vue'

export default {
  name: 'App',
  components: {
    Header,
    Me,
    Game,
    Host,
    CopyRight
  },
  data: function () {
    return {
      message: ""
    }
  }
}
</script>

<style scoped>
#container {
  font-size: 1em;
  margin: 0;
  min-height: 100vh;
  padding: 5vh 0;

  display: flex;
  flex-direction: column;
  justify-content: center;
}

#container .section {
  background-color: #b5a191;
}

#container {
  font-family: 'Helvetica Neue', Helvetica, Arial, PingFangTC-Light, 'Microsoft YaHei', 微软雅黑, 'STHeiti Light',
  STXihei, '华文细黑', Heiti, 黑体, sans-serif;
  margin: 0;
  padding: 0;
}

#container {
  background-size: cover;
  padding-top: 1em;
  margin: 0 auto;
  max-width: 64em;
}

#container,
#container > *:first-child {
  border-top-left-radius: 2em;
}

#container > *:last-child,
#container > *:last-child > *:last-child {
  border-bottom-right-radius: 2em;
}
</style>


