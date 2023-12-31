<!-- Header Section -->
<h1 align="center">Hi there! 👋 I'm Awadhesh Gupta</h1>
<h3 align="center">Passionate Full-Stack Developer from Nepal</h3>

<!-- Coding Image -->
<p align="center">
  <img src="https://camo.githubusercontent.com/9790442a186cf9984a391793e2586ba6c8840cb5a698e26a425d670880f617c5/68747470733a2f2f7777772e77696e677374656368736f6c7574696f6e732e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032322f30332f66756c6c2d737461636b2d646576656c6f706d656e742e676966" alt="Coding" width="800" heignt="auto" />
</p>

<!-- Trophies and Profile Views -->
<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=agupta800" alt="agupta800" />
  </a>
</p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=agupta800" alt="Profile Views" />
</p>

<!-- Skills and Learning Section -->
- 🌱 Currently learning **ASP.NET CORE MVC**
- 💬 Ask me about **React, C#, ASP.NET CORE MVC, ADO.NET, LINQ Query, SQL, PHP, LARAVEL, JAVA**
- 📫 Reach me at **awadheshg577@gmail.com**

<!-- Social Media Links -->
<h3 align="center">Connect with Me:</h3>
<p align="center">
  <a href="https://www.linkedin.com/in/awadhesh-gupta-b229ba21a/" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>
  <a href="https://fb.com/awadhesh.gupta.754918" target="blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="30" width="40" />
  </a>
</p>

<!-- Languages and Tools Section -->
<h3 align="center">Languages and Tools:</h3>
<p align="center">
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular" width="40" height="40"/>
  <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="40" height="40"/>
  <!-- Add more icons for your languages and tools here -->
</p>

<!-- GitHub Streak Stats -->
<p align="center">
  <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=agupta800" alt="GitHub Streak Stats" />
</p>

<!-- Additional Coding Image or Closing Note -->
<p align="center">

  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
         
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            /* background-image:url("BG3.jpg"); */
            background-position: center;
            background-size: cover;
            animation: slide-in-top 0.3s both;
            
        }
        @import url('https://fonts.googleapis.com/css?family=Montserrat:700|Pacifico');

*, *:after, *:before{
  box-sizing:border-box;
  margin:0;
  padding:0;
  -webkit-transition: all 100ms ease-in;
  transition: all 100ms ease-in;
  
}

.feliz{
  width: 100%;
  font-family: cursive;
  font-size: 80px;
  font-weight: 700;
  color: red ;
  text-align: center;
  position: absolute;
  top: 50%;
  opacity: 0;
  animation: vem_feliz 2s ease-in-out 7s forwards;
  
}
.ano_novo{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  padding: 200px 100px 0px 0px;
 

}
.ano_novo>span{
  font-family: 'Montserrat', 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 175px;
  font-weight: 700;
  color: #7a8fe8;
  -webkit-box-reflect: below 10px linear-gradient(to bottom, rgba(0,0,0,0.0), rgba(0,0,0,0.4));

}
span.seis{
  position: absolute;
  top: 50%;
  right: 50%;
  margin-right: -200px;
  animation: vai_2016 5s ease-in-out 5s forwards;
}
span.sete{
  position: absolute;
  right: 0%;
  margin-right: -200px;
  animation: vem_2017 6s ease-in-out forwards;
}
span.sete:before{
  content: '';
  width: 0px;
  height: 6px;
  display: block;
  border-radius: 3px;
  background: #7a8fe8;
  transform: rotate(0deg);
  transform-origin: left top;
  position: absolute;
  top: 55px;
  left: 10px;
  z-index: -1;
  animation: entrega_balao 1s ease-in-out 4s;
}
.balao{
  width: 100px;
  height: 100px;
  display: block;
  background: #e8d57a;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  margin-top: -165px;
  right: 0%;
  margin-right: -200px;
  animation: vem_e_vai_balao 10s ease-in-out forwards;
}
.balao:before{
  content: '';
  width: 0;
  height: 0;
  border-style: solid;
  border-width: 0 10px 20px 10px;
  border-color: transparent transparent #b19b32 transparent;
  position: absolute;
  left: 50%;
  margin-left: -10px;
  bottom: -10px;
  z-index: -1;
}
.balao:after{
  content: '';
  width: 4px;
  height: 100px;
  display: block;
  background: #fff;
  border-radius: 0px 0px 3px 3px;
  position: absolute;
  left: 50%;
  margin-left: -2px;
  bottom: -110px;
}
.fogos{
  width: 90%;
  height: 112%;
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  overflow: hidden;
}
.fogos>div{
  border: 2px solid #fff;
  position: absolute;
  opacity: 0;
  animation: solta_fogos 1.5s ease-in-out 8s forwards;
}
.fogos>div.f1{
  left: 37%;
  top: 40%;
}
.fogos>div.f2{
  left: 27%;
  top: 54%;
}
.fogos>div.f3{
  right: 27%;
  top: 40%;
}
.fogos>div.f4{
  right: 17%;
  top: 54%;
}
.fogos>div span{
  width: 6px;
  height: 6px;
  display: inside;
  position: absolute;
  top: 0;
  left: 0;
  opacity: 0;
  animation: estoura_fogos 0.5s ease-in-out 9s forwards;
}
.fogos>div span:nth-child(1){
  transform: rotate(0deg);
}
.fogos>div span:nth-child(2){
  transform: rotate(120deg);
}
.fogos>div span:nth-child(3){
  transform: rotate(240deg);
}
.fogos>div span:before{
  content: '';
  width: 2px;
  height: 50px;
  display: block;
  background: #f5cc06;
  position: absolute;
  top: -60px;
  left: 2px;
}
.fogos>div span:after{
  content: '';
  width: 2px;
  height: 50px;
  display: block;
  background: #f5cc06;
  position: absolute;
  bottom: -60px;
  left: 2px;
}
.fogos>div span i:before{
  content: '';
  width: 3px;
  height: 3px;
  display: block;
  border-radius: 50%;
  background: #fff;
  position: absolute;
  top: -15px;
  left: 10px;
}
.fogos>div span i:after{
  content: '';
  width: 3px;
  height: 3px;
  display: block;
  border-radius: 50%;
  background: #fff;
  position: absolute;
  top: -10px;
  right: 10px;
}
a.author{
  font-size: 12px;
  text-decoration: dotted;
  color: #f47c7c;
  position: static ;
  bottom: 10px;
  right: 10px;
}

