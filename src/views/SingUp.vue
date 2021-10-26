<template>
    <div> 
        <!-- head -->
        <p class="fw-bold text-secondary ">Sign up with</p>
        <div class="row px-4 ">
            <a href="#" class="text-decoration-none text-dark fw-normal col-sm bg-light p-1 rounded px-0 me-sm-4" ><fa :icon="['fab','github']" class="fs-5 me-1"/>Githube</a>
            <a href="#" class="text-decoration-none text-dark fw-normal col-sm bg-light p-1 rounded px-0 ms-sm-4" ><fa :icon="['fab','google']" class="fs-5 me-1 text-danger"/>Google</a>
        </div> 
    </div>
    <hr>
    <h6 class="mb-4 ">Or sign up with credentials</h6>
    <!-- Sing Up form -->
    <form action="" method="" class="text-secondary">
        <!-- User Name -->
        <div class="form-group text-start py-2">
            <label for="Name">User Name</label>
            <input type="text" class="form-control shadow" placeholder="Enter UserName" required>
        </div>
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
        <!-- Privacy Policy -->
        <div class="form-check text-start py-2">
            <input class="form-check-input" type="checkbox" value="" id="flexCheckIndeterminate">
            <label class="form-check-label pointer" for="flexCheckIndeterminate">
                I agree with the <a href="#" class="text-decoration-none"><span class="text-pink">Privacy Policy</span> </a>
            </label>
        </div>
        <!-- Submit -->
        <button class="btn btn-primary shadow mb-4 px-3 ">Create Account</button>
    </form>
</template>

<script>
    export default {
        name:'SingUp'
    }
</script>

<style scoped>
.text-pink{
    color: #ec65a6;
}
.pointer{
    cursor: pointer;
}
</style>