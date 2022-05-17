<template>
    <div class="">
        <img src="../assets/images/wave.svg" alt="">
<div class="all">

    <div class="container-fluid">
        <p class="text-center pt-5 mb-1">GREAT WORDS MAXCOACH</p>
        <h4 class="title text-center mb-5 fs-2">Our <span class="tit-c">top learners' </span>verbatim </h4>
    </div>
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
        <ol class="carousel-indicators">
            <li  data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></li>
            <li  data-bs-target="#myCarousel" data-bs-slide-to="1"  aria-label="Slide 2"></li>
        </ol>


        <div class="carousel-inner">
            <div class="carousel-item active">
                <div class="container d-flex">
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
             
             
                </div>
            </div>


            <div class="carousel-item">
                <div class="container">
                <h1>esempio 2</h1>
                <p>random</p>
                </div>
            </div>

    </div>
</div>
</div>




</div>
</template>

<script>

export default {
    name:'AppSection3',
    data(){
        return{
            

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

.carousel-item{
    background:$bg;
    height: 900px;
    
}
    


</style>