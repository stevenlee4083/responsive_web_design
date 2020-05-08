<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <style>
  .container h1 { font-size: calc(112.5% + 0.5vw); }
  .container p { font-size: calc(100% + 0.5vw); }
  .container a { font-size: calc(100% + 0.5vw); }
body {
  margin-left: 10px;
  margin-top: 10px;
  padding: 0;
}
  .card {
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
    display: flex;
    transition: 0.3s;
  }

  .card:hover {
    box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }

  .container {
    padding: 2px;
    margin-left: auto;
  }
  .container>h1,p {
    font-size: calc (115% + 0.5vw)
  }
/*.card img {
  width: 5vw;
  height: 10vh;
  border-radius: 50%;
  }*/
  #pic #pot {
  max-width: 100%;
  height: auto;
  border-radius: 40%;
}
  </style>
  </head>
  <body>
  <div class="card">
    <div id="pic">
      <img id="pot" src="https://stevenlee4083.github.io/images/sosewon.jpeg" alt="selfca">
    </div>
    <div class="container">
      <h1>이 승 욱</h1>
      <h1>Steven Lee</h1>
      <p>프론트앤드개발자 웹퍼블리셔</p>
      <p>Frontend Developer</p>
      <a href="https://stevenlee4083.github.io/responsive_web_design/fcctrial527.html">포트폴리오확인하세요</a><br>
      <a href="https://stevenlee4083.github.io/responsive_web_design/fcctrial527.html">Visit my portfolio!</a>
      <p>풍부한 산업경력과 High-Level Language 지식으로 고객 Need를 빠르고 정확하게 구현합니다</p>
    </div>
  </div>
</body>
</html>
