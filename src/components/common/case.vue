<template>
    <div>
       <div class="case">
           <ul class="case-menue">
               <li v-for="(item,index) in tabList">
                   <img :src="item.imgSec">
                   <div class="case-menue-item">
                      <p>{{item.title}}</p>
                   </div>
               </li>
               <li></li>
               <li></li>
               <li></li>
           </ul>
       </div>
    </div>
</template>

<script>
let tabList = [
    {
        imgSec:'.././../../static/case/pic_zhcc@3x.png',
        title:'商业综合体'
    },{
        imgSec:'.././../../static/case/pic_syzht@3x.png',
        title:'无感停车'
    },{
        imgSec:'.././../../static/case/pic_o20sq@3x.png',
        title:'社区o2o'
    },{
        imgSec:'.././../../static/case/pic_csgh@3x.png',
        title:'高楼大厦'
    },
]
export default {
    name: 'case',
    data(){
        return {
            tabList:tabList
        }
    }
}
</script>

<style scoped>
ul,li{
    padding: 0;
    margin: 0;
    list-style: none;
}
.case{
     width: 94%;
    margin: 0 auto;
}
.case-menue{
    overflow: hidden;
}
.case-menue>li{
    list-style: none;
    float: left;
    width: 21vw;
    height: 40vw;
    position: relative;
}
.case-menue-item{
    position: absolute;
    bottom: 0;
    color: white;
    font-size: 3vw;
    padding: 0vw 3vw;
    width: 15vw;
    background: rgba(11, 11, 11, .5)
}
.case-menue>li:nth-of-type(2),
.case-menue>li:nth-of-type(3),
.case-menue>li:nth-of-type(4){
    margin-left: 1.5vw;
}
</style>

