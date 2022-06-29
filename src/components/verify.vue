<template>
<div class="verify">
    <div class="text">
        <div><p class="default center main" style="margin-top: 49px;">Verified token.<br>Great trust</p></div>
        <div><p class="default center description" style="margin-bottom: 49px;">NiceToken is very popular. Used in more NFT-Games</p></div>
    </div>
    <div class="items">
        <div class="item" id="first">
            <div><p class="default itemmain">NiceToken Transactions</p></div>
            <div><p class="default itemnumb">1,961,355</p></div>
        </div>
        <div class="item" id="second">
            <div><p class="default itemmain">NiceToken Transactions</p></div>
            <div><p class="default itemnumb">1,961,355</p></div>
        </div>
        <div class="item" id="third">
            <div><p class="default itemmain">NiceToken Transactions</p></div>
            <div><p class="default itemnumb">1,961,355</p></div>
        </div>
    </div>

</div>
</template>

<script>
export default { name: 'verify' }
</script>

<style scoped>
.verify {
    margin-left: 200px;
    margin-right: 200px;

}
.main {

    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 75px;
    line-height: 91px;
    text-align: center;

    color: #000000;


}
.description {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 15px;
    line-height: 18px;
    text-align: center;

    color: #000000;
    margin-top: 10px;
}
.item{

    padding-left: 16px;
    padding-right: 16px;
    padding-top: 20px;
}
.items {
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 64px;
    padding-right: 64px;
    display: grid;
    grid-template-columns: 30% 30% 30%;
    grid-gap: 3%;

}
#first {
    background: radial-gradient(50% 195.58% at 50% 50%, rgba(255, 0, 0, 0.1) 0%, rgba(0, 178, 255, 0.1) 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */;
    border-radius: 25px;
}
#second {
    background: radial-gradient(50% 195.58% at 50% 50%, rgba(112, 0, 255, 0.1) 0%, rgba(0, 255, 255, 0.1) 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */;
    border-radius: 25px;
}
#third {
    background: radial-gradient(50% 195.58% at 50% 50%, rgba(5, 251, 0, 0.1) 0%, rgba(255, 184, 0, 0.1) 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */;
    border-radius: 25px;
}
.itemmain {

    font-family: 'Inter';
    font-style: normal;
    font-weight: 500;
    font-size: 25px;
    line-height: 30px;

    color: #000000;
}
.itemnumb {
    margin-top: 28px;
    margin-bottom: 60px;
    font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 50px;
    line-height: 61px;

    color: #000000;
}
</style>