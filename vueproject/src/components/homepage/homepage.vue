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
          <img src="./img/lx_zhiIN.jpg" alt="" />
          <img src="./img/lx_jianhuo.jpg" alt="" />
          <img src="./img/lx_jxpinpai.jpg" alt="" />
        </div>
        
        <div class="lx_main_content">

        <!--               跑步鞋              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>跑步鞋</p>
                <span>RUNNING</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               休闲鞋              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>休闲鞋</p>
                <span>CASUAL SHOES</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               休闲服              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>休闲服</p>
                <span>ATHLETIC WEAR</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               篮球鞋              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>篮球鞋</p>
                <span>BASKETBALL</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               足球鞋              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>足球鞋</p>
                <span>FOOTBALL</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               儿童              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>儿童</p>
                <span>CHILDREN</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>
          <!--               包包              -->
          <div class="lx_main_classify">
            <div class="lx_content_t">
              <div class="lx_content_title">
                <p>包包</p>
                <span>BAG</span>
              </div>
              <div class="lx_classify">
                <div class="lx_show">
                  <a href=""><img src="./img/lx_show1.jpg" alt="" /></a>
                </div>
                <ul class="lx_brand">
                  <li>
                    <a href="">
                      <img src="./img/lx_classify1.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify2.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify3.jpg" alt="" />
                    </a>
                  </li>
                  <li>
                    <a href="">
                      <img src="./img/lx_classify4.jpg" alt="" />
                    </a>
                  </li>
                </ul>
                
              </div>
            </div>
            <ul class="lx_content_b">
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content1.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色+碳黑</p>
                    <span class="ls_sale">￥569</span>
                    <span class="ls_old_price">￥899</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content2.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 1号黑色</p>
                    <span class="ls_sale">￥299</span>
                    <span class="ls_old_price">￥499</span>
                  </div>
                </a>
              </li>
              <li>
                <a href="">
                  <img src="./img/lx_content3.jpg" alt="" />
                  <div class="lx_xqing">
                    <p class="lx_goods_title">adidas阿迪达斯 跑步鞋 男 一号黑色+亮白+石墨黑</p>
                    <span class="ls_sale">￥399</span>
                    <span class="ls_old_price">￥829</span>
                  </div>
                </a>
              </li>
            </ul>
          </div>

        </div>
        
        <div class="lx_main_b">
          
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