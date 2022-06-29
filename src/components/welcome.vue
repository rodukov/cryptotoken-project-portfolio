<template>
<div class="welcome">
    <div class="data">
        <div>
            <p class="default main">THE CRYPTO <br>TOKEN FOR <br><span class="gaming">GAMING</span></p>
            <p class="default description">Earn this token via playing our game.<br>Absoulety for free and fast.</p>
        </div>
        <div class="canvas">

        </div>
    </div>
</div>
</template>

<script>
export default { name: 'welcome' }
</script>

<style scoped>
.welcome {
    background-color: #171B1F;
    padding-top: 46px;
    padding-bottom: 67px;
    border-radius: 0px 0px 12px 12px;
}
.main {

    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 100px;
    line-height: 121px;

    color: #FFFFFF;
}
.gaming {
    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 100px;
    line-height: 121px;

    background: radial-gradient(60.94% 207.56% at 60.94% 70.87%, #4DDED5 0%, #79B7F0 100%) /* warning: gradient uses a rotation that is not supported by CSS and may not behave as expected */;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    text-fill-color: transparent;


}
.description {

    font-family: 'Inter';
    font-style: normal;
    font-weight: 800;
    font-size: 30px;
    line-height: 36px;

    color: #FFFFFF;

    margin-top: 12px;

   
}
.data {
    display: flex;
    width: 70%;
    margin: auto;
}
.canvas {
    width: 344px;
    height: 344px;
    border-radius: 50px;
    margin: auto;
    background: #00B2FF;

}
</style>