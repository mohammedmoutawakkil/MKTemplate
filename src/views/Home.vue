<template>
  <div class="container-fluid">
    <!-- Header -->
    <div class="row mb-5">
    <lefthead class="lefthead col-sm ps-4"/>
    <righthead class="righthead col-sm d-none d-md-block "/>
    </div>
    <!-- Section -->
    <Section class="row Section-bg" :style="{ 'backgroundImage': 'url(' + imgsrc + ')' }" />
  </div>
</template>
<script>
import righthead from '../layouts/header/righthead.vue'
import lefthead from '../layouts/header/lefthead.vue'
import Section from '../components/Section.vue'
import { ref } from 'vue'
export default {
  name: 'Home',
  components:{
    righthead,
    lefthead,
    Section
  }, 
  setup(){
            let imgsrc;
                try{
                //Check availability
                    imgsrc=ref(require('@/assets/images/slanted-background.png'))
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
.Section-bg{
    height: auto;
    background-size: cover;
}
.lefthead{
  padding-top: 15%;
}

@media screen and (max-width: 850px) {
 .lefthead{
  padding-top: 15%;
}

}

</style>