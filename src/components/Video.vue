<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 relative">
                <div>
                    <i class="play-btn fas fa-play"></i>
                </div>
                <div class="video-wrapper">
                    <h1>Crossfit workout of the day</h1>
                    <h2>November 15th, 2019</h2>
                    <p class="videos d-inline-block text-white">View all videos</p>
                    <i class="all-arrow fas fa-arrow-right-long"></i>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'VideoIndex'

}
</script>

<style lang="scss" scoped>
@import "./src/styles/partials/_variables.scss";

.container-fluid {
    height:550px;
    width:100%;
    background-image: url('../assets/images/banner14-2x.jpg');
    background-size:cover;
    background-position:center;
}

h1 {
    color:white;
    font-size: 3rem;
    margin-bottom:1rem;
}

.all-arrow {
    margin-left:.5rem;
    font-size: .8rem;
    color: white;
}

.video-wrapper {
    width:50%;
    margin:auto;
    margin-top:15%;
    text-align: center;
}

.video-wrapper h2 {
    color: $yellowColor;
    font-size:2rem;
}

.play-btn {
    background-color: white;
    width: 15px;
    height: 15px;
    color: $blueColor;
    border-radius:50%;
    position:absolute;
    padding:1.8rem;
    top:47%;
    left:50%;
    transform: translate(-50%, -50%);
    
}

</style>