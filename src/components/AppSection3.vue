<template>
    <div class="">
        <img src="../assets/images/wave.svg" alt="">
      <div class="all">

        <div class="container-fluid">
            <p class="text-center pt-5 mb-1">GREAT WORDS MAXCOACH</p>
            <h4 class="title text-center mb-5 fs-2">Our <span class="tit-c">top learners' </span>verbatim </h4>
        </div>
<div class="container">
            <carousel>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
                <div class="card" style="width: 18rem;">
                    <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                        <a href="#" class="card-link">Card link</a>
                        <a href="#" class="card-link">Another link</a>
                    </div>
                </div>
            </carousel>

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
    background-color: $bg;
}
.all{
    background-color: $bg;

}
    
.tit-c{
    color: $green;
    font-weight: 100;
}



.owl-carousel .owl-nav .owl-prev,
.owl-carousel .owl-nav .owl-next {
  font-weight: bold;
  font-size: 24px;
  font-family: monospace;
  padding: 10px 20px;
}

.owl-carousel .owl-nav .owl-prev {
  color: blue;
}
.owl-carousel .owl-nav .owl-prev:hover {
  color: aqua;
}

.owl-carousel .owl-nav .owl-next {
  color: red;
}
.owl-carousel .owl-nav .owl-next:hover {
  color: yellow;
}
    


</style>