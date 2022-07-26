<template>
  <div id="app">
    <Header></Header>
    <Body></Body>
   <router-view></router-view>
  </div>
</template>

<script src="./assets/js/echarts"></script>

<script>
import Overview from './components/Overview.vue'
import Header from './components/Header.vue'
import Body from './components/Body'
export default {
  name: 'App',
  components: {
    Body,
    Header,
    Overview,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

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
        width: 60px;
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
        .piteimg{
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        
    
</style>  
