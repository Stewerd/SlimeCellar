<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Slime Cellar</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: linear-gradient(135deg, #f7d7ff, #d6f8ff, #e5ffd8);
  color: #28142f;
}

header {
  text-align: center;
  padding: 55px 20px 35px;
}

.logo {
  width: 140px;
  height: 140px;
  object-fit: contain;
  border-radius: 50%;
  background: white;
  padding: 10px;
  box-shadow: 0 10px 30px rgba(0,0,0,.15);
}

h1 {
  font-size: 48px;
  margin-top: 20px;
  color: #7b2cff;
}

.subtitle {
  font-size: 20px;
  margin-top: 10px;
  color: #4c3159;
}

.hero-buttons {
  margin-top: 25px;
}

.btn {
  display: inline-block;
  padding: 14px 24px;
  margin: 8px;
  border-radius: 999px;
  text-decoration: none;
  font-weight: bold;
  background: #7b2cff;
  color: white;
  box-shadow: 0 8px 18px rgba(123,44,255,.25);
}

.btn.secondary {
  background: white;
  color: #7b2cff;
}

section {
  max-width: 1150px;
  margin: auto;
  padding: 45px 20px;
}

.section-title {
  text-align: center;
  font-size: 34px;
  margin-bottom: 15px;
}

.section-text {
  text-align: center;
  max-width: 720px;
  margin: 0 auto 35px;
  color: #4d3d55;
  font-size: 17px;
}

.products {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 24px;
}

.card {
  background: rgba(255,255,255,.85);
  border-radius: 26px;
  padding: 22px;
  text-align: center;
  box-shadow: 0 12px 28px rgba(0,0,0,.12);
  transition: .2s;
}

.card:hover {
  transform: translateY(-6px);
}

.product-img {
  height: 180px;
  border-radius: 22px;
  background: linear-gradient(135deg, #ffd6f7, #c8fff4);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 54px;
  margin-bottom: 18px;
}

.card h3 {
  font-size: 23px;
  margin-bottom: 8px;
}

.price {
  font-size: 24px;
  font-weight: bold;
  color: #7b2cff;
  margin: 12px 0;
}

.badge {
  display: inline-block;
  background: #ffe66d;
  color: #4b3b00;
  padding: 6px 12px;
  border-radius: 999px;
  font-size: 13px;
  font-weight: bold;
  margin-bottom: 12px;
}

.locator {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 22px;
}

.location-card {
  background: white;
  border-radius: 24px;
  padding: 24px;
  box-shadow: 0 10px 25px rgba(0,0,0,.1);
}

.location-card h3 {
  color: #7b2cff;
  margin-bottom: 8px;
}

.location-card p {
  margin: 8px 0;
  line-height: 1.5;
}

.map-btn {
  display: inline-block;
  margin-top: 12px;
  background: #27c498;
  color: white;
  padding: 12px 18px;
  border-radius: 999px;
  text-decoration: none;
  font-weight: bold;
}

.mystery {
  background: linear-gradient(135deg, #7b2cff, #ff57c7);
  color: white;
  border-radius: 30px;
  padding: 38px 24px;
  text-align: center;
  box-shadow: 0 14px 35px rgba(123,44,255,.25);
}

.mystery h2 {
  font-size: 34px;
  margin-bottom: 12px;
}

.footer {
  text-align: center;
  padding: 35px 20px;
  background: rgba(255,255,255,.65);
  margin-top: 30px;
}

.footer a {
  color: #7b2cff;
  font-weight: bold;
  text-decoration: none;
}

@media(max-width:600px) {
  h1 {
    font-size: 38px;
  }

  .section-title {
    font-size: 28px;
  }
}
</style>
</head>

<body>

<header>
  <!-- Replace logo.png with your logo image link -->
  <img class="logo" src="logo.png" alt="Slime Cellar Logo" />
  <h1>Slime Cellar</h1>
  <p class="subtitle">Handmade scented slime with mystery charms inside.</p>

  <div class="hero-buttons">
    <a class="btn" href="#shop">Shop Slime</a>
    <a class="btn secondary" href="#locator">Find In Stores</a>
  </div>
</header>

<section class="mystery">
  <h2>Collect the Mystery Charms</h2>
  <p>Every slime container comes with 1 mystery charm inside. Try to collect them all!</p>
</section>

<section id="shop">
  <h2 class="section-title">Shop Our Slime</h2>
  <p class="section-text">
    Soft, stretchy, scented slime made in small batches. Pick your favorite flavor and see what mystery charm you get.
  </p>

  <div class="products">

    <div class="card">
      <div class="product-img">🍓</div>
      <span class="badge">Mystery Charm Included</span>
      <h3>Strawberry Slime</h3>
      <p>Sweet strawberry scented slime.</p>
      <div class="price">$7.99</div>
      <a class="btn" href="#">Buy Now</a>
    </div>

    <div class="card">
      <div class="product-img">🍇</div>
      <span class="badge">Mystery Charm Included</span>
      <h3>Jasmine Purple Slime</h3>
      <p>Soft purple slime with a jasmine scent.</p>
      <div class="price">$7.99</div>
      <a class="btn" href="#">Buy Now</a>
    </div>

    <div class="card">
      <div class="product-img">🍉</div>
      <span class="badge">Mystery Charm Included</span>
      <h3>Watermelon Slime</h3>
      <p>Fresh watermelon scented slime.</p>
      <div class="price">$7.99</div>
      <a class="btn" href="#">Buy Now</a>
    </div>

    <div class="card">
      <div class="product-img">✨</div>
      <span class="badge">Mystery Charm Included</span>
      <h3>Mystery Slime</h3>
      <p>Surprise scent, surprise charm, full mystery.</p>
      <div class="price">$7.99</div>
      <a class="btn" href="#">Buy Now</a>
    </div>

  </div>
</section>

<section id="locator">
  <h2 class="section-title">Store Locator</h2>
  <p class="section-text">
    Want to grab Slime Cellar in person? Find us at these locations.
  </p>

  <div class="locator">

    <div class="location-card">
      <h3>House of Wine and Spirits</h3>
      <p><strong>Location:</strong> San Marcos, CA</p>
      <p><strong>Available:</strong> Slime Cellar products</p>
      <a class="map-btn" href="https://www.google.com/maps/search/House+of+Wine+and+Spirits+San+Marcos+CA" target="_blank">Open Map</a>
    </div>

    <div class="location-card">
      <h3>Old Poway Market</h3>
      <p><strong>Location:</strong> Poway, CA</p>
      <p><strong>Available:</strong> Slime Cellar products</p>
      <a class="map-btn" href="https://www.google.com/maps/search/Old+Poway+Market+Poway+CA" target="_blank">Open Map</a>
    </div>

  </div>
</section>

<section>
  <h2 class="section-title">Wholesale / Store Requests</h2>
  <p class="section-text">
    Want Slime Cellar in your store? Contact us for wholesale pricing and local delivery options.
  </p>

  <div style="text-align:center;">
    <a class="btn" href="tel:6197154575">Call 619-715-4575</a>
    <a class="btn secondary" href="https://instagram.com/" target="_blank">Follow Us</a>
  </div>
</section>

<div class="footer">
  <p>© 2026 Slime Cellar. All rights reserved.</p>
  <p>Handmade slime. Not edible. Keep away from small children.</p>
</div>

</body>
</html>
