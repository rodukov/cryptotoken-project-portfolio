<template>
<div class="footer">
    <div class="items">
        <div class="itemc"><p class="default center item">NiceToken 2022</p></div>
        <div class="social">
            <p class="default"><img alt="Twitter" class="img" src="../assets/icons8-twitter-circled-90.png"></p>
        </div>
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
}
.img {
    width: 33px;
    height: 33px;
    display: block;

}
</style>