<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Merry x-mas MF'S</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Quicksand', sans-serif;
      background: linear-gradient(135deg, #ffe6f2, #e6f7ff); /* Soft pastel gradient */
      color: #5a4a6b;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      overflow: hidden;
    }

    /* Cute snowfall */
    .snow {
      position: absolute;
      top: -10px;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: -1;
    }
    .snowflake {
      position: absolute;
      background: white;
      border-radius: 50%;
      animation: fall linear infinite;
    }
    @keyframes fall {
      to { transform: translateY(100vh); opacity: 0; }
    }

    .container {
      background: linear-gradient(145deg, #fff5f7, #f0f8ff);
      padding: 30px;
      border-radius: 50px; /* Heart-like shape */
      box-shadow: 0 10px 30px rgba(255, 182, 193, 0.3);
      width: 90%;
      max-width: 450px;
      text-align: center;
      position: relative;
      border: 2px solid #ffb6c1;
      animation: heartbeat 2s infinite; /* Cute pulse */
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.02); }
    }

    h1 {
      font-size: 2em;
      color: #ff69b4;
      margin-bottom: 20px;
      text-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .question p {
      font-size: 1.2em;
      margin-bottom: 20px;
      color: #8a2be2;
    }

    button {
      padding: 12px 25px;
      font-size: 16px;
      background: linear-gradient(45deg, #ff69b4, #ffb6c1);
      color: white;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      margin: 5px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 8px rgba(255, 105, 180, 0.3);
      font-weight: 700;
    }

    button:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 12px rgba(255, 105, 180, 0.5);
    }

    #question-container {
      margin-top: 20px;
    }

    #result {
      margin-top: 20px;
      font-size: 1.5em;
      font-weight: bold;
      color: #ff1493;
      animation: sparkle 2s infinite;
    }

    @keyframes sparkle {
      0%, 100% { text-shadow: 0 0 5px #ffd700; }
      50% { text-shadow: 0 0 20px #ffd700, 0 0 30px #ff69b4; }
    }

    .hidden { display: none; }
    .win-gif { max-width: 100%; border-radius: 15px; margin-top: 10px; }
  </style>
</head>
<body>
  <div class="snow">
    <!-- Cute snowflakes -->
  </div>
  <div class="container">
    <h1>Merry x-mas MF'S 💖🎄</h1>
    <div class="question">
      <p>Ready ka na bang mabigyan ng pamasko?</p>
      <button onclick="askQuestion('start')">LET'S GOOOO</button>
    </div>
    <div id="question-container" class="question-container hidden">
      <!-- Questions appear here -->
    </div>
    <div id="result" class="hidden"></div>
  </div>
  
  <script>
    let step = 'start';
    const questionContainer = document.getElementById("question-container");
    const result = document.getElementById("result");
    const startDiv = document.querySelector(".question");

    // Add cute snowfall
    function createSnowflakes() {
      const snowContainer = document.querySelector('.snow');
      for (let i = 0; i < 50; i++) {
        const snowflake = document.createElement('div');
        snowflake.className = 'snowflake';
        snowflake.style.left = Math.random() * 100 + '%';
        snowflake.style.animationDuration = Math.random() * 3 + 2 + 's';
        snowflake.style.width = snowflake.style.height = Math.random() * 5 + 2 + 'px';
        snowContainer.appendChild(snowflake);
      }
    }
    createSnowflakes();

    function askQuestion(currentStep) {
      startDiv.classList.add('hidden');
      questionContainer.classList.remove('hidden');
      result.classList.add('hidden');

      if (currentStep === 'start') {
        questionContainer.innerHTML = `
          <p>Inaanak ba kita?</p>
          <button onclick="askQuestion('proofYes')">yes po Ninong</button>
          <button onclick="askQuestion('proofNo')">jahaha hindi</button>
        `;
        return;
      }

      if (currentStep === 'proofYes') {
        questionContainer.innerHTML = `
          <p>Alam mo ba na ang Pasko ay birthday daw ni Jesus?</p>
          <button onclick="askQuestion('birthdayYes')">amen, yes po opo</button>
          <button onclick="askQuestion('birthdayNo')">ayaw</button>
        `;
        return;
      }

      if (currentStep === 'proofNo') {
        questionContainer.innerHTML = `
          <p>Ikaw ba si Jesus?</p>
          <button onclick="askQuestion('jesusYes')">Oo Anak</button>
          <button onclick="askQuestion('jesusNo')">kinginamerls Anak</button>
        `;
        return;
      }

      if (currentStep === 'birthdayYes') {
        questionContainer.innerHTML = `
          <p>Love mo ba ako?)</p>
          <button onclick="askQuestion('anakYes')">hihi, yes po</button>
          <button onclick="askQuestion('anakNo')">lul, bigte na</button>
        `;
        return;
      }

      if (currentStep === 'birthdayNo') {
        endGame("Next year na pamasko");
        return;
      }

      if (currentStep === 'jesusYes') {
        questionContainer.innerHTML = `
          <p>Birthday ni Jesus kaya dapat s'ya yung bigyan ng gift?</p>
          <button onclick="askQuestion('giftYes')">Opo, amen</button>
          <button onclick="askQuestion('giftNo')">uluuullll</button>
        `;
        return;
      }

      if (currentStep === 'jesusNo') {
        endGame("jahaha next year na pamasko");
        return;
      }

      if (currentStep === 'anakYes') {
        endGame("Bawi na lang next year :>");
        return;
      }

      if (currentStep === 'anakNo') {
        // Secret win path for fun
        if (Math.random() > 0.7) {
          questionContainer.innerHTML = `
            <p>uyy gagi, welcome! You unlocked the secret fcking Santa mode. 🎉</p>
            <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmt0bWE5bmVnOW91YzMwcm1ibGFwdm9vYnB1MjBoN3d3b3pxYWp4YiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/S6O2GuDzHJCoVD7NFm/giphy.gif">
            <p>You get a virtual hug and a meme gift! 🤗</p>
          `;
          result.innerHTML = "<button onclick='resetGame()'>let's go back to the days our love was strong</button>";
          result.classList.remove('hidden');
          return;
        }
        endGame("jahaha next year na nga sabi ang pamasko");
        return;
      }

      if (currentStep === 'giftYes') {
        endGame("xorri, next year na lang");
        return;
      }

      if (currentStep === 'giftNo') {
        endGame("hmm, see u next year");
        return;
      }
    }

    function endGame(message) {
      questionContainer.innerHTML = `<p>${message}</p>`;
      result.innerHTML = "<button onclick='resetGame()'>Wanna try again? (jahaha miss ko na s'ya)</button>";
      result.classList.remove('hidden');
    }

    function resetGame() {
      step = 'start';
      startDiv.classList.remove('hidden');
      questionContainer.classList.add('hidden');
      result.classList.add('hidden');
      questionContainer.innerHTML = '';
      result.innerHTML = '';
    }
  </script>
</body>
</html>
