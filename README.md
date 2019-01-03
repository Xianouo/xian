<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="../csss/csss/bootstrap.min.css">
    <link rel="stylesheet" href="../csss/csss/font-awesome-4.7.0/css/font-awesome.min.css">
    
<!--    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">-->
<!--    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB" crossorigin="anonymous">-->
    <link rel="stylesheet" href="css/style.css">
<!--    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">-->
    <title>Bootstrap Theme</title>
</head>

<body>
    <!-- START HERE -->

    <!-- NAVBAR WITH RESPONSIVE TOGGLE -->
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark ">
        <div class="container">
            <a class="navbar-brand" href="#">宥憲</a>
            <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
      </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item mx-2">
                        <a class="nav-link" href="./end.html">HOME</a>
                    </li>
                </ul>

                <ul class="navbar-nav ml-auto">
                    <li class="nav-item dropdown mr-3">
                        <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown">
                            <i class=""></i> 所有報告
                        </a>
                        <div class="dropdown-menu">
                            <a href="../w01/intro.html" class="dropdown-item">
                                <i class=""></i> W01
                            </a>
                            <a href="../w02/table.html" class="dropdown-item">
                                <i class=""></i> W02-1
                            </a>
                            <a href="../w02(1)/work.html"class="dropdown-item">
                                <i class=""></i> W02-2
                            </a>
                            <a href="../w03/TKU60.html"class="dropdown-item">
                                <i class=""></i> W03-1
                            </a>
                            <a href="../w03(1)/work2.html"class="dropdown-item">
                                <i class=""></i> W03-2
                            </a>
                            <a href="../w04/blog.html"class="dropdown-item">
                                <i class=""></i> W04-1
                            </a>
                            <a href="../w04/ttt.html" class="dropdown-item">
                                <i class=""></i> W04-2
                            </a>
                            <a href="../w04(1)/profile.html" class="dropdown-item">
                                <i class=""></i> W04-3
                            </a>
                            <a href="../w05/imagegallery.html" class="dropdown-item">
                                <i class=""></i> W05
                            </a>
                            <a href="../w06/index.html" class="dropdown-item">
                                <i class=""></i> W06
                            </a>
                            <a href="../w07/gallery.html" class="dropdown-item">
                                <i class=""></i> W07
                            </a>
                            <a href="../w08/index.html" class="dropdown-item">
                                <i class=""></i> W08
                            </a>
                            <a href="../My_Web_page/total.html" class="dropdown-item">
                                <i class=""></i> 我的網頁
                            </a>
                        </div>
                    </li>
                    
                </ul>
            </div>
        </div>
    </nav>
    <!-- HEADER -->
    <header class="bg-primary text-light py-2">
        <div class="container">
            <div class="col-md-6">
                <h1><i class=""></i>期末報告</h1>
            </div>
        </div>
    </header>
    <b><h1><center>我的心得</center></h1></b>
    <b><h3><center>上完了這堂課,<br>我覺得自己學到了很多平常根本不會碰到的東西,<br>我覺得這堂課讓我獲益良多!<br>知道了網頁是如何被設計出來的,<br>也知道了網頁其實沒那麼好設計,<br>希望以後還有機會繼續深入了解!</center></h3></b>
    <!-- ACTIONS -->
    
    
<!--
    <script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8=" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>
    <script src="https://cdn.ckeditor.com/4.11.1/standard/ckeditor.js"></script>
-->
    <script src="../csss/js/jquery-3.3.1.slim.min.js"></script>
    <script src="../csss/js/popper.min.js"></script>
    <script src="../csss/js/bootstrap.min.js"></script>
    
    <script>
        $('#year').text(new Date().getFullYear());
        CKEDITOR.replace('editor1');
    </script>
</body>

</html>
