<!<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Salsa Cake Shop</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      background:#fff7f8;
      color:#5c4b51;
    }

    header{
      background:linear-gradient(135deg,#ffd6e7,#ffeccf);
      padding:40px 20px;
      text-align:center;
      border-bottom-left-radius:40px;
      border-bottom-right-radius:40px;
      box-shadow:0 4px 10px rgba(0,0,0,0.08);
    }

    header h1{
      font-size:48px;
      color:#ff6fa1;
    }

    header p{
      margin-top:10px;
      font-size:18px;
      color:#7a5d66;
    }

    .menu{
      padding:50px 20px;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:30px;
      max-width:1200px;
      margin:auto;
    }

    .card{
      background:#fff;
      border-radius:25px;
      overflow:hidden;
      box-shadow:0 6px 15px rgba(0,0,0,0.08);
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-8px);
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card-content{
      padding:20px;
      text-align:center;
    }

    .card-content h2{
      color:#ff7aa2;
      margin-bottom:10px;
    }

    .price{
      font-size:22px;
      font-weight:bold;
      color:#7a5d66;
      margin-bottom:15px;
    }

    .btn{
      background:#ffc2d4;
      border:none;
      padding:12px 25px;
      border-radius:30px;
      cursor:pointer;
      font-size:16px;
      color:#5c4b51;
      transition:0.3s;
    }

    .btn:hover{
      background:#ff9fbe;
      color:white;
    }

    footer{
      text-align:center;
      padding:20px;
      background:#ffe6ef;
      margin-top:40px;
      color:#7a5d66;
      border-top-left-radius:30px;
      border-top-right-radius:30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Salsa Cake Shop</h1>
    <p>Sweet desserts with pastel vibes ✨</p>
  </header>

  <section class="menu">

    <div class="card">
      <img src="macaron.jpg" alt="Macarons">
      <div class="card-content">
        <h2>Super Yummy Macarons</h2>
        <div class="price">Rp40.000</div>
        <button class="btn">Buy Now</button>
      </div>
    </div>

    <div class="card">
      <img src="cookies.jpg" alt="Cookies Lotus">
      <div class="card-content">
        <h2>Cookies Lotus Yum</h2>
        <div class="price">Rp75.000</div>
        <button class="btn">Buy Now</button>
      </div>
    </div>

    <div class="card">
      <img src="cupcake.jpg" alt="Cupcake">
      <div class="card-content">
        <h2>Cupcake Super Wow</h2>
        <div class="price">Rp25.000</div>
        <button class="btn">Buy Now</button>
      </div>
    </div>

  </section>

  <footer>
    © 2026 Salsa Cake Shop | Made with 💖
  </footer>

</body>
</html>
