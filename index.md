---
title: "Remind Lamia"
member:
  - 권경현
  - 김예린
  - 김예빈
---

<!-- <div class="columns is-centered has-text-centered">
  <div class="column is-four-fifths">
    <h3 class="title is-1">Remind Lamia</h3>
    <div class="content has-text-left" style="margin-top: 1.5em;">
      <p>
        주인공 <strong>'유'</strong>는 어릴 적부터 좋아했던 게임 속 캐릭터 <strong>'리리트'</strong>와 만나<br>
        가상과 현실이 뒤섞인 세계를 모험하며, 위기에 빠진 세상을 구하는<br>
        3D 어드벤처 게임입니다.
      </p>
    </div>
  </div>
</div>

<div class="buttons" style="text-align: center; margin-top: 2em;">
  <img src="./asset/main.png">
</div>

<div style="height: 3em;"></div>

### Game Play
<div class="buttons" style="text-align: center; margin-top: 1em;">
  <img src="./asset/img9.png">
  <img src="./asset/img4.png">
</div>
<div style="text-align: center; margin-top: 2em;">
  <p>다양한 스테이지를 돌아다니며 퍼즐을 풀고, 캐릭터와 상호작용을 하며 스토리를 진행할 수 있습니다</p>
</div>

<div style="height: 3em;"></div>

### Concept art
<div class="buttons" style="text-align: center; margin-top: 2em;">
  <img src="./asset/img5.png">
  <img src="./asset/img6.png">
</div>
<div class="columns is-centered" style="margin-top: 3em;">
  <div class="column is-half">
    <h4 class="title is-4">🎮 유</h4>
    <p>
      어렸을 때부터 <strong>고전 라미아 어드벤처</strong>를 좋아하던 대학생.<br>
      현실 세계에 나타난 리리트를 처음엔 당황스럽게 여기지만,<br>
      함께 위기에 빠진 세상을 구하기 위해 모험을 떠납니다.
    </p>
    <p><strong>성격:</strong> 호기심이 많고 정의감 넘침</p>
    <p><strong>특징:</strong> 리메이크된 라미아 어드벤처는 아직 해보지 않음</p>
  </div>

  <div class="column is-half">
    <h4 class="title is-4">🗡️ 리리트</h4>
    <p><strong>라미아 어드벤처</strong> 속 바빌렌 왕국을 지키는 용사.<br>
      오랫동안 유의 플레이를 지켜보며 유대감을 쌓아왔습니다.<br>
      리메이크된 게임으로 인한 위기를 느끼고, 현실 세계로 나와<br>
      유와 모두를 지키기 위한 여정에 나섭니다.
    </p>
    <p><strong>성격:</strong> 강인하고 책임감 있지만 내면은 따뜻함</p>
    <p><strong>특징:</strong> 마법의 검으로 오염된 것을 정화하는 마법 사용 가능</p>
  </div>
</div>

<div style="height: 6em;"></div>

<hr style="width: 60%; margin: 0 auto 2em auto; border: 1px solid #000;">

<div class="buttons" style="text-align: center;">
  <img src="./asset/img7.png">
  <img src="./asset/img10.png">
</div>

<div style="text-align: center; margin-top: 2em;">
  <p>게임 속 몰입감을 더하는 애니메이션 컷씬과 아름다운 맵들을 만나보세요</p>
</div>

<!-- Team Polaris 구간 앞에 마진 추가 -->
<!-- <div style="margin-top: 10em; text-align: right;">
  <h3 class="title is-3"><strong>Team Polaris</strong></h3>
  Leader & Art 김예린<br>  
  Game Design & script 김예빈<br>
  Programmer 권경현  
