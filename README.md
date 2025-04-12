<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Birthday Akku</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@400;600&display=swap');

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffe0e9, #ffc2d1);
      color: #3e003e;
      text-align: center;
      overflow-x: hidden;
    }

    /* Countdown */
    #countdown-container {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background-color: #ffe0e9;
      color: #3e003e;
      font-family: 'Poppins', sans-serif;
      font-size: 1.5rem;
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      z-index: 9999;
    }

    #countdown {
      font-size: 2rem;
      font-weight: bold;
      margin-top: 1rem;
    }

    header {
      padding: 2rem;
      background-color: #ffaad4;
      color: white;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    h1 {
      margin: 0;
      font-size: 3rem;
      font-family: 'Great Vibes', cursive;
    }

    p.tagline {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: 0 auto;
    }

    /* Perfect Heart */
    .heart-container {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 2rem;
    }

    .heart {
      width: 100px;
      height: 90px;
      position: relative;
      background: red;
      transform: rotate(-45deg);
      animation: pulse 1.5s infinite;
    }

    .heart:before,
    .heart:after {
      content: "";
      position: absolute;
      width: 100px;
      height: 90px;
      background: red;
      border-radius: 50%;
    }

    .heart:before {
      top: -50px;
      left: 0;
    }

    .heart:after {
      left: 50px;
      top: 0;
    }

    @keyframes pulse {
      0% { transform: rotate(-45deg) scale(1); }
      50% { transform: rotate(-45deg) scale(1.1); }
      100% { transform: rotate(-45deg) scale(1); }
    }

    .timeline {
      background-color: #fff0f7;
      border-radius: 20px;
      padding: 2rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .timeline h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .milestone {
      margin-bottom: 1rem;
      text-align: left;
      padding-left: 1rem;
      border-left: 4px solid #ff80ab;
    }

    .milestone strong {
      color: #c2185b;
    }

    .final-message {
      background: #fff0f5;
      padding: 2rem;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(0,0,0,0.05);
      margin-bottom: 4rem;
    }

    .final-message h2 {
      font-size: 2rem;
      color: #880e4f;
    }

    .final-message p {
      font-size: 1.1rem;
      margin-bottom: 1rem;
      line-height: 1.8;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>

  <!-- Countdown Lock -->
  <div id="countdown-container">
    <p>This website will be unlocked in:</p>
    <div id="countdown"></div>
  </div>

  <div id="main-content" style="display: none;">
    <!-- Background Music -->
    <audio autoplay loop>
      <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mp3">
    </audio>

    <!-- First Romantic + Funny Page -->
    <header>
      <h1>Happy 19th Birthday, Akku!</h1>
      <p class="tagline">The one who stole my heart... and my fries.</p>
    </header>

    <div class="heart-container">
      <div class="heart"></div>
    </div>

    <section>
      <p>
        I knew you were special the moment I saw you... but I didn’t know you’d make me laugh, blush, and fall in love all at the same time.
      </p>
      <p>
        You’re like a romantic comedy — full of twists, cute moments, and a love story that keeps getting better. I still can't believe I get to be your Chottu.
      </p>
      <p>
        You're the peanut butter to my jelly, the ketchup to my fries, and the "aww" to all my cheesy lines.
      </p>
    </section>

    <!-- Second Page: Visual Timeline -->
    <section class="timeline">
      <h2>Our Love Timeline</h2>
      <div class="milestone"><strong>21/03/2023:</strong> The day I first told you that I love you. It was straight from the heart and changed everything for us.</div>
      <div class="milestone"><strong>22/03/2023:</strong> At 10:36 PM, we became a couple. The happiest moment, starting our beautiful journey of love.</div>
      <div class="milestone"><strong>05/08/2023:</strong> My first visit to your home to buy cake. I felt so special to be a part of your world.</div>
      <div class="milestone"><strong>28/08/2023:</strong> You sent me a kiss through Snapchat. Even virtually, it made my heart race.</div>
      <div class="milestone"><strong>11/11/2023:</strong> You kissed me on the lips for the first time. I was completely lost in the moment.</div>
      <div class="milestone"><strong>15/11/2023:</strong> I took you to your mother's house. Every moment with you felt meaningful.</div>
      <div class="milestone"><strong>01/12/2023:</strong> You rested on my chest during our bus ride home. I felt complete peace and love.</div>
      <div class="milestone"><strong>17/12/2023:</strong> A perfect day with rain, wind, and you. You slept on my shoulder in the bus—heavenly feeling.</div>
      <div class="milestone"><strong>22/12/2023:</strong> Our first Christmas carol after becoming a couple. It hurt to say goodbye for the holidays.</div>
      <div class="milestone"><strong>06/01/2024:</strong> A surprise extra class turned out to be a blessing. I spent the day with Akku and even slept on her thighs.</div>
      <div class="milestone"><strong>19/01/2024:</strong> When I was feeling down, Akku came to me, pulled my cheek, and gave a sweet kiss. Instantly healed my soul.</div>
    </section>

    <!-- Final Page: Birthday Wish and Love Message -->
    <section class="final-message">
      <h2>Birthday Wish</h2>
      <p>
        Today the world celebrates the day you were born, but my heart celebrates you every single day.
        You’re not just a part of my life, you are my life — my happiness, my peace, and my everything.
      </p>
      <p>
        I thank the stars for the day you came into this world and eventually into mine. On your special day,
        I wish you all the love, laughter, and joy you’ve given me — multiplied a thousand times.
      </p>
      <p>
        Happiest Birthday ever, Akku. You are my forever.
      </p>

      <h2>Romantic Love Message</h2>
      <p>
        I loved you yesterday when I first felt that spark.<br/>
        I love you today with all the moments we've shared.<br/>
        And I will love you tomorrow, and every tomorrow after that,<br/>
        because you're not just a chapter in my story — you're my whole book.
      </p>
      <p>
        No matter what changes, one thing remains true: You are the one I will always choose.
      </p>
    </section>
  </div>

  <script>
  const targetDate = new Date("2025-04-17T00:00:00+05:30").getTime();
  const countdownEl = document.getElementById("countdown");
  const countdownContainer = document.getElementById("countdown-container");
  const mainContent = document.getElementById("main-content");

  const updateCountdown = () => {
    const now = new Date().getTime();
    const distance = targetDate - now;

    if (distance <= 0) {
      countdownContainer.style.display = "none";
      mainContent.style.display = "block";
      clearInterval(timerInterval);
    } else {
      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      // Correcting template literal usage with backticks
      countdownEl.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }
  };

  const timerInterval = setInterval(updateCountdown, 1000);
  updateCountdown();
</script>
</body>
</html>
