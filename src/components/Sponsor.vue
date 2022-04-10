<template>
    <div class="container-fluid">
        <div class="row row-cols-4">
            <div class="col-12 d-flex justify-content-center">
                <div class="sponsor-item">
                    <img src="../assets/images/sponsor-1-2x.png" alt="">
                    <i class="sponsor-icon fas fa-water text-center fs-1 mb-2"></i>
                    <p class="sponsor-text">Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
                    <p class="videos d-inline-block">Visit Yoga Studio</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                </div>
                <div class="sponsor-item">
                    <img src="../assets/images/sponsor-2-2x.png" alt="">
                    <i class="sponsor-icon fas fa-water text-center fs-1 mb-2"></i>
                    <p class="sponsor-text">Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
                    <p class="videos d-inline-block">Join Fitness Center</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                </div>
                <div class="sponsor-item">
                    <img src="../assets/images/sponsor-3-2x.png" alt="">
                    <i class="sponsor-icon fas fa-water text-center fs-1 mb-2"></i>
                    <p class="sponsor-text">Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
                    <p class="videos d-inline-block">Learn about FC</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                </div>
                <div class="sponsor-item">
                    <img src="../assets/images/sponsor-4-2x.png" alt="">
                    <i class="sponsor-icon fas fa-water text-center fs-1 mb-2"></i>
                    <p class="sponsor-text">Tristique aliquam in nullam habitasse nunc, amet vel consectetur. Nulla in suspendisse dolor, aliquet.</p>
                    <p class="videos d-inline-block">Visit Power Gym</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                </div>
                
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SponsorIndex'

}
</script>

<style lang="scss" scoped>
.container-fluid {
    background-color: white;
    padding-top: 3rem;
    padding-bottom:5rem;
}
.sponsor-item {
    width:300px;
    height: 350px;
    text-align:center;
    flex-direction:column;
    padding:2rem;
}
.sponsor-item img {
    width:60%;
    margin-left: 50px;
    align-items: center;
    padding-bottom:.5rem;
    display:block;
}
.all-arrow {
    margin-left:.5rem;
    font-size: .8rem;
}

.sponsor-icon {
    color: #4154ff;
}

.sponsor-text {
    color: #78787a;
}
</style>