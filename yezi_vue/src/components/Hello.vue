<template>
  <div class="hello">
  <div class="nav-head">
      <div class="nav-head-con">
        <div class="nav-head-item">
          <a href="" class="logo fl"></a>
          <a href="/index.php/customer/index.html" class="quit">{{ msg }}</a>
          <ul class="nav-list" id="tabs_nav">
            <li><a href="">健康管理</a></li>
            <li><a href="">我的教练</a></li>
            <li><a href="">个人中心</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '退出'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-head{
  width: 100%;
  min-width:1200px;
  height: 50px;
  background: #FFFFFF;
  position: relative;
  font-family: 'Microsoft Yahei';
}
.nav-head-con {
  width: 100%;
  height: 100%;
  position: absolute;
  box-shadow: 0 0 10px rgba(0,0,0,.3);
  z-index: 10;
  background-color: #fff;
}
.nav-head-item .logo{
  margin-top: 10px;
  background: url(/static/img/anmei-icon.d236c6a.png) no-repeat left top;
  display: block;
  width: 221px;
  height: 40px;
  float: left;
  background-size: 117%;

}
.nav-head-item{
  width: 1200px;
  margin: 0 auto;
  clear: both;
  overflow: hidden;
  zoom: 1;
  height:50px;
  line-height: 50px;
}
.nav-list{
  float: right;
}
.nav-list li{
  float: left;
  padding: 0 32px;
}
.nav-list li a{
  float: left;
  color: #546476;
  text-decoration: none;
  font-size: 18px;
}
.nav-list li a.on{
  color: #47cce2;
}
.nav-head-item>p {
  float: right;
  width: 55px;
  height: 68px;
  line-height: 70px;
  border-bottom: 2px solid #36b4f9;
  text-align: center;
  margin-right: 75px;
  box-sizing: content-box;
}
.quit{
  float: right;
  color: #546476;
    text-decoration: none;
    font-size: 18px;
    font-family: 'Microsoft Yahei' ;
    margin-right: 35px;
    margin-left:100px;
}
</style>
