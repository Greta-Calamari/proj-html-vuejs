<template>
  <div class="container">
      <div class="row hovvver">
          <div class="col-6 col1">
              <h3 class="title">Distant learninbg for further expansion</h3>
              <p>learning is a life-long journey that in fact we never find the terminate stop.Stop searching,enjoy the process.</p>
              <button type="button" class="btn my-3">
                  <i class="fa-solid fa-download"></i>
                  Download free guide
              </button>
              <div class="rev ovv">
                <span>Have questions?</span>
                    <span class="link">
                        Get Free Sample
                    </span>
                    <span class="link">
                        <i class="fa-solid fa-arrow-right-long"></i>
                    </span>
                    
                    <div class="marki">
                    

                    </div>
              </div>



                  



              


          </div>

          <div class="col-6 revi">
              <img src="../assets/images/about-me.jpg" class="circle" alt="">
              <img src="../assets/images/maxcoach-shape-08.png" class="c-1 " alt="">
              <img src="../assets/images/maxcoach-shape-08.png" class="c-2" alt="">
              <img src="../assets/images/maxcoach-shape-07.png" class="c-3" alt="">
              <img src="../assets/images/maxcoach-shape-02.png" class="c-4" alt="">
              <div class="c-5"></div>
          </div>






      </div>

      <div>
          <div class="ms-4">
              <img src="../assets/images/client-logo-01.png" class="p-5 iconn" alt="">
              <img src="../assets/images/client-logo-02.png" class="p-5 iconn" alt="">
              <img src="../assets/images/client-logo-03.png" class="p-5 iconn"  alt="">
              <img src="../assets/images/client-logo-04.png" class="p-5 iconn" alt="">
              <img src="../assets/images/client-logo-05.png" class="p-5 iconn" alt="">
              <img src="../assets/images/client-logo-06.png" class="p-5 iconn" alt="">
          </div>

      </div>

  </div>
</template>



    

<script>



export default {
  name: 'AppJumbotron',
  
}
</script>

<style lang="scss">
@import '../styles/vars.scss';
// EFFETTI

.hovvver{
    transition:1s;
}

.hovvver:hover .c-1,.hovvver:hover .c-2,.hovvver:hover .c-3,.hovvver:hover .c-4,.hovvver:hover .circle,.hovvver:hover .c-5{
   -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: infinite;
        animation-iteration-count: infinite;


}



.ovv .marki::before{
    content: "";
    position: absolute;
    height: 0.2em;
    width: 40%;
    background-color: $bg;
    bottom: -0.1em;
    transition: all ease-in-out 250ms;
}
    

        


.ovv:hover .marki{
    background-color: $green;
    width: 20%;
}
    



        
.revi{
    position: relative;
}

.rev{
    position: relative;
    
}
        






.container{
    // width: 47% !important;
    margin-top: 2% !important;
}

.col1{
  margin-top: 10% !important;
  
}

.title{
    color: $violet;
    font-size: 50px;
}
p{
    color: $gray;
}

.link{
    color:$green;
    font-weight: 700;
    
}
.btn{
    background: $green !important; 
    color: $white !important;
    padding: 15px !important;
    width: 50% !important;

}
.btn:hover{
  background-color: $violet !important;

}

.circle{

    margin-left: 20%;
    border-radius: 50%;
}
// deco
.c-1{
    position: relative;
    bottom:58%;
    left: 8%;
    z-index: -100;
}
.c-2{
    position: relative;
    bottom: 40%;
    right: 16%;
    z-index: -100;

}
.c-3{
    position: relative;
    bottom: 24%;
    left: 30%;
    z-index: -100;

}
.c-4{
    position: relative;
    bottom: 60%;
    left: 35%;
    z-index: -100;

}
.c-5{
    position: relative;
    bottom: 50%;
    left: 14%;
   
}



.c-5{
    width: 50px;
    height: 50px;
    border-radius:50%;
    border: 5px solid $sand;

    
}
.iconn:hover{
   
    opacity: 1;
}
.iconn{
    opacity: 0.5;
    transition: 1s;
}


// ANIMATION
@-webkit-keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
       transform: translateX(-5px);
    } 
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(3px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(2px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}
@keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    30%
    {
        -webkit-transform: translateX(-5px);
        transform: translateX(-5px);
    }
    50%
    {
        -webkit-transform: translateX(3px);
        transform: translateX(3px);
    }
    65%
    {
        -webkit-transform: translateX(-3px);
        transform: translateX(-3px);
    }
    80%
    {
        -webkit-transform: translateX(2px);
        transform: translateX(2px);
    }
    100%
    {
        -webkit-transform: translateX(0);
        transform: translateX(0);
    }
}


</style>