<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pan Asia - Thai & Indo</title>
  <style>
    :root {
      --green:#1a3d3a;
      --accent:#ff9800;
      --ok:#26a69a;
    }
    *{box-sizing:border-box}
    body{
      margin:0; font-family:Arial, sans-serif; color:#fff;
      background: linear-gradient(rgba(0,0,0,.5), rgba(0,0,0,.5)), url('화면 캡처 2025-08-10 211338.png') center/cover no-repeat fixed;
    }
    header{
      background:var(--green); color:#fff; display:flex; align-items:center; justify-content:space-between; padding:10px 30px;
    }
    .logo{height:60px}
    nav a{color:#fff; margin-left:20px; text-decoration:none; font-weight:bold}
    .hero{ height:400px; display:flex; flex-direction:column; align-items:center; justify-content:center; text-align:center; text-shadow:1px 1px 5px rgba(0,0,0,.7); }
    .hero h1{margin:0; font-size:48px}
    .intro{ text-align:center; padding:40px 20px; font-size:1.15em; line-height:1.6; max-width:900px; margin:0 auto; }
    .order-btn{ display:block; margin:24px auto 40px; padding:18px 36px; background:var(--accent); color:#fff; border:none; font-size:1.25em; border-radius:8px; cursor:pointer }
    .order-btn:hover{ background:#e68a00 }
    footer{ background:var(--green); text-align:center; padding:16px 10px; }
    .hero{background:url('화면 캡처 2025-08-10 211338.png') center/cover no-repeat;}
    .intro-bg{background: linear-gradient(rgba(0,0,0,.55), rgba(0,0,0,.55)), url('화면 캡처 2025-08-10 211338.png') center/cover no-repeat;}
  </style>
</head>
<body>
  <header>
    <img src="logo.jpg" alt="Pan Asia Logo" class="logo">
    <h2>Pan Asia - Thai & Indo</h2>
    <nav>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to Pan Asia</h1>
    <p>Authentic Thai & Indonesian Flavors</p>
  </section>

  <section class="intro">
    We are a <b>food-focused</b> Thai & Indonesian kitchen (takeout & delivery). We craft bold, fresh flavors using quality ingredients and our house-made sauces. Enjoy Pad Thai, fragrant curries, and Indonesian favorites prepared fast and with care.
  </section>

  <!-- ✅ 수정된 부분: Uber Eats Webshop으로 이동 -->
  <form action="https://www.order.store/store/pan-asia-thai%26indo-bldg-3-20381-62-avenue/FioLAblDUoGzdeXSNftThw" method="get" style="text-align:center;">
    <button type="submit" class="order-btn">Order Now</button>
  </form>

  <footer id="contact">
    <p>Pan Asia - Thai & Indo | 200381 62 Ave Unit 301, Langley, BC, V3A 5E6, Canada</p>
  </footer>
</body>
