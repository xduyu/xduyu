    <!DOCTYPE html>
    <html lang="ru">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Annecy Bio | Piston</title>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
        <link rel="shortcut icon" href="./img/website-icon.gif">
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <!-- Видео на фоне -->
        <video autoplay muted loop id="background-video">
            <div class="overlay"></div> <!-- Прозрачный фильтр поверх видео -->
            <source src="./img/piston.mp4" type="video/mp4">
            <source src="./img/piston.mp4" type="video/webm">
            Ваш браузер не поддерживает видео.
        </video>


        <div class="full-c">
            <div class="container">
                <!-- Обновленный блок "Обо мне" -->
                <section id="about">
                    <div class="profile">
                        <img id="discord-avatar" src="./img/piston-avatar.jpg" alt="Discord Avatar">
                        <div class="profile-info">
                            <h2 id="discord-nickname" style="display: flex;">Piston <span><img class="emoji" style="max-height: 40px;position: relative; top: 10px; right: -10px;" src="./img/florkflower.png" alt=""><img class="emoji2 emoji" style="max-height: 40px;position: relative; top: 10px; right: -20px;" src="./img/.png" alt=""><img class="emoji2 emoji" style="max-height: 40px;position: relative; top: 10px; right: -30px;" src="./img/" alt=""></span></h2>
                            <p id="discord-status">Aктивен 🌙</p>
                        </div>
                    </div>
                    <p class="bio-description">💖❤️❤️❤️❤️</p>
                </section>
            </div>

        
            <section class="contacts" id="contacts">
                <h2>Контакты</h2>
                <ul>
                    <li>Discord: <a href="https://discord.com/channels/@me/705730434549547068">piston336</a></li>
                    <li>Telegram: <a href="https://t.me/pestonik">pestonik</a></li>
                    <p class="bio-description">💖❤️❤️❤️❤️</p>
                </ul>
        
                <footer>
                    <p>© 2024 Annecy Bio. Все права защищены.</p>
                </footer>
            </section>
        
        </div>
        <!-- Контейнер для дождя -->
        <div id="rain-container"></div>

        <script src="script.js"></script>
    </body>
    </html>
s
