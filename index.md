---
title: "Remind Lamia"
member:
  - 권경현
  - 김예린
  - 김예빈
---

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
      padding-bottom: 200px;
    }

    .header-text {
      text-align: center;
      color: white;
      margin-top: 20px;
    }

    .intro-container {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 30px;
      margin: 40px auto;
      max-width: 1000px;
      flex-wrap: wrap;
      color: white;
    }

    .intro-italic {
      font-style: italic;
      font-size: 16px;
      opacity: 0.9;
      text-align: center;
    }

    .intro-text {
      max-width: 600px;
      line-height: 1.7;
      font-size: 15px;
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
      font-size: 2em;
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
      margin-bottom: 2rem;
      text-align: center;
    }

    .stage-card img {
      width: 100%;
      max-width: 700px;
      height: auto;
      display: block;
      margin: 0 auto;
      border-radius: 8px;
    }

    .stage-description {
      color: rgba(100, 100, 100, 0.7);
      font-size: 0.9rem;
      margin-top: 0.5rem;
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
      width: 240px;
      flex-shrink: 0;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
      margin-bottom: 20px;
    }

    .character-card img {
      width: 100%;
      height: 260px;
      object-fit: contain;
      background-color: transparent;
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
      margin-top: 40px;
      min-height: 60px;
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
      text-align: left;
      max-width: 800px;
      margin: 0 auto;
    }

    .team-section h2 {
      font-size: 1.8em;
      margin-bottom: 20px;
    }

    .team-member {
      margin-bottom: 20px;
      font-size: 0.95em;
      color: #ccc;
    }

    .team-member strong {
      font-size: 1.2em; /* 이름 폰트 크기 키움 */
      color: #ccc; /* 강조 효과 */
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
    <img src="./asset/main.png" alt="Game Title">
    <div class="header-text">
      <h1>리마인드 라미아</h1>
    </div>
    <div class="intro-container">
      <div class="intro-italic"><strong>“게임 속 주인공과 함께, 현실과 가상을 구하는 모험이 시작된다.”</strong></div>
      <div class="intro-text">
        고전 게임인 <strong>라미아 어드벤쳐</strong>의 리메이크작 <strong>라미아 어드벤쳐 3D</strong>가 현대에서 큰 인기를 끌던 중,<br>
        게임을 플레이한 사람들이 차례로 실종되는 기묘한 사건이 벌어집니다.<br>
        고전 게임을 좋아하던 <strong>유</strong>는, 라미아 어드벤쳐의 용사이자 주인공인 <strong>리리트</strong>와 함께<br>
        현실과 가상이 뒤엉킨 세계의 비밀을 파헤치고,<br> 
        위기에 빠진 세상을 구하기 위한 여정을 떠나게 됩니다.
      </div>
    </div>
  </header>

  <section class="section">
    <h2>About the Game</h2>

    <div class="video-row">
      <div class="video-container">
        <video src="asset/drawpuzzle_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        유는 리리트와 함께 퍼즐과 비밀들로 가득찬 세계를<br>돌아다니게 됩니다
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="asset/jumpmap_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        오염된 라미아 어드벤쳐 3D의 영향으로 인해 납치된 사람들의 행방을 조사합니다<br>
        납치된 사람들이 게임 속 NPC의 모습으로 변하기 전에 그들의 흔적을 찾아주세요 
      </div>
    </div>

    <div class="video-row">
      <div class="video-container">
        <video src="asset/pannelpuzzle_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        현실과 게임 속 세상이 뒤섞인 가상의 공간에서<br>
        퍼즐을 진행하며 나아가게 됩니다
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="asset/runandgun_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        리리트와 유를 방해하는 괴물을 조심하세요!<br>
        오염된 게임 속 세상의 영향이 커질수록 현실과 가상의 경계가 점점 무너집니다
      </div>
    </div>

    <div class="video-row">
      <div class="video-container">
        <video src="asset/bullethell_3.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        실종된 사람들의 행방을 쫓아 모든 일의 배후를 조사하세요.<br>
        최종보스 LIA를 무찔러 납치된 사람들을<br>리리트와 함께 구해야 합니다
      </div>
    </div>

    <div class="video-row even">
      <div class="video-container">
        <video src="asset/OP_1.mp4" autoplay muted loop playsinline preload="auto"></video>
      </div>
      <div class="video-description">
        게임 속 아름다운 애니메이션과 컷씬들을 즐겨주세요 
      </div>
    </div>

  </section>

  <section class="section stage-section">
    <h2>STAGE</h2>
    <p style="text-align: center; color: white; margin-bottom: 2rem;">
      리마인드 라미아는 유의 방부터 라미아 어드벤쳐 3D 게임 속 세상까지 7개의 스테이지들로 구성되어있습니다.<br>
      현실과 가상을 넘나드는 맵들을 체험해보세요
    </p>
    
    <div class="stage-card">
      <img src="asset/stage_0.png" alt="Stage 0">
      <p class="stage-description">Stage 1 유의 방</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_1.png" alt="Stage 1">
      <p class="stage-description">Stage 2 도시</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_2.png" alt="Stage 2">
      <p class="stage-description">Stage 3 가상의 도시</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_3.png" alt="Stage 3">
      <p class="stage-description">Stage 4 학교</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_4.png" alt="Stage 4">
      <p class="stage-description">Stage 5 가상의 학교</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_5.png" alt="Stage 5">
      <p class="stage-description">Stage 6 라미아 어드벤쳐 3D</p>
    </div>
    <div class="stage-card">
      <img src="asset/stage_6.png" alt="Stage 6">
      <p class="stage-description">Stage 7 LIA</p>
    </div>
  </section>

  <section class="section" id="characters">
    <h2>Characters</h2>
    <div class="carousel-container">
      <div class="character-carousel" id="characterCarousel">
        <div class="character-card"><img src="asset/U_1.png" alt="Character 1"><h3>유</h3><p>유는 게임 속 캐릭터 리리트와<br> 함께 모험을 떠나는<br>리마인드 라미아의 주인공입니다</p></div>
        <div class="character-card"><img src="asset/lilit.png" alt="Character 2"><h3>리리트</h3><p>고전 게임 라미아 어드벤쳐의<br>주인공인 리리트는 유가 있는<br>세상이 위험에 처한걸 느끼고<br>현실로 나와 유와 함께<br>모험을 하게됩니다</p></div>
        <div class="character-card"><img src="asset/LIA.png" alt="Character 3"><h3>LIA</h3><p>라미아 어드벤쳐 3D를<br>관리하는 AI였습니다.<br>어느 순간 LIA가 게임의 통제권을 갖게되고,<br>플레이한 사람들이 납치되는<br>이상한 현상이 일어나게 됩니다</p></div>
        <div class="character-card"><img src="asset/BusMan.png" alt="Character 4"><h3>버스정류장의 아저씨</h3><p>이 NPC는 언뜻 보기에<br>평범해 보이지만...<br>관리형 AI의 도입으로 인해<br>게임회사에서 정리해고를 당한<br>슬픈 사연을 갖고 있습니다</p></div>
        <div class="character-card"><img src="asset/Pikmin.png" alt="Character 5"><h3>미니 라미안</h3><p>원래는 라미아 어드벤쳐 3D 속<br>캐릭터 중 하나였지만,<br>실종된 사람들이 점점<br>미니 라미안들의 모습으로<br>변해가고 있습니다</p></div>
        <div class="character-card"><img src="asset/Monster.png" alt="Character 6"><h3>도서관의 괴물</h3><p>오염된 라미아 어드벤쳐 3D의<br>영향으로 학교 도서관에서 생겨난<br>끔찍한 존재입니다.<br>리리트와 유가 사람들을 구하는데<br>방해하게 됩니다</p></div>
      </div>
      <div class="carousel-buttons">
        <button onclick="moveCarousel(-1)">&larr;</button>
        <button onclick="moveCarousel(1)">&rarr;</button>
      </div>
    </div>
  </section>

  <section class="team-section">
    <h2>Team Polaris</h2>
    <div class="team-member"><strong>김예린</strong> - 팀장, 3D/2D 디자인 기획 및 제작, 언리얼 컷씬 기획 및 총 제작, 캐릭터 디자인 ,애니메이팅 ,부스 기획<br>아트 작업 노션: https://www.notion.so/Remind-Lamia-1f79b79b4d3f80c59ff8fa18143d0068?pvs=4</div>
    <div class="team-member"><strong>김예빈</strong> - 시나리오, 스크립트, 게임 컨셉, 맵 구조, 퍼즐/시스템 기획, 사운드, 연출, 컷씬, 트레일러 및 일부 영상 에셋 제작</div>
    <div class="team-member"><strong>권경현</strong> - 게임 클라이언트 개발(유니티)</div>
  </section>

  <footer>
    &copy; 2025 Team Polaris. All rights reserved.
  </footer>

  <script>
    let currentIndex = 0;
    const carousel = document.getElementById('characterCarousel');
    const cardWidth = 230; // 320px card + 30px gap

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






