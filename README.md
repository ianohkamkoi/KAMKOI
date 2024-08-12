<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KAMKOI</title>
    <style>
        body {
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            text-align: center;
            overflow: hidden;
        }
        .name-title {
            font-size: 50px;
            font-weight: 700;
            font-family: Arial;
            color: blue;
            background-color: rgb(49, 238, 24);
            padding-top: 50px;
            padding-bottom: 50px;
            margin: 0;
        }
        .watch-tv, .watch-tv-2 {
            font-size: 28px;
            font-weight: 500;
            font-family: Arial;
            color: rgb(250, 235, 22);
            background-color: red;
            margin: 0;
        }
        .watch-tv:hover, .watch-tv-2:hover {
            color: white;
        }
        .enter-button {
            padding: 20px 40px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 60px;
            border-radius: 30px;
            background-color: red;
            color: rgb(250, 235, 22);
            border: red;
            transition: 0.15s;
        }
        .enter-button:hover {
            background-color: rgb(250, 235, 22);
            color: red;
            border: rgb(250, 235, 22);
        }
        .enter-button:active {
            opacity: 0.5;
        }
        footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            text-align: center;
            padding: 10px 0;
            background-color: rgb(102, 98, 98);
            color: black;
            font-size: 20px;
            padding-top: 25px;
        }
        .link-my-channel {
            color: white;
            font-weight: 100;
            text-decoration: none;
        }
        .link-my-channel:hover {
            font-weight: 700;
        }
        .background-video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            z-index: -1;
        }
    </style>
</head>
<body>
    <video class="background-video" autoplay muted loop>
        <source src="background.mp4" type="video/mp4">
    </video>
    <p class="name-title">KAMKOI MOVIES</p>
    <p class="watch-tv">Watch tv series online, </p>
    <p class="watch-tv-2">absolutely free &#46</p>
    <button class="enter-button" onclick="goTohome()">ENTER</button>
    <footer>
        &copy; 2024 KAMKOI MOVIES &#46
        <a href="https://www.youtube.com/@iankaromo6733" target="_blank" class="link-my-channel">My YouTube channel</a>
    </footer>
    <script>
        function goTohome() {
            window.location.href = 'home.html';
        }
    </script>
</body>
</html>
