<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gnomic Shop</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, black 50%, pink 50%);
      color: white;
    }
    header {
      padding: 20px;
      text-align: center;
      background-color: rgba(0, 0, 0, 0.6);
    }
    h1 {
      margin: 0;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .product {
      background-color: rgba(255, 255, 255, 0.1);
      border: 1px solid white;
      border-radius: 10px;
      margin: 10px;
      padding: 10px;
      width: 200px;
      text-align: center;
      transition: transform 0.2s;
    }
    .product:hover {
      transform: scale(1.05);
    }
    .product img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .product h3 {
      margin: 10px 0 5px;
    }
    .product p {
      margin: 0;
    }
    button {
      margin-top: 10px;
      padding: 8px 12px;
      border: none;
      background-color: pink;
      color: black;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #ffb6c1;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gnomic Shop</h1>
  </header>
  <div class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x250" alt="Одежда 1">
      <h3>Футболка</h3>
      <p>1 500 ₽</p>
      <button>В корзину</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x250" alt="Одежда 2">
      <h3>Платье</h3>
      <p>2 800 ₽</p>
      <button>В корзину</button>
    </div>
    <!-- Добавь больше товаров по желанию -->
  </div>
</body>
</html>



