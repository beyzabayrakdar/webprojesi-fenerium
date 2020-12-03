<template>
  <div v-title="title" class="macKombinleri">
    <MacKombinleri/>
>
  </div>
</template>

<script>
import MacKombinleri from '../components/MacKombinleri.vue'

export default {
  name:"app",
  components:{
    MacKombinleri
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