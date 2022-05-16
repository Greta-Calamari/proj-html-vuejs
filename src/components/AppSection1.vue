<template>
    <div class="container c-color">
        <p class="text-center pt-5 mb-1">Stimulated to learn?</p>
        <h4 class="title text-center mb-5 fs-2">Featured Online Courses</h4>
<div class="d-flex flex-wrap justify-content-around">

        <div class="mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/course-02-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title price">$40.<span class="mini">00</span></h5>
                   <p class="card-text tit-ca">Learning to Write as a Professional Author</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines"></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                       50 Students

                       </small></p>
                 </div>
               </div>
       </div>
   </div>
   <div class="mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/stock-full-hd-03-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title price">Free</h5>
                   <p class="card-text tit-ca">Customer-centric info-Tech Strategies</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines"></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                       50 Students

                       </small></p>
                 </div>
               </div>
       </div>
   </div>
   <div class=" mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/stock-full-hd-04-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title">$19.<span class="mini">00</span></h5>
                   <p class="card-text tit-ca">Open Programming Courses for Everyone:Python</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines"></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                       50 Students

                       </small></p>
                 </div>
               </div>
       </div>
   </div>
   <div class=" mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/stock-full-hd-06-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title">$26.<span class="mini">00</span></h5>
                   <p class="card-text tit-ca">Academic Listening and Note-taking</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines"></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                       50 Students

                       </small></p>
                 </div>
               </div>
       </div>
   </div>
   <div class="mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/course-featured-image-01-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title">$39.<span class="mini">00</span></h5>
                   <p class="card-text tit-ca">Master jQuery in a Short Period of Time</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines"></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                       50 Students

                       </small></p>
                 </div>
               </div>
       </div>
   </div>
   <div class=" mb-3" style="max-width: 540px;">
            <div class="row g-0">
                <div class="col-md-4">
                   <img src="../assets/images/stock-full-hd-05-480x298.jpg" class="img-fluid circle" alt="...">
                </div>
                 <div class="col-md-8">
                   <div class="card-body ms-2">
                   <h5 class="card-title">$59.<span class="mini">00</span> </h5>
                   <p class="card-text tit-ca">Introduction to Javascript for Beginners</p>
                   <p class="card-text tit-c"><small class="">
                       <i class="fa-solid fa-file-lines "></i>
                       20 Lessons
                       <i class="fa-solid fa-user ms-4"></i>
                        50 Students

                       </small></p>
                 </div>
               </div>
       </div>
  </div>
</div>

        <button type="button" class="btn my-3 ">
                 View all courses
                 <i class="fa-solid fa-arrow-right-long"></i> 
                
        </button>

    </div>
        


</template>

<script>
export default {
    name:'AppSection1',
    
}
</script>

<style lang="scss" scoped>
@import '../styles/vars.scss';
h5{
    font-size: 20px;
    font-weight: 700;
    color: $green;
}
.c-color{
    background-color: $bg;

}
.title{
    color: $violet;
}

.btn{
    
    width: 20% !important;
    background: $green !important; 
    color: $white !important;
    padding: 15px !important;
    margin: 5% 40% !important;
    
}

.circle{
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
}

.mini{
    font-size: 15px;

}
.tit-ca{
    font-size: 20px;
    font-weight: 700;
    color: $violet;
}

.tit-c{
    color: $violet;
   
}
   


</style>