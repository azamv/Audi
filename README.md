<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Audi — Официальный сайт</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400&display=swap" rel="stylesheet">
    <style>
    

        body {
            margin: 0;
            padding: 0;
            font-family: 'Orbitron', sans-serif;
            background-color: #f9f9f9;
            color: #222;
        }

        header {
            background: linear-gradient(to right, #000, #333);
            color: #fff;
            padding: 15px 50px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        header img {
            height: 50px;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
            font-size: 14px;
            font-weight: 600;
            transition: color 0.3s, transform 0.3s;
        }

        nav a:hover {
            color: #d5d5d5;
            transform: scale(1.1);
        }

        .hero {
            background: url('file:///C:/Users/pc/Downloads/A250100_large.jpg') center/cover no-repeat;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.8);
        }

        .hero h1 {
            font-size: 48px;
            margin: 0;
        }

        .models-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            max-width: 1200px;
            margin: auto;
        }

        .model-card {
            width: 30%;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 15px;
            margin: 10px;
            transition: transform 0.3s ease;
        }

        .model-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }

        .model-card img {
            width: 100%;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .model-card:hover img {
            transform: scale(1.05);
        }

        .carousel {
            position: relative;
            max-width: 100%;
            overflow: hidden;
        }

        .carousel img {
            width: 100%;
            transition: transform 1s ease-in-out;
        }

        .carousel-buttons {
            position: absolute;
            top: 50%;
            width: 100%;
            display: flex;
            justify-content: space-between;
            transform: translateY(-50%);
        }

        .carousel-button {
            background-color: rgba(0, 0, 0, 0.5);
            color: rgb(10, 9, 9);
            border: none;
            padding: 10px;
            cursor: pointer;
            font-size: 20px;
        }

        .carousel-button:hover {
            background-color: rgba(0, 0, 0, 0.7);
        }

        .news-section, .gallery-section, .reviews-section {
            max-width: 1200px;
            margin: auto;
            padding: 40px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .news-item, .review {
            margin-bottom: 20px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 15px;
        }

        .gallery img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .chatbot {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: black;
            color: white;
            padding: 10px 20px;
            border-radius: 50px;
            cursor: pointer;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }
    </style>
</head>
<body>

<header>
    <img src="https://i.pinimg.com/originals/5b/43/a5/5b43a54cecf18e1c3f96a51a9e99ba08.gif" alt="Audi">
    <nav>
        <a href="#about">О компании</a>
        <a href="#models">Модели</a>
        <a href="#testdrive">Тест-драйв</a>
        <a href="#news">Новости</a>
        <a href="#gallery">Галерея</a>
        <a href="#reviews">Отзывы</a>
        <a href="#contact">Контакты</a>
    </nav>
</header>

<div class="hero">
    <h1>Превосходство через технологии</h1>
</div>
<section class="carousel">
    <div class="carousel-buttons">
        <button class="carousel-button" onclick="prevSlide()">&#10094;</button>
        <button class="carousel-button" onclick="nextSlide()">&#10095;</button>
    </div>
</section>

<section id="news" class="news-section">
    <h2>Новости</h2>
    <div class="news-item"><h3>Audi представила новый RS e-tron GT Performance</h3><p>Электрический суперкар с 900 л.с. уже доступен для заказа.</p></div>
    <div class="news-item"><h3>Запуск нового Audi Q3</h3><p>Внедорожник с улучшенной аэродинамикой и продвинутыми технологиями.</p></div>
    <div class="news-item"><h3>Презентация Audi RS5</h3><p>Новое поколение легендарного фастбэка.</p></div>
</section>

<section id="gallery" class="gallery-section">
    <h2>Галерея</h2>
    <div class="gallery">
        <img src="https://avatars.mds.yandex.net/i?id=665d7c2a48bdd55940075dca4568c2cf_l-5345090-images-thumbs&n=13" alt="Audi Image 1">
        <img src="https://d1gl66oyi6i593.cloudfront.net/wp-content/uploads/2024/12/prueba-audi-s5-2025.jpg" alt="Audi Image 2">
        <img src="file:///C:/Users/pc/Downloads/audi_r8_v10_coupe_japan_final_edition_5k-3840x2160.jpg" alt="Audi Image 3">
        <img src="file:///C:/Users/pc/Downloads/audi_rs_e_tron_gt_performance_2025-3840x2160.jpg" alt="Audi Image 4">
    </div>
</section>

<section id="reviews" class="reviews-section">
    <h2>Отзывы клиентов</h2>
    <div class="review"><h3>Кураев Магомед</h3><p>"Audi RS7 — это просто бомбовая ежи"</p></div>
    <div class="review"><h3>Каджаева Радмила</h3><p>"Топовая S5. Как я на ней гоняю ешкин кот"</p></div>
    <div class="review"><h3>Братанов Серёжа</h3><p>"Audi S8 – Боженька просто"</p></div>
</section>

<section class="car-card-section">
    <h2>Рекомендуемая модель</h2>
    <div class="car-card">
        <img src="https://www.carscoops.com/wp-content/uploads/2024/11/Audi-SQ5-Sportback-7-copy.jpg" alt="Audi Car Model">
        <div class="car-card-info">
            <h3>Audi SQ5 Sportback</h3>
            <p>Совершенство в каждой детали. Это ваш путь к комфортному и стильному вождению.</p>
            <button class="explore-button">Узнать больше</button>
    
        </div>
    </div>
</section>

<div class="chatbot">💬 Чат с консультантом</div>


<section id="models">
    <h2>Наши Модели</h2>
    
    <div class="models-grid">
        <div class="model-card">
            <img src="https://cdn.motor1.com/images/mgl/ZngoLK/s1/audi-a6-avant-2025.webp" alt="Audi A6">
            <h3>Audi A6</h3>
            <p>3.0 TFSI, 367 л.с., Quattro</p>
            <p>7 650 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
        <div class="model-card">
            <img src="https://resizer.mail.ru/p/deda66ff-9f3e-56a9-9b8b-52bfe5156c60/AQABXIweSoDCg00Pw7sYuZTakgFB0dqFwIo9Y2Q32ICxvIwqShkBQkql1DR5HEYq3tWYzSrSIx4QmTBiKm3mYQeD-S0.webp" alt="Audi A5L Sportback">
            <h3>Audi A5L Sportback</h3>
            <p>2.0 TFSI, 204 л.с., Quattro</p>
            <p>6 890 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
        <div class="model-card">
            <img src="https://cdn-images.motor.es/image/m/1320w.webp/fotos-jato/audi/uploads/audi-a8-641f32bbc8441.jpg" alt="Audi S8">
            <h3>Audi S8</h3>
            <p>4.0 TFSI, 571 л.с., Quattro</p>
            <p>16 900 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
        <div class="model-card">
            <img src="https://avatars.mds.yandex.net/i?id=b288d0944f36e81eb2f005565c3fbfc3_l-5329060-images-thumbs&n=13" alt="Audi RS7">
            <h3>Audi RS7</h3>
            <p>4.0 TFSI, 600 л.с., Quattro</p>
            <p>14 500 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
        <div class="model-card">
            <img src="https://www.carpixel.net/w/3ec4e9b7134caf854bba5c6e1ddb3516/audi-rs-e-tron-gt-wallpaper-hd-122915.jpg" alt="Audi RS-etrone Performance">
            <h3>Audi RS-etrone Performance</h3>
            <p>Etrone, 925 л.с., Quattro</p>
            <p>21 200 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
        <div class="model-card">
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgemukih_RI_nZvxcmfYDyTUeyIps4WecFc5neGHXn4lrQn8zWnlUgh3fev-cGkrJO0vx-Yx2xWyYDoYecweju7i8erSBKZ5YWuVaDIxb-9OK91GESmgR5wtDyDEr3hGWHgPPm3jkKGdh1L1An0U8HUgYUi8b81xORRgO31R3xjwwLvTVNtC_xuddCjkBPW/s1920/Audi%20RS%20Q8%205.jpg" alt="Audi RSQ8 Performance">
            <h3>Audi RSQ8 Performance</h3>
            <p>4.0 TDI, 640 л.с., Quattro</p>
            <p>16 500 000 ₽</p>
            <button class="buy-button">Купить</button>
        </div>
    </div>
</section>

<style>
    .models-grid {
        display: flex;
        flex-wrap: wrap; /* Позволяет элементам переноситься на новую строку */
        justify-content: space-around; /* Устанавливает равные промежутки между элементами */
    }
    .model-card {
        width: 45%; /* Задаем ширину каждой карточки для двух в ряд */
        box-sizing: border-box; /* Учитывает padding и border в ширине */
        margin: 10px; /* Отступы вокруг карточек */
    }
</style>


<style>
    .models-grid {
        display: flex;
        flex-wrap: wrap; /* Позволяет элементам переноситься на новую строку */
        justify-content: space-around; /* Устанавливает равные промежутки между элементами */
    }
    .model-card {
        width: 45%; /* Задаем ширину каждой карточки для двух в ряд */
        box-sizing: border-box; /* Учитывает padding и border в ширине */
        margin: 10px; /* Отступы вокруг карточек */
    }
</style>

<section id="calculator">
    <div class="calculator">
      <h2>Калькулятор Audi</h2>
      <label for="model-price">Выберите модель:</label>
      <select id="model-price" onchange="updateBasePrice()">
        <option value="7650000">Audi A6 — 7 650 000₽</option>
        <option value="6890000">Audi A5L — 6 890 000₽</option>
        <option value="16900000">Audi S8 — 16 900 000₽</option>
        <option value="14500000">Audi RS7 — 14 500 000₽</option>
        <option value="21200000">Audi RS-Etron — 21 200 000₽</option>
        <option value="16500000">Audi RSQ8 — 16 500 000₽</option>
      </select>
  
      <div class="options">
        <label><input type="checkbox" value="250000" class="option" onchange="animateOption(this)"> Панорамная крыша +250 000₽</label>
        <label><input type="checkbox" value="180000" class="option" onchange="animateOption(this)"> Кожаный салон +180 000₽</label>
        <label><input type="checkbox" value="120000" class="option" onchange="animateOption(this)"> Премиальная аудиосистема +120 000₽</label>
      </div>
  
      <div class="result" id="total">Итог: 7 650 000₽</div>
      <button onclick="calculate()">Рассчитать</button>
    </div>
  </section>
  
  <style>
    #calculator {
      margin: 60px auto;
      max-width: 600px;
      padding: 20px;
    }
    .calculator {
      background: #111;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0, 255, 255, 0.2);
      color: #fff;
      font-family: 'Orbitron', sans-serif;
      transition: 0.3s;
    }
    .calculator h2 {
      text-align: center;
      color: #0ff;
      margin-bottom: 20px;
    }
    .calculator label {
      display: block;
      margin: 10px 0;
      cursor: pointer;
      transition: 0.3s;
    }
    .calculator label:hover {
      color: #0ff;
    }
    .calculator select {
      width: 100%;
      padding: 8px;
      border-radius: 10px;
      border: none;
      margin-bottom: 15px;
      font-size: 16px;
    }
    .result {
      font-size: 24px;
      color: #0ff;
      text-align: center;
      margin-top: 20px;
    }
    .calculator button {
      width: 100%;
      padding: 12px;
      border: none;
      background: linear-gradient(to right, #00c6ff, #0072ff);
      border-radius: 30px;
      font-weight: bold;
      font-size: 16px;
      color: #000;
      cursor: pointer;
      transition: 0.3s;
    }
    .calculator button:hover {
      transform: scale(1.05);
    }
    .options input[type="checkbox"]:checked + label {
      color: #0ff;
    }
    .animated {
      animation: pulse 0.4s ease;
    }
    @keyframes pulse {
      0% { background-color: rgba(0, 255, 255, 0.2); }
      100% { background-color: transparent; }
    }
  </style>
  
  <script>
    function calculate() {
      const modelPrice = parseInt(document.getElementById('model-price').value);
      const options = document.querySelectorAll('.option:checked');
      let total = modelPrice;
  
      options.forEach(opt => {
        total += parseInt(opt.value);
      });
  
      document.getElementById('total').textContent = `Итог: ${total.toLocaleString('ru-RU')}₽`;
    }
  
    function animateOption(checkbox) {
      const label = checkbox.parentElement;
      label.classList.add('animated');
      setTimeout(() => label.classList.remove('animated'), 400);
      calculate();
    }
  
    function updateBasePrice() {
      calculate();
    }
  
    window.onload = calculate;
  </script>

<section id="testdrive">
    <h2>Записаться на тест-драйв</h2>
    <form action="submit_form.php" method="POST">
        <label for="name">Ваше имя</label>
        <input type="text" id="name" name="name" placeholder="Введите ваше имя" required>

        <label for="phone">Телефон</label>
        <input type="tel" id="phone" name="phone" placeholder="Введите ваш телефон" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="Введите ваш email" required>

        <label for="location">Город</label>
        <input type="text" id="location" name="location" placeholder="Выберите город" required>

        <label for="model">Выберите модель</label>
        <select id="model" name="model" required>
            <option value="a6">Audi A6</option>
            <option value="a5l">Audi A5L</option>
            <option value="rs7">Audi RS7</option>
            <option value="rsq8">Audi RSQ8</option>
            <option value="s8">Audi S8</option>
            <option value="q5">Audi Q5</option>
        </select>

        <section id="configurator" class="configurator-section">
            <h2>Конфигуратор Audi</h2>
            <p>Выберите свою идеальную модель Audi</p>
            <select id="model-select">
                <option value="a6">Audi A6</option>
                <option value="a7">Audi A7</option>
                <option value="q8">Audi Q8</option>
                <option value="rs6">Audi RS6</option>
            </select>
            <button onclick="showConfig()">Настроить</button>
            <p id="config-result"></p>
        </section>
        
        <script>
            function showConfig() {
                let model = document.getElementById('model-select').value;
                document.getElementById('config-result').innerText = "Вы выбрали " + model;
            }
        </script>
        
        <div class="chatbot">💬 Чат с консультантом</div>

        <label for="date">Дата тест-драйва</label>
        <input type="date" id="date" name="date" required>

        <label for="time">Время тест-драйва</label>
        <input type="time" id="time" name="time" required>

        <button type="submit">Записаться</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Audi AG. Все права защищены.</p>
</footer>

</body>
</html>
