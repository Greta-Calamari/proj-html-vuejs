<template>
    <div class="container mt-0">
        <div class="row ">
            <div class="col-3 text-center bord mt-5">
                <h3 class="tit-">Succesfully</h3>
                <h3 class="tit-">trained</h3>
                <h1 class="tit-g">1790</h1>
                <p>ENROLLED LAERNERS</p>

            </div>
            <div class="col-3 text-center bord mt-5">
                <h3 class="tit-">Proudly</h3>
                <h3 class="tit-">Received</h3>
                <h1 class="tit-g" >19</h1>
                <p>COUNTRYWIDE AWARDS</p>

            </div>
            <div class="col-3 text-center bord mt-5">
                <h3 class="tit-">Firmly</h3>
                <h3>Established</h3>
                <h1 class="tit-g" >24</h1>
                <p>LOCAL BRANCHES</p>

            </div>
            <div class="col-3 text-center bord mt-5">
                <h3 class="tit-">Getting</h3>
                <h3 class="tit-">Featured on</h3>
                <h1 class="tit-g">1090</h1>
                <p>BLOG POSTS</p>

            </div>

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

.bord{
    border-left: 1px solid $bg;
    border-right: 1px solid $bg;
}
.tit-{
    color: $violet;
}
.tit-g{
    color: $green;
    font-weight: 700;

}
</style>