<template>
<div>
    <div class="close">
     <i class="mdui-icon material-icons">&#xe5cd;</i>
    </div>
</div>
</template>

<script>
import '../../node_modules/mdui/dist/css/mdui.min.css'
export default {
  name: 'HelloWorld',
   beforeCreate () {
    document.querySelector('body').setAttribute('style','background:#58c9d8')
  },
  beforeDestroy () {
    document.querySelector('body').setAttribute('style', '')
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.close {
    margin-top: 1px;
    margin-left: 1px;
    position: relative;

}
</style>
