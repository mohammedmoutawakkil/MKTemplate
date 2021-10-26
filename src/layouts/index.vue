<template>
    <div>
    <div> 
    <!-- navbar -->
        <navbar />
    </div>
   
     <div>
    <!-- body -->
        <router-view/>
     </div>
    </div>
    <!--footer  -->
        <foot :class="'footer '+display" />
</template>

<script>
import navbar from '../components/navbar.vue'
import foot from '../components/foot.vue'
    export default {
        name:'index',
        setup(){
            return{
            }
        },
        components:{
            navbar,
            foot 
        }
    }
</script>

<style scoped>
.footer{
  background-color: #475569;
}
</style>