<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>CHEZ DESTIN FAST FOOD</title>

  <style>
    body {
      font-family: Arial;
      background: #fff5e6;
      margin: 0;
    }

    header {
      background: #e63946;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }

    .item {
      background: white;
      width: 220px;
      margin: 15px;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .price {
      color: #e63946;
      font-weight: bold;
    }

    .btn {
      background: #25D366;
      color: white;
      border: none;
      padding: 10px;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }
  </style>
</head>

<body>

<header>
  <h1>🍔 CHEZ DESTIN FAST FOOD</h1>
  <p>Commande rapide sur WhatsApp</p>
</header>

<div class="menu">

  <div class="item">
    <h3>🍔 Burger</h3>
    <p class="price">3$</p>
    <button class="btn" onclick="commander('Burger')">
      Commander
    </button>
  </div>

  <div class="item">
    <h3>🍟 Frites</h3>
    <p class="price">2$</p>
    <button class="btn" onclick="commander('Frites')">
      Commander
    </button>
  </div>

</div>

<script>
function commander(produit) {
  let numero = "243900042845";

  let message =
    "Bonjour CHEZ DESTIN 🍔, je veux commander : " + produit;

  let url =
    "https://wa.me/" + numero +
    "?text=" + encodeURIComponent(message);

  window.open(url, "_blank");
}
</script>

</body>
</html>
