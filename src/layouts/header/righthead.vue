<template>
    <div> 
        <img  :src="imgsrc" alt="header image">
    </div>
</template>

<script>
    import { ref } from 'vue'
    export default {
        name:'righthead',
        setup(){
    // Image source
    let imgsrc;

    try{
      //Check availability
        imgsrc=ref(require('@/assets/images/headerbackground.png'))
    }
    catch(error){
      console.error(error);
    }
    return{
      imgsrc
    }
  }
    }
</script>

<style scoped>
img{
  width: 100%;
}
</style>