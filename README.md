<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday Message</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
        }
        .heart-icon {
            font-size: 36px;
            color: #ff007f;
            cursor: pointer;
            transition: transform 0.3s ease;
            animation: heartbeat 1s infinite;
        }
        .heart-icon:hover {
            transform: scale(1.1);
        }
        @keyframes heartbeat {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }
        .birthday-message {
            display: none;
            background-color: #ffc0cb; /* Pink background color */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
            margin-top: 20px;
            font-size: 14px; /* Adjusted font size */
            color: #333333;
            max-width: 80%; /* Limit width to prevent overflow */
            margin-left: auto;
            margin-right: auto;
        }
        .gif {
            max-width: 100px; /* Adjusted size */
            height: auto; /* Maintain aspect ratio */
        }
        .song-info {
            background-color: #ffadad; /* Coral background color */
            padding: 10px;
            border-radius: 5px;
            color: #333333;
            font-size: 20px;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://media4.giphy.com/media/l4pTdcifPZLpDjL1e/giphy.webp?cid=790b7611qkxwpgc7cu9ccl17u7v20zdwzz1s4op2rq8c2j4f&ep=v1_gifs_search&rid=giphy.webp&ct=g" alt="GIF1" class="gif">
        <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWt4d3BnYzdjdTljY2wxN3U3djIwemR3enoxczRvcDJycThjMmo0ZiZlcD12MV9naWZzX3NlYXJjaCZjdD1n/R6gvnAxj2ISzJdbA63/giphy.webp" alt="GIF2" class="gif">
        <div class="heart-icon" onclick="toggleMessage()">💜</div>
        <div class="song-info">Hi Pookie (Click the Heart)<br>always drink your water</div>
        <div class="birthday-message" id="birthdayMessage">
            <img src="https://media0.giphy.com/media/26FLdmIp6wJr91JAI/200.webp?cid=790b7611qkxwpgc7cu9ccl17u7v20zdwzz1s4op2rq8c2j4f&ep=v1_gifs_search&rid=200.webp&ct=g" alt="GIF3" class="gif">
            <img src="https://media.giphy.com/media/l0HU2sYgCZh3HiKnS/giphy.gif" alt="GIF4" class="gif">
            <p>Dear Lia,</p>
            <p>It's August 25 as I was writing this message, 12:15 midnight. I was supposed to study biochem and anaphy, but I figured out, why not make you a short message. So I'm hoping you'd read this💜(fav color mo lol)</p>
            <p>I have no idea paano ko napunta sa point na to, writing you a message, umaamin on what I'm feeling. But the first time we met, I wasn't really feeling this way. I just got from a breakup around Feb/March, and it really affected me mentally. Mahirap mag-trust or open up to someone, especially to a girl, but with you, everything felt natural.</p>
            <p>You probably know me (maybe not), but gusto ko lang sabihin na I really appreciate how great of a person you are, how beautiful you are (is it true, chat?), and lastly, how great your personality is. I'm hoping na kahit anong challenge that college will throw at you, di ka magbabago as a person. It's the very first thing that made me love you.</p>
            <p>I never expected that I would like you like this, because the very first time palang, akala ko you were that "it girl" type. All the events that we attended, the stories we shared, knowing the real you, made me love you (yuck). To be honest, I thought I was just infatuated, but never ko ma-eexpect that I would get jealous of someone na kasama mo (fuck that should be me talaga).</p>
            <p>Anyways, it took me about 2 hours to make this alongside the coding part of the website, and I don’t really know if I will send it to you (your goddamn right I’m a fcking torpe). Anyways, good luck to your quiz and battle next week. Hopefully, you get accepted sa student council. For now, I have my own battles I need to face as well. So good luck and take care.</p>
            <p>Xoxo,<br>FEU BSN 2024035531</p>
            <p>Ps: Happy birthday to Angel, fuck sana nainvite ako</p>
        </div>
    </div>

    <script>
        function toggleMessage() {
            var message = document.getElementById("birthdayMessage");
            if (message.style.display === "none") {
                message.style.display = "block";
            } else {
                message.style.display = "none";
            }
        }
    </script>
</body>
</html>
