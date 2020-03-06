<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<header>
    <div class="navigation">
        <a class="logo" href="#"><img src="panda.png" width="100" height="100" alt="A logo of WWF"/></a>
        <nav class="home">
            <ul>
                <li><a href="https://www.youtube.com/">Contacts</a></li>
                <li><a href="https://www.w3schools.com/html/default.asp">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="https://www.google.com/webhp?authuser=1">services</a></li>
                <li><a href="web2.html">Home</a></li>
            </ul>
        </nav>
    </div>
</header>
<div class="get">
<h1>Hello Get Start</h1>
<a href="navigation.html">Start</a>
</div>
</body>
<style>
    .get{
        margin-top: 150px;
        align-content: center;
        justify-content: center;
        margin-left: 600px;
        line-height: 100px;
    }
    .get a{
        margin-left: 70px;
        padding: 12px;
        border: 3px solid white;

        background-color:transparent;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: 400;
        font-family: Arial, Helvetica, sans-serif;
        color: whitesmoke;
        transition: 0.1s;
    }
    .get h1{
        color: ghostwhite;
    }
    .get a:hover{
        background-color:darkred;  
    }
    .get a:active{
        background-color: chartreuse;
    }
    header{
        height: 100px;
        background-color:transparent;
    }
.navigation{
 margin: 0px 10px;


}
.logo{
    float: left;   
}
.navigation .home ul{
    background-color: transparent;
    overflow: hidden;
}
.navigation .home ul li{
    float:right;
        list-style-type: none;
       
    
}
.navigation .home ul li a{
    display: block;
    text-decoration: none;
    text-transform: uppercase;
    padding: 10px;
    border-radius: 8px;
    font-weight: 400;
    font-family: Arial, Helvetica, sans-serif;
    color: azure;
     transition: 0.5s;

}
.navigation .home ul li a:hover{
    background-color: darkred;
}
.navigation .home ul li a:active{
    background-color: burlywood;
}
body{
    background-image:url(gras.jpg);
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
}
</style>
</html>
