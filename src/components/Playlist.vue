<template>
    <div class="container-fluid pb-5">
        <div class="row row-cols-2">
            <div class="col-6 relative">
                <img class="service-img" src="../assets/images/service15-2x.jpg" alt="">
                <div>
                    <i class="play-btn fas fa-play"></i>
                </div>
            </div>
            <div class="right-content col-6">
                <p class="tune-up">Tune up your workouts</p>
                <h2 class="mb-4">The best health & fitness advice online</h2>
                <div class="d-flex">
                    <div>
                    <img class="d-block mb-4" src="../assets/images/unnamed.jpg" alt="">
                </div>
                <div class="youtube-channel">
                    <p class="ytb-user">ThemeFusion</p>
                    <img class="ytb-counter" src="../assets/images/youtube-counter.png" alt="">  
                </div>
                </div>
                
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eius fuga assumenda dignissimos, illo, ipsum dolor sit amet consectetur, adipisicing elit </p>
                <button class="yt-channel-button btn rounded-pill schedule text-white btn-youtube px-3"><i class="fab fa-youtube icon-ytb"></i>Visit my YouTube channel</button>
            </div>
        </div>
        <div class="container mt-5 p-5">
            <div class="row row-cols-3">
                <div class="latest col-12 d-flex">
                    <p class="featured">Featured playlists</p>
                    <div>
                    <p class="videos d-inline-block">View all videos</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                    </div>
                </div>
                <div class="relative">
                    <div>
                    <i class="playlist-btn fas fa-play"></i>
                    </div>
                    <img class="playlist-img" src="../assets/images/video2-2x.jpg" alt="">
                    <div class="text-center">
                        <p class="mt-4 mb-1">Thighs & glute workout</p>
                        <p class="text-primary">Increase your mobility</p>
                    </div>
                </div>
                <div class="relative">
                    <div>
                        <i class="playlist-btn fas fa-play"></i>
                    </div>
                    <img class="playlist-img" src="../assets/images/video7-2x.jpg" alt="">
                    <div class="text-center">
                        <p class="mt-4 mb-1">Lift, firm & perk up</p>
                        <p class="text-primary">Feel young again</p>
                    </div>
                </div>
                <div class="relative">
                    <div>
                        <i class="playlist-btn fas fa-play"></i>
                    </div>
                    <img class="playlist-img" src="../assets/images/video9-2x.jpg" alt="">
                    <div class="text-center">
                        <p class="mt-4 mb-1">Slim and trim your waist</p>
                        <p class="text-primary">Shed those extra pounds</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'PlaylistIndex'

}
</script>

<style lang="scss" scoped>
@import "./src/styles/partials/_variables.scss";

h2{
    font-size: 4rem;
}
.container-fluid {
    background-color:white;
    
}
.service-img {
    width:90%;
    margin-top:-50px;
    margin-left:-12px;
    border-bottom-right-radius: 40px;
    border-top-right-radius: 5px;
}

.tune-up {
    font-size: 1.5rem;
    color: $blueColor;
}

.play-btn {
    background-color: white;
    width: 15px;
    height: 15px;
    color:$blueColor;
    border-radius:50%;
    position:absolute;
    padding:1.8rem;
    top:48%;
    left:44%;
    transform: translate(-44%, -48%);
}

.playlist-btn {
    background-color: white;
    width: 10px;
    height: 10px;
    color: $blueColor;
    border-radius:50%;
    position:absolute;
    padding:1rem;
    top:40%;
    left:50%;
    transform: translate(-50%, -50%);
}

.right-content {
    margin-top:10rem;
    width:600px;
}

.yt-channel-button {
    background-color: $redColor;
    margin-top:1rem;
}

.playlist-img {
    width:375px;
    height:235px;
    border-radius:5px;
    border-bottom-right-radius:3rem;
    margin-top:1rem;
}

.text-primary {
    margin-top:0
}

.videos, .all-arrow {
    font-size:.9rem;
    margin-right: .2rem;
}

.featured {
    font-size:1.5rem;
}
.icon-ytb {
    margin-right:.5rem;
}
.latest {
    width:96%;
    justify-content:space-between;
}
.ytb-counter {
    width:50%;
    padding-top:0;
}

.ytb-user {
    color: #bc8b96;
    margin-bottom:10px;
    

}
.youtube-channel {
    margin-left: 1rem;
    line-height:0;
}
</style>