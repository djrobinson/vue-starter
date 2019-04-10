<template>
  <div id="app">
    <Header
      class="header"
    />
    <ToolWindow
      msg="testo chango"
      class="main"
    />
  </div>
</template>

<script>
import ToolWindow from './components/ToolWindow.vue'
import Header from './components/Header.vue'

export default {
  name: 'app',
  components: {
    Header,
    ToolWindow
  }
}
</script>

<style>
#app {
  text-align: center;
}
.header {
  height: 150px;
}
.main {

}
</style>
