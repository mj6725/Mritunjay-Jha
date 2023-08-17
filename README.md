<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADVENTURE</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/responsive.css">
    <link rel="apple-touch-icon" sizes="180x180" href="img/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="img/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="img/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
</head>
<body onload='if (window.location.href.substr(window.location.href.length - 6) == "#about") { introAboutLogoTransition(); }'>
    <!--navbar-->
    <nav class="navbar glass" style="height: 70px;">
        <span><a href="#home" style="display:flex; align-items: center;"><img class="img2" src="./img/mountain.png" width="40"
            style="margin: -25px -10px -25px -20px"><h1 class="logo">&nbsp;ADVENTURE</h1></a></span>
        <ul class="nav-links">
            <li><a href="#home" id="pri" class="active cir_border">Home</a></li>
            <li><a href="#events"  id="sec" class="cir_border">Tours</a></li>
            <li><a href="#explore" id="tri" class="cir_border">Explore</a></li>
            <li><a href="#about" id="quad" class="cir_border">About</a></li>
            <li><a href="#contribution" id="quint" class="cir_border">Contributions</a></li>
            <li><a href="#contact" id="hex" class="cir_border">Contact</a></li>
            <li><div>
                <input type="checkbox" class="checkbox dark" id="checkbox">
              <label for="checkbox" class="label">
                <i class="fa fa-moon-o"></i>
                <i class='fa fa-sun-o'></i>
                <div class='ball'>
              </label>
            </div></li>
        </ul>
        <img src="./img/menu-btn.png" alt="" class="menu-btn">
    </nav>
    <!--navbar-->



 
     

</html>
