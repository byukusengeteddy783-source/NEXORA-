# NEXORA-
NEXORA - Urubuga rwa mobile rufite products, deposit, withdrawal na referral
<!DOCTYPE html>
<html lang="rw">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NEXORA</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f1f8f4;
      color: #123d28;
    }

    header {
      background: #087f3d;
      color: white;
      padding: 18px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    header h1 {
      font-size: 26px;
    }

    header p {
      margin-top: 5px;
      font-size: 13px;
    }

    .container {
      max-width: 600px;
      margin: auto;
      padding: 15px;
    }

    .balance {
      background: linear-gradient(135deg, #087f3d, #16a05a);
      color: white;
      border-radius: 18px;
      padding: 22px;
      margin-bottom: 18px;
      box-shadow: 0 5px 15px #0002;
    }

    .balance small {
      opacity: .9;
    }

    .balance h2 {
      font-size: 30px;
      margin: 8px 0;
    }

    .buttons {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      margin-top: 15px;
    }

    button {
      border: none;
      border-radius: 12px;
      padding: 13px;
      font-size: 15px;
      cursor: pointer;
    }

    .deposit {
      background: white;
      color: #087f3d;
    }

    .withdraw {
      background: #075f30;
      color: white;
    }

    h2.section {
      margin: 20px 0 12px;
      font-size: 21px;
    }

    .products {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .product {
      background: white;
      border-radius: 15px;
      padding: 15px;
      box-shadow: 0 3px 10px #0001;
    }

    .product h3 {
      color: #087f3d;
      margin-bottom: 8px;
    }

    .product p {
      font-size: 13px;
      margin: 5px 0;
    }

    .buy {
      width: 100%;
      background: #087f3d;
      color: white;
      margin-top: 10px;
    }

    .menu {
      margin-top: 20px;
      background: white;
      border-radius: 15px;
      overflow: hidden;
    }

    .menu div {
      padding: 16px;
      border-bottom: 1px solid #eee;
    }

    .menu div:last-child {
      border-bottom: none;
    }

    footer {
      text-align: center;
      padding: 25px;
      font-size: 12px;
      color: #777;
    }

    @media (max-width: 380px) {
      .products {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>NEXORA</h1>
  <p>Urubuga rwawe rw'iterambere</p>
</header>

<div class="container">

  <div class="balance">
    <small>Balance yawe</small>
    <h2>RWF 0</h2>
    <p>Murakaza neza kuri NEXORA</p>

    <div class="buttons">
      <button class="deposit" onclick="deposit()">Kubitsa</button>
      <button class="withdraw" onclick="withdraw()">Kubikuza</button>
    </div>
  </div>

  <h2 class="section">Products</h2>

  <div class="products">

    <div class="product">
      <h3>Product 1</h3>
      <p>Igiciro: RWF 7,000</p>
      <p>Inyungu: RWF 600</p>
      <p>Iminsi: 45</p>
      <button class="buy" onclick="buyProduct(1)">Gura</button>
    </div>

    <div class="product">
      <h3>Product 2</h3>
      <p>Igiciro: RWF 10,000</p>
      <p>Inyungu: RWF 850</p>
      <p>Iminsi: 45</p>
      <button class="buy" onclick="buyProduct(2)">Gura</button>
    </div>

    <div class="product">
      <h3>Product 3</h3>
      <p>Igiciro: RWF 15,000</p>
      <p>Inyungu: RWF 1,300</p>
      <p>Iminsi: 45</p>
      <button class="buy" onclick="buyProduct(3)">Gura</button>
    </div>

    <div class="product">
      <h3>Product 4</h3>
      <p>Igiciro: RWF 20,000</p>
      <p>Inyungu: RWF 1,700</p>
      <p>Iminsi: 45</p>
      <button class="buy" onclick="buyProduct(4)">Gura</button>
    </div>

  </div>

  <h2 class="section">Menu</h2>

  <div class="menu">
    <div>🏠 Home</div>
    <div>💰 Deposit</div>
    <div>💸 Withdrawal</div>
    <div>🎁 Welcome Bonus</div>
    <div>👥 Referral</div>
    <div>📊 Dashboard</div>
  </div>

</div>

<footer>
  © 2026 NEXORA — All Rights Reserved
</footer>

<script>
  function deposit() {
    alert("Deposit page ya NEXORA iraza.");
  }

  function withdraw() {
    alert("Withdrawal page ya NEXORA iraza.");
  }

  function buyProduct(number) {
    alert("Wahisemo Product " + number);
  }
</script>

</body>
</html>
