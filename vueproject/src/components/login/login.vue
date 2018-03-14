<template>
   <div>
      
      <div class="lx_login">
        
        <header id="lx_l_head">
          <a class="lx_reg_back" href="">返回</a>
          <p>名鞋库-用户登录</p>
          <a class="lx_login_log" href="">注册</a>
        </header>

        <main id="lx_login_box">
          <ul class="lx_fangshi">
            <li class="lx_login_active">账号登录</li>
            <li>短信验证登录</li>
          </ul>
          <form id="lx_login_form" name="lx_login_form" action="">
            <input id="lx_login_username" name="lx_login_username" type="phone" placeholder="请输入手机号" />
            <p class="lx_login_tishi">用户名或密码错误</p>
            <input id="lx_login_pwd" name="lx_login_pwd" type="password" placeholder="请输入您的密码" />
            <input id="lx_mdl" name="lx_mdl" checked type="checkbox" /><label for="lx_mdl">一个月内免登录</label>
            <span>忘记密码？</span>
            <input id="lx_login_btn" name="lx_login_btn" type="button" value="登录" />
          </form>
        </main>
  
      </div>

   </div>
</template>

<script>

  import '../homepage/base.css'
  import './login.scss'

   export default{
       data(){
           return{
               text:'这是登录组件',
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