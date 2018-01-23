<template>
  <div id="app">
  </div>
</template>

<script type="text/ecmascript-6">
  import axios from 'axios'
  import HelloWorld from './components/HelloWorld'

  export default {
    name: 'App',
    mounted() {
      this._getData()
    },
    methods: {
      _getData() {
//        axios.get("/add/add").then((res) => {
//          console.log(res.data)
//        })
//        axios.get("/remove/remove").then((res) => {
//          console.log(res.data)
//        })
//        axios.get("/update/update").then((res) => {
//          console.log(res.data)
//        })
//        axios.get("/get/get").then((res) => {
//          console.log(res.data)
//        })
      }
    },
    components: {
      HelloWorld
    }
  }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
