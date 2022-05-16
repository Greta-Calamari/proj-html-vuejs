<template>
    <div class="container">
        <p class="text-center pt-5 mb-1">MAX COACH AVAILABLE</p>
        <h4 class="title text-center mb-5 fs-2">Access <span class="tit-c">Smart Tutoring </span>Program for Benefits.</h4>
        
    <div class="d-flex justify-content-around">

         <div class="" style="width: 18rem;">
            <img src="../assets/images/home-2-image-box-03.png" class="card-img-top img" alt="...">
             <div class="card-body">
             <h5 class="tit-ca">Customize Preferences</h5>    
             <p class="card-text">Learners are given the right to arrange and customize their study schedule and timetable based on preferences.</p>
             <p class="tit-cc">
                 Start here
                 <i class="fa-solid fa-arrow-right-long"></i>

             </p>
            </div>
        </div>

         <div class="" style="width: 18rem;">
            <img src="../assets/images/about-us-02-image-box-02.png" class="card-img-top" alt="...">
             <div class="card-body">
             <h5 class="tit-ca">Cloud Storage</h5>
             <p class="card-text">You can store online lessons via online cloud or download to your devide and revise lessons on the way.</p>
             <p class="tit-cc">
                 Get Free Quote
                 <i class="fa-solid fa-arrow-right-long"></i>

             </p>

            </div>
        </div>

        <div class="" style="width: 18rem;">
            <img src="../assets/images/home-2-image-box-01.png" class="card-img-top" alt="...">
             <div class="card-body">
            <h5 class="tit-ca">Multimedia Channels</h5>
             <p class="card-text">We provide study materials with various formats:
                 video,audio,slides,doc,prints,books and applications.
             </p>
             <p class="tit-cc">
                 Start now
                 <i class="fa-solid fa-arrow-right-long"></i>

             </p>
            </div>
        </div>
   </div>

   <div class="row mt-5">
        <div class="col-5 mt-4">
              <img src="../assets/images/home-2-popup-video-poster.jpg" class="rounded img2" alt="">
              <img src="../assets/images/maxcoach-shape-05.png" alt="" class="c--1">
              <img src="../assets/images/icon-youtube-play.png" alt="" class="c--2">
              <img src="../assets/images/maxcoach-shape-07.png" class="c--3" alt="">
              <div class="c--5"></div>
              <img src="../assets/images/shape-2.svg" class="c--6" alt="">
          </div>

       <div class="col-5 ms-5 mt-5">
              <p class="sub">GET STARTED <span class="tit-cc"> EFFORTLESSLY</span> </p>
              <h3 class="title">Enjoy our <p class="tit-c">Companionship</p> </h3>
              <p class="larg">Sneek peek into what has in store for you or online teaching and mentoring portal. Seek some hidden hints of early-bird rewards as well.</p>

              <p class="subb mt-4">
                  Download free guidebook
                  <i class="fa-solid fa-arrow-right-long"></i>

              </p>
        </div>
              

              


   </div>

</div>
</template>

<script>
export default {
    name:'AppSection2',
    
}
</script>

<style lang="scss" scoped>
@import '../styles/vars.scss';

.img{
    width: 90%;
}

.img2{
    width: 100%;
}

.tit-c{
    color: $green;
    font-weight: 100;
}
.tit-ca{
    font-size: 20px;
    font-weight: 700;
    color: $violet;
}

.tit-cc{
    color: $gun;
    font-weight: 700;
}
sub{
    color: $violet;
}
.subb{
    color: $green;
    font-weight: 700;
    text-decoration:1px underline $gray;
}
.larg{
    width: 70%;
}

.c--1{
    position: relative;
    bottom: 40%;
    right:20%;
    z-index: -100;

}
.c--2{
    position: relative;
    bottom: 40%;
    left:5%;

}
.c--3{
    position: relative;
    bottom: 10%;
    left:17%;
    z-index: -100;


}
.c--5{
    position: relative;
    bottom: 78%;
    left:110%;
    width: 50px;
    height: 50px;
    border-radius:50%;
    border: 5px solid $sand;
}
.c--6{
    position: relative;
    bottom: 90%;
    right:10%;
    width: 30%;
    z-index: -1000;
}




    


</style>