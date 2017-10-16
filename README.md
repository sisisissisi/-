# -
一个以怀旧为主题的网站
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0,
           minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="stylesheet" href="lib/bootstrap-3.3.7-dist/css/bootstrap.min.css" type="text/css">
    <link rel="stylesheet" href="./css/navBar.css">
    <link rel="stylesheet" href="./css/mainScreen.css" type="text/css">
    <link rel="stylesheet" href="./css/footer.css">
    <title>Title</title>
    <style>
        *{
            margin: 0px;
            padding: 0px;
        }
         body{
                font-family: "Adobe 楷体 Std R";

         }
         a{
             text-decoration: none;
         }
         a:hover{
             text-decoration: none;

         }


/*@media (max-width:768px) {
    .bg{

    }
}*/
  /*     .example ul{
           width:1030px;
           height: 90px;
           margin: 20px auto;
           position: relative;
       }
        .example ul li{
            margin-top: 32px;
            width: 280px;height: 32px;margin-right: 0px;text-align: center;line-height: 32px;
            cursor: pointer;
        }
        .example ul li a{
            display: inline-block;
            width: 32px;
            height: 32px;
            color: #ffffff;
            box-shadow: 0px 0px 0px 2px #ffffff inset;
            transition: box-shadow 0.3s ease 0s;
            border-radius: 19px ;
            margin-left: 30px;
        }
        .example ul li a:hover{
            box-shadow: 0 0 0 16px #ffffff inset;
            color: #C1DCC5;
        }
        .example .you{
            position: absolute;
            color: #999999;

        }
        .example .you li{
            width: 180px ;
            height: 56px ;
            border-radius: 28px;
            background: #ffffff;
            text-align: left;
        }
        .example .you  .one{
            line-height: 56px;
            position: absolute;
            left: -1920px;
            opacity: 0;
            top: 40px;
            transition: all 1s ease-in 0s;
        }
        .example .you  .two{
            line-height: 56px;
            position: absolute;
            left:-1920px;
            opacity: 0;
            top: 40px;
            transition: all 1s ease-in 0s;
        }
        body:hover .example .you .one{
            position: absolute;
            left: 200px;
            opacity: 0.8;
            top: 40px;

        }
        body:hover .example .you .two{
            position: absolute;
            left: 400px;
            opacity: 0.8;
            top: 40px;
        }
        .example .you  .one span,.example .you  .two span{
            float: left;
            width: 40px;
            height: 40px;
            text-align: center;
            line-height: 40px;
            border-radius: 20px;
            margin: 8px 10px 0 10px ;
            box-shadow: 0 0 0 1px #90c197 inset;
            transition: box-shadow 0.3s ease 0s;
            color: #90c197;
        }
        .example .you  .two span{
            margin: 8px 30px 0 10px;
        }
        .example .you  .one:hover span,.example .you  .two:hover span{
            box-shadow: 0 0 0 20px #90c197 inset;
            color: #ffffff;
        }*/

    </style>
</head>
<body>
<nav class="navbar  navbar-fixed-top " role="navigation" id="nav">
    <div class="container-fluid">
        <div class="navbar-header">
            <button type="button" class=" menu navbar-toggle" data-toggle="collapse" data-target="#navigations">
                <span class="sr-only">切换导航栏</span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
                <span class="icon-bar"></span>
            </button>
            <a href="#" class="navbar-brand">他的情怀</a>
        </div>
        <div class="collapse navbar-collapse navbar-right" id="navigations">
            <ul class="nav navbar-nav daohang">
                <li><a href="#"  class="active" >文化</a></li>
                <li><a href="#">生活</a></li>
                <li><a href="#">文化生活</a></li>
                <li class="login"><a href=""><span class="glyphicon glyphicon-edit"></span> 注册</a></li>
                <li class="login"><a href=""><span class="glyphicon glyphicon-log-in"></span> 登录</a></li>
            </ul>
        </div>
    </div>
</nav>
<div  class="bg">
    <div class="container">
        <header id="title">
            <h1>他的情怀，你的生意</h1>
            <h3>His feelings,Your business</h3>
        </header>
        <form action="login.html" method="post" name="formLogin" id="login">
            <button class="btn btn-primary btn-lg">GET STARTED</button>
        </form>
        <div class="goDown">
            <ul class="menu_down">
                <li><span class="glyphicon glyphicon-menu-down"></span></li>
                <li><span class="glyphicon glyphicon-menu-down"></span></li>
            </ul>
            <div class="learnMore">
                <h3>LEARN MORE</h3>
            </div>
        </div>
    </div>
