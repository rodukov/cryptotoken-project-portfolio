<template>
<div class="footer">
        <p class="default center item" style="margin-left: auto;">NiceToken 2022</p>
        <div class="social">
            <a class="default" href="#"><img alt="Twitter" class="img" src="../assets/icons8-twitter-circled-90.png"></a>
            <a class="default" href="#"><img alt="Github" class="img" src="../assets/icons8-github-90.png"></a>
            <a class="default" href="#"><img alt="Email" class="img" src="../assets/icons8-circled-envelope-100.png"></a>
        </div>
</div>
</template>

<script>
export default { name: 'footers' }
</script>

<style scoped>
.footer {
    margin-left: 200px;
    margin-right: 200px;
    display: flex;
    align-items:center;
    justify-content: center; 
}
.item {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 15px;
    line-height: 18px;
    text-align: center;

    color: #000000;
    padding-top: 33px;
    padding-bottom: 33px;
}
.items {
    display: flex;
}
.social {
    display: flex;
    margin-left: auto;
    margin-right: 25px;
}
.img {
    width: 33px;
    height: 33px;
    display: block;

}
</style>