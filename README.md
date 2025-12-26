# web-journey<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Сайт для бизнеса</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Я делаю сайты для бизнеса</h1>
    <img src="images/hero.jpg" alt="Сайт для бизнеса" width="600">
    <p>Помогаю получать клиентов через интернет</p>
    <a href="https://t.me/@Qwehva" class="btn">Получить консультацию</a>
    
    <h2>Почему выбирают нас</h2>
    <div class="advantages">
      <div class="advantage">
        <h3>Профессионализм</h3>
        <p>Создаём сайты, которые приносят клиентов</p>
      </div>
      <div class="advantage">
        <h3>Быстро</h3>
        <p>Сайт за 3–5 дней</p>
      </div>
      <div class="advantage">
        <h3>Поддержка</h3>
        <p>Всегда на связи</p>
      </div>
    </div>
  </div>

  <form action="https://formspree.io/f/maqwrewj" method="POST" class="form">
    <input type="text" name="name" placeholder="Ваше имя" required>
    <input type="email" name="email" placeholder="Email" required>
    <textarea name="message" placeholder="Сообщение" required></textarea>
    <button

body {
  font-family: Arial, sans-serif;
  background: #f4f6f8;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 900px;
  margin: 60px auto;
  background: #fff;
  padding: 40px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 10px 30px rgba(0,0,0,.1);
}

h1 {
  color: #1e66ff;
}

img {
  max-width: 100%;
  height: auto;
  margin: 20px 0;
}

.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 14px 28px;
  background: #1e66ff;
  color: #fff;
  text-decoration: none;
  border-radius: 8px;
}

.advantages {
  display: flex;
  gap: 20px;
  margin-top: 40px;
}

.advantage {
  background: #f9fafb;
  padding: 20px;
  border-radius: 10px;
}
