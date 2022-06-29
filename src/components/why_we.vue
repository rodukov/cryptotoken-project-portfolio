<template>
<div class="why_we">
    <div class="item">
        <div><p class="default center" style="margin-top: 37px; "><img src="../assets/icons8-open-source-100.png" class="img" alt="Open Source"></p></div>
        <div><p class="default center main" style="margin-top: 13px; ">Open Source</p></div>
        <div><p class="default center description" style="margin-top: 13px; margin-bottom: 58px;">You can find source of token on GitHub</p></div>
    </div>
    <div class="item">
        <div><p class="default center" style="margin-top: 37px; "><img src="../assets/icons8-approval-90.png" class="img" alt="Open Source"></p></div>
        <div><p class="default center main" style="margin-top: 13px; ">Verified</p></div>
        <div><p class="default center description" style="margin-top: 13px; margin-bottom: 58px;">Our token using 30% of all NFT Games</p></div>
    </div>
    <div class="item">
        <div><p class="default center" style="margin-top: 37px; "><img src="../assets/icons8-lightning-bolt-100.png" class="img" alt="Open Source"></p></div>
        <div><p class="default center main" style="margin-top: 13px; ">Fast</p></div>
        <div><p class="default center description" style="margin-top: 13px; margin-bottom: 58px;">Very fast transactions based on ETH blockchain</p></div>
    </div>
</div>
</template>

<script>
export default { name: 'why_we' }
</script>

<style scoped>
.why_we {
    margin-left: 200px;
    margin-right: 200px;
    display: grid;
    grid-template-columns: 30% 30% 30%;
    grid-gap: 3%;
    margin-top: 28px;
    margin-bottom: 28px;
    padding-left: 95px;
    padding-right: 95px;
}
.img {
    width: 97px;
    height: 97px;
}
.main {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 35px;
    line-height: 42px;
    text-align: center;

    color: #4D4D4D;
}
.description {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 24px;
    text-align: center;

    color: #626262;
}
.item {
    box-sizing: border-box;
    background: #FFFFFF;
    border: 1px solid rgba(0, 0, 0, 0.22);
    box-shadow: 0px 0px 20px rgba(7, 7, 7, 0.07);
    border-radius: 25px;
    padding-left: 46px;
    padding-right: 46px;
}
</style>