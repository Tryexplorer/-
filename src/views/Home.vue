<template>
  <div class="home">
    <div class="topbar">
      <div class="container">
        <div class="topbar_nav">
          <a href>小米商城</a>
          <span>|</span>
          <a href>MIUI</a>
          <span>|</span>
          <a href>IoT</a>
          <span>|</span>
          <a href>云服务</a>
          <span>|</span>
          <a href>金融</a>
          <span>|</span>
          <a href>有品</a>
          <span>|</span>
          <a href>小爱开放平台</a>
          <span>|</span>
          <a href>企业团购</a>
          <span>|</span>
          <a href>资质证照</a>
          <span>|</span>
          <a href>协议规则</a>
          <span>|</span>
          <a href>下载app</a>
          <span>|</span>
          <a href>Select Location</a>
        </div>
        <div class="topbar_cart">
          <a href>购物车(0)</a>
        </div>
        <div class="topbar_info">
          <a href>登录</a>
          <span>|</span>
          <a href>注册</a>
          <span>|</span>
          <a href>消息通知</a>
          <span>|</span>
        </div>
      </div>
    </div>
    <!------------------------------ header导航栏 ------------------------->
    <div class="header">
      <div class="header_container">
        <div class="header_img">
          <a href="#"></a>
        </div>
        <div class="header_nav">
          <a href>小米手机</a>
          <a href>Redmi 红米</a>
          <a href>电视</a>
          <a href>笔记本</a>
          <a href>家电</a>
          <a href>路由器</a>
          <a href>智能硬件</a>
          <a href>服务</a>
          <a href>社区</a>
        </div>
        <div class="header_search">
          <form action class="searth_form">
            <input type="text" class="searth_text" />
            <!--                        <input type="submit" value="el-icon-zoom-in" class="searth_btn iconfont"/>-->
            <div
              class="searth_btn"
              style="display: flex;align-items: center;justify-content: center"
            >
              <i class="el-icon-zoom-in"></i>
            </div>
          </form>
        </div>
        <div></div>
      </div>
    </div>

    <!---------------------------------- 轮播图----------------------------- -->
    <div class="home">
      <div class="container">
        <div class="home_li">
          <a href="#">
            <span>手机 电话卡</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>电子 盒子</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>笔记本 显示器 平板</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>家电 插线板</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>出行 穿戴</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>智能 路由器</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>电源 配件</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>健康 儿童</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>耳机 音箱</span>
            <img src="../assets/image/right.png" alt />
          </a>
          <a href="#">
            <span>生活 箱包</span>
            <img src="../assets/image/right.png" alt />
          </a>
        </div>
        <div class="home_rolling">
          <div class="block">
            <el-carousel trigger="click" height="460px">
              <el-carousel-item v-for="(item,index) in carousel" :key="index">
                <img :src="item.img" alt width="100%" height="100%" />
              </el-carousel-item>
            </el-carousel>
          </div>
        </div>
      </div>
    </div>

    <!--------------------------------- 商品展示-------------------------------- -->
    <div class="home_two">
      <div class="home_flex">
        <div style="width: 234px;display: flex;flex-wrap: wrap;">
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/1.png" alt />
              <br />
              <span>小米商城</span>
            </a>
          </div>
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/2.png" alt />
              <br />
              <span>企业团购</span>
            </a>
          </div>
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/3.png" alt />
              <br />
              <span>F码通道</span>
            </a>
          </div>
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/4.png" alt />
              <br />
              <span>米粉卡</span>
            </a>
          </div>
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/5.png" alt />
              <br />
              <span>以旧换新</span>
            </a>
          </div>
          <div class="home_flexDiv">
            <a href="#">
              <img src="../assets/image/6.png" alt />
              <br />
              <span>话费充值</span>
            </a>
          </div>
        </div>
        <div style="width: 316px ">
          <a href="#">
            <img src="../assets/image/k30.jpg" alt width="100%" />
          </a>
        </div>
        <div style="width: 316px ">
          <a href="#">
            <img src="../assets/image/k301.jpg" alt width="100%" />
          </a>
        </div>
        <div style="width: 316px ">
          <a href="#">
            <img src="../assets/image/手环4.jpg" alt width="100%" />
          </a>
        </div>
      </div>
    </div>

    <!-- -----------------------------------右侧导航---------------------------------- -->
    <div class="home-right">
      <a href="#">
        <img src="../assets/image/right1.png" class="right_img" alt />
        <br />
        <span>手机APP</span>
      </a>
      <a href="#">
        <img src="../assets/image/right2.png" class="right_img" alt />
        <br />
        <span>个人中心</span>
      </a>
      <a href="#">
        <img src="../assets/image/right3.png" class="right_img" alt />
        <br />
        <span>售后服务</span>
      </a>
      <a href="#">
        <img src="../assets/image/right4.png" class="right_img" alt />
        <br />
        <span>人工客服</span>
      </a>
      <a href="#">
        <img src="../assets/image/right5.png" class="right_img" alt />
        <!-- <br /> -->
        <span style="width:100%">购物车</span>
      </a>
    </div>
    <!--------------------------------- 回到顶部 --------------------------------------->
    <div class="blackTop" @click="backTop()" v-show="this.scrollTop> 800 ? true : false">
      <a href="#">
        <img src="../assets/image/right6.png" class="right_img" alt />
        <br />
        <span style="width:100%;color:#757575">回顶部</span>
      </a>
    </div>
    <!-- ----------------------------------     小米闪购      ----------------------------------------->
    <div class="main-home">
      <div class="container">
        <h2 class="container-h2">小米闪购</h2>
        <div style="display:flex;justify-content:space-between">
          <div class="flashsale" v-for="(item,index) in carouselTwo" :key="index">
            <img style="width:100%" :src="item.img" alt />
            <h3 style="width:100%">{{item.name}}</h3>
            <p style="width:100%">{{item.details}}</p>
            <p style="width:100%">{{item.price}}</p>
          </div>
        </div>
      </div>
      <!---------------------------------------- 图片 ---------------------------------------->

      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp1.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <!----------------------------------------- 手机---------------------------------------- -->

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">手机</h2>
            <span>查看全部</span>
          </div>

          <div style="width:1240px;height:628px;display:flex">
            <div class="phone-img1">
              <img src="../assets/image/phone.png" alt />
            </div>
            <div class="container-phone">
              <div class="phone-div" v-for="(item,index) of carouselThree" :key="index">
                <img style="width:160px;hight:160px" :src="item.img" alt />
                <h3 class="phone-h3">{{item.name}}</h3>
                <p class="phone-p1">{{item.details}}</p>
                <p class="phone-p2">{{item.price}}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!---------------------------------------- 图片 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp2.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">家电</h2>
            <span>查看全部</span>
          </div>
          <div class="publicDiv">
            <div class="publicDiv1" v-for="(item,index) of 9" :key="index"></div>
            <div class="publicDiv2">
              <div class="publicDiv3"></div>
              <div class="publicDiv4"></div>
            </div>
          </div>
        </div>
      </div>

      <!---------------------------------------- 图片3 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp3.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">智能</h2>
            <span>查看全部</span>
          </div>
          <div class="publicDiv">
            <div class="publicDiv1" v-for="(item,index) of 9" :key="index"></div>
            <div class="publicDiv2">
              <div class="publicDiv3"></div>
              <div class="publicDiv4"></div>
            </div>
          </div>
        </div>
      </div>

      <!---------------------------------------- 图片4 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp4.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">搭配</h2>
            <span>查看全部</span>
          </div>
          <div class="publicDiv">
            <div class="publicDiv1" v-for="(item,index) of 9" :key="index"></div>
            <div class="publicDiv2">
              <div class="publicDiv3"></div>
              <div class="publicDiv4"></div>
            </div>
          </div>
        </div>
      </div>

      <!---------------------------------------- 图片5 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp5.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">配件</h2>
            <span>查看全部</span>
          </div>
          <div class="publicDiv">
            <div class="publicDiv1" v-for="(item,index) of 9" :key="index"></div>
            <div class="publicDiv2">
              <div class="publicDiv3"></div>
              <div class="publicDiv4"></div>
            </div>
          </div>
        </div>
      </div>

      <!---------------------------------------- 图片6 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp6.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>

      <div class="main-phone">
        <div class="container">
          <div style="display:flex;justify-content: space-between;align-items: center">
            <h2 class="container-h2">周边</h2>
            <span>查看全部</span>
          </div>
          <div class="publicDiv">
            <div class="publicDiv1" v-for="(item,index) of 9" :key="index"></div>
            <div class="publicDiv2">
              <div class="publicDiv3"></div>
              <div class="publicDiv4"></div>
            </div>
          </div>
        </div>
      </div>

      <!---------------------------------------- 图片7 ---------------------------------------->
      <div class="main-img">
        <div class="container">
          <a href="#">
            <img src="../assets/image/tp7.jpg" width="100%" height="100%" alt />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {},
  data() {
    return {
      // 滚动条的高度
      scrollTop: 0,
      //轮播图
      carousel: [
        { img: require("@/assets/image/lb1.jpg") },
        { img: require("@/assets/image/lb2.jpg") },
        { img: require("@/assets/image/lb3.jpg") },
        { img: require("@/assets/image/lb4.jpg") },
        { img: require("@/assets/image/lb5.jpg") }
      ],
      carouselTwo: [
        {
          img: require("@/assets/image/lbt1.jpg"),
          name: "小米音箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/lbt2.jpg"),
          name: "卫生纸",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/lbt3.jpg"),
          name: "灯泡",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/lbt4.jpg"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/lbt5.jpg"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        }
      ],
      carouselThree: [
        {
          img: require("@/assets/image/phone1.png"),
          name: "小米音箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone2.png"),
          name: "卫生纸",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone3.png"),
          name: "灯泡",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone4.png"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone5.png"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone6.png"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone7.png"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        },
        {
          img: require("@/assets/image/phone8.png"),
          name: "烤箱",
          details: "声音大,音量足",
          price: 338
        }
      ]
    };
  },
  mounted() {
    this.setBorderColor();
    window.addEventListener("scroll", this.handleScroll, true);
  },
  methods: {
    setBorderColor() {
      let index = document.getElementsByClassName("flashsale");
      if (index.length !== 0) {
        for (let i = 0; i < index.length; i++) {
          var r = Math.floor(Math.random() * 256);
          var g = Math.floor(Math.random() * 256);
          var b = Math.floor(Math.random() * 256);
          var color = "#" + r.toString(16) + g.toString(16) + b.toString(16);
          index[i].style.borderTopColor = String(color);
        }
      } else {
        return;
      }
    },
    // 保存滚动值，这是兼容的写法
    handleScroll() {
      this.scrollTop =
        window.pageYOffset ||
        document.documentElement.scrollTop ||
        document.body.scrollTop;
      
    },

    // 滚动条回到顶部
    backTop() {
      if (this.scrollTop > 10) {
        document.documentElement.scrollTop = 0;
      }
    }
  },
  destroyed() {
    // 离开该页面需要移除这个监听的事件，不然会报错
    window.removeEventListener("scroll", this.handleScroll);
  }
};
</script>