</div> --> 

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Game Website</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
    }

    header {
      height: 100vh;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
    }

    header img {
      max-width: 90%;
      height: auto;
    }

    .section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .section h2 {
      font-size: 2.5em;
      margin-bottom: 20px;
    }

    .video-row {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;
      margin-bottom: 60px;
      align-items: center;
    }

    .video-row.even {
      flex-direction: row-reverse;
    }

    .video-container {
      flex: 1 1 45%;
    }

    .video-container video {
      width: 100%;
      border-radius: 10px;
    }

    .video-description {
      flex: 1 1 45%;
      font-size: 1.1em;
      line-height: 1.6em;
    }

    .stage-section {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .stage-card {
      margin-bottom: 40px;
      text-align: center;
    }

    .stage-card img {
      width: 80%;
      max-width: 600px;
      border-radius: 10px;
    }

    .stage-card p {
      margin-top: 10px;
      font-size: 1.1em;
    }

    .carousel-container {
      position: relative;
      overflow: hidden;
    }

    .character-carousel {
      display: flex;
      transition: transform 0.5s ease;
      gap: 30px;
    }

    .character-card {
      background-color: #222;
      padding: 20px;
      border-radius: 16px;
      width: 250px;
      flex-shrink: 0;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    .character-card img {
      width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .character-card h3 {
      margin: 15px 0 10px;
      font-size: 1.1em;
    }

    .character-card p {
      font-size: 0.9em;
      color: #ccc;
    }

    .carousel-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    .carousel-buttons button {
      background-color: #333;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 1em;
      border-radius: 8px;
      cursor: pointer;
    }

    .carousel-buttons button:hover {
      background-color: #555;
    }

    .team-section {
      padding: 40px 20px;
      background-color: #111;
      text-align: center;
    }

    .team-member {
      margin-bottom: 20px;
      font-size: 0.95em;
      color: #aaa;
    }

    footer {
      background-color: #111;
      padding: 30px;
      text-align: center;
      color: #666;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <img src="assets/main.png" alt="Game Title">
  </header>

  <section class="section">
    <h2>About the Game</h2>

    <!-- 영상 태그 확인용 preload 추가 -->
    <div class="video-row">
      <div class="video-container">
        <video src="assets/drawpuzzle_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        리리트와 함께 오염된 게임 세계를 다시 되돌려주세요 [그림퍼즐]
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="assets/jumpmap_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        오염된 라미아 어드벤쳐 3D 게임의 영향으로 인해 납치된 사람들의 행방을 찾아야합니다 [점프맵]
      </div>
    </div>

    <div class="video-row">
      <div class="video-container">
        <video src="assets/pannelpuzzle_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        현실과 게임 속 세상이 뒤섞인 가상의 공간에서 퍼즐을 진행하며 나아가게 됩니다 [패널보드]
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="assets/runandgun_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        리리트와 유를 방해하는 괴물을 조심하세요! 오염된 게임 속 세상의 영향이 커질수록 현실과 가상의 경계가 점점 무너집니다
      </div>
    </div>

    <div class="video-row">
      <div class="video-container">
        <video src="assets/bullethell_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        실종된 사람들의 행방을 좇아 모든 일의 배후를 조사하세요. 최종보스 LIA를 무찔러 납치된 사람들을 리리트와 함께 구해야 합니다
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="OP_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        게임 속 아름다운 애니메이션과 컷씬을 확인하세요
      </div>
    </div>
  </section>

  <section class="section stage-section">
    <h2>Stages</h2>
    <div class="stage-card"><img src="assets/stage1.jpg" alt="Stage 1"><p>스테이지 1 설명</p></div>
    <div class="stage-card"><img src="assets/stage2.jpg" alt="Stage 2"><p>스테이지 2 설명</p></div>
    <div class="stage-card"><img src="assets/stage3.jpg" alt="Stage 3"><p>스테이지 3 설명</p></div>
    <div class="stage-card"><img src="assets/stage4.jpg" alt="Stage 4"><p>스테이지 4 설명</p></div>
    <div class="stage-card"><img src="assets/stage5.jpg" alt="Stage 5"><p>스테이지 5 설명</p></div>
    <div class="stage-card"><img src="assets/stage6.jpg" alt="Stage 6"><p>스테이지 6 설명</p></div>
    <div class="stage-card"><img src="assets/stage7.jpg" alt="Stage 7"><p>스테이지 7 설명</p></div>
  </section>

  <section class="section" id="characters">
    <h2>Characters</h2>
    <div class="carousel-container">
      <div class="character-carousel" id="characterCarousel">
        <div class="character-card"><img src="assets/U.png" alt="Character 1"><h3>Character Name 1</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
        <div class="character-card"><img src="assets/lilit.png" alt="Character 2"><h3>Character Name 2</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
        <div class="character-card"><img src="assets/LIA.png" alt="Character 3"><h3>Character Name 3</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
        <div class="character-card"><img src="assets/BusMan.png" alt="Character 4"><h3>Character Name 4</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
        <div class="character-card"><img src="assets/Pikmin.png" alt="Character 5"><h3>Character Name 5</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
        <div class="character-card"><img src="assets/Monster.png" alt="Character 6"><h3>Character Name 6</h3><p>설명 1줄~3줄 정도의 캐릭터 소개.</p></div>
      </div>
      <div class="carousel-buttons">
        <button onclick="moveCarousel(-1)">&larr;</button>
        <button onclick="moveCarousel(1)">&rarr;</button>
      </div>
    </div>
  </section>

  <section class="team-section">
    <h2>Team Members</h2>
    <div class="team-member"><strong>ddd</strong> - 게임 기획 및 시스템 디자인 담당</div>
    <div class="team-member"><strong>sss</strong> - 캐릭터 아트 및 애니메이션 담당</div>
    <div class="team-member"><strong>aaa</strong> - 프로그래밍 및 구현 담당</div>
  </section>

  <footer>
    &copy; 2025 Your Game Studio. All rights reserved.
  </footer>

  <script>
    let currentIndex = 0;
    const carousel = document.getElementById('characterCarousel');
    const cardWidth = 280; // card width + margin

    function moveCarousel(direction) {
      const maxIndex = carousel.children.length - 1;
      currentIndex += direction;
      if (currentIndex < 0) currentIndex = 0;
      if (currentIndex > maxIndex - 2) currentIndex = maxIndex - 2;
      carousel.style.transform = `translateX(${-currentIndex * cardWidth}px)`;
    }
  </script>
</body>
</html>





