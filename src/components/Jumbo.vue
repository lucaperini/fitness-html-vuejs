<template>
    <div class="bg container-fluid">
        <div>
            <i class="play-btn fas fa-play"></i>
        </div>
        <div class="row p-5">
            <div class="content col mt-5">
                <h5 class="above-title mb-2">Certified fitness professional</h5>
                <h1 class="title mb-2">Take Control Of Your Health</h1>
                <i class="fas fa-water text-center text-warning fs-1"></i>
                <h5 class="under-title pb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ab perspiciatis corrupti...</h5>
                <button class="btn bg-primary rounded-pill schedule text-white btn-youtube mr-1"><i class="fab fa-youtube"></i>Visit my youtube channel</button>
                <button class="btn btn-outline-info rounded-pill text-white btn-avada">Buy Avada today    <i class="fas fa-arrow-right align-items-center"></i></button>
            </div>
        </div>
        <div class="container">
            <div class="row row-cols-3">
                <div class="relative">
                    <img class="jumbo-img" src="../assets/images/service6-2x.jpg" alt="">
                    <div class="jumbo-description">
                        <i class="fas fa-water text-center text-white fs-1"></i>
                        <h2 class="service-title">Crossfit workout</h2>
                        <h4 class="service-subtitle">Push your limits</h4>
                    </div>
                </div>
                <div class="relative">
                    <img class="jumbo-img" src="../assets/images/box1-2x.jpg" alt="">
                    <div class="jumbo-description">
                        <i class="fas fa-water text-center text-white fs-1"></i>
                        <h2 class="service-title">New gym apparel</h2>
                        <h4 class="service-subtitle">Look good, feel good</h4>
                    </div>
                </div>
                <div class="relative">
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
    filter: brightness(50%);
}

.service-title {
    color: white;
    font-weight:600;
}

.service-subtitle {
    color: rgb(255, 249, 102);
    font-weight:600;
}

.content {
    margin-left:6%;
}

.above-title {
    color:#bc0428;
}

.under-title {
    color: #78787a;
    font-weight:400;
    margin-top:1rem;
    font-size:1.2rem;
    
}

.title {
    color: white;
    font-size: 4rem;
}

.btn-youtube {
    padding: 12px 20px 10px;
    background-color: #4257ef;
    margin-right:1rem;
}

.btn-avada {
    padding: 8px 25px 8px;
    border-color:gray;
    
}

.play-btn {
    background-color: white;
    width: 15px;
    height: 15px;
    color:#4257ef;
    border-radius:50%;
    position:absolute;
    padding:1.8rem;
    top:34%;
    right:21%;
}
</style>