<template>
    <!-- authentication card -->
    <div class="wrapper d-flex justify-content-center align-items-center mn-100 min-vh-100 position-relative">
        <div class="auth-content p-2 position-relative mt-5">
            <div class="card border-0 mb-0">
                <div class="card-body text-center pt-0 pb-5 px-4 ">
                    <div class="mb-4">
                        <img class="brand" src="#" alt="">
                    </div>
                    <!-- Sing Up component or Sing In component -->
                    <component :is="activeform" />
                    <p class="mb-2 text-muted" v-show="links">Forgot password? <button class="text-primary border-0 text-decoration-underline bg-transparent fw-bold">Reset</button></p>
                    <p class="mb-0 text-muted" v-show="links">Don't have account yet? <button @click="[activeform='SingUp',links=false]" class="text-primary border-0 text-decoration-underline bg-transparent fw-bold">Signup</button></p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import { ref } from 'vue'
import login from '../views/login.vue'
import SingUp from '../views/SingUp.vue'
    export default {
        name:'auth',
        setup(){
            //shown component
            const activeform=ref('login')
            //hide or show Forgot password link and create account link
            const links=true
                return{
                   activeform,
                   links
                }
        },
        components:{
            SingUp,
            login
        }
    }
</script>

<style scoped>

.wrapper{
    background-color: #1E293B;
}
.auth-content {
    width: 400px;
}

.auth-content .card {
    box-shadow: 0 1px 20px 0 rgba(69, 90, 100, 0.08);
    background-color:#E2E8F0 ;
}

p.text-muted {
    font-size: 13px;
}


</style>