</div>
<div style="height: 1000px ;background-color: white" class="traCulture">
<!--    <ul>
        <li>
            <a href="">&#xe65e;</a>
            <a href="">&#xe608;</a>
            <a href="">&#xf012a;</a>
            <a href="">&#xe68e;</a>
        </li>
    </ul>
    <ul class="you">
        <li class="one"><span>&#xe662;</span>STANDARD标准</li>
        <li class="two"><span>&#xe6662;</span>HD标准</li>

    </ul>-->
    <div class="container-fluid">
        <div class="Content">
            <div class="col-md-1"></div>
            <!--这里有个a连接要跳转-->
            <div class="kunImg col-md-5 " >
                <a href="">
                    <img src="images/kun.jpg" alt="昆剧" class=" img-responsive" title="昆剧">
                </a>
            </div>
            <div class="col-md-6 ">
                <div class="Direction">
                    <h2>昆剧</h2>
                    <p>入选时间：<strong>2001年5月18日</strong>，联合国教科文组织在巴黎宣布<strong>第一批</strong>“人类口头和非物质遗产代表作”
                        (以下简称“代表作”)名单，共有19个申报项目入选，其中包括中国的昆曲艺术，<strong>中国成为首次获此殊荣
                            的19个国家之一</strong>。
                    </p>
                </div>
            </div>
        </div>
        <div class="clearfix"></div>

        <div class="Content">
            <div class="col-md-6 pull-left">
                <div class="Direction">
                    <h2>古琴艺术</h2>
                    <p>入选时间： 联合国教科文组织<strong>2003年11月7日</strong>在其巴黎总部宣布了世界<strong>第二批</strong>
                        “人类口头和非物质遗产代表作”，中国的古琴艺术名列其中。</p>
                </div>
            </div>
            <div class="col-md-1"></div>
            <!--这里有个a连接要跳转-->
            <div class="GuQinImg col-md-5 pull-right">
                <a href="">
                    <img src="images/Guqin.jpg" alt="古琴艺术" class=" img-responsive" title="古琴艺术">
                </a>
            </div>
        </div>
        <div class="clearfix"></div>
        <div class="Content">
            <div class="col-md-1"></div>
            <!--这里有个a连接要跳转-->
            <div class="MengGuImg col-md-5">
                <a href="">
                    <img src="images/Menggu.jpg" alt="蒙古长调" class=" img-responsive" title="蒙古长调">
                </a>
            </div>
            <div class="col-md-6">
                <div class="Direction">
                    <h2>蒙古长调</h2>
                    <p>入选时间：<strong>2005年11月25日</strong>，联合国教科文组织在巴黎总部宣布了
                        <strong>第三批</strong>“人类口头和非物质遗产代表作”，中国、蒙古国联合申报的
                        <strong>“蒙古族长调民歌”</strong>榜上有名。</p>
                </div>
            </div>
        </div>
        <div class="clearfix"></div>

        <div class="Content">
            <div class="col-md-5">
                <div class="Direction">
                    <h2>端午节</h2>
                    <p>入选时间：<strong>2009年9月28日至10月2日</strong>举行的联合国教科文组织保护非物质文化
                        遗产政府间委员会第四次会议</p>
                </div>
            </div>
            <div class="col-md-1"></div>
            <!--这里有个a连接要跳转-->
            <div class="col-md-5 pull-right">
                <a href="">
                    <img src="images/DragonBost.jpg" alt="端午节" class="img-responsive" title="端午节">
                </a>
            </div>
        </div>
    </div>
</div>
<div class="clearfix"></div>
<!--这里有个a连接要跳转-->
<div class="GoCulture">
    <div class="col-md-1 pull-right">
        <a href="" title="更多">
            <span class="glyphicon glyphicon-menu-right"></span>
            <span class="glyphicon glyphicon-menu-right"></span>
            <span class="glyphicon glyphicon-menu-right"></span>
        </a>

    </div>
</div>

<!--<h1 class="page-header" style="margin-top: 20px"></h1>-->
<footer>
    <div class="container-fluid">
        <div class="col-md-4">

            <p><a href="">他的情怀</a> (以下简称“代表作”)名单，共有19个申报项目入选，
                其中包括中国的昆曲艺术，</p>
        </div>
        <div class="col-md-2 pull-right">
            <div class="GoTop">
                <span class="glyphicon glyphicon-arrow-up"></span>
            </div>
        </div>

    </div>
</footer>


<script src="lib/jquery-1.12.4.js" type="text/javascript"></script>
<script src="lib/bootstrap-3.3.7-dist/js/bootstrap.min.js" type="text/javascript"></script>
<script src="./js/navBar.js" type="text/javascript"></script>
<script src="./js/mainScreen.js"  type="text/javascript"></script>
<script src="./js/footer.js" type="text/javascript"></script>
<script>

</script>
</body>
</html>
