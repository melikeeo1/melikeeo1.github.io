<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Melike Oduncu</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@200&display=swap" rel="stylesheet">
    <style>
        *{
            box-sizing: border-box;
        }
 
        html{
            font-size:62.5%;/*1rem = 10px*/
        }
 
        body,h1,h2,ul{
            margin:0;
            padding:0;
            
        }
        ul{
            list-style: none;
        }
 
        /*******************/
        body{
            font-family: 'Times New Roman', regular;
        }
        .arkaplan{
            background-color: #3B5998;
        }
        .kapsayici{
            width: 960px;
            margin:0 auto;
        }
        
        .ust{
            display: flex;
            justify-content: space-between;
            align-items: center;
            min-height: 200px;
        }
 
        .ust .logo{
            text-align: center;
            color:#fff;
        }
        .ust .logo h1{
            font-size:4rem;
            letter-spacing: .5rem;
        }
 
        .ust .logo h1::first-letter{
            color:#FFFFFF;
        }
 
        .ust .logo h1:hover::first-letter{
            background-color: #3B5998;
            color:#000022;
        }
 
        .ust .logo h2{
            font-size:2.4rem;
        }
 
        
 
        
 
        .ust .menu ul{
            display: flex;
        }
        .ust .menu ul li{
            margin:0 1rem;
        }
 
        .ust .menu ul a{
            color:#fff;
            text-decoration: none;
            font-size:1.8rem;
            padding:0 2rem;
        }
        .ust .menu ul a:hover{
            color:#000022;
        }
 
        .orta .bolum1{
            margin-top:20px;
            border:10px solid #FFFFFF;
            padding:20px;
        }
 
        .orta .bolum1 img{
            display: block;
            width: 100%;
        }
 
        .orta .bolum2{
            margin-top:20px;
            display: flex;
            justify-content: space-between;
        }
        .orta .bolum2 .kutu{
            flex-basis: 290px;
        }
 
        .orta .bolum2 .kutu h2{
            font-size: 2rem;
        }
 
        .orta .bolum2 .kutu p{
            font-size: 1.6rem;
        }
 
        .orta .bolum3{
            display: flex;
            justify-content: space-between;
            gap:20px;
        }
 
        .orta .bolum3 h1{
            font-size:2.5rem;
        }
 
        .orta .bolum3 p{
            font-size:1.6rem;
        }
 
        .alt{
            margin-top:20px;
            padding:20px 0;
            display: flex;
            gap:20px;
        }
        .alt .baglanti{
            flex-grow: 1;
        }
 
        .alt .baglanti ul li{
            border-bottom:dotted 1px #FFFFFF;
            margin:5px 0;
        }
 
        .alt .baglanti a{
            font-size:1.6rem;
            text-decoration: none;
            color:#FFFFFF;
        }
 
 
        .cizgi{
            border-top:dotted 1px #3B5998;
            margin:20px 0;
        }
 
        .alt-kenar-10{
            border-bottom:10px solid #3B5998;
        }
        
    </style>
</head>
<body>
 
    <!-- sayfa ??st??-->
    <div class="arkaplan alt-kenar-10">
        <div class="ust kapsayici">
            <div class="logo">
                <h1>Sanat Galeri</h1>
                <h2>Melike Oduncu</h2>
            </div>
            <div class="menu">
                <ul>
                    <li><a href="#">HAKKIMDA</a></li>
                    <li><a href="#">FOTO??RAFLAR</a></li>
                    <li><a href="#">??EK??MLER</a></li>
                    <li><a href="#">??LET??????M</a></li>
                </ul>
            </div>
        </div>
    </div>
 
    <!-- sayfa ortas??-->
    <div class="orta kapsayici">
        <div class="bolum1">
            <img src="2.jpg" width="500" height="600" alt="Kapak resmi">
        </div>
        <div align="center" class="bolum2">
            <div class="kutu">
                <img src="3.jpg" width="150" height="200" alt="">
                <h2>Ortodoks Klisesi</h2>
                <p></p>
            </div>
            <div class="kutu">
                <img src="4.jpg" width="150" height="200" alt="">
                <h2>Mendil Satan K??????k K??z</h2>
                <p></p>
            </div>
            <div class="kutu">
                <img src="5.jpg" width="150" height="200" alt="">
                <h2>Kediler ve Kara Tren</h2>
                <p></p>
            </div>
 
 
        </div>
        <div class="cizgi"></div>
        <div class="bolum3">
            <div class="icerik">
                <h1>Melike Oduncu</h1>
                <p>Ben Melike Oduncu. F??rat ??niversitesi G??rsel ??leti??im Tasar??m?? 4. s??n??f ????rencisiyim. 	Foto??raf ??ekmeyi ve farkl?? yerler, farkl?? insanlar tan??may?? ??ok seviyorum.  </p>
            </div>
            <div class="gorsel">
                <img src="1.jpg" width="200" height="300" alt="??lgili ??r??n bilgisi">
            </div>
        </div>
    </div>
 
    <!-- sayfa alt??-->
    <div align="center" class="arkaplan">
        <div class="alt kapsayici">
            <div class="baglanti">
                <ul>
                    <li><a href="#">Melike Oduncu</a></li>
					<p></p>
					<p></p>
					 <img src="6.png" width="30" height="30" alt="Kapak resmi">		 
&nbsp;  
&nbsp;
&nbsp;			 
					 <img src="7.png" width="30" height="30" alt="Kapak resmi"> 
&nbsp;  
&nbsp;
&nbsp;
					 <img src="8.png" width="30" height="30" alt="Kapak resmi">
&nbsp;  
&nbsp;
&nbsp;
					 <img src="9.png" width="30" height="30" alt="Kapak resmi">
                </ul>
            </div>
        </div>
    </div>
    
</body>
</html>
