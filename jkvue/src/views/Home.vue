<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld v-bind:msg=message />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  data(){
    return{
      message:'三星大眼睛'
    }
  },
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
