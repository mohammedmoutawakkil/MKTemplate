<template>
    <nav class="navbar navbar-expand-sm navbar-light fixed-top bgwhite py-3 ">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="mynavbar">
          <ul class="navbar-nav me-auto ps-sm-5 ms-sm-5">
            <!-- Home -->
            <li class="nav-item">
              <router-link to="/home" class="nav-link fw-bold" tag="button"  active-class="active">Home</router-link> 
            </li>
            <!-- Contact Us -->
            <li class="nav-item">
              <router-link to="/Contact" class="nav-link fw-bold" tag="button"  active-class="active">Contact Us</router-link> 
            </li>
            <!-- About Us -->
            <li class="nav-item">
              <router-link to="/about" class="nav-link fw-bold" tag="button"  active-class="active">About Us</router-link>
            </li>
          </ul>
          <div class="d-sm-flex text-center pe-sm-5 me-sm-5 my-4 my-md-0">
            <!-- facebook -->
            <a href="#" class="mx-4"><fa :icon="['fab','facebook']" class="fa fb"/></a>
            <!-- twitter -->
            <a href="#" class="mx-4"><fa :icon="['fab','twitter']" class="fa tw"/></a>
            <!-- github -->
            <a href="#" class="mx-4"><fa :icon="['fab','github']" class="fa gh"/></a>
          </div>
            <div class="btn-group">
              <!-- Sign in -->
               <router-link to="/auth/login" class="btn btn hpink"  tag="button">Sign in</router-link>
              <!-- Sing Up -->
               <router-link to="/auth/login" class="btn btn hblue"  tag="button">Sign Up</router-link>
            </div>
        </div>
      </div>
    </nav>
</template>

<script>
    export default {
      name:'navbar',
      setup(){
        return{
        }
      }
    }
</script>

<style  scoped>
@import url('https://fonts.googleapis.com/css2?family=Maven+Pro:wght@500&display=swap');
.bgwhite{
background-color: white;
} 
.hpink:hover{
  background: #ED64A6;
  color: white;
}
.hblue:hover{
  background: #667EEA;
  color: white;
}
nav{
    box-shadow: 0px 0.5px 10px rgb(180, 180, 180);
}
.fa{
   color: #94A3B8;
   font-size: 2.6vh;
}
.fa:hover{
  animation-name: example;
  animation-duration: 2s;
}
.fb:hover{
color: rgb(0, 102, 255);
}
.tw:hover{
  color:rgb(0, 162, 255);
}
.gh:hover{
color: black;
}
@keyframes example {
  from {transform: rotate(0deg);}
  to {transform: rotate(360deg);}
}
.nav-item a.router-link-exact-active {
   text-shadow: 1px 8px 9px rgb(41, 40, 40);
   font-family: 'Maven Pro', sans-serif;
}
</style>