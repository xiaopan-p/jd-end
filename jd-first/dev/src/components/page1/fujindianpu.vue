<template>
    <div class="app">
      <h3>附近店铺</h3>
      <hr>
      <p>
        <span @click="fn(index)" v-for="(item ,index) in list" :class="{color : index ===selectindex}">{{item}}</span>
        <span @click="fn(index)" class="span-s">筛选∠</span>
      </p>
      <ul class="xuan">
        <li>减免运费</li>
        <li>高优门店</li>
        <li>叠加红包</li>
        <li>首单优惠</li>
      </ul>
      <div class="bottom">
        <div class="b-left"><img src="../../../../vue项目素材/jd/f6440d3b288500ae.png"/></div>
        <div class="b-right">
          <h3>山姆会员商店 （双井）</h3>
          <li class="span-ccc"><span class="span-orange">❤❤❤❤❤❤</span><span class="span-orange">4.8</span><span>月售2千+</span><span class="r-span">102分钟</span><span class="r-span">4.6公里</span></li>
          <li  class="span-ccc"><span>起送￥0</span><span>基础费用￥5</span><span class="r-span span1">达达专送</span></li>
          <li class="span-red"><span>领100元券</span><span>领10元运费券</span><span>领88元叠加券</span><span class="r-span span2" style="color: #000">></span></li>
          <li  class="span-ccc"><span>返礼</span><span>指定联合利华商品满39返5元生鲜券</span></li>
        </div>
      </div>
      <div class="bottom">
        <div class="b-left"><img src="../../../../vue项目素材/jd/f6440d3b288500ae.png"/></div>
        <div class="b-right">
          <h3>山姆会员商店 （双井）</h3>
          <li class="span-ccc"><span class="span-orange">❤❤❤❤❤❤</span><span class="span-orange">4.8</span><span>月售2千+</span><span class="r-span">102分钟</span><span class="r-span">4.6公里</span></li>
          <li  class="span-ccc"><span>起送￥0</span><span>基础费用￥5</span><span class="r-span span1">达达专送</span></li>
          <li class="span-red"><span>领100元券</span><span>领10元运费券</span><span>领88元叠加券</span><span class="r-span span2" style="color: #000">></span></li>
          <li  class="span-ccc"><span>返礼</span><span>指定联合利华商品满39返5元生鲜券</span></li>
        </div>
      </div>
    </div>
</template>

<script>
    export default {
        name: "fujindianpu",
      data(){
          return{
            list:['综合排序','销量','距离'],
            selectindex :0
          }
      },
      methods:{
          fn(index){
            this.selectindex = index
          }
      }
    }
</script>

<style scoped>
.app{
  width: 1242px;
  height: 1284px;
  border-radius: 30px 30px 0 0;
  background: white;
}
  h3{
    font-size: 6vw;
    text-align: left;
    padding-left: 30px;
    padding-top: 30px;
  }
  p{
    text-align: left;
  }
  p span{
    font-size: 5vw;
    padding-left: 30px;
  }
  .span-s{
    float: right;
    padding-top: 30px;
    padding-right: 30px;
  }
  .color{
    color: greenyellow;
  }
  .xuan{
    height: 150px;
  }
  .xuan li{
    width: 260px;
    height: 100px;
    background: #cccccc7a;
   margin-left: 40px;
    text-align: center;
    line-height: 100px;
    margin-top: 30px;
  }
  .bottom{
    width: 1242px;
    height: 425px;
  }
  .b-left{
     width: 174px;
     height: 174px;
     float: left;
   }
  .b-left img{
    width: 174px;
    height: 174px;
    margin-left: 30px;
    margin-top: 50px;
  }
.b-right{
  width: 1000px;
  height: 360px;
  float: right;
  border-bottom: 1px solid #ccc;
}
  .b-right li{
    width: 100%;
    height: 50px;
    text-align: left;
    line-height: 50px;
  }
  .b-right li span{
    margin-left: 30px;
  }
  .r-span{
    float: right;
    margin-right: 50px;
    padding: 0px 5px;
  }
  .span-red{
    color:red;
  }
  .span-ccc{
    color:#897c7c;
  }
 .span-red .span2{
    transform: rotate(89deg);
    margin-top: 20px;
    font-size: 3vw;
   margin-right: 40px;
   border: 0;
  margin-top: -8px;
  }
  .span-orange{
    color: orange;
  }
  .span1{
    border: 1px solid blue;
    border-radius:10px;
  }
  .span-red span{
    padding: 5px;
    border: 1px solid red;
    border-bottom: 0;
  }
</style>
