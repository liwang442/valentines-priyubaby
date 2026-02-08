<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Our Love Story ❤️</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #ff6a88, #ff99ac);
      color: white;
      text-align: center;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 50px 20px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    h2 {
      font-weight: 300;
      margin-bottom: 30px;
    }

    .heart {
      font-size: 4rem;
      animation: beat 1.5s infinite;
    }

    @keyframes beat {
      0%,100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    .card {
      background: rgba(255,255,255,0.2);
      border-radius: 20px;
      padding: 25px;
      margin: 25px 0;
      backdrop-filter: blur(10px);
    }

    .timeline {
      text-align: left;
      margin-top: 20px;
    }

    .event {
      margin-bottom: 20px;
    }

    .event span {
      font-weight: bold;
      color: #fff6f8;
    }

    button {
      background: white;
      color: #ff4b6e;
      border: none;
      padding: 14px 30px;
      border-radius: 30px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 20px;
    }

    .hidden {
      display: none;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      opacity: 0.9;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="heart">❤️</div>

  <h1>Our Love Story</h1>
  <h2>me & youmybaby 💕</h2>

  <div class="card">
    <p>
      Every love story is special, but ours is my favorite.
      It’s filled with laughter, kisses, memories,
      and a love that keeps growing every day.
    </p>
  </div>

  <div class="card">
    <h3>Our Timeline ⏳</h3>
    <div class="timeline">
      <div class="event">
        <span>❤️ October 23, 2022</span><br>
        The day we became *us*.  
        The day my heart chose you, Priyu.
      </div>
      <div class="event">
        <span>💞 Every day after</span><br>
        More love, more memories, more reasons to smile.
      </div>
      <div class="event">
        <span>♾️ Forever</span><br>
        Still writing our story… together.
      </div>
    </div>
  </div>

  <button onclick="reveal()">One Last Thing 💌</button>

  <div id="final" class="card hidden">
    <p>
      Priyu, thank you for loving me, choosing me,
      and walking this journey with me.
    </p>
    <h3>I choose you — always ❤️</h3>
  </div>

  <footer>
    Made with love since October 23, 2022 💖
  </footer>
</div>

<script>
  function reveal() {
    document.getElementById("final").classList.remove("hidden");
  }
</script>

</body>
</html>
