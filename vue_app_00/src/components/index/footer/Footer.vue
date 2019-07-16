<template>
    <div>
        <div class="footer">
            <!-- 黑杠 -->
            <div class="pw_footer_top">
                <div class="footer_nav">
                    <table></table>
                    <a href="#" class="footer_a_bg1">
                        <div>
                            高档花材
                            <span>100品质保障</span>
                        </div>
                    </a>
                    <a href="#" class="footer_a_bg2">
                        <div>
                            同城配送
                            <span>1-3小时送达</span>
                        </div>
                    </a>
                    <a href="#" class="footer_a_bg3">
                        <div>
                            特色服务
                            <span>高端私人订制</span>
                        </div>
                    </a>
                    <a href="#" class="footer_a_bg4">
                        <div>
                            时尚原创花艺
                            <span>资深花艺师独家设计</span>
                        </div>
                    </a>
                    <div style="clear:both"></div>
                </div>
            </div>
            <!-- 底部文字 -->
            <div class="footer_text_box mt-5">
                <div class="footer_text row">
                    <div class="footer_left col-6 d-flex justify-content-between">
                        <ul>
                            <li>购物说明</li>
                            <li><a href="#">App专享介绍</a></li>
                            <li><a href="#">购物流程</a></li>
                            <li><a href="#">支付说明</a></li>
                        </ul>
                        <ul>
                            <li>配送说明</li>
                            <li><a href="#">配送说明</a></li>
                            <li><a href="#">配送范围</a></li>
                            <li><a href="#">配送费用</a></li>
                        </ul>
                        <ul>
                            <li>售后保障</li>
                            <li><a href="#">取消/修改订单</a></li>
                            <li><a href="#">关于签收</a></li>
                            <li><a href="#">关于投诉</a></li>
                        </ul>
                        <ul>
                            <li>关于我们</li>
                            <li><a href="#">品牌介绍</a></li>
                            <li><a href="#">实例证明</a></li>
                            <li><a href="#">花语大全</a></li>
                            <li><a href="#">鲜花百科</a></li>
                        </ul>
                        <ul>
                            <li>同城配送</li>
                            <li><a href="#">北京鲜花</a></li>
                            <li><a href="#">上海鲜花</a></li>
                            <li><a href="#">广州鲜花</a></li>
                            <li><a href="#">更多城市</a></li>
                        </ul>
                        <!-- 友情链接 -->
                        <div>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                            <a href="#"></a>
                        </div>
                    </div>
                    <div class="footer_center col-3 text-center">
                        <span>客服电话</span>
                        <h4>4000-192-520</h4>
                        <p>工作日08:30-21:30</p>
                        <p>节假日06:00-24:00</p>
                    </div>
                    <div class="footer_right col-3 d-flex justify-content-around">
                        <div>
                            <p>Iphone下载</p>
                            <div>
                                <img src="../../../img/footer-img/微信图片_20190716194210.png" alt="">
                            </div>
                        </div>
                        <div>
                            <p>Android下载</p>
                            <div>
                                <img src="../../../img/footer-img/微信图片_20190716194240.png" alt="">
                            </div>
                        </div>
                        
                    </div>
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
/* 黑杠 */
    .footer{
        height: 300px;
    }
   .pw_footer_top{
       width: 100%;
       background-color: #000;
       height: 100px;
   } 
   .footer_nav{
       width: 70%;
       height: 100px;
       margin:0 auto;
   }
    .footer_nav a{
        display: block;
        width: 315px;
        height: 70px;
        float: left;
        color: #fff;
        text-decoration: none;
        padding-top: 11px;
    }
    .footer_nav div{
        font-size: 22px;
        padding-top: 5px;
        font-family:Georgia, 'Times New Roman', Times, serif;
        margin-left: 88px;
    }
    .footer_nav div>span{
        display: block;
        margin-top: 6px;
        font-size: 14px;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
    .footer_a_bg1{
        margin-left: 216px;
        background-image:url(../../../img/footer-img/_20190716110447.png);
        background-repeat:no-repeat;
        background-position-x: 12px ;
        background-position-y:14px;
        background-size:67px;
    }
    .footer_a_bg2{
        background-image:url(../../../img/footer-img/_201907161104471.png);
        background-repeat:no-repeat;
        background-position-x: 12px ;
        background-position-y:14px;
        background-size:61px;
    }
    .footer_a_bg3{
        background-image:url(../../../img/footer-img/_201907161104472.png);
        background-repeat:no-repeat;
        background-position-x: 14px ;
        background-position-y:14px;
        background-size: 57px;
    }
    .footer_a_bg4{
        background-image:url(../../../img/footer-img/_201907161104473.png);
        background-repeat:no-repeat;
        background-position-x: 12px ;
        background-position-y:14px;
        background-size: 62px;
    }
    /*  底部文字*/
    .footer_text_box{
        width: 100%;

    }
    .footer_text{
        width: 70%;
        margin:0 auto;
    }
    .footer_text ul{
        list-style: none;
    }
    .footer_left ul li:first-child{
        font-size: 20px;
        color:#333;
    }
    .footer_left ul li a{
        text-decoration: none;
        color:#666;
        line-height: 44px;
    }
    .footer_left ul li a:hover{
        color:#000;
    }
    .footer_center h4{
        font-size: 34px;
        line-height: 55px;
        color:#555;
    }
    .footer_center span{
        font-size: 20px;
        color: #333;
    }
    .footer_left,.footer_center{
        border-right: 1px solid #e8e8e8;
    }
    .footer_right>div:first-child{
        margin-right: -108px;
    }
    .footer_right>div>div{
        border:1px solid #e8e8e8;
        padding:5px;
    }
</style>