<template>
    <div class="bg container-fluid">
        <div class="row justify-content-start ml-5 p-5">
            <div class="content col">
                <h5 class="above-title mb-2">Join our mailing list today</h5>
                <h1 class="title mb-3">Insider offers & flash sales in your inbox every week.</h1>
                <i class="d-block fas fa-water text-center text-warning fs-1 mb-3"></i>
                <input class="mailing bg-light rounded-pill text-info mr-1 p-2" placeholder="Inserisci il tuo indirizzo e-mail...">
                <button class="subscribe btn bg-primary rounded-pill text-white">Subscribe</button>
                <h5 class="under-title mt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae iste exercitationem tempora cumque? Lorem ipsum dolor sit amet</h5>
            </div>
        </div>

    </div>
</template>

<script>
export default {
    name: 'MailingIndex'

}
</script>

<style lang="scss" scoped>
.bg{
    background-size: cover;
    background-position-x:right;
    padding-bottom:10rem;
    width:100%;
    background-image: linear-gradient(90deg, rgb(6 6 7) 45%,rgba(6,6,7,0) 75%),url('../assets/images/banner1-2x.jpg');
}

.above-title {
    color:#bc0428;
}

.under-title {
    color: #78787a;
    font-weight:400;
    margin-top:4rem;
    font-size:1.2rem;
    width:720px;
    line-height:1.5rem;
    
}

.title {
    color: white;
    font-size: 3rem;
    width:50%;
    
}

.content {
    margin-left:6%;
    margin-top:5%;
}
.mailing{
    width:500px;
    padding:10px 8px;
    margin-top:2rem;
    border: none;
    margin-right:1rem;
    
}
.subscribe{
    width: 220px;
    padding:10px 8px;
    border: none;
    margin-right:2rem;
    
}

</style>