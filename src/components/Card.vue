<template>
    <div class="container">
        <div class="cards-wrapper row row-cols-3 align-items-center">
            <div class="card-item text-center text-white p-5">
                <i class="fa-light fa-watch-fitness"></i>
                <h4>Team training</h4>
                <h5>Find a partner</h5>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi, quasi qui ipsam earum laudantium nulla ducimus alias suscipit porro, reiciendis iusto, in tempore sit soluta excepturi velit deleniti iure ratione?</p>
                <div>
                    <p class="videos d-inline-block">Find a partner</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                </div>
            </div>
            <div class="card-item">
                ciccio
            </div>
            <div class="card-item">
                ciccio
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'CardIndex'

}
</script>

<style lang="scss" scoped>
.container {
    background-color:#060606;
    
    width:100%;
}
.card-item {
    width: 400px;
    height: 560px;
    border: 3px solid #4154ff;
    border-radius: 10px;
    margin-right: 2.5rem;
    
}

.cards-wrapper {
    margin-top: 100px;
    padding-bottom: 100px;
}

</style>