<style scoped>
.topbar {
  width: 100%;
  height: 40px;
  background-color: #333;
  color: #b0b0b0;
  font-size: 12px;
}

.topbar a {
  color: #b0b0b0;
}

.topbar a:hover {
  color: #fff;
}

.topbar span {
  margin: 0.5em;
  color: #333;
}

.topbar_nav {
  height: 40px;
  line-height: 40px;
  float: left;
}

.topbar_info {
  float: right;
}

.topbar_cart {
  float: right;
}

.topbar_cart a {
  display: block;
  height: 40px;
  text-align: center;
  background: #424242;
  width: 120px;
  line-height: 40px;
}

.topbar_cart a:hover {
  background-color: #fff;
  color: #ff6700;
}

.topbar_info a {
  float: left;
  line-height: 40px;
  padding: 0 5px;
}

.header {
  width: 100%;
  height: 100px;
  display: flex;
}

.header_container {
  width: 1226px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.header_nav {
  height: 100px;
  line-height: 100px;
  font-size: 16px;
  color: #333;
}

.header_nav a {
  padding: 26px 10px 38px;
  color: #333;
}

.header_nav a:hover {
  color: #ff6700;
}

.header_input {
  width: 245px;
  height: 50px;
}

.header_img a {
  display: block;
  width: 55px;
  height: 55px;
  background: #ff6700 url("../assets/image/mi-logo.png") no-repeat 50% 50%;
}

.home {
  width: 100%;
  height: 460px;
}

.home_two {
  width: 100%;
  height: 170px;
  display: flex;
  margin-top: 14px;
  margin-bottom: 26px;
}

.home_li {
  float: left;
  width: 234px;
  height: 460px;
}

.home_rolling {
  width: 100%;
  height: 460px;
}

.home_flex {
  display: flex;
  width: 1226px;
  margin: 0 auto;
  justify-content: space-between;
}

.home_flexDiv {
  width: 78px;
  height: 85px;
  /* line-height: 84px; */
  color: #fff;
  background: #5f5750;
  text-align: center;
  border: ridge #665e57 1px;
  box-sizing: border-box;
}

.home_flexDiv a {
  color: #fff;
  display: block;
  opacity: 0.7;
  filter: none;
}

.home_flexDiv a:hover {
  /* color: white; */
  opacity: 1;
  filter: grayscale(100%);
}

.home_flexDiv img {
  width: 25px;
  height: 25px;
  margin-top: 15px;
}

.swiper-container {
  width: 991px;
  height: 460px;
}

.swiper-slide img {
  width: 100%;
  height: 100%;
}

.searth_form {
  position: relative;
  display: block;
  width: 296px;
  height: 50px;
}

.searth_form .searth_text {
  position: absolute;
  top: 0;
  right: -27px;
  display: block;
  width: 245px;
  height: 50px;
  line-height: 50px;
  border: 1px solid #e0e0e0;
  outline: 0;
}

.searth_form .searth_btn {
  position: absolute;
  top: 0;
  right: -78px;
  display: block;
  width: 52px;
  height: 50px;
  border: 1px solid #e0e0e0;
  font-size: 24px;
  line-height: 24px;
  background: #fff;
  color: #616161;
  outline: 0;
}

.searth_btn:hover {
  background: #ff6700;
  color: #fff;
}

.home_li {
  display: flex;
  flex-wrap: wrap;
  position: relative;
  background: rgba(150, 157, 158, 1);
}

.home_li a {
  width: 100%;
  height: 42px;
  color: #fff;
  padding: 0 0 0 30px;
  line-height: 42px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  /* color: #fff; */
}

.home_li a:nth-child(1) {
  margin-top: 20px;
}

.home_li a:nth-child(10) {
  margin-bottom: 20px;
}

.home_li a:hover {
  background: #ff6700;
}

.home_li img {
  margin-right: 20px;
  font-size: 16px;
  color: #e0e0e0;
}

* {
  margin: 0;
  padding: 0;
}

body {
  height: 2000px;
  font: 14px/1.5 Helvetica Neue, Helvetica, Arial, Microsoft Yahei,
    Hiragino Sans GB, Heiti SC, WenQuanYi Micro Hei, sans-serif;
}

.container {
  width: 1226px;
  margin: 0 auto;
}

a {
  text-decoration: none;
}

.el-carousel__item h3 {
  color: #475669;
  font-size: 14px;
  opacity: 0.75;
  line-height: 150px;
  margin: 0;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
.main-home {
  width: 1903px;
  height: 6035px;
  background: #f5f5f5;
  padding: 4px 0 12px;
}
.flashsale {
  width: 234px;
  height: 334px;
  border: 1px solid white;
  float: left;
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  text-align: center;
  background: #fff;
}
.container-h2 {
  margin: 0;
  font-size: 22px;
  font-weight: 200;
  line-height: 58px;
  color: #333;
}
.main-img {
  height: 120px;
  margin: 22px 0;
}
.container-phone {
  width: 978px;
  height: 614px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-content: space-between;
  text-align: center;
  margin-left: 14px;
}
.phone-div {
  width: 234px;
  height: 300px;
  background: white;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  align-content: center;
  cursor: pointer;
}
.phone-h3 {
  width: 100%;
  font-size: 14px;
  margin: 0 10px 2px;
}
.phone-p1 {
  width: 100%;
  margin: 0 10px 10px;
  height: 18px;
  font-size: 12px;
  color: #b0b0b0;
}
.phone-p2 {
  font-size: 14px;
  width: 100%;
  margin: 0 10px 14px;
}
.phone-div:hover {
  position: relative; /*改成相对定位*/
  top: -1px; /*向上挪动5px*/
  box-shadow: 0px 5px 10px 0px #999; /*增加阴影效果*/
  transition: all 500ms; /*动画过渡*/
}
.phone-img1 {
  width: 234px;
  height: 614px;
}
.phone-img1 :hover {
  position: relative; /*改成相对定位*/
  top: -1px; /*向上挪动5px*/
  box-shadow: 0px 5px 10px 0px #999; /*增加阴影效果*/
  transition: all 500ms; /*动画过渡*/
}
.publicDiv1 :hover {
  position: relative; /*改成相对定位*/
  top: -1px; /*向上挪动5px*/
  box-shadow: 0px 5px 10px 0px #999; /*增加阴影效果*/
  transition: all 500ms; /*动画过渡*/
}
.publicDiv3 :hover {
  position: relative; /*改成相对定位*/
  top: -1px; /*向上挪动5px*/
  box-shadow: 0px 5px 10px 0px #999; /*增加阴影效果*/
  transition: all 500ms; /*动画过渡*/
}
.publicDiv4 :hover {
  position: relative; /*改成相对定位*/
  top: -1px; /*向上挪动5px*/
  box-shadow: 0px 5px 10px 0px #999; /*增加阴影效果*/
  transition: all 500ms; /*动画过渡*/
}

.home-right {
  position: fixed;
  bottom: 155px;
  right: 0;
  z-index: 99;
  display: flex;
  width: 84px;
  flex-wrap: wrap;
  text-align: center;

  /* align-content: center; */
}
.blackTop {
  position: fixed;
  bottom: 32px;
  right: 0;
  z-index: 99;
  width: 84px;
  height: 92px;
  justify-content: center;
  align-items: center;
  display: flex;
  background: #fff;
  text-align: center;
}

.home-right a {
  justify-content: center;
  display: flex;
  width: 100%;
  height: 92px;
  border: 1px solid #f5f5f5;
  margin-top: -1px;
  background-color: #fff;
  align-content: center;
  flex-wrap: wrap;
  box-sizing: border-box;
}
.right_img {
  width: 30px;
  height: 30px;
  margin: 0 auto 8px;
}
.home-right span {
  color: #757575;
  transition: color 0.3s;
}
.home-right span:hover {
  color: #ff6700;
}
.publicDiv {
  width: 1240px;
  height: 628px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.publicDiv1 {
  border: 1px solid black;
  width: 234px;
  height: 300px;
  cursor: pointer;
}
.publicDiv2 {
  border: 1px solid black;
  width: 234px;
  height: 300px;
  display: flex;
  flex-wrap: wrap;
  align-content: space-between;
}
.publicDiv3 {
  width: 100%;
  height: 143px;
  border: 1px solid black;
}
.publicDiv4 {
  width: 100%;
  height: 143px;
  border: 1px solid black;
}
</style>