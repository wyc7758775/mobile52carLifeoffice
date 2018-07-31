<template>
    <div>
        <div class="product">
            <div class="product-video">
                <video width="320" height="240" controls="controls">
                    <source src="https://v.youku.com/v_show/id_XMzc1Mjg4MjAyMA==.html?spm=a2hww.11359951.m_26670.5~5!2~5~5~5!4~5~5~A" type="video/ogg">
                    <source src="https://v.youku.com/v_show/id_XMzc1Mjg4MjAyMA==.html?spm=a2hww.11359951.m_26670.5~5!2~5~5~5!4~5~5~A" type="video/mp4">
                </video>
            </div>
            <div class="product-text">
                <p>以移动互联网为平台，立足柳州、面向全国、网罗全国2亿车主。深度开发汽车后市场O2O模式，为车主提供更便捷、安全、智能化的车生活体验。</p>
                <p>
                    实时更新空位数量、一键导航、在线预约车位、无感支付、用置时段车位共享。
                </p>
            </div>
            <div class="product-title">
                <div class="product-title-text">
                    <p>52嗨停 应用</p>
                    <p>一款停洗车神器</p>
                </div>
                <div class="product-title-encode">
                    <img src="../../../static/PIc_xcx@3x.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "product"
};
</script>

<style scoped>
.product{
    width: 94%;
    margin: 1vw auto;
    border: .4vw solid rgb(219,219,219);
}
.product-text{
    font-size: 3vw;
    text-indent: 6vw;
    padding: 0 3vw;
    text-align: left;
    color: rgb(130,130,130);
}
.product-video{
    padding-top: 2vw;
}
.product-title{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 3vw;
}
.product-title-encode{
    width: 15vw;
    height: 15vw;
    margin-right: 3vw;
}
.product-title-text{
    padding-left: 3vw;
}
.product-title-text>p:nth-of-type(1){
    font-size: 6vw;
}
.product-title-text>p:nth-of-type(2){
    font-size: 4vw;
}
</style>


