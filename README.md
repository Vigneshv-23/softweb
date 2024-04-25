# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
## HOME.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
   <style>
    body{
    margin: 0;
    padding: 0;
    background-color:white;
    overflow: hidden;
}
.web-cov .title{
    top: 1px;
    font-size: 120px;
    position: relative;
    color: white;
}
.web-cov .bg{
    object-fit: cover;
    position:fixed;
    height: 100%;
    width: 100%;
}
.web-cov .html{
    height: 100px;
    position: absolute;
    right: 9px;
    top: 19px;
}
.web-cov.logo {
    position:absolute;
    top: 30px;
    height: 100px;
    width: 200px;
 
}

.abt{
    text-align: center;
    margin-top: 360px;
}
.btn{
    border: 1px solid #3498db;
    background: none;
    color: white;
    padding: 10px 20px ;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 10px;
    top: 50px;
    left: 800px;
}
.btn:hover {
    color: #fff; 
    background-color: #3498db; 
    transition: background-color 0.3s ease; 
}
.dev{
    text-align: center;
    margin-top: 360px;
}
.dev
.dev{
    border: 1px solid #3498db;
    background: none;
    color: white;
    padding: 10px 20px;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 12px;
    top: 50px;
    left: 1000px;
    text-align: center;
    box-sizing: border-box; 
}
.dev:hover {
    color: #fff;
    background-color: #3498db;
    transition: background-color 0.3s ease; 
}
.home
{
    border: 1px solid #3498db;
    background: none;
    color: white;
    padding: 10px 28px;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 12px;
    top: 50px;
    left: 600px;
    text-align: center;
    box-sizing: border-box; 
}
.home:hover{
    color: #fff;
    background-color: #3498db;
    transition: background-color 0.3s ease; 
}
.ser
{
    width: 100%;
    min-height: 100vh;
    padding: 10px 28px;
    background-position: center;
    background-size: cover;
    position: absolute;
    display: flex;
    left: 1600px;
    top: 20px; 
}
.searchbar
{
    width: 100%;
    max-width: 700px;
    background-color: rgba(225,225,225,0.2) ;
    display: flex;
    position:absolute;
    border-radius: 60px;
    padding: 10px 20px;

}
.searchbar input{
    background:transparent;
    flex: 1;
    border: 0;
    outline: none;
    padding: 24px 20px;
    font-size: 30px;
    color: #cac7ff;
}
::placeholder
{
    color: #cac7ff;
}
.searchbar button img{
    width: 25px;
}
.searchbar button {
    border: 0;
    border-radius: 50%;
    width: 60px;
    height: 60px;
    top: 19px;
    right: 22px;
    position:absolute;
    background:#58629b ;
    cursor: pointer;
}
.log {
    position:absolute;
    border: 1px solid  #3498db;
    color: white;
    background: none;
    margin: 12px;
    font-size: 20px;
    box-sizing: border-box;
    padding: 10px 20px;
    cursor: pointer;
    left: 1240px;
    top: 50px;
}
.log:hover{
    color: #fff;
    background-color: #3498db;
    transition: background-color 0.3s ease; 
}
.rectangle1{
    width: 460px;
    height: 600px;
    background-color:#9195F6;
    position: absolute;
    color: black;
    top: 320px;
    left: 320px;
    opacity: 0.7;
    border-radius: 60px;
    overflow-wrap: break-word;
    font-size: 30px;
    font-weight: bold;
}
.rectangle1:hover
{
    color: #fff;
    background-color:#6962AD;
    transform: scale(1.3);
    transition: background-color 0.2s ease, transform 0.2s ease;
    opacity: 0.9;
}
.pyimg{
    position:absolute;
    height: 120px;
    width: 120px;
    left: 5px;
    top: 5px;
}
.rm1{
    border: 1px solid #3498db;
    background: #3498db;
    color: white;
    padding: 10px 20px ;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 10px;
    top: 500px;
    left: 249px;
}
.rectangle2{
    width: 460px;
    height: 600px;
    background-color:#9195F6;
    position: absolute;
    color: black;
    top: 320px;
    left: 920px;
    opacity: 0.7;
    object-fit:cover;
    border-radius: 60px;
    overflow-wrap: break-word;
    font-size: 30px;
    font-weight: bold;
}
.rectangle2:hover {
        color: #fff;
        background-color:#6962AD;
        transform: scale(1.3);
        transition: background-color 0.2s ease, transform 0.2s ease;
        opacity: 0.9;
}
.rm2{
    border: 1px solid #3498db;
    background: #3498db;
    color: white;
    padding: 10px 20px ;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 10px;
    top: 500px;
    left: 249px;
}
.cssimg
{
    position:absolute;
    height: 120px;
    width: 120px;
    left: 0px;
    top: 5px;
    z-index: 1;
}
.rectangle3{
    width: 460px;
    height: 600px;
    background-color:#9195F6;
    position: absolute;
    color: black;
    top: 320px;
    left: 1520px;
    opacity: 0.7;
    object-fit:cover;
    border-radius: 60px;
    overflow-wrap: break-word;
    font-size: 30px;
    font-weight: bold;
}
.rectangle3:hover {
    color: #fff;
    background-color:#6962AD;
    transform: scale(1.3);
    transition: background-color 0.2s ease, transform 0.2s ease;
    opacity: 0.9;
}
.htmlimg{
    position:absolute;
    height: 110px;
    width: 110px;
    left: 0px;
    top: 20px;
    z-index: 1;
}
.rm3{
    border: 1px solid #3498db;
    background: #3498db;
    color: white;
    padding: 10px 20px ;
    position: absolute;
    font-size: 20px;
    cursor: pointer;
    margin: 10px;
    top: 500px;
    left: 249px;
}


   </style>
