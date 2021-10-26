<template>
   <div> 
       <!-- head -->
        <p class="fw-bold text-secondary">Sign in with</p>
        <div class="row px-4">
            <a href="#" class="text-decoration-none text-dark fw-normal col-sm bg-light p-1 rounded px-0 me-sm-4 mt-2 mt-md-2 mt-lg-0" ><fa :icon="['fab','github']" class="fs-5 me-1"/>Githube</a>
            <a href="#" class="text-decoration-none text-dark fw-normal col-sm bg-light p-1 rounded px-0 ms-sm-4 mt-2 mt-md-2 mt-lg-0" ><fa :icon="['fab','google']" class="fs-5 me-1 text-danger"/>Google</a>
        </div> 
    </div>
    <hr>
    <h6 class="mb-4 ">Or sign in with credentials</h6>
    <!-- Sing in form -->
    <form action="" method="" class="text-secondary">
        <!-- Email Address -->
        <div class="form-group text-start py-2">
            <label for="email">Email adress</label>
            <input type="email" class="form-control shadow" placeholder="Enter Email" required>
        </div>
        <!-- Password -->
        <div class="form-group text-start py-2">
            <label for="password">Password</label>
            <input type="password" class="form-control shadow" placeholder="Password" required>
        </div>
        <!-- Remember this section or device -->
        <div class="form-check text-start py-2 ">
            <input class="form-check-input " type="checkbox" value="" id="flexCheckIndeterminate">
            <label class="form-check-label pointer" for="flexCheckIndeterminate">
                Remember me on this device
            </label>
        </div>
        <!-- Submit -->
        <button class="btn btn-primary shadow mb-4 px-3 ">Login</button>
    </form>
</template>

<script>
    export default {
        name:'login'
    }
</script>

<style >
.pointer{
    cursor: pointer;
}
</style>
