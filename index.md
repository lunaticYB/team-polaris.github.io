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
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Characters Section</title>
  <style>
    body {
      margin: 0;
      background-color: #000;
      color: #fff;
      font-family: Arial, sans-serif;
    }

    .section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: 0 auto;
    }

    .section h2 {
      font-size: 2.5em;
      border-bottom: 1px solid #444;
      padding-bottom: 10px;
    }

    .carousel-wrapper {
      position: relative;
      margin-top: 40px;
    }

    .carousel-container {
      display: flex;
      gap: 20px;
      overflow-x: auto;
      scroll-behavior: smooth;
      scroll-snap-type: x mandatory;
      padding: 40px 20px;
    }

    .character-card {
      flex: 0 0 auto;
      width: 200px;
      background-color: #222;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      scroll-snap-align: center;
    }

    .character-image {
      height: 200px;
      background-color: #333;
      color: #aaa;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 5px;
      margin-bottom: 15px;
    }

    .carousel-button {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background-color: #000a;
      border: none;
      color: white;
      font-size: 2em;
      padding: 10px;
      cursor: pointer;
      z-index: 1;
    }

    .carousel-button.left {
      left: 0;
    }

    .carousel-button.right {
      right: 0;
    }
  </style>
</head>
<body>

  <section class="section">
    <h2>Characters</h2>
    <div class="carousel-wrapper">
      <button class="carousel-button left" onclick="scrollCharacters(-1)">&#9664;</button>
      <div class="carousel-container" id="carousel">
        <div class="character-card">
          <div class="character-image">[CHARACTER 1 IMAGE]</div>
          <h3>Character 1</h3>
          <p>Brief character description goes here.</p>
        </div>
        <div class="character-card">
          <div class="character-image">[CHARACTER 2 IMAGE]</div>
          <h3>Character 2</h3>
          <p>Brief character description goes here.</p>
        </div>
        <div class="character-card">
          <div class="character-image">[CHARACTER 3 IMAGE]</div>
          <h3>Character 3</h3>
          <p>Brief character description goes here.</p>
        </div>
        <!-- 추가 캐릭터 가능 -->
      </div>
      <button class="carousel-button right" onclick="scrollCharacters(1)">&#9654;</button>
    </div>
  </section>

  <script>
    const scrollAmount = 220; // 카드 폭 + 간격

    function scrollCharacters(direction) {
      const container = document.getElementById("carousel");
      container.scrollBy({ left: scrollAmount * direction, behavior: "smooth" });
    }

    // 첫 번째 카드가 중앙에 오도록 로딩 시 자동 스크롤
    window.addEventListener('load', () => {
      const container = document.getElementById('carousel');
      const firstCard = container.querySelector('.character-card');
      const containerCenter = container.offsetWidth / 2;
      const cardCenter = firstCard.offsetWidth / 2;
      const offset = firstCard.offsetLeft - (containerCenter - cardCenter);
      container.scrollTo({ left: offset, behavior: 'smooth' });
    });
  </script>

</body>
</html>




