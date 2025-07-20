<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>11th Month 💖</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #fbe9f3;
      color: #333;
      text-align: center;
    }
    .container {
      display: none;
      padding: 30px 20px;
      max-width: 700px;
      margin: auto;
      animation: fadeIn 0.8s ease-in-out;
    }
    .active {
      display: block;
    }
    img {
      width: 200px;
      height: 200px
      object-fit: cover;
      border-radius: 50%;
      margin-bottom: 20px;
      box-shadow: 0 0 20px rgba(255, 105, 180, 0.5);
    }
    button {
      margin: 10px;
      padding: 12px 20px;
      font-size: 16px;
      background-color: #ff69b4;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    button:hover {
      background-color: #e754a5;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    h1, h2 {
      color: #d63384;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      margin: 10px 0;
      font-size: 18px;
    }
    .heart {
      font-size: 22px;
      line-height: 1.6;
      white-space: pre-wrap;
      text-align: left;
      background-color: #fff;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>

  <!-- PAGE 1: WISH -->
  <div id="page1" class="container active">
    <h1>Happy 11 Months My Princess 💗</h1>
    <img src="couple.jpg" alt="Our Pic">
    <p>Thank you for Being with me pakkii 🥹💖</p>
    <button onclick="showPage('page2')">11 Things I Love About You</button>
  </div>

  <!-- PAGE 2: 11 THINGS -->
  <div id="page2" class="container">
    <h2>11 Things I Love About You 😍</h2>
    <ul>
      <li>1. Your Eyes when You smiles</li>
      <li>2. You Chilled Nose</li>
      <li>3. Your Lovely Legs</li>
      <li>4. Your Slap when You are Angry</li>
      <li>5. You Calling me Kanna</li>
      <li>6. You confronting me when I'm low</li>
      <li>7. Your Hair when You just bathed</li>
      <li>8. Your fingers when You holds my hands</li>
      <li>9. Your Anger when I made a mistake</li>
      <li>10. You Coming back to me when I was angry at You</li>
      <li>11.  You. All of Yours.. Only You.. My Forever Princess 💗</li>
    </ul>
    <button onclick="showPage('page3')">Click Here to See My Heart</button>
  </div>

  <!-- PAGE 3: LOVE LETTER -->
  <div id="page3" class="container">
    <h2>This is My Heart 💌</h2>
    <div class="heart">
Pakkkkiii ye...  
      Enakku theriyila engenu thodangenu because words have never felt enough for what I want to say or feel about you...

It's Been 11 Months.. 11 Months of turning my ordinary life into something I have never thought I Deserved.. You've been my Calm when my mind was Storming.. My Strength when I had nothing.. Unakku theriyaathu pakkii but nee ennaya treat pannutha vitham, nee ennaya kanna nu vilichuthath, naan ethengi thappu pannumba enatta kova paduthath, Ellaam enayya oru Lucky aatt feel panna vachuthu..

Every tiny bit of you.. Your Smile, Antha kannu, Unakka Kaalu, Unakka voice, Ellaathayum vida enakka mela nee kaattutha softness ithellaam ipa enakka oru part aatt iruthu yeah it's all a part of me now.. When I hold your hand, I feel Safe.. Nee enatta adi vachund thirichu enatta varumba pakkii I feel like I Fucking Won Everything in this World.. I feel loved.. Unakka kooda irunthu thaan pakkii "Home" ulla word ka meaning naan manasilaakkunen..

You have seen my worst.. you've seen me Angry, Broken, Lazy, Selfish.. but ithellaathayum nee enakka kooda iruntha.. you never left me... You never gave up.. And That's why no matter what happens in this World pakkii enatha nadanthaalum.. I will Fight For you, I will Protect you and love you till my last breath.. I will make a Queen of My Fucking Empire..

Nee Enakku verum oru Lover mattum illa pakkii.. you're the part of me that I never knew I was missing.. Naan eppalum chelluven nee enakka paathi nu aana nee enakka paathi illa pakkii you are my Whole life, my heart and my everything.. 

I Love You Kannammaa 💗.. I Love you so much than these Words could ever carry... 😘💗
    </div>
  </div>

  <script>
    function showPage(pageId) {
      document.querySelectorAll('.container').forEach(page => {
        page.classList.remove('active');
      });
      document.getElementById(pageId).classList.add('active');
    }
  </script>
</body>
</html>