@keyframes vem_2017 {
  0% {
    right: 0%;
  }
  66.6666% {
    right: 50%;
    margin-right: -300px;
  }
  90% {
    right: 50%;
    margin-right: -300px;
  }
  100% {
    right: 50%;
  }
}
@keyframes vem_e_vai_balao {
  0% {
    right: 0%;
  }
  40% {
    right: 50%;
    margin-right: -300px;
  }
  50% {
    right: 50%;
    margin-right: -200px;
    top: 50%;
  }
  100% {
    top: -100%;
    right: 50%;
  }
}
@keyframes entrega_balao {
  0% {
    transform: rotate(-30deg);
    width: 40px;
  }
  100% {
    transform: rotate(-150deg);
    width: 70px;
  }
}
@keyframes vai_2016 {
  0% {
    top: 50%;
  }
  100% {
    top: -100%;
  }
}
@keyframes vem_feliz {
  0% {
    margin-top: 0px;
    opacity: 0;
  }
  100% {
    margin-top: -200px;;
    opacity: 1;
  }
}
@keyframes solta_fogos {
  0% {
    margin-top: 100%;
    opacity: 0;
    width: 2px;
    height: 30px;
    display: block;
    border-radius: 50%;
  }
  75% {
    margin-top: 0%;
    opacity: 1;
    width: 2px;
    height: 30px;
    display: block;
    border-radius: 50%;
  }
  80%{
    margin-top: 0px;
    margin-left: 0px;
    opacity: 1;
    width: 10px;
    height: 10px;
    display: block;
    border-radius: 50%;
    transform: scale(0.2);
  }
  100%{
    opacity: 1;
    width: 10px;
    height: 10px;
    display: block;
    border-radius: 50%;
    transform: scale(1);
  }
}
@keyframes estoura_fogos {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

    </style>
</head>
<body>
    <div class="feliz">HAPPY NEW YEAR</div>
<div class="ano_novo">
  <span>202</span>
  <span class="seis">3</span>
  <span class="sete">4</span>
  <div class="balao"></div>
</div>
<div class="fogos">
  <div class="f1">
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
  </div>
  <div class="f2">
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
  </div>
  <div class="f3">
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
  </div>
  <div class="f4">
    <span><i></i></span>
    <span><i></i></span>
    <span><i></i></span>
  </div>
</div>
</body>
</html>
</p>
<p align="center">
  <em>Let's code something amazing together! 😊</em>
</p>