</head>
    <body>
        <div class="web-cov">
        <section id="home">
        <div class="webpg"></div>
        <img src="background.png" alt="bg" class="bg">
        <a href="#home"><img src="logo.png" alt="logo" class="logo"></a>
            <div class="abt">
               <a href="about.html"> <button class="btn btn1">ABOUT US</button></a>
            </div>
            <div class="dev">
                <a href="dev.html"><button class="dev">OUR DEVS</button></a>
            </div>
            <div class="ser">
                <form action="" class="searchbar">
                    <input type="text" placeholder="search anything" name="q">
                    <button type="submit"><img src="search.png" alt="ser"></button>
                </form>
            </div>
            <div class="login">
                <a href="login.html"><button class="log">LOGIN</button></a>
            </div>

            <div class="rectangle1">
               <a href="readmpy.html"><button class="rm1">READ MORE</button></a> 
                <img src="python.png" alt="py" class="pyimg">
                <br><br><br>
                <p align="center">Are you ready to embark on an exciting journey into the world of programming with Python? Whether you're a complete beginner or an experienced coder looking to expand your skills, our Python course is designed to empower you with the knowledge and confidence to thrive in today's digital landscape</p>
            </div>
            <div class="rectangle2">
                <button class="rm2">READ MORE</button>
                <img src="csslogo.png" alt="css" class="cssimg">
                <br><br><br><br>
                <p align="center">Are you ready to unleash your creativity and bring your web design skills to the next level? Our CSS course is your gateway to mastering the art of styling and layout on the web.</p>
            </div>
            <div class="rectangle3">
                <button class="rm3">READ MORE</button>
                <img src="html.png" alt="html" class="htmlimg">
                <br><br><br>
                <p align="center">Ready to embark on your journey into the heart of web development? Welcome to our HTML course, your gateway to crafting the digital world! Discover the language that forms the backbone of every webpage – Hypertext Markup Language (HTML). </p>
            </div>

    </section>
    <nav>
        <a href="#home"><button class="home" >HOME</button></div>
    </nav>
    </body>
