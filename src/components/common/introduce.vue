<template>
    <div>
       <div class="introduce">
           <div class="introduce-leftBox">
               <img src="../../../static/introduce/pic_tupian1@3x.png">
           </div>
           <div class="introduce-right">
               <div>
                   <img src="../../../static/introduce/pic_tupian2@3x.png">
               </div>
               <div>
                   广西卡莱网络科技有限公司，成立于2017年1月，是一加大数据时代背景下新诞生的典型的
                   互联网+企业，公司以互联网为依托，深度开发汽车后市场。
                   卡莱科技在成立支出，就深刻认识到时代趋势，决定...
               </div>
           </div>
       </div>
    </div>
</template>

<script>
export default {
    name: 'introduce'
}
</script>

<style scoped>
*{
    padding: 0;
    margin: 0;
}
img{
    width: 100%;
    height: 100%;
}
.introduce{
    color: white;
    width: 94%;
    margin: 0 auto;
    overflow: hidden;
}
.introduce-leftBox{
    width: 40vw;
    height: 50vw;
    float: left;
}
.introduce-right>div:nth-of-type(1){
    width: 49.99vw;
    float: left;
}
.introduce-right>div:nth-of-type(2){
    background: rgb(238,238,238);
    color: rgb(153,153,153);
    font-size: 2.8vw;
    float: left;
    width: 43.9vw;
    margin-top: 1vw;
    padding: 2.5vw 3vw;
}
</style>

