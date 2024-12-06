<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Достар еда</title>
    <style>
        body {
            background-color: #FFFFFF; /* Задаем белый фон */
            font-family: Arial, sans-serif; /* Добавляем шрифт для красоты */
        }
        h1 {
            color: #008000; /* Цвет заголовка */
            font-family: "Ink Free", cursive;
            text-align: center; /* Выравнивание заголовка */
        }
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #FFFF00; /* Желтый фон */
            color: black; /* Черный текст */
            border: 2px solid green; /* Зеленая рамка */
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            font-family: "Ink Free", cursive;
        }
        button:hover {
            background-color: #0084ff; /* Синий фон при наведении */
            color: white; /* Белый текст при наведении */
        }
    </style>
</head>
<body>
    <h1>"ДОСТАР" еда</h1>

    <button id="openWhatsApp1">Триумф шашлык нажмите что бы заказать</button>
    <button id="openWhatsApp2">Доставка супа нажмите чтобы заказать</button>

    <script>
        // Настраиваем первую кнопку
        const button1 = document.getElementById("openWhatsApp1");
        button1.addEventListener("click", function () {
            const phoneNumber1 = "77474705053";
            const url1 = `https://api.whatsapp.com/send?phone=${phoneNumber1}`;
            window.open(url1, "_blank");
        });

        // Настраиваем вторую кнопку
        const button2 = document.getElementById("openWhatsApp2");
        button2.addEventListener("click", function () {
            const phoneNumber2 = "77474706060"; // Измените номер, если нужно
            const url2 = `https://api.whatsapp.com/send?phone=${phoneNumber2}`;
            window.open(url2, "_blank");
        });
    </script>
</body>
</html>
