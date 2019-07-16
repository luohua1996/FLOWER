<template>
    <div>
        <div class="nav_tl clear-fix">
            <div class="nav_list">
                <div class="nav_tl_list">
                    <ul class="nav_list_go">
                        <li>
                            <div class="one"><a href="#">首页</a></div>
                            <div class="two"><a href="#">首页</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">进口鲜花</a></div>
                            <div class="two"><a href="#">进口鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">爱情鲜花</a></div>
                            <div class="two"><a href="#">爱情鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">生日鲜花</a></div>
                            <div class="two"><a href="#">生日鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">问候长辈</a></div>
                            <div class="two"><a href="#">问候长辈</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">祝福庆贺</a></div>
                            <div class="two"><a href="#">祝福庆贺</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">探病慰问</a></div>
                            <div class="two"><a href="#">探病慰问</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">道歉鲜花</a></div>
                            <div class="two"><a href="#">道歉鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">生活鲜花</a></div>
                            <div class="two"><a href="#">生活鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                           <div class="one"><a href="#">全部鲜花</a></div>
                            <div class="two"><a href="#">全部鲜花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">开业花篮</a></div>
                            <div class="two"><a href="#">开业花篮</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">永生花</a></div>
                            <div class="two"><a href="#">永生花</a></div>
                            <i>/</i>
                        </li>
                        <li>
                            <div class="one"><a href="#">礼品</a></div>
                            <div class="two"><a href="#">礼品</a></div>
                        </li>
                    </ul>
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
    .nav_tl{
        border-bottom: 1px solid #d2d2d2;
        /* padding:15px 0 15px; */
        width: 100%;
        min-width: 1200px;
        position: absolute;
        top:208px;
        z-index: 100;
        height: 60px;
        /* margin-bottom: 25px; */
        background: #fff;
        font-size: 12px;
        color: #555;
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
        box-sizing: border-box;
    }
    .nav_list{
        margin:0 auto;
        width: 80%;
        position: relative;
        height: 60px;
        text-align: center;
    }
    .nav_tl_list{
        margin:0 auto;
        clear: both;
        width: 100%;
        height: 60px;
        
    }
    .nav_tl_list>.nav_list_go{
        list-style: none;
        height: 60px;
        width: 100%;
        padding-left:219px;
    }
    .nav_list_go li:first-child{
        margin-left: 0;
    }
    .nav_list_go li{
        overflow: hidden;
        float: left;
        width: 116px;
        position: relative;
        height: 60px;
        line-height: 60px;
        
    }
    .nav_list_go li i{
        width: 10px;
        height: 60px;
        text-align: center;
        line-height: 60px;
        position: absolute;
        top: 0;
        right: 18px;
        color: #999;
    }
    .nav_list_go li div.one{
        top:0;
        left:0;
        z-index: 1;
    }
    .nav_list_go li div{
        cursor: pointer;    
        line-height: 60px;
        bottom:5px;
        width: 72px;
        text-align: center;
        position: absolute;
    }
    .nav_list_go li div.two a{
        font-size: 16px;
        color:#c3a563;
    }
    .nav_list_go li div.one a{
        color: #666;
    }
    .nav_list_go li div{
        transition: all 0.3s ease-in-out;
    }
    .nav_list_go li:hover .one{
        top:-60px;
    }
    .nav_list_go li:hover .two{
        bottom:4px;
    }
    .nav_list_go li div.two{
        bottom:-65px;
        left:5px;
        z-index: 2;
        line-height: 50px;
        background-color: hsla(0,0%,100%,0.96);
        box-shadow: 1px 0 10px rgba(0,0,0,.9);
    }
</style>