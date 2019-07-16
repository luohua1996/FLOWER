<template>
    <div>
        <div id="ceiling">
            <div class="header_bar_l">
                <div class="header_left_1">
                    <em class="iconfont icon-dianhua"></em>
                    <span>4000-192-520</span>
                </div>
                <p>|</p>
                <div class="header_left_2">
                    <a href="#"><em class="iconfont icon-shouji"></em></a>
                    <span><a href="#">下载Rosewin鲜花APP</a></span>
                </div>
            </div>
            <div class="header_bar_r">
                <div class="header_right_1">
                    <span><a href="#" class="">登录</a></span>
                    <span><a href="#">注册</a></span>
                </div>
                <p>|</p>
                <div class="header_right_2">
                    <em class="iconfont icon-gouwuche"></em><a href="#">我的购物车</a>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>
<style>
    *{box-sizing: border-box;}
    a{text-decoration: none !important;}
    #ceiling{
        background-color: #fafafa;
        height: 35px;
        border-bottom: 1px solid #f5f5f5;
        position: relative;
        font-size: 13px;
        font-family: Arial, Helvetica, sans-serif;
        color:#555;
    }
    .header_bar_l{
        float: left;
    }
   #ceiling a{
       color: #555;
   }
   #ceiling a:hover{
       color:rgb(22, 22, 22);
   }
    .header_bar_r{
        float:right;
    }
    .header_left_1{
        position: absolute;
        top:4px;
        left:382px;
    }
    .header_left_1 em,.header_left_2 em{
        margin-right: 6px;
    }
    .header_left_2{
        position: absolute;
        top:4px;
        left:543px;
    }
     .header_bar_l p{
        position: absolute;
        top:0px;
        left:513px;
    }
    .header_right_1{
        position: absolute;
        top:6px;
        right:512px;
    }
    .header_right_2{
        position: absolute;
        top:2px;
        right:343px;
    }   
    .header_bar_r p{
        position: absolute;
        top:0;
        right:475px;
    }
    .header_right_1 span{
        margin-left: 20px;
    }
    .header_right_2 em{
        margin-right: 5px;
    }
    #ceiling p{
        font-size: 20px;
        color: #999;
    }
</style>