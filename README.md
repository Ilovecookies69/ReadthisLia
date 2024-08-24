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

            font-size: 14px; /* Adjust the font size here */

            color: #333333;

        }

        .gif {

            max-width: 100px; /* Adjust size as needed */

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

        <div class="heart-icon" onclick="toggleMessage()">❤️</div>

        <div class="song-info">Hanger ka ba ni mama? <br> because you hit different</div>

        <div class="birthday-message" id="birthdayMessage">

            <img src="https://media0.giphy.com/media/26FLdmIp6wJr91JAI/200.webp?cid=790b7611qkxwpgc7cu9ccl17u7v20zdwzz1s4op2rq8c2j4f&ep=v1_gifs_search&rid=200.webp&ct=g" alt="GIF3" class="gif">

            <img src="https://media4.giphy.com/media/Gn1Ij0VOFntE1CkK7B/200.webp?cid=ecf05e47kt5p8qfa6it9h08kwym0kgdheempxqwxcr6qwoi3&ep=v1_gifs_search&rid=200.webp&ct=g" alt="GIF4" class="gif">

            <!-- Your birthday message goes here -->

          <p>It's April 5, 2024, 10:29 PM as I write this message.  I promised myself that I'd be the first to greet you on the happiest and most special day of the year.</p>

            <p>I wanted to greet you, but I felt a simple text would be plain and boring. I coded this using my phone so its not the best looking thing. Actually I have a code way better than this, i have a project in my laptop named after you, I started it on April 3rd. It was supposed to be a website dedicated for you and your birthday, but days has gone by, it's still ongoing and still lots of work to do. Actually im very disappointed I didnt finish it before your birthday, but once i finish it I will send the website to you. Recently, I learned programming during my work immersion, I chose computer engineering, and coding has been a big interest for me the last few weeks.Making this birthday message for you has been one of the best things I've done. It took me almost two hours to make this, but it was worth it. Hopefully, you appreciate this gesture; it's not the best, but I've put my heart into it.</p>

            <p>I want you to know that I still deeply care about you, as much as before. I know you don't trust me anymore, but I'm working to change myself, not just for you, but also for myself and the people around me. But for now, I'll continue loving you in silence. You'll always have a special place in my heart no matter what happens.</p>

            <p>Until next time we cross our paths, hopefully this time, with a better version of myself. May God always protect you, your family, and your precious smile. Don't lose your beautiful smile. That's what makes you attractive and beautiful.</p>

            <p>You can do it, my future CPA! Your sacrifices will pay off soon. I believe in you, and I'll be there to celebrate your achievements and accomplishments. Keep fighting towards your goal, chase your dreams! Sabe nga nila in bisaya "Sagdi lang, ma okay ra lage ang tanan." </p>



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

</html></html>
