<template>
  <header class="header">
    <div class="clearfix">
      <!-- Logo & Navigation -->
      <header style="height:72px;">
        <div class="container clearfix">
          <div class="row">
            <div class="span12" style='height:72px;'>
              <!-- Logo -->
              <h1 class="brand brand_">
                <a
                  href="index.html"
                  style="float: left;
              font-size: 18px;
              color: #28a5fa;
              padding-left: 46px;
              background: url(img/logo.png) 0 10px no-repeat;
              background-size: 90px 33px;
              font-weight: 400;height: 60px;
              line-height: 54px;"
                >
                  <span style="margin-left:55px">智普信科技</span>
                </a>
              </h1>
              <!-- Navigation -->
              <div class="navbar navbar_">
                <div class="container">
                  <!--=========== menu ===============-->
                  <div class="nav-collapse nav-collapse_ collapse">
                    <ul class="nav sf-menu">
                      <!-- <li class="active sub-menu"><a href="index.html">首页</a>
                        
                      </li>-->
                      <!-- <li class="sub-menu"><a href="#">产品及服务 </a>
                     
                      </li>-->
                      <li class="sub-menu">
                        <a href="#">产品及服务</a>
                        <ul :style="height" class="list-services">
                          <li>
                            <figure class="img-circle">
                              <img class="img-circle" alt src="../../public/img/heaer-gui.png" width="113" height="73">
                            </figure>
                            <div style='float:left;margin-left:55px;'>
                              <a class="lead-1 ft16" href="#" style="margin-top:20px;">储物保管系列</a>
                              <router-link to="/safirst/safirst-summary" class="sub_title">初柜</router-link>
                              <a href="" class="sub_title">屉柜</a>
                              <a href="" class="sub_title">保管柜</a>
                              <a href="" class="sub_title">智能枪弹柜</a>
                              <a href="" class="sub_title">智能保管柜</a>
                            </div>
                          </li>
                           <li>
                            <figure class="img-circle">
                              <img class="img-circle" alt src="../../public/img/suo.png" width="60" height="126">
                            </figure>
                            <div style='float:left;margin-left:55px;'>
                              <a class="lead-1 ft16" href="#" style="margin-top:20px;">出入锁控系列</a>
                              <a href="" class="sub_title">入户门锁</a>
                              <a href="" class="sub_title">户内门锁</a>
                              <a href="" class="sub_title">人脸门禁</a>
                              <a href="" class="sub_title">车位锁</a>
                              
                            </div>
                          </li>
                          <li>
                            <figure class="img-circle">
                              <img class="img-circle" alt src="../../public/img/suo.png" width="60" height="126">
                            </figure>
                            <div style='float:left;margin-left:55px;'>
                              <a class="lead-1 ft16" href="#" style="margin-top:20px;">解决方案</a>
                              <a href="" class="sub_title">自用办公安全</a>
                              <a href="" class="sub_title">家居安全</a>
                              <a href="" class="sub_title">公寓安全</a>
                              <a href="" class="sub_title">社区安全</a>
                              <a href="" class="sub_title">定制化解决方案</a>
                            </div>
                          </li>
                           <li >
                            <figure class="img-circle">
                              <img class="img-circle" alt src="../../public/img/zu.png" width="113" height="78">
                            </figure>
                            <div style='float:left;margin-left:55px;'>
                              <a class="lead-1 ft16" href="#" style="margin-top:20px;">IoT赋能模组</a>
                              <a href="" class="sub_title">WiFi锁控模组</a>
                              
                            </div>
                          </li>
                          <li  >
                            <figure class="img-circle">
                              <img class="img-circle" alt src="../../public/img/phone.png" width="60" height="126">
                            </figure>
                            <div style='float:left;margin-left:55px;'>
                              <a class="lead-1 ft16" href="#" style="margin-top:20px;">智能安防云</a>
                              <a href="" class="sub_title">云端数据服务</a>
                              <a href="" class="sub_title">APP及软件服务</a>
                              <a href="" class="sub_title">定制安防服务</a>
                              
                            </div>
                          </li>
                        </ul>
                      </li>
                      <li class="sub-menu">
                        <a href="#">客户案例</a>
                      </li>
                      <li class="sub-menu">
                        <a href="#">新闻中心</a>
                        <ul>
                          <li>
                            <a href="blog.html">我要出租</a>
                          </li>
                          <li>
                            <a href="single-blog.html">联系我们</a>
                          </li>
                          <li>
                            <a href="single-blog.html">我要承租</a>
                          </li>
                        </ul>
                      </li>
                      <li class="sub-menu">
                        <a href="#">关于智普信</a>
                      </li>
                      <li>
                        <a href="contact.html">加入智普信</a>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
              <div class="clear"></div>
            </div>
          </div>
        </div>
      </header>
    </div>
  </header>
</template>
 
<script>
export default {
  name: "Header",
  props: {},
  data() {
    return {
      height: {
        width: ""
      }
    };
  },
  created() {
    this.hh();
  },
  methods: {
    hh() {
      this.height.width = window.innerWidth - 19 + "px";
    }
  },
  mounted(){
     
  }
};
</script>
<style scoped lang="scss">
.header {
  max-width: 100%;
  height: 72px;
}
.navbar_{
  margin:0;
}
.sub-menu ul {
  background: #42403e;
  // opacity: 0.7;
  overflow: hidden;
  clear: both;
  box-sizing: border-box;
  padding-left: 18%;
  // display: flex;
}
.sub-menu ul li {
  width: 400px;
  // margin:0 auto!important;
  float: left;
  height:230px;
}
.sub-menu ul li:hover{
  background: #4f4f4d;
}
.sub-menu ul li a {
  color: #fff;
  font-size:14px;
}
.sub-menu ul li a:hover{
  background: none!important;
  color:#28a5fa
}
.ft16{
  font-size: 16px!important;
}
.sub_title{
  line-height: 0!important;
  margin:0 0 7px 0;
  // padding:0!important;
}
.list-services li:first-child figure { 
  float: left;
   margin: 60px 15px 6px 0; 
   border:none;
   }
   .list-services li:nth-child(2) figure { 
  float: left;
   margin: 40px 15px 6px 0; 
   border:none;
   }
     .list-services li:nth-child(3) figure { 
  float: left;
   margin: 40px 15px 6px 0;
   border:none; 
   }
     .list-services li:nth-child(4) figure { 
  float: left;
   margin: 40px 15px 6px 0;
   border:none; 
   }
      .list-services li:nth-child(5) figure { 
  float: left;
   margin: 50px 15px 6px 0;
   border:none; 
   }
   .ft14{
     font-size: 14px;
   }
   .nav-collapse_ .nav ul{
     border-top:none;
   }
   .nav-collapse_ .nav > li > a{
     height: 57px;
     line-height: 71px;
   }
    .nav-collapse_ .nav > li > a:hover{
      border-bottom: 3px solid #0291f3;
    }
   .nav-collapse_ .nav{
       height: 71px;
   }
</style>
