<template>
    <div>
    <div class="productFilter my_flex">
        <div class="left_pro">
            <ul class="my_flex">
                <li><a>排序:</a></li>
                <li><a>新品</a></li>  
                <li><a>人气</a></li>  
                <li><a>价格</a> </li>
                <li>
                    <a><i class="el-icon-caret-top"></i></a>
                    <a><i class="el-icon-caret-bottom"></i></a>   
                </li>      
            </ul>
        </div>
        <div class="right_pro">
            <span>58个结果</span>
            <el-pagination  background  layout="prev, pager, next" :total="40"  ></el-pagination>
        </div>         
    </div>
    <div class="my_flex main">
        <div  v-for="(elem,i) of list" :key="i" class="main_pro">
            <a :href="elem.href"><img :src="`http://127.0.0.1:3000/`+elem.pic" ></a>
            <p >
                <a v-text="elem.title" :href="elem.href"></a>
            </p>
            <p v-text="elem.price"></p>
        </div>
    
    </div>
</div>
    
</template>
<script>
  export default{
        data(){
            return{
                list:[],
               
            }
        },
        
        created() {
              var url="extend";
                this.axios.get(url).then(result=>{
                    console.log(result);
                     this.list=result.data
                })
        },     
    }
</script>
<style scoped>
   
    a{
        cursor: pointer;
    }
    .app-container{
       overflow-x: unset;
    }
    .productFilter{
        width:1200px;
        margin:0 auto;
        border-bottom: 1px solid #d2d2d2;
        border-top: 1px solid #d2d2d2;
    }
    ul li{
        list-style:none
    }
    .my_flex{
        display:flex;
        flex-wrap:wrap;
        justify-content:space-between;
    }
    .right_pro{
        display:flex;
        flex-wrap:wrap;
        justify-content:right
    }
    .my_flex>li:last-child{
        position:relative;
    }
    .el-icon-caret-top{
        position:absolute;
        left:-37px;top:4px;
        color:#d2d2d2;
    }
     .el-icon-caret-bottom{
        position:absolute;
        left:-37px;top:9px;
        color:#d2d2d2;
    }
    .left_pro>ul>li{
        margin:0 20px;
    }
     .left_pro>ul>li>a{
         font: 12px "微软雅黑",Helvetica,sans-serif
     }
     .right_pro>span{
         font: 12px "微软雅黑",Helvetica,sans-serif;
         color: #b3b3b3;
         display:inline-block;
         height:53px;
         line-height:63px;
        margin-right: 30px;
        position:absolute;
        left:-305px;
        top: 1px;
     }
     .el-pagination{
        height:53px;
        position:absolute;
        left: -240px;
        top: 12px;
}

 .right_pro{
         position:relative;
     }
  .main{
      width:1200px;
      margin:0 auto;
      margin-top:20px
  }  
  .main img{
      width:280px;
      height:280px;
  }
 .main a{
     color: #666;
    text-decoration: none;
    font-size:12px;
 }
 .main p{
     color: #999;
    
    font-size:12px;
 }
 .main_pro{
     margin:10px 0;
 }

</style>