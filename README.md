```
index.html

<html>
    <head>
        <title>My portfolio</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="main">
            <div class="navbar">
                <img src="A.png" class="logo">
                <ul type="none">
                    <li><a href="#">HOME</a></li>
                    <li><a href="#">ABOUT</a></li>
                    <li><a href="#">TOOLS</a></li>
                    <li><a href="#">MYWORK</a></li>
                    <li><a href="#">CONTACT</a></li>
                </ul>
            </div>
            <div class="info">
                <h3>Hi, I'm <span>Arini</span>.</h3>
                <h1><span>W</span>EB <span>D</span>ESIGNER</h1>
                <h4>Web designer and developer from Neyveli,India.
                    I create<br> websites to do business do better<br>
                    online.</h4>

                <button><a href="#">Hire me</a></button>
            </div>
            <div class="image">
                <img src="mine.jpg" class="mine">
            </div>
            <div class="about">
                <h1>About</h1>
                <h4>
                    <span>A web designer </span> on the aesthetics and layout of websites.<br>
                    They create visually appealing designs using tools like Adobe XD <br>
                    or Figma, ensuring a seamless user experience. Their role involves<br>
                    selecting color schemes, typography, and graphics, and often <br>
                    collaborating with developers to implement the design into<br>
                    functional web pages.<br>
                </h4>
            </div>
            <div class="tool">
                <h1>Tools</h1>
                <ol><b>
                    <li>Figma</li>
                    <li>Adobe XD</li>
                    <li>Adobe Photoshop</li>
                    <li>Adobe Illustrator</li>
                    <li>Canva</li></b>
                </ol>
            </div>
            <div class="Foot">
                <h1>Arini</h1>
                <h1>Arish</h1>
                <h1>Ananadhavalli</h1>
            </div>
        </div>
    </body>
</html>

style.css

*{
    margin:0;
    padding:0;
}
.main{
    width:100%;
    background: url(bg.png);
    background-position: center;
    height:100%auto;
    position :relative;
    font-family: sans-serif;

}
.navbar
{
    width:100%;
    display:flex;
    margin:auto;
    padding: 15px 0;
    align-items: center;
    justify-content:space-between;
    background-color: rgba(0, 0, 0, 0.637);

}
.navbar .logo
{
    width:160px;
    cursor: pointer;
    margin-top:-3%;
    margin-left:-2%;
}
ul{
    margin-top: -2%;
    
}
ul li{
    display: inline-block;
    padding:10px 16px;
}
ul li a
{
    font-size: 16px;
    font-family: bold;
    text-decoration:none;
    transition: .4s ease;
    color: aliceblue;
}
ul li a:hover{
    color:red;
}
.info
{  
    margin-left: 7%;   
}
.info h3{
    margin-top: 10%;
}
span{
    color:rgba(11, 34, 110, 0.562);
}
.info a{
    text-decoration: none;
    color:white;
    
}
button{
    margin-top: 3%;
    width:80px;
    height: 30px;
    background:black;
}
.info button:hover{
    background-color: blueviolet;
}
.image
{
    width:30%;
    height:60%;
    position:absolute;
    right:100px;
    bottom:0;

}
.image img
{
    margin-top: -40%;
    position:center;
    height:50%;
    left:40%;
    transform: translate(-55%);
    bottom:0;
    transition: left 2s ease;
}
.image:hover .mine
{
    left: 55%;
}
.about
{
    padding-top:80px;
    margin-left: 7%;
}
.about h4{
    padding-top: 20px;
    
}
.about span{
    color:rgba(11, 34, 110, 0.562);
}
.tool
{
    padding-top:80px;
    margin-left: 9%;
}
.tool h1{
    padding-bottom: 20px;
}

.foot h1
{
    background-color: black;
}

###OUTPUT:
![Screenshot (25)](https://github.com/Arini22009085/codsoft/assets/119643315/737ccfce-c990-4729-abc7-3d6b20259305)

![Screenshot (26)](https://github.com/Arini22009085/codsoft/assets/119643315/2d8b1583-b00c-48af-a1e8-201af214eb8f)
```
