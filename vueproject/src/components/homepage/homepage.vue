<template>
  
  <div>
<!-- 
    <h1>{{text}}</h1>
    <p>{{get_msg}}</p>
    <p></p>
    <button @click='getmsg'>get请求点我</button>
    <button @click="postmsg">post请求点我</button> -->

    <div class="lx_home">

      <header id="lx_head">
        <div class="lx_logo">
          <i>名鞋库首页</i>
        </div>
        <form action="" name="lx_search_form" id="lx_search_home">
          <input class="lx_search_c" name="lx_search_n" type="search" placeholder="输入关键字搜索"/>
          <button class="lx_search_btn"><i class="iconfont icon-fangdajing"></i></button>
        </form>
        <div class="lx_menu">
          <i class="iconfont icon-tubiao13"></i>
        </div>
      </header>

      <div id="lx_banner">
          <!-- <div class="container clearfix"> -->
            <div class="lx_banner">
              <ul>
                <li><img src="./img/lx_banner1.jpg" alt="" /></li>
                <li><img src="./img/lx_banner2.jpg" alt="" /></li>
                <li><img src="./img/lx_banner3.jpg" alt="" /></li>
                <li><img src="./img/lx_banner4.jpg" alt="" /></li>
              </ul>
            </div>
          <!-- </div> -->
      </div>

      <main id="lx_main">
        <div class="lx_m_img">
          <img src="./img/lx_jianhuo.jpg" alt="" />
          <img src="./img/lx_jxpinpai.jpg" alt="" />
          <img src="./img/lx_zhiIN.jpg" alt="" />
        </div>
        
      </main>

      <footer id="lx_footer">
        <ul>
          <li class="active">
            <i class="iconfont icon-home"></i>
            <span>首页</span>
          </li>
          <li>
            <i class="iconfont icon-pinpai"></i>
            <span>品牌</span>
          </li>
          <li>
            <i class="iconfont icon-tubiao13"></i>
            <span>分类</span>
          </li>
          <li>
            <i class="iconfont icon-gouwuche"></i>
            <span>购物车</span>
          </li>
          <li>
            <i class="iconfont icon-wode"></i>
            <span>我的</span>
          </li>
        </ul>
      </footer>

    </div>

  </div>

</template>


<script>

  import './css/base.css'
  import './sass/homepage.scss'
  // import './js/homepage.js'
  // import './lib/flexible.debug.js'
  // import './lib/flexible_css.debug.js'

  export default{
      data(){
          return{
              text:'这是首页组件',
          }
      },
      methods:{
          getmsg(){
              this.$store.dispatch('getmsg_get',{path:'product/',msg:{houseOwner:'Kemo'}});
          },
          postmsg(){
              this.$store.dispatch('getmsg_post',{path:'product',msg:{houseOwner:'Kemo'}});
          }
      },
      computed:{
          get_msg:{
              get:function(){
                  console.log(11555);
                  return this.$store.getters.getmsg_get;
              }
          }
      }
  }

</script>