</html>
```
## LOGIN.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login</title>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-image: url('sea.jpg') ;
    background-size: cover;
}
.wrap{
    width: 350px;
    height: 390px;
    background:transparent;
    color: #fff;
    border-radius: 10px;
    padding: 14px 17px;
    opacity: 0.9;
    
}
.wrap h1{
    color: white;
    font-size: 32px;
    text-align: center;
    margin-bottom: 40px;
}
.wrap .inputbox{
    position: relative;
    width: 300px;
    height: 50px;
    background:#77c7d7;
    margin: 3px 0;
    margin-bottom: 20px;
    align-items: center;
    justify-content: center;
    left: 14px;
    border-radius: 20px;
}
.inputbox input{
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid rgba(225,225,225,.2);
    border-radius:40px;
    opacity: 0.4;
}
.inputbox input::placeholder{
    color:#fff;
    position:absolute;
    left: 20px;
    
}
.inputbox i{
    position: absolute;
    right: 20px;
    top:20px;
    transform: translateY(-20%);
}
.wrap .remember-forgot{
    display: flex;
    justify-content: space-between;
    margin: 2px 0;
}
.remember-forgot label input{
    accent-color: #fff;
    
}
.remember-forgot a:hover
{
    text-decoration: underline;
    
}
.wrap .btn{
    width: 100%;
    height: 35px;
    border-radius: 60px;
    border: none;
    margin-bottom: 30px;
    cursor: pointer;
}
.wrap .btn:hover{
    transform: scale(1.1);
}
.wrap .register-link{
    display: flex;
    text-align: center;
    position:absolute;
    left: 545px;
    margin: 4px 2px;


}
    </style>
</head>
<body>
    <div class="wrap">
        <form action="">
        <h1>Login</h1>
        <div class="inputbox">
        <input type="text" placeholder="Username" required>
        <i class='bx bx-user'></i>
        </div>
        <br>
        <div class="inputbox">
        <input type="password" placeholder="Password" required>
        <i class='bx bx-key'></i>
        </div>
        <div class="remember-forgot">
            <label>
                <input type="checkbox">Remember me
            </label>
            <a href="#">Forgot password?</a>
            <br><br>
        </div>
        <button type="submit" class="btn">Login</button>
        <div class="register-link">
            <P>Don't have an account?</P><a href="#">Register</a>
        </div>
        <div class="rect"></div>
    </form>
    </div>
   
</body>
</html>
```
## ABOUT.HTML
```
<html>
    <head>
        <title>About us</title>
        <link rel="stylesheet" href="about.css">
    </head>
    <body>
            <div class="para1">
           <div class="wel">
            
            <p>
                Welcome to our website! We are Total Solutions, a leading provider of courses dedicated to industries. Our journey began in 2012 with a vision to Education. Over the years, we have grown into a trusted brand known for our commitment to excellence and customer satisfaction.</p>
        </div>
    </div>
        <div class="rect"></div>
        <div class="head">
            <h1>About Us</h1>
        </div>
        <div class="we">
            <div class="weinfo">
            <p>
                We are a team of passionate individuals driven by innovation and a desire to make a difference. From our skilled developers to our dedicated customer support team, every member of our staff plays a crucial role in ensuring that we deliver top-notch products/services and an exceptional experience to our customers.</p>
            </div>
        </div>
       
            <a href="home.html"><button class="home">HOME</button></a>
    
    </body>
</html>
```
## DEV.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Devs</title>

    <style>
        * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

h1 {
    font-size: 32px;
}

main {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.developer {
    margin: 20px;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: #fff;
    text-align: center;
}

.developer img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
}

.developer h2 {
    font-size: 24px;
    margin-bottom: 5px;
}

.developer p {
    font-size: 18px;
    color: #888;
}
.developer:hover{
    transform: scale(1.2);
    cursor: pointer;
}

    </style>
</head>
<body>
    <header>
        <h1>Meet Our Devs</h1>
    </header>
    <main>
        <div class="developer">
            <img src="sundar.jpg" alt="Developer 1">
            <h2>Sundar</h2>
            <p>Lead Developer</p>
        </div>
        <div class="developer">
            <img src="jeff.jpeg" alt="Developer 2">
            <h2>Jeff</h2>
            <p>Frontend Developer</p>
        </div>
        <div class="developer">
            <img src="mypic.png" alt="">
            <h2>Vignesh</h2>
            <p>CEO</p>
        </div>
        <div class="developer">
            <img src="tim.jpg" alt="">
            <h2>Tim</h2>
            <p>Backend developer</p>
        </div>
    </main>
</body>
</html>

```
## OUTPUT:
![image](https://github.com/Vigneshv-23/softweb/assets/110780412/86454c7c-455d-4c50-bc90-67334f9945b6)
![image](https://github.com/Vigneshv-23/softweb/assets/110780412/9b2d8766-9249-4683-8f9b-d327712177ea)
![image](https://github.com/Vigneshv-23/softweb/assets/110780412/2df0b727-e687-4be1-82e9-6fd688c2e223)
![image](https://github.com/Vigneshv-23/softweb/assets/110780412/e0fc231b-9803-479a-9afe-4eb004516c5d)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
