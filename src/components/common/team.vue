<template>
    <div>
       <div class="team">
           <div class="team-imgbox">
               <img src="../../../static/pic_td01@3x@3x.png">
           </div>
           <div class="team-text">
                 卡莱科技聚集了一批潮气蓬勃、积极向上、勇于创新、敢于挑战的高素质专业型人才，他们
               有来自互联网领域高精尖科技型人才，也有来自市场营销的销售精英。在时代与梦想的召唤下，
               聚集到一起。我们青春洋溢、我们不畏艰险，在卡莱科技这艘大船上，乘着大数据时代的东风，
               我们像勇敢的水手，坚韧果敢地向互联网的蓝海。
           </div>
       </div>
    </div>
</template>

<script>
export default {
    name: 'team'
}
</script>

<style scoped>
.team{
    border: .5vw solid rgb(222,222,222);
}
img{
    width: 100%;
    height: 100%;
}
.team-imgbox{
    width: 93vw;
    margin: 1vw auto;
}
.team-text{
    text-indent: 6vw;
    font-size: 3vw;
    padding: 1vw 3vw;
    text-align: left;
    color: rgb(130,130,130);
    font-family: Arial, Helvetica, sans-serif;
    letter-spacing: .1vw;
    line-height: 5vw;
}
</style>

