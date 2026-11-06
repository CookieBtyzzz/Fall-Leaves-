<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fall Leaves!!! 🍂</title>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  background: #fff8ed;
  color: #553b2b;
  font-family: Georgia, serif;
}

header {
  background: #75452e;
  color: #fff5df;
  text-align: center;
  padding: 28px 15px;
}

header h1 {
  font-size: 42px;
  letter-spacing: 3px;
}

header p {
  margin-top: 8px;
  font-style: italic;
}

nav {
  background: #a85d36;
  padding: 15px;
  text-align: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 12px;
  font-size: 14px;
  font-weight: bold;
}

nav a:hover {
  color: #ffe2a8;
}

.hero {
  min-height: 430px;
  background:
    linear-gradient(rgba(55, 32, 17, .38), rgba(55, 32, 17, .45)),
    url("https://images.unsplash.com/photo-1507371341162-763b5e419408?auto=format&fit=crop&w=1600&q=85");
  background-size: cover;
  background-position: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  padding: 30px;
}

.hero h2 {
  font-size: 52px;
  text-shadow: 2px 3px 8px #402414;
}

.hero p {
  font-size: 19px;
  margin: 15px 0 25px;
}

.hero button {
  background: #f4c27a;
  color: #56351e;
  border: none;
  padding: 13px 25px;
  border-radius: 25px;
  font-weight: bold;
  cursor: pointer;
}

section {
  max-width: 1050px;
  margin: auto;
  padding: 55px 22px;
}

.section-title {
  text-align: center;
  color: #99552e;
  font-size: 32px;
  margin-bottom: 15px;
}

.intro {
  text-align: center;
  line-height: 1.8;
  max-width: 700px;
  margin: auto;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.card {
  background: #fff0d9;
  border: 1px solid #ead3b4;
  border-radius: 18px;
  padding: 25px;
  text-align: center;
  box-shadow: 0 5px 14px #8c60301a;
  transition: .2s;
}

.card:hover {
  transform: translateY(-5px);
}

.card .emoji {
  font-size: 42px;
  margin-bottom: 12px;
}

.card h3 {
  color: #99552e;
  margin-bottom: 10px;
}

.card p {
  line-height: 1.6;
}

.banner {
  background: #75452e;
  color: #fff5df;
  text-align: center;
  padding: 45px 20px;
}

.banner h2 {
  font-size: 30px;
  margin-bottom: 12px;
}

.checklist {
  max-width: 550px;
  margin: 25px auto 0;
  background: #fff0d9;
  padding: 25px;
  border-radius: 18px;
}

.checklist label {
  display: block;
  padding: 10px;
  cursor: pointer;
  font-size: 17px;
}

.checklist input {
  accent-color: #a85d36;
  margin-right: 10px;
}

#progress {
  text-align: center;
  margin-top: 15px;
  font-weight: bold;
  color: #99552e;
}

.quote {
  background: #f2dfc4;
  border-radius: 20px;
  padding: 35px;
  text-align: center;
  font-size: 22px;
  font-style: italic;
  line-height: 1.6;
}

footer {
  background: #75452e;
  color: #fff5df;
  text-align: center;
  padding: 25px;
  line-height: 1.8;
}

@media (max-width: 600px) {
  header h1 { font-size: 32px; }
  .hero h2 { font-size: 38px; }
  nav a { margin: 5px; display: inline-block; }
}
</style>
</head>

<body>

<header>
  <h1>🍂 FALL LEAVES!!! 🍂</h1>
  <p>a little corner of autumn magic ♡</p>
</header>

<nav>
  <a href="#home">HOME</a>
  <a href="#about">ABOUT</a>
  <a href="#favorites">FALL FAVES</a>
  <a href="#bucketlist">BUCKET LIST</a>
</nav>

<div class="hero" id="home">
  <h2>Hello, Autumn! 🍁</h2>
  <p>Golden leaves, cozy days & pumpkin everything.</p>
  <button onclick="document.getElementById('about').scrollIntoView()">
    Explore autumn ♡
  </button>
</div>

<section id="about">
  <h2 class="section-title">♡ WELCOME TO FALL ♡</h2>
  <p class="intro">
    Welcome to Fall Leaves!!! Your cozy little autumn corner.
    Imagine chilly mornings, warm blankets, beautiful orange trees,
    cinnamon smells and the prettiest sunsets.
    Let's make this season magical! 🍂
  </p>
</section>

<div class="banner">
  <h2>🍁 Sweater Weather Is Here 🍁</h2>
  <p>Life is better with a little autumn magic.</p>
</div>

<section id="favorites">
  <h2 class="section-title">MY FALL FAVORITES</h2>
  <p class="intro">All the little things that make autumn special ♡</p>

  <div class="cards">
    <div class="card">
      <div class="emoji">🎃</div>
      <h3>Pumpkin Season</h3>
      <p>Pumpkins, pumpkin decorations and cute autumn displays!</p>
    </div>

    <div class="card">
      <div class="emoji">☕</div>
      <h3>Cozy Drinks</h3>
      <p>Warm cocoa, cinnamon drinks and something sweet.</p>
    </div>

    <div class="card">
      <div class="emoji">🍂</div>
      <h3>Falling Leaves</h3>
      <p>Beautiful golden trees and crunchy leaves everywhere.</p>
    </div>

    <div class="card">
      <div class="emoji">🧸</div>
      <h3>Cozy Nights</h3>
      <p>Soft blankets, comfy pajamas and movie nights.</p>
    </div>

    <div class="card">
      <div class="emoji">🕯️</div>
      <h3>Autumn Scents</h3>
      <p>Cinnamon, vanilla, caramel and warm cozy smells.</p>
    </div>

    <div class="card">
      <div class="emoji">🌅</div>
      <h3>Pretty Sunsets</h3>
      <p>Golden skies and beautiful orange evening colors.</p>
    </div>
  </div>
</section>

<section id="bucketlist">
  <h2 class="section-title">MY AUTUMN BUCKET LIST</h2>
  <p class="intro">Check off your favorite fall activities! ♡</p>

  <div class="checklist">
    <label><input type="checkbox" onchange="updateProgress()"> Decorate pumpkins 🎃</label>
    <label><input type="checkbox" onchange="updateProgress()"> Watch a cozy fall movie 🎬</label>
    <label><input type="checkbox" onchange="updateProgress()"> Take pictures of fall leaves 📸</label>
    <label><input type="checkbox" onchange="updateProgress()"> Have a hot chocolate ☕</label>
    <label><input type="checkbox" onchange="updateProgress()"> Wear a cozy sweater 🧥</label>
    <label><input type="checkbox" onchange="updateProgress()"> Bake something yummy 🍪</label>
    <label><input type="checkbox" onchange="updateProgress()"> Go on a fall walk 🍁</label>

    <div id="progress">0 of 7 completed! 🍂</div>
  </div>
</section>

<section>
  <div class="quote">
    "And all at once, summer collapsed into fall." 🍂
    <p style="font-size:15px; margin-top:12px;">♡ a little autumn reminder ♡</p>
  </div>
</section>

<footer>
  <h2>🍂 FALL LEAVES!!! 🍂</h2>
  <p>Made with love & a little autumn magic.</p>
  <p>Thank you for visiting my cozy corner! ♡</p>
</footer>

<script>
function updateProgress() {
  const boxes = document.querySelectorAll('.checklist input');
  const checked = document.querySelectorAll('.checklist input:checked');
  document.getElementById('progress').textContent =
    checked.length + ' of ' + boxes.length + ' completed! 🍂';
}
</script>

</body>
</html>
