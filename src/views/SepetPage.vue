<template>
  <div v-title="title" class="sepet">
    <Sepet/>
>
  </div>
</template>

<script>
import Sepet from '../components/Sepet.vue'

export default {
  name:"app",
  components:{
    Sepet
  }, 
  data (){
      title:"Fenerium"
  }
}
</script>
    
<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>