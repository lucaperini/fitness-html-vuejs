<template>
    <header>
    
      <nav class="navbar navbar-expand-lg">
        <div class="container">
        
        <a class="navbar-brand" href="#">
        <img class="main-logo" src="../assets/images/logo-2x.png" alt="">
        </a>
        <div  id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0 fs-5">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Services</a>
        </li>
        
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Videos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Blog</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Store</a>
        </li>
      </ul>
    </div>
  </div>

</nav>




    
  </header>
</template>

<script>
export default {
    name: "IndexHeader"

}
</script>

<style lang="scss" scoped>
    
    .navbar {
        background-color: #060606;
        height:100px;
    }

    ul li {
        color: grey;
        margin-right:1rem;
    }

    .nav-item li{
        color: white;
        padding: 12rem 0;
    }
    
    .main-logo {
        width:50%;
        
    }
</style>