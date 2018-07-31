<template>
    <div>
        <div class="vnav">
            <div class="vnav-banner">
                <div class="vnav-banner-text">
                    <div>52嗨停</div>
                    <div>一款停车神器</div>
                </div>
                <div class="vnav-banner-iphoneBox">
                    <img src="../../../static/nav/Iphone Mockup @3x@3x.png" alt="">
                </div>
            </div>
            <div class="vnav-tab">
                <ul>
                    <li class="vnav-tab-item" v-for="(item,index) in tabList">
                        <div>
                            <img :src="item.imgsrc">
                        </div>
                        <div>{{item.content}}</div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
let tabList = [
    {
        imgsrc:'../../../static/nav/icon_gsjj@3x.png',
        content: '公司简介'
    }, {
        imgsrc:'../../../static/nav/icon_ys@3x.png',
        content: '优势特点'
    }, {
        imgsrc:'../../../static/nav/icon_td@3x.png',
        content: '企业团队'
    }, {
        imgsrc:'../../../static/nav/icon_hz@3x.png',
        content: '对外合作'
    }, {
        imgsrc:'../../../static/nav/icon_cp@3x.png',
        content: '产品介绍'
    }, {
        imgsrc:'../../../static/nav/icon_anli@3x.png',
        content: '新闻资讯'
    }, {
        imgsrc:'../../../static/nav/icon_anli@3x.png',
        content: '服务案例'
    }, {
        imgsrc:'../../../static/nav/icon_anli@3x.png',
        content: '在线联系'
    },
]
export default {
  name: "vnav",
  data(){
      return {
          tabList: tabList
      }
  }
};
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
.vnav {
  width: 100%;
  background: white;
  margin-bottom: 6vw;
}
.vnav-banner {
  background-image: url(../../../static/nav/pic_banner@3x@3x.png);
  background-size: 100% 100%;
  color: white;
  font-size: 2vw;
  text-align: left;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.vnav-banner-iphoneBox{
    width: 20vw;
    height: 40vw;
    padding: 5vw 0;
}
.vnav-banner-iphoneBox>img{
    width: 100%;
    height: 100%;
}
.vnav-tab {
    overflow: hidden;
    width: 100%；
}
.vnav-tab ul>li{
    list-style: none;
    width: 23.4vw;
    height: 20vw;
    float: left;
    border: 1px solid rgb(239,239,239);
    color: grey;
    font-size: 3vw;
}
.vnav-tab-item>div:nth-of-type(1){
    width: 8vw;
    height: 6vw;
    margin: 3.5vw auto;
}
</style>

