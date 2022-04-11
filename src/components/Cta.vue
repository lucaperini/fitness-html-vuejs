<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 relative">
                <div class="quote-wrapper d-flex align-items-center">
                    <h1 class="quote text-center">"I've failed over and over again in my life. And that is why I succeed."</h1>
                    <i class="fas fa-water text-center text-warning fs-1 p-2 separator mb-2"></i>
                    <p class="cta-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias illum tempore explicabo, in ipsum eros adipiscing elit</p>
                    <button class="btn rounded-pill bg-primary text-white fw-bold px-4 py-2">Buy Avada today<i class="icon-avada fas fa-arrow-right align-items-center"></i></button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CtaIndex'
}
</script>

<style lang="scss" scoped>


h1 {
    color:white;
    font-size:3rem;
}

.container-fluid {
    height:600px;
    width:100%;
    background-image: url('../assets/images/banner2-2x.jpg');
    background-size:cover;
    background-position:center;
}

.quote-wrapper {
        width:50%;
        flex-direction:column;
        margin:auto;
        margin-top:9%;
    }

.cta-text {
    font-size: 1.2rem;
    text-align:center;
    color: lightgrey;
}

.icon-avada {
    margin-left:.5rem;
}


</style>