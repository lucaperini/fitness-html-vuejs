<template>
    <div class="container">
        <div class="cards-wrapper row row-cols-3 justify-content-center">
            <div class="card-item text-center text-white p-5">
                <div class="card-content">
                    <i class="card-icon fas fa-mobile"></i>
                    <h4>Team training</h4>
                    <h5>Find a partner</h5>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi, quasi qui ipsam earum laudantium nulla ducimus</p>
                </div>
                <div>
                    <p class="videos d-inline-block text-white">Find a partner</p>
                    <i class="card-arrow fas fa-angle-right"></i>
                </div>
            </div>
            <div class="card-item text-center text-white p-5">
                <div class="card-content">
                    <i class="card-icon fas fa-dumbbell"></i>
                    <h4>Crossfit workout</h4>
                    <h5>Push your limits</h5>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi, quasi qui ipsam earum laudantium nulla ducimus</p>
                </div>
                <div>
                    <p class="videos d-inline-block text-white">Learn about crossfit</p>
                    <i class="card-arrow fas fa-angle-right"></i>
                </div>
            </div>
            <div class="card-item text-center text-white p-5">
                <div class="card-content">
                    <i class="card-icon fas fa-weight-scale"></i>
                    <h4>Weight Loss Plan</h4>
                    <h5>Shed those pounds</h5>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi, quasi qui ipsam earum laudantium nulla</p>
                </div>
                <div>
                    <p class="videos d-inline-block text-white">Schedule a workout</p>
                    <i class="card-arrow fas fa-angle-right"></i>
                </div>
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


h5 {
    color: #fff941;
    margin-bottom: 2.5rem;
}
.container {
    background-color:#060606;
    width:100%;
}

.card-item {
    width: 350px;
    height: 500px;
    border: 3px solid #4154ff;
    border-radius: 10px;
    margin-right: 2.5rem;
    transition: all .2s ease-in-out;
}

.card-item:hover {
 transform: scale(1.1); 
}

.card-item p{
    color: #78787a;
    margin-bottom: 2rem;
    font-weight:600;
    align-items:center;
}

.card-icon {
    font-size: 4rem;
    margin-bottom: 2rem;
}

.cards-wrapper {
    margin-top: 100px;
    padding-bottom: 100px;
}

.card-arrow {
    margin-left: .3rem;
    font-size: .8rem;
    font-weight: 600;
}

.card-content {
    margin-top:5%;
}


</style>