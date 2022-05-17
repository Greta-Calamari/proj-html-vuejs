<template>
    <div class="mt-0">
        <img src="../assets/images/wave.svg" alt="">
      <div class="all">

        <div class="container-fluid">
            <p class="text-center pt-5 mb-1">GREAT WORDS MAXCOACH</p>
            <h4 class="title text-center mb-5 fs-2">Our <span class="tit-c">top learners' </span>verbatim </h4>
        </div>
<div class="container">
            <carousel>
                <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-01.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
                
                <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-02.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
                

                <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-03.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
                

                <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-04.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
               
               <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-01.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
                

                <div class="card" style="width: 20rem;">
                    <div class="card-body">
                        <h5 class="card-title tit-d">High level of efficiency and scientific teaching methods</h5>
                        <p class="card-text">I am free to learn at my own peace, follow my own schedule and choose the subject i want to learn from the syllabus.Great study portal for people like me.</p>

                        <div class="row">
                            <div class="col-4">

                                <img src="../assets/images/testimonial-avata-02.jpg" class="w-100 imgl" alt="">
                            </div>
                            <div class="col-8">
                                    <p class="tit-d">MINA HOLLACE</p>
                                    <p>/Freelancer</p>

                            </div>
                        </div>
                        
                        
                    </div>
                </div>
            </carousel>

</div>

<div class="container">
    <div>
    <img src="../assets/images/maxcoach-shape-01.png" class="c1" alt="">
    <img src="../assets/images/maxcoach-shape-02.png" class="c2" alt="">
    <div class="circle c3"></div>
    <h4 class="tit-d text-center">Start today for getting <span class="tit-c text-center">Online Certification</span> </h4>
    <h2 class="tit-d text-center">You can be your own guiding star with our help!</h2>
    <button class="btn text-center">
        Get started now
    </button>

    </div>



</div>
    
               



    </div>  
</div>
</template>

<script>
import carousel from 'vue-owl-carousel'
export default {
    name:'AppSection3',
    components: { 
                 carousel 
                 },
    data(){
        return{
             components: { 
                 carousel 
                 },
             

        }
    }
   
    
}
</script>

<style lang="scss" scoped>
@import '../styles/vars.scss';
.container-fluid{
    background-color: #FAFBFC;
}
.all{
    background-color: #FAFBFC;

}
    
.tit-c{
    color: $green;
    font-weight: 100;
}

.tit-d{
    color: $violet;
    font-weight: 700;
}




.owl-carousel .owl-nav .owl-prev,
.owl-carousel .owl-nav .owl-next {
  font-weight: bold;
  font-size: 24px;
  font-family: monospace;
  padding: 10px 20px;
}

.imgl{
border-radius: 50%;    
}

.card{
    border:none !important;
}

.btn{
    
    width: 20% !important;
    background: $green !important; 
    color: $white !important;
    padding: 15px !important;
    margin: 5% 40% !important;
}

.circle{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: 5px solid $sand;
}

.c1{
    position: relative;
    top: 200px;
    right: 10px;
  
}



.c2{
    position: relative;
    left:80%;
    top: 250px;

}

.c3{
    position: relative;
    right: 200px;
    top: 50px;

}




</style>