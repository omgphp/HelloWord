# HelloWord
小小程序
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>简单的纯css导航</title>
   <style type="text/css">
        *{
            margin: 0;
            padding: 0;
        }
        .nav{
            width: 960px;
            height: 60px;
            background-color: black;
            margin: 20px auto;

        }
        .nav a:link ,.nav a:visited{
            height: 58px;
            line-height: 58px;
            padding-left: 30px;
            padding-right: 30px;
            color: white;
            text-decoration:none;
            float: left;
        }
        .nav_menu1{
            background-color: red;
        }
        .nav a:hover{
            background-color: red;
        }

    </style>
</head>
<body>
<div class="nav">
    <a href="#" class="nav_menu1">首页</a>
    <a href="#">免费视频</a>
    <a href="#">直播课程</a>
    <a href="#">学员作品</a>
    <a href="#">社区</a>
</div>

</body>
</html>
