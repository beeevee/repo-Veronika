<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио</title>
    <style>
        * {
            box-sizing: border-box; /* Устанавливаем box-sizing для всех элементов */
        }

        body {
            font-family: 'Arial', sans-serif; /* Стили шрифта */
            margin: 0;
            padding: 0;
            background-color: #f9f9f9; /* Цвет фона страницы */
            color: #333; /* Цвет текста */
        }

        header {
            text-align: center;
            background-color: #E6E6FA; /* Нежный фиолетовый для заголовка */
            color: #4B0082; /* Тёмно-фиолетовый цвет текста */
            padding: 20px 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #4B0082; /* Тёмно-фиолетовый для ссылок */
            font-weight: bold; /* Увеличиваем вес шрифта для ссылок */
            transition: color 0.3s; /* Эффект перехода для наведения */
        }

        nav ul li a:hover {
            color: #ffeb3b; /* Цвет при наведении */
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white; /* Цвет фона для секций */
            border-radius: 8px; /* Скругление углов */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Легкая тень для секций */
        }

        h2 {
            color: #A594D6; /* Нежный фиолетовый для заголовков секций */
        }

        #about {
            text-align: center; /* Центрируем текст в секции "О себе" */
        }

        #skills ul {
            list-style-type: disc; /* Стилизация списка навыков */
            padding-left: 20px;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .item {
            margin: 10px;
            text-align: center;
            border-radius: 8px; /* Скругление углов для элементов */
            overflow: hidden; /* Прячем переполненные элементы */
            transition: transform 0.3s; /* Эффект перехода для элементов галереи */
        }

        .item:hover {
            transform: scale(1.05); /* Увеличение элемента при наведении */
        }

        .item img {
            max-width: 100%;
            height: auto;
            display: block; /* Убираем лишние отступы */
            border-bottom: 2px solid #A594D6; /* Подчеркивание изображения (нежный фиолетовый) */
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #E6E6FA; /* Нежный фиолетовый для подвала */
            color: #4B0082; /* Тёмно-фиолетовый для текста в подвале */
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать!</h1>
        <nav>
            <ul>
                <li><a href="#about">О себе</a></li>
                <li><a href="#skills">Навыки</a></li>
                <li><a href="#portfolio">Портфолио</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>О себе</h2>
        <p>Привет! Я Вероника, и я специализируюсь на С#. Я стремлюсь развиваться в области веб-дизайна, углубляя свои знания в современном дизайне пользовательского интерфейса и опыте. В ближайшие несколько лет хочу изучить новые инструменты и технологии, такие как Figma и Adobe XD, а также освоить принципы адаптивного и доступного дизайна.</p>
    </section>
    
    <section id="skills">
        <h2>Навыки</h2>
        <ul>
            <li>Языки программирования: C#, JavaScript, HTML, CSS</li>
            <li>Знание баз данных: SQL, NoSQL</li>
        </ul>
    </section>

    <section id="portfolio">
        <h2>Портфолио</h2>
        <div class="gallery">
            <div class="item"><a href="https://beeevee.github.io/vx/" target="_blank">GitHub</a>
                <p>Описание работы 1</p>
            </div>
            <div class="item">
                <img src="https://via.placeholder.com/150" alt="Работа 2">
                <p>Описание работы 2</p>
            </div>
            <div class="item">
                <img src="https://via.placeholder.com/150" alt="Работа 3">
                <p>Описание работы 3</p>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Контакты</h2>
        <p>Вы можете связаться со мной по электронной почте: hanakochkakun@yandex.ru</p>
    </section>

    <footer>
        <p>&copy; 2025. Все права защищены.</p>
    </footer>
</body>
</html>
