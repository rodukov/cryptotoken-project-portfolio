<template>
<div class="headers">
    <div class="header-items-left">
        <div><p class="default header-item header-item-logo" style="padding-right: 0;">NiceToken</p></div>
    </div>
    <div class="header-items-center">
        <p class="default header-item">What is NCT?</p>
        <p class="default header-item">Community</p>
        <p class="default header-item">For Developers</p>
        <p class="default header-item">Twitter</p>
    </div>
</div>
</template>

<script>
export default {
    name: 'headers'
}
</script>

<style scoped>
.headers {
    display: flex;
    background-color: #171B1F;
}

.header-items-center {
    display: flex;
    margin: auto;

}
.header-item {
    padding-top: 45px;
    padding-bottom: 45px;
    padding-left: 41px;
    padding-right: 41px;



    font-family: 'Inter';
    font-style: normal;
    font-weight: 600;
    font-size: 25px;
    line-height: 30px;

    color: #FFFFFF;


}
.header-item-logo {

    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 25px;
    line-height: 30px;

    color: #FFFFFF;


}
</style>