<template>
    <div>
        <div class="container">
        <div class="main">
            <div class="login_box">
                <div class="swich_type">
                    <a href="#" data-toggle="tab"data-id="content1" >账号登录</a>
                    <a href="#" data-toggle="tab" data-id="content1" class="active">用户注册</a>
                </div>
                <div class="login_in" id="content1">
                    <div class="mobile_yzm">
                        <a href="#">使用手机验证码登录</a>
                    </div>
                    <div class="item_info">
                        <i class="iconfont icon-44"></i>
                        <input type="text" placeholder="请输入手机号" >
                    </div>
                    <div class="item">
                            <i class="iconfont icon-suo"></i>
                            <input type="password" placeholder="请输入密码" >
                    </div>
                    <div class="login_button">
                        <button >登录</button>
                    </div>
                   <div class="forget_pwd">
                       <a href="#">忘记密码?</a>
                   </div>
                </div>
              <div class="reg" id="content2">
                    <div class="item_info">
                        <i class="iconfont icon-44"></i>
                        <input type="text" placeholder="请输入注册手机号" id="uname">
                    </div>
                    <div class="pic_reg">
                        <input type="text" placeholder="图形验证码" id="uphone">
                        <a href="#">
                            <img src="../../img/captcha.png" alt="">
                        </a>
                        <a href="#">看不清换一张</a>
                    </div>
                    <div class="reg_msg">
                        <i class="iconfont icon-xin"></i>
                        <input type="text" placeholder="请输入短信验证码" id="uemail">
                        <button>获取短信验证码</button>
                    </div>
                    <div class="item_info">
                            <i class="iconfont  icon-suo"></i>
                            <input type="password" placeholder="请输入密码" id="upwd">
                        </div>
                        <div class="item">
                                <i class="iconfont icon-anquan"></i>
                                <input type="password" placeholder="确认密码">
                        </div>
                    <div class="login_button">
                        <button onclick="reg()">注册</button>
                    </div>
                   <div class="forget_pwd">
                       <a href="#">忘记密码?</a>
                   </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>
<script>
export default {
    data(){
        return{}
    }
}
</script>
<style scoped>

    *{margin:0;padding: 0}
body{
    font: 12px "微软雅黑",Helvetica,sans-serif;
}
.main{
    background-image: url(../../img/login_bg3.jpg);
    width:100%;height: 530px;
    position:relative;
}
.login_box{
    width:270px;height: 370px;
    padding: 20px 40px 30px;
    background-color:#fff;
    position: absolute;
    left: 1244px;
    top: 54px;     
}
a{
    text-decoration: none
}
.swich_type{
    display: flex;
    justify-content: space-between
}
.swich_type>a{
    font-size:18px;
    color: #888;
    border-bottom: 1px solid #d1d1d1;
    padding:13px;
    width:134px;height: 27px;
    text-align: center;
    font-weight: bolder
}
.active{
    border-bottom: 2px solid #333 !important;
    color: #333 !important;
}
.mobile_yzm{ 
    height:16px ;
}
.mobile_yzm>a{
    color:#333;
    float: right;
    margin-top: 20px;
}
.item_info{
    margin-top: 30px;
}
.icon-44::before{
    position: absolute;
    left: 8px;
    top: 54px;
    font-size:23px;
    color:#e8e8e8
}
input{
    width:223px;height: 28px;
    padding: 5px 10px 5px 35px;
    border: 1px solid #d2d2d2;
    font: 12px/1.5 Microsoft ;
    color: #555
}
.item{
    position: relative;
    margin-top: 15px;
}
.icon-suo::before{
    position: absolute;
    left: 9px;top:8px;
    font-size:23px;
    color:#e8e8e8
}
.login_button>button{
    width: 100%;height: 40px;
    background-color: #333;
    margin-top: 20px;
    border: 0;
    font-size: 16px;
    font-weight: bold;
    border-radius: 3px;
    color:#fff
}
.forget_pwd{
    margin-top: 10px;
}
.forget_pwd>a{
    color:#8c8c8c;
}
.forget_pwd>a:hover{
    text-decoration: underline;
    color:#555
}
.reg>.item_info{
    margin-top: 20px;
}
.reg .icon-44::before{
    position: absolute;
    left: 4px;
    top: 19px;
}
.pic_reg{
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    margin-top: 10px
}
.pic_reg>input{
    width: 80px;height: 28px !important;
    padding: 4px 5px 5px 4px !important;
   
}
.pic_reg>a:last-child{
    color: #ff6a00;
    height: 20px;
    line-height: 62px
}
.reg_msg{
    margin-top: 6px;
}
.reg_msg>input{
    width:110px;height: 28px !important;
}
.icon-xin{
    position: absolute;
    left: 9px;
    top: 122px;
    color:#e8e8e8
}
.reg_msg>button{
    width: 100px;
    height: 38px;
    font-size: 12px;
    color: #808080;
    background: #F3F3F3;
    border: 1px solid #E5E5E5;
    cursor: pointer;
    font-weight: 600;
    margin-left: 9px;
}
.reg>.item_info{
    margin-top: 10px;
}
.icon-anquan{
    position: absolute;
    left: 10px;
    top: 13px;
    color:#e8e8e8
}
.reg>.item{
    margin-top: 10px;
}
.reg>.login_button>button{
    margin-top: 10px;       
}
.reg .icon-suo{
    position: absolute;
    left: -2px;
    top: 157px;
}
#content2{
	position: absolute;
    top: 84px;
    left: 40px;
    
}
#content1{
	position: absolute;
    top: 69px;
    left: 40px;
    display: none   
}
.pic_reg>a[data-v-29e7a0e0]:last-child{
    font-size:12px;
}
.forget_pwd>a[data-v-29e7a0e0]{
    font-size:12px;
}
</style>