<!DOCTYPE html>
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.2/font/bootstrap-icons.css">
    <title>Site</title>
    <style>
        html{
            font-size:62.5%;
        }
        body {
            min-height: 100vh;
            background: url(cimen.png) bottom center repeat-x,
                url(bulut.png) top center fixed,
                #1DABB8;
            margin: 0;
        }
 
        .kapsayici {
            width: 1080px;
            margin: 200px auto 0 auto;
        }
 
        nav {
            /* min-height: 100px; */
            /* background-color: #25373D; */
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
        }
        nav ul{
            list-style: none;
            margin:0;
            padding:0;
        }
        nav ul li{
            display: inline-block;
        }
 
        nav .menu a{
            color:#fff;
            font-size:2rem;
            background-color: #25373D;
            padding:15px 30px;
            display: block;
            border:#D2D7D3 solid 5px;
            border-bottom:none;
            border-radius: 30px 30px 0 0;
            font-weight: 600;
            text-decoration: none;
        }
        nav .menu a:hover{
            background-color:#D2D7D3;
            color:#25373D;
        }
 
        nav .sosyal a{
            color:#25373D;
            font-size:2rem;
            background-color: #FEC606;
            width: 32px;
            height: 32px;
            line-height: 32px;
            text-align: center;
            padding:8px;
            display: block;
            border-radius: 50%;
            margin-bottom:5px;
        }
 
        .bolum1 {
            min-height: 300px;
            background-color: #D2D7D3;
            margin-bottom: 40px;
        }
 
        .bolum2 {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap:20px;
            padding:20px;
            background-color: #6C8784;
            margin-bottom: 40px;
        }
 
        .bolum2 .kutu{
            width: 330px;
            height: 330px;
            line-height: 330px;
            text-align: center;
            font-size:4rem;
            background-color: #D33257;
            color:#fff;
        }
 
        .bolum3 {
            display: flex;
            justify-content: space-between;
            padding:10px;
            min-height: 200px;
            background-color: #E7E7E7;
            margin-bottom: 40px;
        }
        .bolum3 .kutu{
            width: 200px;
            height: 200px;
            line-height: 200px;
            font-size:5rem;
            text-align: center;
            background-color: #D33257;
            color:#fff;
            
        }
    </style>
</head>
 
<body>
 
    <div class="kapsayici">
        <header>
            <nav>
                <ul class="menu">
                    <li><a href="#">sayfa</a></li>
                    <li><a href="#">sayfa</a></li>
                    <li><a href="#">sayfa</a></li>
                    <li><a href="#">sayfa</a></li>
                    <li><a href="#">sayfa</a></li>
                </ul>
                <ul class="sosyal">
                    <li><a href="#"><i class="bi bi-facebook"></i></a></li>
                    <li><a href="#"><i class="bi bi-facebook"></i></a></li>
                    <li><a href="#"><i class="bi bi-youtube"></i></a></li>
                    <li><a href="#"><i class="bi bi-tiktok"></i></a></li>
                </ul>
            </nav>
        </header>
        <div class="bolum1"></div>
        <div class="bolum2">
            <div class="kutu">1</div>
            <div class="kutu">2</div>
            <div class="kutu">3</div>
            <div class="kutu">4</div>
            <div class="kutu">5</div>
            <div class="kutu">6</div>
        </div>
        <div class="bolum3">
            <div class="kutu">1</div>
            <div class="kutu">2</div>
            <div class="kutu">3</div>
            <div class="kutu">4</div>
            <div class="kutu">5</div>
        </div>
    </div>
 
</body>
 
</html>
 
