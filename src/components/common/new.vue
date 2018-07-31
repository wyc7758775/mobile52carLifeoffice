<template>
    <div>
       <div class="new">
            <div class="new-img">
                <img src="../../../static/pic_XWZX@3x.png" alt="">
            </div>
            <div class="new-content">
                <p class="new-content-time">
                    <span>2018.03.15</span>
                    <span>09:41:03</span>
                </p>
                <p class="new-content-title">建设首个无感支付停车场试点</p>
                <p class="new-content-content">
                    在柳州本地建设首个无感支付停车场示范点，加快实行构建智慧型城市及停车诱导系统，提高便民生活品质
                </p>
            </div>
       </div>
    </div>
</template>

<script>
export default {
    name: 'news'
}
</script>

<style scoped>
.new{
    width: 94%;
    margin: 10vw auto;
     border: .4vw solid rgb(219,219,219);
     display: flex;
     justify-content: space-around;
     align-items: center;
}
.new-img{
    width: 140vw;
    padding: 0 2vw;
}
.new-content{
    font-size: 3vw;
    text-align: left;
    padding-right: 1vw;
}
.new-content-time{
    color: rgb(130,130,130);
}
.new-content-title{
    color: rgb(121,167,223);
    font-size: 3vw;
    margin-top: -1vw;
}
.new-content-content{
    font-size: 2vw;
    margin-top: -2vw;
}
</style>
