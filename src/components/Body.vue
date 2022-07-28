<template>
    <div class="body">
        <div class="main">
            <div class="main-left">
                <div class="container">
                    <div class="panel">
                        <div class="panel-header">
                            空间使用情况
                        </div>
                        <div class="panel-body">
                            <img src=".././assets/img/7天播放.jpg" alt="">
                        </div>
                    </div>
                </div> 
                <div class="container">
                    <div class="panel">
                        <div class="panel-header">
                            空间使用情况
                        </div>
                        <div class="panel-body">
                            <img src=".././assets/img/7天播放.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="container">
                    <div class="panel">
                        <div class="panel-header">
                            空间使用情况
                        </div>
                        <div class="panel-body">
                            <img src=".././assets/img/7天播放.jpg" alt="">
                        </div>
                    </div>
                </div>
                <div class="container">
                    <div class="panel">
                        <div class="panel-header">
                            空间使用情况
                        </div>
                        <div class="panel-body">
                            <img src=".././assets/img/7天播放.jpg" alt="">
                        </div>
                    </div>
                </div>             
            
       
       
       
       
       
       
            </div>
            <div class="main-right">
                <div class="container-right">
                    <div class="panel">
                        <div class="panel-header">
                            账号信息
                        </div>
                        <div class="panel-body">
                            <p>电子邮箱: xiaojunkang@polyv.net</p>
                            <p>用户名称: 前端-肖俊康</p>
                            <p>视频总数: 7</p>
                            <p>注册时间: 2022-07-15</p>
                            <p>服务套餐: 体验版
                                <button id="askforservice">我要升级套餐</button>
                            </p>
                        </div>
                    </div>
                </div>  
                <div class="container-right">
                    <div class="panel">
                        <div class="panel-header">
                            账号信息
                        </div>
                        <div class="panel-body">
                            <div class="announcement">
                            <h4>VRM12重磅升级！</h4>
                            <span>2021-11-11 11:11</span>
                            <span >保利威一直在致力于提升视频播放的安全性,保护您的视频资源。VRM解决方案也已经发展到了12.0版本。此次升级不仅提升了视频安全性，更解决了业界移动端播放器劫持的问题</span>
                            <p>
                                <a href="">查看详情</a>
                            </p>
                            </div>
                        </div>
                    </div>
                </div>        
            </div>
        </div> 
    </div>  
</template>
<style scoped>
*{
    box-sizing: border-box;
}
    img{
        width:427px;
        /* height:560px; */
    }
    .body{
        
        padding-top: 70px;
    }
    .main{       
        
        width: 100%;
    }
    .main .main-left{
        width:75%;
        float: left;
    }

    .main .main-right{
        float:left;
        width:25%;
        
    }.main .main-right .container-right{
        
        padding-left: -15px;
        padding-right: -15px;
        margin: 15px;
    }
    .main .main-left .container{
        float: left;
        padding-left: -15px;
        padding-right: -15px;
        margin: 15px;
    }
    .main .main-left .container .panel{
        border:1px solid transparent;
        border-radius: 4px;
        border-color: #ddd;
        color: #333;
        background-color: #fff;
    }
    .main .main-left .container .panel .panel-header{
        background-color: #f5f5f5;
        border-color: #ddd;
        padding :10px 15px;
        border-bottom: 1px solid transparent;
        border-top-left-radius: 3px;
        border-top-right-radius: 3px;
    }
     .main .main-right .container-right .panel{
        border:1px solid transparent;
        border-radius: 4px;
        border-color: #ddd;
        color: #333;
        background-color: #fff;
     }
     .main .main-right .container-right .panel .body{
        padding:15px;
        line-height: 1.42857143;
        display: table;
        content: " ";
}
    
     .main .main-right .container-right .panel .panel-header{
        background-color: #f5f5f5;
        border-color: #ddd;
        padding :10px 15px;
        border-bottom: 1px solid transparent;
        border-top-left-radius: 3px;
        border-top-right-radius: 3px;
        /* margin: 0px; */
    }
    #askforservice{
    color: #fff;
    background-color: #f0ad4e;
    border-color: #eea236;
    display: inline-block;
    padding: 6px 12px;
    margin-bottom: 0;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.42857143;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    -ms-touch-action: manipulation;
    touch-action: manipulation;
    cursor: pointer;
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    background-image: none;
    border: 1px solid transparent;
    border-radius: 4px;
}
p{
    margin:0px 0px 10px 10px;
    
}
.announcement{
    margin-left: 10px;
}
    
</style>

 
