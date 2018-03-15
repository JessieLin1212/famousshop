<template>
  
  <div>

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
          <img src="./img/lx_zhiIN.jpg" alt="" />
          <img src="./img/lx_jianhuo.jpg" alt="" />
          <img src="./img/lx_jxpinpai.jpg" alt="" />
        </div>
        
        <div class="lx_main_content">

          <!-- /*++++++++跑步鞋++++++++*/ -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>跑步鞋</p>
                <span>RUNNING</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <router-link to="" href=""><img src="./img/lx_show1.jpg" alt="" /></router-link>
                </div>
                <ul class="lx_brand">
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify11.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify12.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify13.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify14.jpg" alt="" />
                    </router-link>
                  </li>
                </ul>
                
              </div>
            </div>

            <ul class="lx_content_b">
              <li v-for="(obj,key) in paobuxie">
                <router-link to="" href="">
                  <img :src="imgurl + 'img/' + obj.url" alt=""/>
                  <div class="lx_xqing">
                    <p class="lx_goods_title">{{obj.name}}</p>
                    <span class="ls_sale">￥{{obj.price}}</span>
                    <span class="ls_old_price">￥{{obj.discounts}}</span>
                  </div>
                </router-link>
              </li>
             <!--  <li>
                <router-link to="" href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </router-link>
              </li> -->
              
            </ul>

          </div>

          <!-- /*++++++++休闲鞋++++++++*/ -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>休闲鞋</p>
                <span>CASUAL SHOES</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <router-link to="" href=""><img src="./img/lx_show2.jpg" alt="" /></router-link>
                </div>
                <ul class="lx_brand">
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify21.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify22.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify23.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify24.jpg" alt="" />
                    </router-link>
                  </li>
                </ul>
                
              </div>
            </div>

            <ul class="lx_content_b">
              <li v-for="(obj,key) in xiuxianxie">
                <router-link to="" href="">
                  <img :src="imgurl + 'img/' + obj.url" alt=""/>
                  <div class="lx_xqing">
                    <p class="lx_goods_title">{{obj.name}}</p>
                    <span class="ls_sale">￥{{obj.price}}</span>
                    <span class="ls_old_price">￥{{obj.discounts}}</span>
                  </div>
                </router-link>
              </li>
            </ul>

          </div>

          <!-- /*++++++++篮球鞋++++++++*/ -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>篮球鞋</p>
                <span>BASKETBALL</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <router-link to="" href=""><img src="./img/lx_show3.jpg" alt="" /></router-link>
                </div>
                <ul class="lx_brand">
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify31.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify32.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify33.jpg" alt="" />
                    </router-link>
                  </li>
                  <li>
                    <router-link to="" href="">
                      <img src="./img/lx_classify34.jpg" alt="" />
                    </router-link>
                  </li>
                </ul>
                
              </div>
            </div>

            <ul class="lx_content_b">
              <li v-for="(obj,key) in lanqiuxie">
                <router-link to="" href="">
                  <img :src="imgurl + 'img/' + obj.url" alt=""/>
                  <div class="lx_xqing">
                    <p class="lx_goods_title">{{obj.name}}</p>
                    <span class="ls_sale">￥{{obj.price}}</span>
                    <span class="ls_old_price">￥{{obj.discounts}}</span>
                  </div>
                </router-link>
              </li>
            </ul>

          </div>

        </div>
        
        <div class="lx_main_b">
          <div class="lx_loginbox">
            <router-link to="" href="">登录</router-link>
            <router-link to="" href="">注册</router-link>
          </div>
          <ul class="lx_service">
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-zhengpinbaozhang"></i>
                <p>正品保证</p>
              </router-link>
            </li>
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-servicebaoyouqia"></i>
                <p>满399包邮</p>
              </router-link>
            </li>
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-tuihuochuli"></i>
                <p>自由退货</p>
              </router-link>
            </li>
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-tianmaohuodaofukuan"></i>
                <p>货到付款</p>
              </router-link>
            </li>
          </ul>
          <ul class="lx_contact">
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-web-icon-"></i>
                <p class="">4001162228</p>
              </router-link>
            </li>
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-weixin"></i>
                <p class="">scnmall</p>
              </router-link>
            </li>
          </ul>
          <ul class="lx_pc">
            <li>
              <router-link to="" href="">
                <span>触屏版</span>
                <i class="iconfont icon-shouji"></i>
              </router-link>
            </li>
            <li>
              <router-link to="" href="">
                <i class="iconfont icon-msnui-pc"></i>
                <span>电脑版</span>
              </router-link>
            </li>
          </ul>
          <p class="lx_fankui">
            ©2008-2015 s.cn&nbsp; 名鞋库 &nbsp;闽ICP备08106896号&nbsp;
            <router-link to="" href="">意见反馈</router-link>&nbsp;
            <router-link to="" href="">商圈</router-link>
          </p>
        </div>

      </main>

      <footer id="lx_footer">
        <ul>
          <li class="active">
            <router-link to="" href="">
              <i class="iconfont icon-home"></i>
              <span>首页</span>
            </router-link>
          </li>
          <li>
            <router-link to="" href="">
              <i class="iconfont icon-pinpai"></i>
              <span>品牌</span>
            </router-link>
          </li>
          <li>
            <router-link to="" href="">
              <i class="iconfont icon-tubiao13"></i>
              <span>分类</span>
            </router-link>
          </li>
          <li>
            <router-link to="" href="">
              <i class="iconfont icon-gouwuche"></i>
              <span>购物车</span>
            </router-link>
          </li>
          <li>
            <router-link to="" href="">
              <i class="iconfont icon-wode"></i>
              <span>我的</span>
            </router-link>
          </li>
        </ul>
      </footer>

      <div class="lx_top" @click="totop">
        <i class="iconfont icon-jiantou21"></i>
      </div>

    </div>

  </div>

</template>


<script>

  import './base.css'
  import './homepage.scss'
  import http from '../../httpClient/httpClient.js'
  // import './js/homepage.js'

  export default{
      data(){
          return{
              text:'这是首页组件',
              paobuxie:[],
              xiuxianxie:[],
              lanqiuxie:[],
              imgurl:'/src/components/homepage/'
          }
      },
      methods:{
          getmsg(){
              this.$store.dispatch('getmsg_get',{path:'product/',msg:{houseOwner:'Kemo'}});
          },
          postmsg(){
              this.$store.dispatch('getmsg_post',{path:'product',msg:{houseOwner:'Kemo'}});
          },
          totop(){

          }
      },
      mounted(){
        http.post('getallproducts').then(res=>{
          console.log(res);
          for(var i=0; i<res.data.length;i++){
              if(res.data[i].type=='跑步鞋'){
                this.paobuxie.push(res.data[i]);
              }else if(res.data[i].type=='休闲鞋'){
                this.xiuxianxie.push(res.data[i]);
              }else if(res.data[i].type=='篮球鞋'){
                this.lanqiuxie.push(res.data[i]);
              }
          }
          // console.log(this.paobuxie,this.xiuxianxie,this.lanqiuxie);
        })
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