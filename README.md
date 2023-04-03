# Dog-Adoption-Agency
First Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content=""with-device-width, initial-scale="1.0">
    <title>The CFG Dog Shelter Website</title>
<link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&display=swap" rel="stylesheet">
</head>
​
  <body>
<section class="header">
  <nav>
     <a href="index.html"><img src="cfg shelter logo.png"></a>
     <div class="nav-links">
    <ul>
      <li><a href="">HOME</a></li>
      <li><a href="about.html">ABOUT US</a></li>
      <li><a href="">BROWSE DOGS</a></li>
      <li><a href="">DONATE</a></li>
    </ul>
​
     </div>
  </nav>
    
<div class="text-box">
  <h1>The CFG Dog Shelter</h1>
<p>When a dog is in distress, we care for them. When a dog needs a home, we find them a loving family. <br> When an owner needs a helping hand (or paw), we are ready to step in.</p>
<a href=""class="home-btn">Visit us to know more</a>
​
</div>
</section>
​
​
​
​
<section>
​
<!-------Adopt a Rescue Dog------->
​
<section class="adopt">
  <h1>Adopt a Rescue Dog</h1>
  <p>Click one of our amazing dogs below to find out more</p>
​
  <div class="row">
    <div class="dog-col">
      <img src="bella dog home.jpeg">
      <h3>Bella</h3>
      <p></p>
  </div>
​
    <div class="dog-col">
      <img src="oscar.jpg">
      <h3>Oscar</h3>
  </div>
​
    <div class="dog-col">
      <img src="Benson1.jpeg">
      <h3>Benson</h3>
  </div>
​
​
</section>
​
​
​
  <!------How you can help----->
​
<section class="help">
    <h1>How you can help</h1>
  
​
    <div class="row">
      <div class="how-help">
        <h3>Adopt</h3>
        <p>If you think you are the right fit, then choose to adopt one of our lovely dogs today!</p>
      </div>
​
​
        <div class="how-help">
        <h3>Foster</h3>
        <p>Can only commit to providing a home for one of our dogs temporarily? Click to find out more about fostering. </p>
        </div>
​
​
      <div class="how-help">
        <h3>Donate</h3>
        <p>Give whatever you can and help give animals in need a second chance</p>
​
    </div>
    </section>
​
  
<footer>
  <p class="text"> Sign up to recieve our newsletter and adoption alerts </p>
            <form>
                <input type="email" required>
                <input type="submit" value="Sign Up">
                </form>
                <ul class="list-footer">
                    <li><a href="">About Us</a></li>
                    <li><a href="#">Donate</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>
               
                <p class="copyrights">&copy; 2023 CFG Adoption Service
</footer>
​
​
  </body>
​
​
</html> 

*{
    margin: 0; 
    padding:0;
    font-family: 'Poppins', sans-serif;
}
    
.header{
    min-height: 100vh;
    width: 100%;
    background-image: linear-gradient(rgba(4,9,30,0.7),rgba(4,9,30,0.7)), url(images/banner.jpeg);
    background-position: center;
    background-size: cover;
    position: relative;
}
.header img{
    width: 40%;
    
}
nav{
    display: flex;
    padding: 2% 6%;
    justify-content: space-between;
    align-items: center;
}
nav img{
    width: 150px
}
.nav-links{
    flex: 1; 
    text-align: right;
}
.nav-links ul li{
    list-style: none;
    display: inline-block;
    padding: 8px 12px;
    position: relative;
}
.nav-links ul li a{
    color: white;
    text-decoration: none;
    font-size: 13px;
}
.nav-links ul li::after{
    content: '';
    width: 0%;
    height: 2px;
    background: #597C2B;
    display: block;
    margin: auto;
    transition: 0.5s;
}
.nav-links ul li:hover::after{
    width: 100%;
}
.text-box{
    width: 90%;
    color: white;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
}
.text-box h1{
    font-size: 62px;
}
.text-box p{
    margin: 10px 0 40px;
    font-size: 14px;
    color: white;
}
.home-btn{
    display: inline-block;
    text-decoration: none;
    color: white;
    border: 1px solid white;
    padding: 12px 34px;
    font-size: 13px;
    background: transparent;
    position: relative;
    cursor: pointer;
}
.home-btn:hover{
    border: 1px solid #357A4E;
    background: #357A4E;
    transition: 1s;
}
/*-------- how you can help -------*/
.help{
    width: 80%;
    margin: auto;
    text-align: center;
    padding-top: 30px;
}
h1{
    font-size: 30px;
    font-weight: 600;
}
p{
    color: black;
    font-size: 14px;
    font-weight: 300; 
    line-height: 22px;
    padding: 10px;
}
.row{
    margin-top: 5%;
    display: flex;
    justify-content: space-between;
}
.how-help{
    flex-basis: 31%;
    background:#357A4E;
    border-radius: 10px;
    margin-bottom: 5%;
    padding: 20px 12px;
   box-sizing: border-box;
   transition: 0.5s;
}
.how-help:hover{
box-shadow: 0 0 20px 0px rgba(0,0,0,0.2);
}
/*---------adopt-------*/
.adopt{
width: 80%;
margin: auto;
text-align: center;
padding-top: 50px;
}
.dog-col{
    flex-basis:31%;
    border-radius: 10px;
    margin-bottom: 5%;
    text-align: center;
}
.dog-col img{
    width: 100%;
    border-radius: 10px;
}
/*Footer*/
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
 }
 body {
    font-family: 'Merriweather', serif;
     }
         footer {
        width: 100%;
        position: relative;
        bottom: 0;
        background:#357A4E;
        display: flex;
        align-items: center;
        flex-direction: column;
        text-align: center;
        color: #fff;
        padding: 5px;
        }
        .text {
            font-size: 28px;
            font-weight: bold;
            font-family: 'Merriweather', serif;
            margin: 20px auto;
        }
        footer input[type='email']{
            width: calc(100vw - 55vw);
            font-size: 25px;
            padding: 5px;
            border-radius: 30px 0 0 30px;
            outline: none;
            border: none;
            color: #31AD35;
        }
        footer input[type='submit']{
            border: none;
            outline: none;
            border-radius: 0 30px 30px 0;
            padding: 5px;
            color: #fff;
            background-color: #0E8F3D;
            font-family: 'Merriweather', serif;
            font-size: 25px;
            cursor: pointer;
        }
        footer input:hover[type='submit'] {background-color: #66AD77;}
        .list-footer {
            margin: 40px auto;
            display: flex;
            list-style-type: none;
        }
      .list-footer li a {
        text-decoration: none;
        color: #fff;
        font-size: 20px;
        font-weight: bold;
        padding: 20px;
        }
    .list-footer li a:hover{color: #66AD77;}
    @media(max-width:810px){
        .text , footer input[type="email"] ,
        footer input[type="sumbit"]{
            font-size: 20px ;
        }
        .list-footer li a {
            padding: 15px;
            font-size: 15px;
        }
    }
    @media(max-width:610px){
        .text , footer input[type="email"] ,
        footer input[type="sumbit"]{
            font-size: 14px ;
        }
        .list-footer li a {
            padding: 10px;
            font-size: 12px;
        }
    }
@media(max-width:470px){
    .text {
        font-size: 12px;
    }
}
@media(max-width:330px){
    .text {
        font-size: 10px;
            }
}
