<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css">
    <link rel="stylesheet" href="./style.css">
    <title>Profile Card</title>
</head>

<body>
    
    <div class="card">
        <section class="main">
            <p class="name">Stephanie Tornito</p>
            <p>UX/UI  Developer | Future Cyber Security</p>
        </section>
        <section class="more">
            <p>Contact Me...</p>
            <div class="social-links">
                <a href="https://www.facebook.com/noonewilllovemeback?mibextid=ZbWKwL#" class="facebook">
                    <i class="fab fa-facebook-f"></i>
                </a>
                <a href="https://www.youtube.com/@stephanietornito5060#" class="youtube">
                    <i class="fab fa-youtube"></i>
                </a>
                <a href="https://t.me/FkkuM#" class="telegram">
                    <i class="fab fa-telegram"></i>
                </a>
                <a href="https://discord.gg/steph²#5019#" class="discord">
                    <i class="fab fa-discord"></i>
                </a>
                <a href="https://twitter.com/steph00phanie?t=Mua9uHz_agHGIfAQggZdGg&s=07#" class="twitter">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="https://mail.yahoo.com/stephanietornito@yahoo.com#" class="yahoo">
                    <i class="fab fa-yahoo"></i>
                </a>
            </div>
        </section>

        <section class="info">
            <section>
                <p>Posts</p>
                <p class="value">100</p>
            </section>
            <section>
                <p>Likes</p>
                <p class="value">3017</p>
            </section>
            <section>
                <p>Comments</p>
                <p class="value">1986</p>
            </section>
            <button id="openerBtn">
                <i class="fas fa-plus"></i>
                <i class="fas fa-minus"></i>

            </button>
        </section>
    </div>

</body>

<script>
    var buttonEl = document.getElementById('openerBtn');
    var cardEl = document.querySelector('.card');

    buttonEl.addEventListener('click', function() {
        cardEl.classList.toggle('opened');
    })
</script>

</html>
