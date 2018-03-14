<template>
   <div>
      
      <div class="lx_register">
        
        <header id="lx_r_head">
          <a class="lx_reg_back" href="">返回</a>
          <p>名鞋库-用户注册</p>
          <a class="lx_reg_log" href="">登录</a>
        </header>

        <main id="lx_reg_box">
          <form id="lx_reg_form" name="lx_reg_form" action="">
            <input id="lx_username" name="lx_username" type="phone" placeholder="请输入手机号" />
            <p class="lx_reg_tishi">请输入正确的手机号</p>
            <input id="lx_pwd" name="lx_pwd" type="password" placeholder="请输入密码" />
            <input id="lx_regbtn" name="lx_regbtn" type="button" value="注册" />
          </form>
        </main>

      </div>

   </div>
</template>

<script>

  import '../homepage/base.css'
  import './register.scss'

   export default{
       data(){
           return{
               text:'这是注册组件',
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