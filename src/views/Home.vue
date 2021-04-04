<template>
  <div>
    <Navbar/>
    
    <!-- <p v-for="(computer,index) in computers " :key="index">{{computer}}</p> -->
    
    

  </div>
</template>

<script>
import computers from '@/Books/computer.js';
//  const bb = JSON.stringify(books);

// Nav bar mmenu importation 
import Navbar from '@/components/Navbar'
export default {
  name: 'App',
  components:{
    Navbar
  },
  data() {
    return {
      computers
    }
  },
}
</script>
<style scoped>
.maincolor{
  background-color:#F5F5F5;
}
</style>