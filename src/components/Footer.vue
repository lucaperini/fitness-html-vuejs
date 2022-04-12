<template>
    <div class="container-fluid">
        <div class="row row-cols-3">
            <div class="col-12 d-flex justify-content-center">
                <div class="footer-column">
                    <img src="../assets/images/logo-2x.png" alt="">
                    <p>Ac aliquam nequediam faucibus vitae purus turpis phasellus. Pellentesque consectetur amt purus ultrices mauris.
                    <div class="social-bar">
                        <i class="social-item fab fa-facebook-f"></i>
                        <i class="social-item fab fa-twitter"></i>
                        <i class="social-item fab fa-youtube"></i>
                        <i class="social-item fab fa-instagram"></i>
                        <i class="social-item fab fa-linkedin-in"></i>
                    </div>
                </div>
                <div class="footer-column">
                    <h5 class="recent text-white pb-4 text-uppercase">Recent Posts</h5>
                    <ul v-for="(element, index) in articlesList" :key="index">
                        <li><i class="all-arrow fas fa-angle-right"></i><a href="">{{element.title}}</a></li>
                        
                        
                        <!-- <li><i class="all-arrow fas fa-angle-right"></i><a href="">The best protein shake</a></li>
                        <li><i class="all-arrow fas fa-angle-right"></i><a href="">Ultimate cardio workout</a></li>
                        <li><i class="all-arrow fas fa-angle-right"></i><a href="">New juices available now</a></li>
                        <li><i class="all-arrow fas fa-angle-right"></i><a href="">Tips to find training partners</a></li>
                        <li><i class="all-arrow fas fa-angle-right"></i><a href="">20 best healthy recipes</a></li> -->
                    </ul>
                </div>
                <div class="footer-column">
                    <h5 class="text-white pb-4 text-uppercase">Contact informations</h5>
                    <p class="address">4746 Tipple Road Michigan 48449</p>
                    <p class="mobile text-white">Mobile: 1.800.000.0000</p>
                    <p class="text-white">Email: info@your-company.com</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterIndex',
    data: function(){
        return {
            articlesList: [
                {
                    title:"The best protein shake",
                    url:"#",
                },
                {
                    title:"Ultimate cardio workout",
                    url:"#",
                },
                {
                    title:"New juices available now",
                    url:"#",
                },
                {
                    title:"Tips to find training partners",
                    url:"#",
                },
                {
                    title:"20 best healthy recipes",
                    url:"#",
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>
@import "./src/styles/partials/_variables.scss";

h3 {
    text-align:center;
}

h5 {
    font-size:1.1rem;
}

ul {
    list-style-type: none;
}

ul li {
    margin-bottom: 1rem;
}

ul li a{
    text-decoration: none;
    color: white;
}

.container-fluid {
    background-color: $bgdarkColor;
    margin-top: 5rem;
    padding-bottom: 5rem;
}


.footer-column {
    width:300px;
    text-align: center;
    color: $greyColor;
    margin-right: 5rem;
}

.footer-column img {
    width:70%;
    margin-bottom:2rem;
}

.footer-column p {
    margin-bottom:2.5rem;
    font-size: 1.1rem;
}

.recent {
    padding-left: 2rem;
}

.footer-column .mobile{
    margin-bottom:.2rem;
}

.footer-column .address{
    margin-bottom:1rem;
}

.social-bar { 
    color: $redColor;
    font-size: 1rem;
}

.social-item{
    margin-right: 1rem;
}

.all-arrow {
    color:white;
    margin-right:.3rem;
}
</style>