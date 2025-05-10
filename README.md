<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Seninle Geleceğe</title>
    <style>
        body {
            background: linear-gradient(to right, #ffe0ec, #fdf2f8);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            position: relative;
            overflow-x: hidden;
        }

        .container {
            max-width: 700px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            text-align: center;
        }

        h1 {
            font-size: 2em;
            color: #d44a7d;
            margin-bottom: 30px;
        }

        .photo {
            margin-bottom: 30px;
            position: relative;
        }

        .photo img {
            width: 100%;
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }

        .photo p {
            margin-top: 10px;
            font-size: 1.1em;
            color: #555;
        }

        .footer-text {
            font-size: 1.2em;
            font-style: italic;
            background-color: #fff0f5;
            padding: 20px;
            border-radius: 10px;
            margin-top: 40px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .signature {
            position: fixed;
            bottom: 10px;
            left: 20px;
            font-size: 1.1em;
            color: #888;
        }

        .heart {
            position: absolute;
            color: red;
            font-size: 24px;
            animation: float 6s infinite ease-in-out;
        }

        @keyframes float {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            100% { transform: translateY(-300px) scale(1.5); opacity: 0; }
        }

        .heart:nth-child(1) { left: 10%; animation-delay: 0s; }
        .heart:nth-child(2) { left: 30%; animation-delay: 1s; }
        .heart:nth-child(3) { left: 50%; animation-delay: 2s; }
        .heart:nth-child(4) { left: 70%; animation-delay: 3s; }
        .heart:nth-child(5) { left: 90%; animation-delay: 4s; }

    </style>
</head>
<body>

    <div class="container">
        <h1>Seninle Bir Gelecek Hayal Ediyorum</h1>

        <div class="photo">
            <img src="foto1.jpg" alt="Senin Gülüşün">
            <p>Sen gülümsediğinde, dünya biraz daha güzel oluyor.</p>
        </div>

        <div class="photo">
            <img src="foto2.jpg" alt="Beraberliğimiz">
            <p>Seninle kuracağım hayatı sabırsızlıkla bekliyorum.</p>
        </div>

        <div class="footer-text">
            <p>Sen sadece bugünüm değil, yarınımsın. Bir gün seninle bir aile kurmak, seni çocuklarımın annesi olarak görmek... işte o hayali yaşatıyorsun bana. Her geçen gün sana daha da aşkla bağlanıyorum.</p>
        </div>
    </div>

    <div class="signature">Yasin Şahin</div>

    <!-- Kalp animasyonları -->
    <div class="heart">❤️</div>
    <div class="heart">❤️</div>
    <div class="heart">❤️</div>
    <div class="heart">❤️</div>
    <div class="heart">❤️</div>

</body>
</html>
