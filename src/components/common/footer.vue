<template>
    <div>
        <div class="footer">
            <div class="footer-top">
                <div class="footer-top-img">
                    <img src="../../../static/logo_logo@3x.png">
                </div>
                <div class="footer-top-text">快捷导航</div>
            </div>
            <div class="footer-bottom">
                <div class="footer-bottom-top">
                    <span>关于卡莱</span>
                    <span>联系我们</span>
                    <span>法律声明</span>
                    <span>帮助中心</span>
                </div>
                <div class="footer-bottom-bottom">
                    ©备案号：桂Icp备17003197号
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'vfooter'
}
</script>

<style scoped>
ul,li{
    padding: 0;
    margin: 0;
    list-style: none;
}
.footer{
    margin-top: -30vw;
}
.footer-top{
    background: rgb(83,84,86);
    color: white;
    display: flex;
    justify-content:center;
    align-items: center;
    padding: 5vw 0;
}
.footer-top-img{
    width: 10vw;
    height: 5vw;
    margin-right: 5vw;
}
.footer-top-text{
    margin-left: 5vw;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.footer-bottom{
    background: rgb(43,44,46);
    color: rgb(110,111,113);
     padding-top: 5vw;
     padding-bottom: 5vw; 
}
.footer-bottom-top>span{
    font-size: 3.5vw;
    margin: 1vw;
}
.footer-bottom-bottom{
    padding-top: 5vw;
    font-size: 3vw;
}
</style>


