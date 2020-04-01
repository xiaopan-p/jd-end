<template>
    <div class="app">
      <h3>限时抢购 <span> 更多></span></h3>
      <div class="lun">
        <li>
          <img src="../../../../vue项目素材/jd/ff8051f35e3e6ae4.png"/>
          <p>三八妇女节欢迎抢购</p>
          <div class="l-left"><span class="span1">￥59</span><span class="span2">￥89</span></div>
          <div class="l-right"><img src="../../../../vue项目素材/jd/seckillQiang.3882994a.png"/></div>
        </li>
        <li>
          <img src="../../../../vue项目素材/jd/ff8051f35e3e6ae4.png"/>
          <p>三八妇女节欢迎抢购</p>
          <div class="l-left"><span class="span1">￥59</span><span class="span2">￥89</span></div>
          <div class="l-right"><img src="../../../../vue项目素材/jd/seckillQiang.3882994a.png"/></div>
        </li>
        <li>
          <img src="../../../../vue项目素材/jd/ff8051f35e3e6ae4.png"/>
          <p>三八妇女节欢迎抢购</p>
          <div class="l-left"><span class="span1">￥59</span><span class="span2">￥89</span></div>
          <div class="l-right"><img src="../../../../vue项目素材/jd/seckillQiang.3882994a.png"/></div>
        </li>
      </div>
    </div>
</template>

<script>
    export default {
        name: "xianshi-Q"
    }
</script>

<style scoped>
.app{
  width: 1242px;
  height: 760px;
  background: white;
  border-radius: 50px;
  margin-bottom: 20px;
}
  h3{
    text-align: left;
    padding-top: 20px;
    font-size: 6vw;
    padding-left: 30px;
  }
  h3 span{
    display: block;
    font-size: 3vw;
   float: right;
    padding-right: 30px;
  }
  .lun{
    width: 100%;
    height: 600px;
  }
  .lun li{
    width: 358px;
    height: 450px;
    border-radius: 30px;
    margin-left: 30px;
    margin-top: 30px;
    float: left;
  }
  .lun img{
    width: 358px;
    height: 358px;
    border-radius: 30px;
  }
  .lun p{
    margin-top: -70px;
    font-size: 3vw;
  }
  .l-left{
    float: left;

  }
  .l-left span{
    display: block;
    width: 50px;
    height: 60px;
    line-height: 50px;
  }
  .l-right{
    float: right;
  }
  .l-right img{
    width: 100px;
    height: 100px;
  }
  .span1{
    color: red;
  }
  .span2{
    color:#ccc;
    text-decoration: line-through;
  }
</style>
