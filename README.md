# Birthday-message-
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Привітання</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: black;
            color: white;
            font-size: 24px;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #message {
            max-width: 80%;
        }
    </style>
</head>
<body>
    <div id="message">Хєлоу) 🙃 натискай на єкран</div>

    <script>
        const messages = [
        
 "Я довго думала як тебе привітати з днем народження)🎁",
"Нічого краще я не придумала, тому клацай далі)🔥",
"Ось тобі і виповнилось 24 рочки🤯",
"Нехай у твоєму житті буде стільки щастя, скільки зірок на небі…✨ а якщо це надто багато, то хоча б стільки ж, скільки тобі років сьогодні!2️⃣4️⃣ "
" Нехай усі твої бажання здійснюються, навіть ті, що ти забув, коли їх загадував.🤫"
"І пам’ятай: вік — це просто число, а твоя веселість і класність завжди на висоті! 🎂🍻"
"Бажаю, щоб твоя життя була як Netflix – завжди з новими, цікавими епізодами і без рекламних пауз.📺📱"
"Нехай твій день буде настільки чудовим, як і твоя здібність тримати всю гру  під контролем.🎮👾
 "Пам’ятай, що з віком вино стає кращим, а ти… Ну, а ти поки просто стаєш старшим.🤗",
 " Ти дуже цінний , чк ніяк 24 роки витримки )"
 "А ше ти на один рік ближче до знижок для пенсіонерів. Насолоджуйся молодістю, поки вона ще не втекла!",
 " Але можеш бути спокійним, самим першим пенсіонером станеш все одно не ти"
 "Сподіваюся, ти збережеш своє почуття гумору – тобі воно ще знадобиться, коли побачиш кількість свічок на торті.",
"Ти досяг віку, коли 'веселі шумні вечірки' означають домашній затишок і ранній сон!",
"Хоча з кожним роком це звучить усе менш весело, одна річ незмінна: усі твої друзі невимовно чекають цього дня, щоб добряче напитися!",
"Здоров’я тобі. Бо всі оті побажання успіху і грошей уже не актуальні.",
" Та і думаю ти їх ітак достатньо отримаєш сьогодні"
"Не кожен доживає до такого поважного віку, тим більше із твоїм стилем життя. Тож здоров’я я таки побажаю тобі🤗",
"Кажу одразу, я не знаю як там далі 😂 бо ти старше мене.",
"Можу сказати те, що завжди буде моментами добре і моментами все херово🫠",
         "‼️!!! Але !!!‼️",
"Вмій насолоджуватись життям)",
"Лишайся такою ж булочкою з корицею🧁",
"Скоро виʼємо кави ввечері☕️"
" І по плану варимо глінтвейн🍷🍊"
" Тепер до подарунку, так як ти вже людина у віці , від мене ти отримаєш щось дуже мʼяке і те що зігріє взимку 🥶"
"А грілку на все тіло, знайдеш вже якось сам)🔥"
"Ще раз з днем народження, посміхнись)"
"З найкращими побажаннями, Юля 🤗"
"і взагалі я рада, що знайома з тобою)"
" Всьо ти догортав до кінця, сподіваюсь тобі сподобалось і ти посміхнувся)) Ще раз з днем народження🧁✨🥂🍻🎂🎉🎊"
   ];

        let index = 0;
        document.body.addEventListener('click', function() {
            if (index < messages.length) {
                document.getElementById('message').innerText = messages[index];
                index++;
            }
        });
    </script>
</body>
</html>
