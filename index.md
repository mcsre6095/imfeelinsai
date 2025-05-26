---
title: Welcome to my blog
---
<meta charset="UTF-8">
<html>
<head>
  <style>
  body {
  margin: 0;
  height: 100vh;
  background-image: url("favicon.jpg");
  background-size: 500% 300%;
  animation: rainbow 4.77612s ease infinite;
  animation-delay: -2.2s;
}

@keyframes rainbow {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
.thi {
font-size: 114;
font-family: 'Arial', sans-serif;
color: #114514;
}

  </style>
  <link rel="icon" type="image/x-icon" href="\favicon.jpg">
  <title> 塞塞 </title>
</head>
<body>
  <audio id="lk" src="lk_1kbps.mp3" loop></audio>
  <audio id="114514" src="114514.mp3"></audio>
  <h1> 我塞了 </h1>
  <img src="jacklin.jpg" alt="rich">
  <p>塞塞的結果 很羨慕吧</p>
  <p>大家一起來塞塞</p>
  <button id="saima" onclick="document.getElementById('lk').play()">進入塞塞王國</button>
  <p>(開聲音)</p>
  <a href="#" onclick="document.getElementById('114514').play()" class="thi" return false;>點我塞塞</a>
  <script>
    document.getElementById("saima").addEventListener("click", function() {
      alert("一起來塞吧");
    });
  </script>
  
</body>
</html>
