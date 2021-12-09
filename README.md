# Final-Project

index.html:

<!doctype html>

<html lang="en">

<head>

    <meta charset="utf-8">

    <title>Home</title>

    <link rel="stylesheet" href="css/style.css" type="text/css">

</head>

<body>

    <div class="container">

        <div class="fullwidth">

            <div class="header">

                <div class="logo"><img src="image/logo.png" alt="logo1" style="width:70px; height:70px;"></div>

                <nav>

                    <ul>

                        <li><a href="index.html">Home</a></li>

                        <li><a href="carrier.html">Carrier</a></li>

                        <li><a href="contact.html">Contact Us</a></li>

                    </ul>

                </nav>

            </div>

            <div class="slider">

                <img src="image/about.jpg" alt="about">

            </div>

            <div class="full_page">

                <div class="about">

                    <aside>

                        <p><strong>About me</strong><br>Hello, I’m a UI/UX Designer & Front End Developer from New York, America. I hold a degree in Computer Science from ABC University.</p>

                        <h3>Hobbies</h3>

                        <ul>

                            <li>Lorem ipsum dolar sit amet.</li> <!---dummy text-->

                            <li>Lorem ipsum dolar sit amet.</li> <!---dummy text-->

                            <li>Lorem ipsum dolar sit amet.</li> <!---dummy text-->

                        </ul>

                        <h3>Interest</h3>

                        <ul>

                            <li>Lorem ipsum dolar sit amet.</li> <!---dummy text-->

                        </ul>

                    </aside>

                    <p>Working directly with clients, I play a key role in the development of clean and modern solutions that utilize hand-coded HTML5, CSS3, JQuery, JavaScript, Bootstrap and XML along with accessible, standards-based implementations and modern trends in web/mobile design.</p><!---dummy text-->

                </div>

                <div style="clear:both;"></div>

            </div>

            <div class="footer">

                <div class="address">

                    <h2>Address...</h2>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p> <!---dummy text-->

                </div>

                <div class="socials"><img src="image/social.png" alt="social1"></div>

            </div>

        </div>

    </div>

</body>

</html>

carrier.html:

<!doctype html>

<html lang="en">

<head>

    <meta charset="utf-8">

    <title>Carrier</title>

    <link rel="stylesheet" href="css/style.css" type="text/css">

</head>

<body>

    <div class="container">

        <div class="fullwidth">

            <div class="header">

                <div class="logo"><img src="image/logo.png" alt="logo1" style="width:70px; height:70px;"></div>

                <nav>

                    <ul>

                        <li><a href="index.html">Home</a></li>

                        <li><a href="carrier.html">Carrier</a></li>

                        <li><a href="contact.html">Contact Us</a></li>

                    </ul>

                </nav>

            </div>

            <div class="slider">

                <img src="image/about.jpg" alt="about">

            </div>

            <div class="full_page">

                <div class="about">

                    <h1>Carrier</h1>

                    <p>Working directly with clients, I play a key role in the development of clean and modern solutions that utilize hand-coded HTML5, CSS3, JQuery, JavaScript, Bootstrap and XML along with accessible, standards-based implementations and modern trends in web/mobile design.</p><!---dummy text--><br><br>

                </div>

                <div style="clear:both;"></div>

            </div>

            <div class="footer">

                <div class="address">

                    <h2>Address...</h2>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>

                </div>

                <div class="socials"><img src="image/social.png" alt="social1"></div>

            </div>

        </div>

    </div>

</body>

</html>

contact.html:

<!doctype html>

<html lang="en">

<head>

    <meta charset="utf-8">

    <title>Contact</title>

    <link rel="stylesheet" href="css/style.css" type="text/css">

</head>

<body>

    <div class="container">

        <div class="fullwidth">

            <div class="header">

                <div class="logo"><img src="image/logo.png" alt="logo1" style="width:70px; height:70px;"></div>

                <nav>

                    <ul>

                        <li><a href="index.html">Home</a></li>

                        <li><a href="carrier.html">Carrier</a></li>

                        <li><a href="contact.html">Contact Us</a></li>

                    </ul>

                </nav>

                <div></div>

            </div>

            <div class="slider">

                <img src="image/about.jpg" alt="about">

            </div>

            <div class="full_page">

                <div class="about">

                    <h1>Contact</h1>

                    <p>ABC Street</p><!---dummy text-->

                    <p>New York</p><!---dummy text-->

                    <p>83434</p><!---dummy text-->

                    <p>America</p><!---dummy text-->

                    <br><br>

                </div>

                <div style="clear:both;"></div>

            </div>

            <div class="footer">

                <div class="address">

                    <h2>Address...</h2>

                    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>

                </div>

                <div class="socials"><img src="image/social.png" alt="social1"></div>

            </div>

        </div>

    </div>

</body>

</html>

style.css:

@charset "utf-8";

/* CSS Document */

html{

    font-family:"Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, sans-serif;

    color:#333;}

body{

    background:#ccc;

    margin:0;}

.container{

    width:1000px;

    margin:0 auto;

    background:#fff;}

.container .fullwidth{

    width:95%;

    margin:0 auto !important;}

.header{

    width:100%;

    height:60px;

    background-color:#333;

    border-bottom:1px solid #c7c7c7;}

    

.logo{

    float:left;

    width:40px;

    height:40px;

    margin:10px;}

.login{

    color:#fff;

    float:right;

    width:120px;

    height:30px;

    margin:10px;}

.login a{

    text-decoration: none;

    color: white;

}

/* Navigation Menu */

nav{

    clear: both;

float: right;

height: 40px;}

nav ul{

color: #fff;

float: left;

margin: 0 0 0 10px;

overflow: hidden;

width: 100%;}

nav ul li{

    float:left;

    overflow:hidden;

    margin:0 0 0 10px;}

nav ul li a{

    color: #000;

display: block;

float: left;

font-size: 12px;

    margin-top:10px;

/* padding: 10px 80px;*/

text-decoration: none}

    

nav ul li a:hover{

    background-color:#028C82;

    color:#fff;}

    

/* end Navigation menu */   

.slider img{

    width:100%;

    height:350px;}

.full_page{

    width:100%;}

    

    

.about{

    width:100%;

    height:auto;

    float:left;}

.page{

    width:100%;}

    

.footer{

    width:100%;

    background-color:#C5C2C2;}

    

.footer .links{

    width:20%;}

    

.footer .links ul{

    float:left;

    list-style-type:none;}

    

.footer .links ul li a{

    text-decoration:none;

    font-size:12px;

    font-family:"Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, sans-serif;

    color:#626161;}

    

.footer .links ul li a:hover{

    color:#16A2B3;}

    

.footer .address{

    padding:20px;

    margin-left:22%;

    width:45%;}

.footer .address h2{

    font-size:16px;

    font-family:"Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, sans-serif;}

    

.footer .address p{

    font-size:12px;

    font-family:"Lucida Grande", "Lucida Sans Unicode", "Lucida Sans", "DejaVu Sans", Verdana, sans-serif;}

    

.footer .socials{  

     margin-top:-50px;

     margin-left:70%;}

    

.footer .socials img{

     height:35px;

     width:200px;}

sample output:

