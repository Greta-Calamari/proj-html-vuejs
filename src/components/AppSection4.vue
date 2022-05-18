<template>
<div>

    <div class="container">
        <div class="row">
            <div class=" col-12 col-sm-12 col-md-3 col-lg-3 text-center bord mt-5">
                <h3 class="tit-">Succesfully</h3>
                <h3 class="tit-">trained</h3>
                <h1 class="tit-g hovv">1790</h1>
                <p>ENROLLED LAERNERS</p>

            </div>
            <div class="col-12 col-sm-12 col-md-3 col-lg-3  text-center bord mt-5">
                <h3 class="tit-">Proudly</h3>
                <h3 class="tit-">Received</h3>
                <h1 class="tit-g hovv" >19</h1>
                <p>COUNTRYWIDE AWARDS</p>

            </div>
            <div class="col-12 col-sm-12 col-md-3 col-lg-3  text-center bord mt-5">
                <h3 class="tit-">Firmly</h3>
                <h3>Established</h3>
                <h1 class="tit-g hovv" >24</h1>
                <p>LOCAL BRANCHES</p>

            </div>
            <div class="col-12 col-sm-12 col-md-3 col-lg-3  text-center bord mt-5">
                <h3 class="tit-">Getting</h3>
                <h3 class="tit-">Featured on</h3>
                <h1 class="tit-g hovv">1090</h1>
                <p>BLOG POSTS</p>

            </div>

        </div>
    </div>


<div class="sub-sec">

    <div class="container">
        <div class="row pad">
            <div class="col-12 col-sm-12 col-md-12 col-lg-4 ">
                <p class="lh" >ENJOYABLE INSIGHTS</p>
                <h4 class="tit- lh">Most Viewed <span class="tit-gr">Best Blogs</span> </h4>
                <ul>
                    <li class="lh">
                        <i class="fa-solid fa-arrow-right-long tit-"></i>
                        <span class="tit-"> Become a Better Blogger: Content Planning</span> 

                    </li>
                    <li class="lh">
                        <i class="fa-solid fa-arrow-right-long tit-"></i>
                        <span class="tit-"> Promoting Your Online Business on Pinterest</span> 
                    </li>
                    <li class="lh">
                        <i class="fa-solid fa-arrow-right-long tit-"></i>
                        <span class="tit-"> Gamification and Game-Based Learning</span>
                    </li>
                    <li class="lh">
                        <i class="fa-solid fa-arrow-right-long tit-"></i>
                        <span class="tit-"> Designing an Online from Expert's Perspective</span>
                    </li>
                    <li class="lh">
                        <i class="fa-solid fa-arrow-right-long tit-"></i>
                        <span class="tit-"> Why Online Courses Are the Future of Education</span>
                    </li>

                </ul>

            </div>
            <div class="col-12 col-sm-12 col-md-12 col-lg-4 my-2 hovv">
                <div class="card" style="width: 18rem;">
                    <img src="../assets/images/artist-blog-03-480x352.jpeg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">ARTIST</p>
                        <h5 class="card-title tit-">Brush Strokes Energize Trees in Paintings</h5>
                        <span class="card-text text-muted"> 
                            <i class="fa-solid fa-calendar-week"></i>
                            May 15,2020
                        </span>

                        <span class="card-text px-3 text-muted"> 
                            <i class="fa-solid fa-eye"></i>
                            688 views

                        </span>
                        
                        
                    </div>
                </div>

            </div>
            
            <div class="col-12 col-sm-12 col-md-4 col-lg-4 hovv">
                <div class="card" style="width: 18rem;">
                    <img src="../assets/images/artist-blog-01-480x352.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <p class="card-text">ARTIST</p>
                        <h5 class="card-title tit-">Pocket-Sized Notebooks Hold Miniature Paintings</h5>
                        <span class="card-text text-muted"> 
                            <i class="fa-solid fa-calendar-week"></i>
                            May 15,2020
                        </span>

                        <span class="card-text px-3 text-muted"> 
                            <i class="fa-solid fa-eye"></i>
                            603 views

                        </span>
                        
                        
                    </div>
                </div>

            </div>



        </div>


    </div>
</div>



    <div class="container text-center hovve">
        <h4 class="tit-"> Subscribe <span class="tis-gr"> Newsletters</span> </h4>
        <p class="text-muted">Enter tour email to register to our newsletter subscription </p>
        <p class="text-muted">delivered on a regular basis!</p>

        <div class="input-group">
            <input type="text" class="form-control" placeholder="Enter your email" aria-label="Recipient's username" aria-describedby="button-addon2">
            <button class="btn" type="button" id="button-addon2">Subscribe</button>
        </div>

        <div class="circle c11"></div>
        <img src="../assets/images/maxcoach-shape-02.png" class="c22" alt="">

    </div>

    
</div>


        

</template>

<script>
export default {
    name:'AppSection4',
    
}
</script>

<style lang="scss" scoped>
@import '../styles/vars.scss';
.hovv{
    transition: 1s;
}
.hovv:hover{
    -webkit-transform: scale(1.3);
    -ms-transform: scale(1.3);
    transform: scale(1.3);

}
.hovve{
    transition: 1s;
}

.hovve:hover .c22,.hovve:hover .c11{
   -webkit-animation: swing 1s ease;
        animation: swing 1s ease;
        -webkit-animation-iteration-count: infinite;
        animation-iteration-count: infinite;


}


.bord{
    border-left: 1px solid $bg;
    border-right: 1px solid $bg;
}
.tit-{
    color: $violet;
    font-weight: 700;
}
.tit-g{
    color: $green;
    font-weight: 700;

}

.sub-sec{
    background-color: $pink;
}

.tit-gr{
    color: $green;

}

.pad{
    padding: 80px;
}

.btn{
    width: 45% !important; 
    
}

.input-group{
    width: 40% !important;
    height: 20% !important;
    margin: 0 auto !important;
}
.circle{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    border: 5px solid $green;
}


.c11{
    position: relative;
    bottom: 80px;
    right: 200px;

}

.c22{
    position: relative;
    bottom: 180px;
    left: 500px;

}
.lh{
    line-height: 50px;
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