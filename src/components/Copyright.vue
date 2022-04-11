<template>
    <div class="bg container-fluid relative">
        <div class="to-top">
            <i class="play-btn fas fa-angle-up text-white"></i>
        </div>
        <div class="row">
            <div class="col text-center">
                <p class="copy-text m-4">&copy;Copyright 2012 - 2022 | Avada theme by <a href="">ThemeFusion</a> | All right Reserved | Powered by <a href="">Wordpress</a></p>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: 'CopyrightIndex'

}
</script>

<style lang="scss" scoped>


.bg {
    background-color: #060606;
    height:80px;
    border-top: 1px solid #78787a;
}

.copy-text {
    color: #78787a;
}

.copy-text a {
    color: white;
}

.to-top {
    background-color: rgb(47, 47, 47);
    width: 50px;
    height: 40px;
    font-size: 1rem;
    padding:.5rem;
    text-align:center;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    position:absolute;
    bottom:0;
    right: 10%;
}

</style>