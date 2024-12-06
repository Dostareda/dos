# ...
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
Достар еда
	</a>
	</title>
    <style>
        body {
            background-color: #FFFFFF; /* Задаем белый фон */
            font-family: Arial, sans-serif; /* Добавляем шрифт для красоты */
        }
        h1 {
            color: #000; /* Цвет заголовка */
            text-align: вваапter;
        }
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #0084ff;
            color: white;
            border: ;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title></title>
  <style>
    /* Стили для изображения */
    h1 {
      color: #008000;
	  font-family: "Ink Free", cursive;
    }
  </style>
</head>
<body>
  <h1>
  "ДОСТАР" ед@
  </h1>
</body>
</html>



    <button id="openWhatsApp">Master doner нажмите для заказа</button>

    <script>
        // Получаем кнопку
        const button = document.getElementById("openWhatsApp");

        // Устанавливаем стили
        button.style.backgroundColor = "#FFFF00"; // Желтый фон
        button.style.color = "black"; // Черный текста
        button.style.width = "auto"; // Ширина кнопки
        button.style.height = "auto"; // Автовысота
        button.style.border = "2px solid green"; // Зеленая рамка
        button.style.fontSize = "16px"; // Размер текста
        button.style.float = "left"; // Размещаем кнопку слева
        button.style.marginTop = "20px"; // Отступ сверху (по желанию)
		button.style.fontFamily = "'Ink Free', cursive";

        // Обработчик клика
        button.addEventListener("click", function () {
            const phoneNumber = "77474705053";
            const url = `https://api.whatsapp.com/send?phone=${phoneNumber}`;
            window.open(url, "_blank");
        });
    </script>
</body>

    </script>
</body>
</html>
