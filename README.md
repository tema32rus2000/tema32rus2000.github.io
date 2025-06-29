<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>FNaF 2 Jumpscare</title>
    <style>
        #foxyJumpscare {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 9999;
            pointer-events: none;
        }
        #foxyJumpscare img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <!-- Контент страницы -->
    <h1>Осторожно, Фокси!</h1>
    <p>Каждую секунду с шансом 1/10000 может появиться скример.</p>

    <!-- Скрытый скример Фокси -->
    <div id="foxyJumpscare">
        <img src="https://media.tenor.com/bS_6FmV06qMAAAAj/foxy-jumpscare.gif" alt="FNaF 2 Foxy Jumpscare">
    </div>

    <script>
        const foxyJumpscare = document.getElementById("foxyJumpscare");
        const chance = 1 / 10000; // Шанс 1 к 10000

        // Проверяем каждую секунду
        setInterval(() => {
            if (Math.random() < chance) {
                // Показываем скример
                foxyJumpscare.style.display = "block";
                
                // Проигрываем звук (опционально)
                const audio = new Audio("https://www.myinstants.com/media/sounds/fnaf-2-death-scream.mp3");
                audio.play();

                // Убираем скример через 2 секунды
                setTimeout(() => {
                    foxyJumpscare.style.display = "none";
                }, 2000);
            }
        }, 1000); // 1000 мс = 1 секунда
    </script>
</body>
</html>
