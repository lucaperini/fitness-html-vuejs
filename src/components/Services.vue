<template>
    <div class="container-fluid">
        <div class="quote-wrapper p-5">
            <h1 class="quote text-center">"How you respond to the challenge in second half will determine what you become after the game, wheter you are a winner or a loser."</h1>
            <i class="fas fa-water text-center text-warning fs-1 p-2 separator"></i>
            <div class="author-quote-wrapper">
                <img class="testimonial" src="../assets/images/avatar-1-2x.jpg" alt="">
                <p class="fw-bold fs-5 text-white mt-2 ml-5 mr-1 d-inline-block">Brad Johnson</p><span class="mt-2 fs-5">Las Vegas</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'ServicesIndex'
}
</script>

<style lang="scss" scoped>
@import "./src/styles/partials/_variables.scss";

h1 {
    font-size:3rem;
    color:white;
    text-align:center;
    margin-top:30%;
    margin-left:20%;
}

.container-fluid {
    background: rgb(22,36,206);
    background: linear-gradient(147deg, rgba(22,36,206,1) 0%, rgba(241,8,8,1) 81%);
}

.jumbo-img {
    width:400px;
    height:430px;
}

.quote-wrapper {
    width:80%;
}

.testimonial {
    border-radius:50%;
    width:10%;
    display:inline-block;
    margin-left:8%;
}

.author-quote-wrapper{
    margin-left:40%;
    margin-bottom:15%;
    padding:2px;
}

.separator {
    margin-left: 55%;
}

span,p {
    color: $greyColor;
    margin-left:1rem;
}

</style>