<template>
    <div class="bg container-fluid">
        <div>
            <i class="play-btn fas fa-play"></i>
        </div>
        <div class="box-demos">
            <i class="box-icon fab fa-connectdevelop"></i>
            <h5>Demos</h5>
        </div>
        <div class="box-discount">
            <h5 class="fs-2 pt-1 mb-0 text-success"><sup><small>$</small></sup>39</h5>
            <h5>On sale</h5>
        </div>
        <div class="row p-5">
            <div class="content col mt-5">
                <h5 class="above-title mb-2">Certified fitness professional</h5>
                <h1 class="title mb-2">Take Control Of Your Health</h1>
                <i class="fas fa-water text-center text-warning fs-1"></i>
                <h5 class="under-title pb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab perspiciatis corrupti...</h5>
                <button class="youtube-button btn rounded-pill btn-youtube px-3"><i class="icon-ytb fab fa-youtube"></i>Visit my youtube channel</button>
                <button class="avada-button btn rounded-pill">Buy Avada today<i class="icon-avada fas fa-arrow-right align-items-center"></i></button>
            </div>
        </div>
        <div class="container">
            <div class="row row-cols-3">
                <div class="relative">
                    <div class="overlay"></div>
                    <img class="jumbo-img" src="../assets/images/service6-2x.jpg" alt="">
                    <div class="jumbo-description">
                        <i class="fas fa-water text-center text-white fs-1"></i>
                        <h2 class="service-title">Crossfit workout</h2>
                        <h4 class="service-subtitle">Push your limits</h4>
                    </div>
                </div>
                <div class="relative">
                    <div class="overlay"></div>
                    <img class="jumbo-img" src="../assets/images/box1-2x.jpg" alt="">
                    <div class="jumbo-description">
                        <i class="fas fa-water text-center text-white fs-1"></i>
                        <h2 class="service-title">New gym apparel</h2>
                        <h4 class="service-subtitle">Look good, feel good</h4>
                    </div>
                </div>
                <div class="relative">
                    <div class="overlay"></div>
                    <img class="jumbo-img" src="../assets/images/box3-2x.jpg" alt="">
                    <div class="jumbo-description">
                        <i class="fas fa-water text-center text-white fs-1"></i>
                        <h2 class="service-title">Team training</h2>
                        <h4 class="service-subtitle">Find a partner</h4>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'JumboIndex',

}
</script>

<style lang="scss" scoped >
@import "./src/styles/partials/_variables.scss";

.container {
    width:84%;
}
.bg{
    
    background-size: cover;
    height:560px;
    width:100%;
    background-image: linear-gradient(90deg, rgb(6 6 7) 45%,rgba(6,6,7,0) 75%),url('../assets/images/slider82x-scaled.jpg');
}

.jumbo-description {
    position:absolute;
    top: 63%;
    left: 12%;
}

.relative {
    position:relative;
}

.jumbo-img {
    width:350px;
    height:400px;
    border-radius:5px;
    border-bottom-right-radius:3rem;
    margin-top:1rem;
}

.service-title {
    color: white;
    font-weight:600;
}

.service-subtitle {
    color: $yellowColor;
    font-weight:600;
}

.content {
    margin-left:6%;
}

.above-title {
    color: $redColor;
    font-size:1.5rem;
}

.under-title {
    color: $greyColor;
    font-weight:400;
    margin-top:1rem;
    font-size:1.2rem;
    
}

.title {
    color: white;
    font-size: 4rem;
}

.play-btn {
    background-color: white;
    width: 15px;
    height: 15px;
    color: $blueColor;
    border-radius:50%;
    position:absolute;
    padding:1.8rem;
    top:34%;
    right:21%;
}

.youtube-button {
    padding: 12px 20px 10px;
    background-color: $blueColor;
    margin-right:1rem;
    color:white;
    transition: background-color .1s ease-in;
}

.youtube-button:hover {
    background-color: $redColor;
    color:white;
}


.avada-button {
    background-color:transparent;
    border-radius:15px;
    border: 3px solid #78787a;
    padding:6px 20px;
    text-align: center;
    transition: background-color 1s easein;
    transition: color 1s easein;
    padding: 8px 25px 8px;
    border-color: $greyColor;
    color:white;
    
}

.avada-button:hover {
    color: $bgdarkColor;
    background-color: white;
    border-color: white;
}

.icon-ytb, .icon-avada {
    margin-right:.5rem;
    
}
.icon-avada {
    margin-left:.5rem;
}

.box-demos {
    width: 65px;
    height: 65px;
    background-color: white;
    border-radius:10px;
    position: absolute;
    top:20%;
    right:1rem;
}

.box-discount {
    width: 65px;
    height: 65px;
    background-color: white;
    border-radius:10px;
    position: absolute;
    top:28%;
    right:1rem;
}

.box-icon {
    font-size:1.8rem;
    margin-top: .5rem;
    margin-left: 1rem;
    margin-bottom: .2rem;
}

.box-demos h5, .box-discount h5{
    margin-left: .7rem;
    font-size: 1rem;
    color: #78787a;
}

.overlay {
    position:absolute;
    width:350px;
    height:420px;
    background-color: rgba(0, 0, 0, .3);
    border-radius:5px;
    border-bottom-right-radius:3rem;
}
</style>