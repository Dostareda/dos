<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Достар еда</title>
    <style>
        body {
            background-color: #FFFFFF; /* Белый фон */
            font-family: Arial, sans-serif; /* Общий стандартный шрифт */
        }
        h1 {
            color: #008000; /* Зеленый цвет заголовка */
            text-align: center; /* Выравнивание заголовка */
        }
        button {
            display: block;
            margin: 20px 0; /* Отступ сверху и снизу */
            padding: 10px 20px; /* Внутренние отступы */
            background-color: #FFFF00; /* Желтый фон */
            color: black; /* Черный текст */
            border: 2px solid green; /* Зеленая рамка */
            border-radius: 5px; /* Слегка закругленные углы */
            cursor: pointer;
            font-size: 16px; /* Размер текста */
            font-family: Arial, sans-serif; /* Стандартный шрифт для кнопок */
            text-align: left; /* Текст кнопки слева */
        }
        button:hover {
            background-color: #FFD700; /* Темно-желтый при наведении */
            color: black;
        }
        .button-container {
            text-align: left; /* Выравнивание кнопок по левому краю */
            margin-left: 20px; /* Отступ слева от края страницы */
        }
    </style>
</head>
<body>
    <h1>"ДОСТАР" еда</h1>

    <div class="button-container">
        <button id="openWhatsApp1">Триумф шашлык нажмите чтобы заказать</button>
        <button id="openWhatsApp2">Донер нажмите чтобы заказать</button>
    </div>

    <script>
        // Обработчик для первой кнопки
        const button1 = document.getElementById("openWhatsApp1");
        button1.addEventListener("click", function () {
            const phoneNumber1 = "77474705053";
            const url1 = `https://api.whatsapp.com/send?phone=${phoneNumber1}`;
            window.open(url1, "_blank");
        });

        // Обработчик для второй кнопки
        const button2 = document.getElementById("openWhatsApp2");
        button2.addEventListener("click", function () {
            const phoneNumber2 = "77002726869"; // Измените номер, если нужно
            const url2 = `https://api.whatsapp.com/send?phone=${phoneNumber2}`;
            window.open(url2, "_blank");
        });
    </script>
</body>
</html>
