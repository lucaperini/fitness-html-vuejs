<template>
    <header class="container p-3"> 
        <div class="row">
            <div class="header-content col-12 d-flex">
                <a href="">
                <img class="main-logo" src="../assets/images/logo-2x.png" alt="">
                </a>
                <nav>
                    <ul v-for="(element, index) in linkList" :key="index">
                        <a href=""><li :class="element.myclass">{{element.text}}</li></a>
                    </ul>
                </nav>
                <div>
                    <a class="btn-sm new d-inline-block">new</a>
                    <button class="workout-button btn rounded-pill text-white schedule">Schedule a workout</button>
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
                    myclass:"text-white"
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
                    myclass:"m-0",
                },
            ],
        }
    },
}
</script>

<style lang="scss" scoped>
@import "./src/styles/partials/_variables.scss";

.container{
    margin-right:0;
}

.header{
    background-color: bgdarkColor;
}



ul{
    list-style-type: none;
    margin-top:1rem;
    display:inline-block;
    padding: 0;
    font-size: 1.3rem;
    
}

ul li {
    color: $greyColor;
    margin-right: 1.5rem;
    display: inline-block;
}


.main-logo {
    width: 50%;
    margin-top: 1rem;
}

.new {
    background-color: $yellowColor;
    font-size:.8rem;
    color:black;
    text-decoration: underlined;
    padding:2px 5px 3px;
    text-align:center;
    margin-top:1.3rem;
    margin-right:1rem;
    margin-left: .3rem;
}

.workout-button {
    font-size: 1rem;
    padding: 8px 20px 10px;
    background-color: $blueColor;
    font-weight:500;
    margin-left:1rem;
    border:none;
    transition: background-color .1 ease-in;
}

.workout-button:hover {
    background-color: $redColor;
}

.cart {
    color: $greyColor;
    vertical-align:bottom;
}

</style>