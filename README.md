<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashain Invitation</title>
    <link href="https://fonts.googleapis.com/css2?family=Festive&family=Raleway:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Raleway', sans-serif;
            background: linear-gradient(135deg, #FFD700, #FF6347, #FF1493, #FF8C00);
            background-size: 300% 300%;
            animation: GradientBackground 10s ease infinite;
        }

        @keyframes GradientBackground {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            text-align: center;
            padding: 50px;
            color: #fff;
        }

        .invite {
            font-family: 'Festive', cursive;
            font-size: 4rem;
            letter-spacing: 5px;
            margin-bottom: 10px;
            animation: zoomIn 2s ease-in-out infinite alternate;
        }

        .subtext {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        @keyframes zoomIn {
            0% {
                transform: scale(1);
                color: #fff;
            }
            100% {
                transform: scale(1.1);
                color: #FFD700;
            }
        }

        .colorful-text {
            display: inline-block;
            font-size: 2.5rem;
            font-weight: bold;
            background-image: linear-gradient(45deg, #FF1493, #FFD700, #00FF7F, #1E90FF, #FF6347);
            -webkit-background-clip: text;
            color: transparent;
            animation: textColorShift 3s ease-in-out infinite;
        }

        @keyframes textColorShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .dashain-image {
            width: 100%;
            max-width: 600px;
            margin-top: 30px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.5);
            border-radius: 10px;
        }

        .footer {
            margin-top: 50px;
            font-size: 1rem;
            color: #fff;
        }

        .footer a {
            color: #FFD700;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>

    <div class="container">
        <h1 class="invite">You Are Invited!</h1>
        <p class="subtext">Celebrate Dashain with us in a joyous and colorful celebration.</p>

        <p class="colorful-text">By Aadarsh</p>

        <img class="dashain-image" src="https://images.unsplash.com/photo-1600047500745-1b18fc0286f3?ixlib=rb-4.0.3&auto=format&fit=crop&w=700&q=80" alt="Dashain Celebration">
        
        <div class="footer">
            <p>Let's rejoice together in the happiness and prosperity of Dashain.</p>
            <p><a href="#">RSVP Here</a></p>
        </div>
    </div>

</body>
</html>
