<template>
<div class="view_all" style="margin-top: 30px;">
    <div><p class="default center main">All NFT companies<br> that use our token</p></div>
    <div><p class="default center description" style="padding-bottom: 35px;">Our token is used by a huge<br>number of companies. You can<br> become one of them.</p></div>
    <div><p class="default center" style="margin-bottom: 30px;"><a class="default link" href="#">View all</a></p></div>
</div>
</template>

<script>
export default { name: 'view_all' }
</script>

<style scoped>
.view_all {
    margin-left: 200px;
    margin-right: 200px;
    background: linear-gradient(0deg, rgba(143, 195, 255, 0.15), rgba(143, 195, 255, 0.15)), #FFFFFF;
    border-radius: 50px;
    padding-top: 17px;
    padding-bottom: 17px;
}
.main {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 65px;
    line-height: 79px;

    color: #000000;
}
.description {

    margin-top: 35px;
    margin-bottom: 35px;

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 30px;
    text-align: center;

    color: #575757;
}
.link {
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 119px;
    padding-right: 119px;
    background: #2EB7E2;
    border-radius: 5px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 30px;
    text-align: center;
    color: #FFFFFF;
    text-decoration: none;
    transition: .2s;
}
.link:hover {
    background: #35aed3;
}
</style>