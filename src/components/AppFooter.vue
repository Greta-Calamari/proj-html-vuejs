<template>
<div class="bg">

    <div class="container p-5">
        <div class="row">
            <div class="col-12 col-sm-12 col-md-6 col-lg-6">

                <ul>
                    <li class="lh lh-g">{{myarray[0].name}}</li>
                    <li class="lh gr">{{myarray[1].name}} </li>
                    <li class="lh gr">{{myarray[2].name}} </li>
                    <li class="lh gr">{{myarray[3].name}} </li>
                    <li class="lh gr">
                       <a href="https://www.facebook.com/groups/3722639544507216"><i class="gr fa-brands fa-facebook-square px-2 ico"></i></a>
                        <i class="gr fa-brands fa-twitter px-2 ico"></i>
                        <i class="gr fa-brands fa-instagram px-2 ico"></i>
                        <i class="gr fa-brands fa-linkedin px-2 ico"></i>


                    </li>
                </ul>
            </div>
            <div class="col-12 col-sm-12 col-md-6 col-lg-6 d-flex">

                <ul class="px-5">
                    <li class="lh lh-g ">{{myarray[4].name}}</li>
                    <li class="lh gr">{{myarray[5].name}}</li>
                    <li class="lh gr">{{myarray[6].name}}</li>
                    <li class="lh gr">{{myarray[7].name}}</li>

                </ul>

                <ul>
                    <li></li>
                    <li class="lh mt-5 gr">{{myarray[8].name}}</li>
                    <li class="lh gr">{{myarray[9].name}}</li>
                    <li class="lh gr">{{myarray[10].name}}</li>
                </ul>

                <ul>
                    <li class="lh lh-g " >{{myarray[11].name}}</li>
                    <li class="lh gr">{{myarray[12].name}}</li>
                    <li class="lh gr">{{myarray[13].name}}</li>
                    <li class="lh gr">{{myarray[14].name}}</li>
                </ul>
            </div>


        </div>

        <div class="text-muted text-center mt-5 pos">
            <i class="fa-solid fa-copyright gr"></i>
            <span class="gr"> 2020</span>
            <span class="gr"> Maxcoach. All Rights Reserved</span>
            
            
        </div>
        <div class="down">
            <a href="#start" class="down">
            <i class="fa-solid fa-arrow-up-long"></i>

            </a>

        </div>

        

    </div>
</div>
</template>

<script>
import  dati from '../dati2.json'
export default {
    name:'AppFooter',
    data(){
        return{
            myarray:dati,
        }
    }
    
}
</script>

<style lang="scss" scoped>
@import '../styles/vars.scss';

.gr:hover{
    color: $green;
}

.bg{
    background-color: $bg ;
}

.ico{
    font-size: 30px;
    color: $gray;
}
.lh{
    line-height: 50px;
}
.lh-g{
    font-size: 20px;
    font-weight: 700;
}

.pos{
    position: relative;
}

.down{
    position: absolute;
    right: 0;
    text-align: center;
    line-height: 50px;
    width: 50px;
    height: 50px;
    color: $white;
    border-radius: 50%;
    background-color: $green;
}

</style>