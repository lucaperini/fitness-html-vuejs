<template>
    <header class="container p-3"> 
        <div class="row">
            <div class="col-12 d-flex justify-content-center">
                <a href="">
                <img class="main-logo" src="../assets/images/logo-2x.png" alt="">
                </a>
                <nav>
                    <ul>
                        <a href=""><li>Home</li></a>
                        <a href=""><li>Services</li></a>
                        <a href=""><li>About</li></a>
                        <a href=""><li>Videos</li></a>
                        <a href=""><li>Blog</li></a>
                        <a href=""><li class="mx-1">Store</li></a>
                    </ul>
                </nav>
                <div>
                    <a class="nav-link btn-sm new d-inline-block">new</a>
                    <button class="btn rounded-pill text-white schedule">Schedule a workout</button>
                    <div class="d-inline-block">
                        <i class="fas fa-cart-shopping cart mx-5"></i>
                        <i class="fas fa-search cart"></i>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "IndexHeader",
    data: function() {
        return {
        
        linkList: [
                {
                    text:"Home",
                    url:"#",
                },
                {
                    text:"Services",
                    url:"#",
                },
                {
                    text:"About",
                    url:"#",
                },
                {
                    text:"Videos",
                    url:"#",
                },
                {
                    text:"Blog",
                    url:"#",
                },
                {
                    text:"Store",
                    url:"#",
                },
            ],
        }
    },
}
</script>

<style lang="scss" scoped>

.header{
    background-color: #060606;
}

ul {
    list-style-type: none;
    margin-top:1rem;
}

ul li {
    color: #78787a;
    margin-right:1.5rem;
    display:inline-block;
    font-size:1.3rem;
}

.active{
    color: white;
    }

.main-logo {
    width:45%;
    margin-top:1rem;
    
}

.new {
    background-color: rgb(255, 249, 102);
    font-size:.8rem;
    color:black;
    text-decoration: none;
    padding:2px 5px 3px;
    text-align:center;
    margin-top:1.3rem;
    margin-right:1.5rem;
}

.schedule {
    font-size: 1rem;
    padding: 8px 20px 10px;
    background-color: #4257ef;
    font-weight:500;
    margin-left:1rem;
    
}

.schedule.btn{
    border:none;
}

.cart {
    color:#78787a;
    vertical-align:bottom;
    }

.nav-link:hover {
    color: #78787a;
}

.nav-link:active {
    color: white;
}
a:active {
    color:white;
}
</style>