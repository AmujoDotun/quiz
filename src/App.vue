<template>
  <div id="app">
   <Header />
   <b-row>
     <b-col sm="6" offset="3">
       <QuestionsBox />
     </b-col>
   </b-row>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import QuestionsBox from './components/QuestionsBox'

export default {
  name: 'App',
  components: {
    Header,
    QuestionsBox
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>
