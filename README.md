<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تطبيق حمزة</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            padding-top: 20%;
            background-color: #f0f0f0;
        }
        h1 {
            color: #ff1493;
        }
    </style>
</head>
<body>
    <h1>حمزة بيحبك ❤️</h1>
    <audio id="background-music" autoplay loop>
        <source src="romantic-song.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <script>
        // تشغيل الأغنية تلقائيًا
        document.addEventListener('DOMContentLoaded', function() {
            var audio = document.getElementById('background-music');
            audio.play();
        });
    </script>
</body>
</html>
