<template>
    <div>
        <div class="nav-background"> 
        <div  class="logo">
            <img src="../assets/img/logo.png" alt="" > 
        </div>  
        <div class="header">
            <li><a href="https://my.polyv.net/secure/main" class="qaq">云点播</a>
                <img src="/img/箭头.png" alt="" class="logo2">
                <ul>
                    <li><a href="https://console.polyv.net/home/">产品首页</a></li>
                    <li><a href="https://console.polyv.net/home/" style="color:rgb(33, 150, 243)">云点播</a></li>
                    <li><a href="https://console.polyv.net/live/#/channel">云直播</a></li>
                    <li><a href="https://portal.polyv.net/index">视频微门户</a></li>
                </ul>
            </li>
        
        </div>
        <div class="nav1">
            <ul>               
                <li class="overview"><a href="https://my.polyv.net/secure/main" >概览</a></li>
                <li><a href="https://my.polyv.net/secure/uploadvideochunk_v2">上传视频</a></li>
                <li><a href="https://my.polyv.net/secure/video/">视频列表</a></li>
                <li><a href="https://my.polyv.net/secure/player">播放器设置</a></li>
                <li><a href="https://my.polyv.net/secure/advertising/">广告管理</a></li>
                <li><a href="https://data.polyv.net/secure/overview/?lang=zh_CN">数据统计</a></li>
                
            </ul>
        </div>  
        <div class="setting">
            <li><a href="">设置</a>
                <ul>
                    <li><a href="https://my.polyv.net/secure/setting/callback">回调设置</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/api">API接口 </a> </li>
                    <li><a href="https://my.polyv.net/secure/setting/account/">账号管理</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/playsafe">加密设置</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/video">视频设置</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/host_setting">播放域名设置</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/questionnaire">访客信息收集</a></li>
                    <li><a href="https://my.polyv.net/secure/setting/wechat-share">微信分享设置</a></li>
                </ul> 
            </li>
        </div>  
        <div class="nav2">
            <li class="help"><a href=""><img src="../assets/img/帮助.png" alt=""></a></li>
            <li class="download"><a href=""><img src="../assets/img/下载1.png" alt=""></a></li>
            <li class="data"><a href=""><img src="../assets/img/数据库,数据.png" alt=""></a></li>
            <li><a href="" >中文</a>
                <ul>
                    <li><a href="">中文</a></li>
                    <li><a href="">English</a></li>
                </ul>
            </li>          
        </div>     
    </div> 
    <div class="test"></div>
    
    </div>
</template>
<style>
    .nav-background{
        position: fixed;
    }
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        }
        body{
        font-size: 14px ;
        }
        .logo{
        display: block;
        line-height: 56px;
        margin-top: 5px;
        margin-left: 20px;
        margin-right: 20px;
        }
        .logo2{
            width: 8px;
            vertical-align: middle;
        }
        .nav-background{
        background-color: rgb(39, 44, 47);
        height: 56px;
        width: 100%;
        min-width: 1280px;
        display: flex;
        z-index: 1030;
            
        }
        .nav-background .nav1 ul{
        list-style: none;
        }
        .nav1 ul { 
        display: flex;
        justify-content: flex-start ;
        height: 56px;
        }
        .nav1 ul li{
        line-height: 56px;
        margin: 0 20px;
        width: 70px;
        text-align: center;
        }
        .nav1 ul li a{
        text-decoration: none;
        color: #fff;
        }
       
        .nav1 ul .header{
        background-color: rgb(33, 150, 243);
        }
        .header li ul li{
        background-color: rgba(39, 44, 47, .7);
        width: 100px;
        display: none;
        padding: 0;
        text-align: center;
        }
        .header li ul li a{
            margin-left: -8px;

        }
       
       .header{
        z-index: 1000;
       }
       .header li{
        list-style: none;
        height: 56px;
        background-color: rgb(33, 150, 243);
        width: 100px;
        text-align: center;
       }
       .header li a{
        text-decoration: none;
        line-height: 56px;
        color: #fff;
       }
       .header li:hover ul li{
        display: block;
       }
      .header li ul li:hover {
        background-color: rgba(39, 44, 47);
      }
      
      .nav-background .nav1 ul li:hover{
        background-color: rgba(103, 107, 109, .7);
      }
      .nav1 ul li ul li{
        display: block;
      }
      .setting li{
        list-style: none;
        height: 56px;
        background-color: rgb(39, 44, 47);
        width: 100px;
        text-align: center;
       }
       .setting li a{
        text-decoration: none;
        color: #fff;
        line-height: 56px;
       }
       .setting li ul li{
        background-color: rgba(39, 44, 47, .7);
        display: none;
        
       }
       .setting li ul li a{
        color: #fff;
       }
       .setting li ul li:hover{
        background-color:rgba(39, 44, 47) ;
        }
        .setting li:hover ul li{
            display: block;
        }
        .nav2{
            margin-right: 0px;
            display: flex;
            width: 40%;
           flex-direction: row-reverse;
        }
        .nav2 li {
            list-style: none;
            height: 56px;
            width: 45px;
            text-align: center;
       }
       .nav2 li:hover {
        background-color: rgba(39, 44, 47);
       }

        .nav2 li a{
            text-decoration: none;
            line-height: 56px;
            color: #fff;
        }
        .setting{
          z-index: 999;
        }
        .setting ul{
          z-index: 1001;
        }
        .nav2 li ul li{
        background-color: rgba(103, 107, 109,.7);
        display: none;
        }
        .nav2 li:hover ul li{
        display: block;
            
        }
       
       
        .nav2 li ul li:hover{
        background-color: rgba();
        }
        .nav2  .data{
        height: 56px;

        }
        .nav2 .data img {
        width: 16px;
        line-height: 56px;
        margin-bottom: -5px;
        }
        .nav2 .download{
        height: 56px;
        }
        .nav2 .download img{
            width: 30px;
            margin-bottom:-12px;
        } 
        .nav2 .help img{
            width: 20px;
            margin-bottom:-5px;
        }
</style>