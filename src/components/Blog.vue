<template>
    <div class="container-fluid">
        <div class="container">
            <div class="row row-cols-3">
                <div class="latest col-12 d-flex justify-content-between">
                    <p class="featured">Latest articles</p>
                    <div>
                    <p class="videos d-inline-block">Read all articles</p>
                    <i class="all-arrow fas fa-angle-right"></i>
                    </div>
                </div>
                <div>
                    <img class="blog-img" src="../assets/images/video2-2x.jpg" alt="">
                    <div>
                        <h4 class="mt-4 mb-0">The best protein shake</h4>
                        <p class="meta-text">By admin | November 26th, 2019 | Gym</p>
                    </div>
                </div>
                <div>
                    <img class="blog-img" src="../assets/images/video7-2x.jpg" alt="">
                    <div>
                        <h4 class="mt-4 mb-0">Ultimate cardio workout</h4>
                        <p class="meta-text">By admin | November 26th, 2019 | Gym</p>
                    </div>
                </div>
                <div>
                    <img class="blog-img" src="../assets/images/video9-2x.jpg" alt="">
                    <div>
                        <h4 class="mt-4 mb-0">New juices available now</h4>
                        <p class="meta-text">By admin | November 26th, 2019 | Gym</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BlogIndex'

}
</script>

<style lang="scss" scoped>


.container-fluid {
    padding-top: 100px;
    height: 700px;
    background-color: white;
}

.videos, .all-arrow {
    font-size:.9rem;
    margin-right: .2rem;
}

.featured {
    font-size:1.5rem;
}

.blog-img {
    width:400px;
    height:260px;
    margin-top:1rem;
}

h4, .meta-text {
    margin-left: 1rem;
}
.meta-text {
    color: #78787a;
}

.latest {
    width:96%;
}

</style>