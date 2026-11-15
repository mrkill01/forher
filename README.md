<html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>for madam ganda ♡</title>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Alex+Brush&family=DM+Sans:wght@400;500&family=Playfair+Display:ital,wght@0,500;1,500&display=swap');

    * {
      box-sizing: border-box;
    }

    html {
      background: #f8dce5;
    }

    body {
      margin: 0;
      padding: 0;
      background: #f8dce5;
      font-family: 'DM Sans', sans-serif;
    }

    .page {
      --unit: min(100vw, 736px);
      position: relative;
      width: min(100%, 736px);
      min-height: 100vh;
      margin: 0 auto;
      padding: 25px 35px 35px;
      overflow: hidden;
      isolation: isolate;
      background:
        radial-gradient(ellipse at 15% 35%, #fff1f5 0%, transparent 35%),
        radial-gradient(ellipse at 90% 75%, #f5b8cb 0%, transparent 35%),
        repeating-linear-gradient(
          45deg,
          rgba(255,255,255,.12) 0px,
          rgba(255,255,255,.12) 2px,
          transparent 2px,
          transparent 12px
        ),
        linear-gradient(145deg, #f8c8d8, #fce7ed 48%, #f4bfd0);
      border: 9px solid #fff0f4;
      box-shadow: 0 0 25px rgba(135, 66, 91, .15);
    }

    /* decorative background */

    .page::before {
      content: "";
      position: absolute;
      inset: 12px;
      z-index: -1;
      border: 2px dashed rgba(194, 100, 133, .35);
      border-radius: 18px;
      pointer-events: none;
    }

    .page::after {
      content: "♡";
      position: absolute;
      right: 25px;
      top: 255px;
      color: rgba(190, 91, 130, .35);
      font-size: 75px;
      transform: rotate(15deg);
      z-index: -1;
    }

    /* header */

    .top-section {
      position: relative;
      display: flex;
      align-items: center;
      min-height: 245px;
      gap: 20px;
      margin-bottom: 22px;
    }

    .photo-frame {
      flex: 0 0 32%;
      aspect-ratio: 1;
      padding: 7px;
      border-radius: 50%;
      background: #fff7f8;
      border: 3px solid #d98aa7;
      box-shadow: 0 7px 18px rgba(130, 62, 88, .2);
      transform: rotate(-4deg);
    }

    .photo-frame img {
      display: block;
      width: 100%;
      height: 100%;
      border-radius: 50%;
      object-fit: cover;
      object-position: center;
      border: 2px solid #f1c2d1;
    }

    .heading {
      flex: 1;
      text-align: center;
      padding: 10px 0;
    }

    .small-heart {
      color: #c86d91;
      font-size: 22px;
      letter-spacing: 8px;
    }

    .heading h1,
    .heading h2 {
      margin: 0;
      color: #bd6688;
      font-family: 'Alex Brush', cursive;
      font-weight: 400;
    }

    .heading h1 {
      font-size: clamp(32px, 7.2vw, 53px);
      line-height: 1.15;
    }

    .heading h2 {
      font-size: clamp(27px, 6vw, 44px);
      line-height: 1.1;
    }

    .underline {
      width: 75%;
      height: 4px;
      margin: 12px auto 0;
      border-radius: 50%;
      background: #d987a5;
      transform: rotate(-2deg);
    }

    /* letter panels */

    .letter {
      position: relative;
      z-index: 2;
      padding: 25px 30px;
      margin-bottom: 25px;
      background:
        radial-gradient(ellipse at top left, rgba(255,255,255,.8), transparent 65%),
        #fff6e9;
      border: 2px solid #fff;
      border-radius: 18px 12px 22px 14px;
      outline: 2px dashed rgba(208, 126, 151, .55);
      outline-offset: -10px;
      box-shadow: 0 7px 15px rgba(124, 68, 84, .13);
    }

    .letter p {
      margin: 0;
      color: #422c35;
      font-family: 'DM Sans', sans-serif;
      font-size: 14px;
      line-height: 1.55;
      font-weight: 400;
      text-align: left;
      overflow-wrap: break-word;
    }

    .first,
    .second {
      min-height: unset;
    }

    /* decorations */

    .decor {
      position: absolute;
      z-index: 1;
      color: #c66f91;
      pointer-events: none;
    }

    .decor-one {
      top: 280px;
      left: 15px;
      font-size: 48px;
      transform: rotate(-15deg);
    }

    .decor-two {
      top: 730px;
      right: 15px;
      font-size: 55px;
      opacity: .65;
    }

    .decor-three {
      bottom: 65px;
      left: 15px;
      font-size: 55px;
      transform: rotate(15deg);
    }

    .decor-four {
      top: 220px;
      right: 90px;
      font-size: 28px;
    }

    .sticker {
      position: absolute;
      z-index: 3;
      color: #c66f91;
      pointer-events: none;
    }

    .sticker-one {
      top: 215px;
      right: 20px;
      font-size: 48px;
      transform: rotate(15deg);
    }

    .sticker-two {
      bottom: 35px;
      right: 25px;
      font-size: 45px;
    }

    /* closing message */

    .closing-message {
      position: relative;
      z-index: 2;
      text-align: center;
      color: #bd6688;
      font-family: 'Alex Brush', cursive;
      font-size: clamp(30px, 7vw, 42px);
      line-height: 1.35;
      padding: 10px 0 15px;
      margin-top: 5px;
    }

    /* mobile adjustments */

    @media (max-width: 500px) {
      .page {
        min-height: 100vh;
        padding: 15px 17px 25px;
        border-width: 5px;
      }

      .top-section {
        min-height: 180px;
        gap: 10px;
        margin-bottom: 15px;
      }

      .photo-frame {
        flex-basis: 34%;
        padding: 4px;
      }

      .heading h1 {
        font-size: clamp(25px, 7vw, 35px);
      }

      .heading h2 {
        font-size: clamp(22px, 6vw, 31px);
      }

      .small-heart {
        font-size: 16px;
        letter-spacing: 4px;
      }

      .letter {
        padding: 25px 21px;
        margin-bottom: 20px;
        border-radius: 14px;
      }

      .letter p {
        font-size: clamp(12px, 2.8vw, 13px);
        line-height: 1.55;
      }

      .first,
      .second {
        min-height: unset;
      }

      .sticker-one {
        top: 160px;
        font-size: 32px;
      }

      .closing-message {
        font-size: clamp(29px, 7vw, 36px);
        padding-bottom: 10px;
      }
    }
  </style>
</head>

<body>

<main class="page">

  <div class="decor decor-one">♡</div>
  <div class="decor decor-two">✿</div>
  <div class="decor decor-three">♡</div>
  <div class="decor decor-four">✧</div>

  <div class="top-section">
    <div class="photo-frame">
      <img
        src="https://i.ibb.co/pBzWZp4f/Picsart-26-11-15-23-26-37-199.jpg"
        alt="our photo"
      >
    </div>

    <div class="heading">
      <span class="small-heart">♡ ✧ ♡</span>
      <h1>hi, madam ganda.</h1>
      <h2>it’s your tomboy here.</h2>
      <div class="underline"></div>
    </div>
  </div>

  <div class="sticker sticker-one">🎀</div>
  <div class="sticker sticker-two">♡</div>

  <section class="letter first">
    <p>uhm, first, I just want to say thank you for being in my life. you’re the greatest gift I could ever ask for. I appreciate you so much, and your existence means a lot to me. words are not enough to express how grateful I am to have you on this journey, to have you in my life. you brought happiness into my life in a way no one else could. lei, all I can say is thank you for everything. I truly appreciate all the things you do for me, and they literally melt my heart. thank you for always putting in the effort, for always playing with me even though we always lose the game. and especially, thank you for choosing me over something that is really important to you. I promise to do my best to give you the same love you give me. I will reciprocate your efforts and give you genuine love because that's what you deserve. you deserve to be treated like a diamond, something to be cherished and kept forever. you deserve to be valued forever. I will love you through your perfections and imperfections. I will love all your flaws, your insecurities, and everything that makes you question your worth. so please, don't hesitate to lean on me when everything feels so cruel. you can always run to me whenever you feel like the world is against you. yap to me, disturb me, rant to me. I will listen to everything without hesitation, and I promise to welcome you with open arms.</p>
  </section>

  <section class="letter second">
    <p>I know we're too young for this, but one thing I'm sure of is how I feel about you. I want to build my teenage life with you in it, if you'll let me. I know a lot of people say teenage love doesn't last forever, but I hope ours does. and because we're still young, I just want you to know that I'm not rushing things between us. let's take things one at a time, step by step. prioritize your dreams without feeling rushed. there's no rush at all. I want us to help each other become the best versions of ourselves, the versions we could only dream of becoming. I hope we achieve the life we've always dreamed of, and I hope that when that time comes, we'll still be by each other's side. lei, I know this might be earlier than you expected, but I wanted to ask if I could court you. I'm courting you not just because I love you. love is important, yes, but what I feel for you goes beyond that. and I want you to know that I'm doing this without expecting anything in return. you are a risk I'm willing to take, without any regrets. there's something about you that makes me want to dive in, even though I don't know how deep it is or whether I'll drown in the end. I'd rather face the uncertainty than live forever with the regret of never trying. I'd rather risk falling than spend my days wondering what could have been. and whatever the outcome may be, it's a risk I'll always be willing to take. others may admire you for your appearance, but my feelings for you go far beyond what the eyes can see. I love you for who you are.</p>
  </section>

  <div class="closing-message">
    mahal ba mahal kita, eliza.<br>
    higit pa sa sobra :)
  </div>

</main>

<audio id="bgMusic" loop preload="auto">
  <source src="https://audio.jukehost.co.uk/01a1e07a-c59d-7242-84cd-cf5de77d0542" type="audio/mpeg">
</audio>

<script>
  const music = document.getElementById("bgMusic");

  music.volume = 0.5;

  function startMusic() {
    if (music.paused) {
      music.play().then(() => {
        document.removeEventListener("click", startMusic);
        document.removeEventListener("touchstart", startMusic);
        document.removeEventListener("keydown", startMusic);
      }).catch(error => {
        console.log("Music playback failed:", error);
      });
    }
  }

  window.addEventListener("load", () => {
    startMusic();
  });

  document.addEventListener("click", startMusic);
  document.addEventListener("touchstart", startMusic);
  document.addEventListener("keydown", startMusic);
</script>

</body>
</html>
