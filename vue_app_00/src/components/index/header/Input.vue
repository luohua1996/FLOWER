<template>
    <div>
      <div class="header_middle">
        <div class="header_logo ">
            <a href="">
                <img src="../../../../img/header-img/huazan_logo.png" alt="">    
            </a>    
        </div>    
        <div class="header_search ">
            <input type="text" placeholder="请输入关键字">
            <button class="header_search_btn"><em class="iconfont icon-sousuo"></em></button>  
        </div>    
        <div class="header_down">
            <a href=""><img src="../../../../img/header-img/2019071.png" alt="" class="mr-4"></a>    
            <a href=""><img src="../../../../img/header-img/201907.png" alt=""></a>    
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
    .header_middle{
        display: flex; 
        justify-content: space-around;
        align-items: center;
        padding-top: 66px;
        margin-bottom: 137px;
    }
    .header_search input{
        text-indent: 20px;
        width: 400px;
        padding:0 40px 0 0;
        height:39px;
        border:1px solid #e8e8e8;
        border-radius: 30px;
        outline: none;
    }
    .header_search{
        margin:0 -373px;
    }
    .header_search_btn {
        width: 30px;
        height: 38px;
        border: none;
        background: #fff;
        position: absolute;
        right: 991px;
        top: 111px;
        border-radius: 30px;
        padding:0;
    }    
    
    
</style>