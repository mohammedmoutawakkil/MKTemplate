<template>
    <div class="container-fluid p-more">
        <div class="row">
            <div class="col-sm text-start ms-sm-5 ps-sm-5">
                <h1 class="fw-bold">Find Us!</h1>
                <p class="text-dark">Find us on any of these platforms, we respond 1-2 business days.</p>
                <div class="row ms-sm-5 text-center">
                    <!-- facebook -->
                        <div class="col-sm-2   fs-1"><a href="#"><fa :icon="['fab','facebook']" class="text-primary p-2 bg-light shadow rounded-circle"/></a></div>
                    <!-- twitter -->
                        <div class="col-sm-2   fs-1"><a href="#"><fa :icon="['fab','twitter']" class="tw p-2 bg-light shadow rounded-circle"/></a></div>
                    <!-- Github -->
                        <div class="col-sm-2   fs-1"><a href="#"><fa :icon="['fab','github']" class="text-dark p-2 bg-light shadow rounded-circle"/></a></div>
                    <!-- linkedin -->
                        <div class="col-sm-2   fs-1"><a href="#"><fa :icon="['fab','linkedin']" class="text-primary p-2 bg-light shadow rounded-circle"/></a></div>
                </div>
            </div>
            <div class="col-sm">
                <div class="row row-cols-1 text-start">
                    <!-- Location -->
                    <div class="col text-dark">Location: <a class="text-secondary text-decoration-none" target="_blank" href="https://www.google.com/maps/place/Meknes/@33.8809852,-5.6080603,12z/data=!3m1!4b1!4m5!3m4!1s0xda044d23bfc49d1:0xfbbf80a99e4cde18!8m2!3d33.8730164!4d-5.5407299">Meknes,Morocco</a></div>
                    <!-- Email Address -->
                    <div class="col mt-3 text-dark">
                        <address>
                       <p>Email Address:<a class="text-secondary ms-2 text-decoration-none text-break" href="mailto:webmaster@example.com">MohamedMoutawakkil1999@gmail.com</a></p> 
                        </address>
                    </div>
                    <!-- Tel -->
                    <div class="col text-dark">Call us at : <a class="text-secondary text-decoration-none" href="tel:+2126########">+212-6##-##-##-##</a></div>
                </div>
            </div>
            <div class="col-sm">
                <div class="row">
                    <div class="col"> 
                                <!-- Grid container -->
                                <div class="container p-4 pb-0">
                                    <!-- Section: Form -->
                                    <section class="">
                                    <form @submit.prevent>
                                        <!--Grid row-->
                                        <div class="row d-flex justify-content-center">
                                        <!--Grid column-->
                                        <div class="col-auto">
                                            <p class="fs-5 text-dark">
                                            Sign up for our newsletter
                                            </p>
                                        </div>
                                        <!--Grid column-->

                                        <!--Grid column-->
                                        <div class="col-md-5 col-12">
                                            <!-- Email input -->
                                            <div class="form-outline mb-4">
                                            <input type="email" id="form5Example27" class="form-control" placeholder="Email adress"/>
                                            </div>
                                        </div>
                                        <!--Grid column-->

                                        <!--Grid column-->
                                        <div class="col-auto">
                                            <!-- Submit button -->
                                            <button type="submit" class="btn btn-pink mb-4 text-light">
                                            Subscribe
                                            </button>
                                        </div>
                                        <!--Grid column-->
                                        </div>
                                        <!--Grid row-->
                                    </form>
                                    </section>
                                    <!-- Section: Form -->
                                </div>
                                <!-- Grid container -->

                    </div>
            </div>
            
        </div>
        <div class="px-5 b-0"><hr></div>
        <div class="text-center p-3 text-dark">
            © {{date}} Copyright :
            <a class="text-secondary text-decoration-none" href="#"> Mohammed Moutawakkil</a>
        </div>
    </div>
</div>
</template>
<script>
import { ref } from 'vue'
    export default {
        name:'foot',
        setup(){
            //Copyright Date
            const date=ref(new Date().getFullYear())
            return{
                date
            }
        }
    }
</script>

<style scoped>
.p-more{
    padding-top: 200px;
}
.btn-pink{   
      background-color: #667EEA;
}
.btn-pink:hover{
  background-color: #ED64A6;
}
.tw{
  color:rgb(0, 162, 255);
}
</style>