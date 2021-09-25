<template>
  <div id="app">
    <h1>app根组件</h1>
    <test :msg='msg' />
    <!-- <router-view/> -->
  </div>
</template>
<script>
/*eslint-disable*/
import test from './components/test.vue'
export default{
  data(){
    return{
  msg:'Welcome to Your Vue.js component'
    }
   
  },
  // name:'app',
  components:{
    test
    }
}
</script>


<style>

</style>
