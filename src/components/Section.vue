<template>
  <div >
    <div class="row">
      <!-- First Card -->
      <div class="col-sm-8">
        <div class="card rounded-3 p-0 border-0 Computercard">
          <img class="card-img-top" :src="Computer" alt="Card image" >
          <div class="card-body m-0 rounded-bottom pb-5 Computercardbody">
              <h5 class="card-title text-light fw-bold mt-3">Make some awesome project</h5>
              <p class="card-text text-light fs-6">"Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
          </div>
        </div>
      </div>
      <!-- Tools -->
      <div class="col-sm-4">  
          <div class="row  text-center mt-5 me-sm-5">
            <!-- Bootstrap -->
            <div class="col-sm ">   
              <div class="col-sm fs-3 d-inline p-2 shadow bg-light rounded-circle">
                  <fa :icon="['fab','bootstrap']" class="text-other"/>
              </div> 
              <div class="pt-3" >
                  <h5 class="fw-bold">Bootstrap </h5>
                  <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              </div> 
            </div>
            <!-- Vue Js -->
            <div class="col-sm ">
                    <div class="col-sm fs-3 d-inline p-2 bg-light shadow rounded-circle">
                        <fa :icon="['fab','vuejs']" class="text-success" />
                    </div>
                <div class="pt-3" > 
                    <h5 class="fw-bold">Vue js</h5>
                    <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                </div>
            </div>
          </div> 
          <!-- JavaScript -->
            <div class="row  text-center mt-5 me-sm-5">
                <div class="col-sm ">
                            <div class="col-sm fs-3 d-inline p-2 pb shadow bg-light rounded-circle">
                            <fa :icon="['fab','js']"  class="text-warning"/>
                        </div> 
                        <div class="pt-3" >
                            <h5 class="fw-bold">JavaScript Components </h5>
                            <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                        </div> 
                </div>
                <!-- css -->
                <div class="col-sm ">
                        <div class="col-sm fs-3 d-inline p-2 bg-light shadow rounded-circle">
                            <fa :icon="['fab','css3']" class="text-primary" />
                        </div>
                    <div class="pt-3" > 
                        <h5 class="fw-bold">CSS</h5>
                        <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                    </div>
                </div>
          </div> 
      </div>
  </div>
  <!-- card Title -->
  <h1 class="text-center fw-bold mt-4 text-pink">Cards</h1>
  <!-- cards -->
  <div class="row  g-4 p-sm-5">
    <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
   <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
    <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
   <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
    <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
  <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
    <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
    <!-- card -->
  <div class="col-sm-3 up ">
    <div class="card border-0">
      <!-- card image -->
      <img :src="grid" class="card-img-top" alt="...">
      <div class="card-body bg-pink rounded-bottom text-light">
        <!-- card title -->
        <h3 class="card-title  ">Card title</h3>
        <!-- card text -->
        <p class="card-text card-p text-center">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      </div>
    </div>
  </div>
</div>
<!-- View More -->
<div class="my-5"><a href="#" class="text-center text-decoration-none text-pin fw-bold">View more >></a></div>
  <div class="px-5"><hr class="mt-5"/></div>
  <div class="row mt-5">
    <!-- Comments -->
    <h1 class="text-center fw-bold mt-5 text-pink">Comments</h1>
    <!-- Comment -->
   <div class="col-sm m-sm-5 p-sm-4">
     <div>
       <!-- comment image -->
        <img :src="p1" alt="" class="img-thumbnail rounded-circle"></div> <div class="pt-3" > 
       <!-- User Name -->
        <h5 class="fw-bold">john weak</h5>
      <!-- comment text -->
        <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
     </div>
   </div>
   <!-- Comment -->
      <div class="col-sm m-sm-5 p-sm-4">
        <div>
          <!-- comment image -->
          <img :src="p2" alt="" class="img-thumbnail rounded-circle">
        </div> 
        <div class="pt-3" > 
          <!-- User Name -->
          <h5 class="fw-bold">sara dimo</h5>
          <!-- comment text -->
          <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
    </div>
    <!-- Comment -->
   <div class="col-sm m-sm-5 p-sm-4">
     <div>
       <!-- comment omage -->
        <img :src="p3" alt="" class="img-thumbnail rounded-circle">
      </div>
        <div class="pt-3" > 
          <!-- User Name -->
            <h5 class="fw-bold">stivan corn</h5>
            <!-- comment text -->
            <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        </div>
      </div>
      <!-- Comment -->
   <div class="col-sm m-sm-5 p-sm-4"><div>
     <!-- comment image -->
     <img :src="p4" alt="" class="img-thumbnail rounded-circle">
   </div> 
      <div class="pt-3" > 
        <!-- User Name -->
        <h5 class="fw-bold">stephan hold</h5>
        <!-- comment text -->
        <p class="fs-6 text-secondary">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
     </div>
  </div>
  </div>

</template>

<script>
import { reactive, toRefs } from 'vue'
    export default {
        name:'Section',
        setup(){
            let profiles;

                try{
                //Check availability
                    profiles=reactive({
                      p1:require('@/assets/images/p1.jpg'),
                      p2:require('@/assets/images/p2.jpg'),
                      p3:require('@/assets/images/p3.jpg'),
                      p4:require('@/assets/images/p4.jpg'),
                      Computer:require('@/assets/images/p3.png'),
                      grid:require('@/assets/images/grid.jpg'),
                    })
                    
                }
                catch(error){
                console.error(error);
                }
                return{
                ...toRefs(profiles)
                }
        }
    }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Festive&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Festive&family=Varela+Round&display=swap');
.up{
  cursor: pointer;
}
.up img:hover{
  opacity: 0.4;
}
.up:hover{
  padding-top: 0px;
}

.Computercard{
        width: 40%;
        margin-left:19%;
        box-shadow: 5px 4px 3px rgb(180, 180, 180);
               
}
.card-p {
  font-family: 'Festive', cursive;
font-family: 'Varela Round', sans-serif;
text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;
}
.text-pin{
  color: #334155;
}
.text-other{
    color: #7952B3;
}
.bg-other{
    background-color: #7952B3;
}
.Computercardbody{
    background-color: #5f79ec;
}
.bg-pink{
  background-color:#a1366a ;
}
.bg-pink>h3{
  font-family: 'Festive', cursive;
  text-shadow: 2px 2px 4px #000000;
}
</style>
