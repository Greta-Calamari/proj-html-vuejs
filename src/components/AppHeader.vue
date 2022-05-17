<template>
<div class="border">
  <div class="utility">
    <ul class="icons">
      <li><i class="fa-solid fa-ruler"></i></li>
      <li><i class="fa-solid fa-life-ring"></i></li>
      <li><i class="fa-solid fa-book"></i></li>
      <li><i class="fa-solid fa-cart-shopping"></i></li>
    </ul>

  </div>

<nav id="start" class="navbar navbar-expand-lg bg-light d-flex justify-content-center ">
  <div class="d-flex justify-content-between">
    <a class="navbar-brand" href="#">
        <img src="../assets/images/dark-logo.png" class="w-50" alt="">
    </a>
    <div class="collapse navbar-collapse" id="navbarScroll">
      <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[0].name}}
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[1].name}}
            
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[2].name}}
             
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[3].name}}
             
            
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[4].name}}
          
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item dropdown">
          <a class="nav-link color-nav dropdown-toggle hov" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            {{myArray[5].name}}
            
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>

        <li class="nav-item px-3">
          <i class="fa-solid fa-circle-user hov" ></i>
        </li>

      
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search..." aria-label="Search">
        <i class="fa-solid fa-magnifying-glass glass"></i>

      </form>
        
      

      
    </div>
  </div>
</nav>


    </div>
</template>

<script>
import  dati from '../dati.json'
export default {
    name:'AppHeader',
    data(){
        return{
          myArray:dati,
          

        }
    }
    
}
</script>

<style lang="scss" scoped>
@import "../styles/vars.scss";

.hov:hover{
  color: $green;

}


.utility{
  position:fixed;
  right: 0;
  box-shadow: -11px 5px 20px 4px rgba(0,0,0,0.47);
  z-index: 1000;
  
 
  
}

.icons{
  line-height: 40px;
  padding: 10px;
}
.border{
    box-shadow: -11px 5px 20px 4px rgba(0,0,0,0.47);
}

.glass{
    position: relative;
    top:10px;
    right:40px;
    color: $green;
}
.color-nav{
  color: $gray;
}


</style>