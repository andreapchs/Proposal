# Proposal
Proposal for your crush etc!!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Little Something for You</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif; /* A cute and friendly font */
            background-color: #fce4ec; /* Light pink background */
            color: #4a148c; /* Deep purple text */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }
        .container {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            text-align: center;
            position: relative;
        }
        .heart {
            color: #e91e63; /* Pink heart color */
            font-size: 50px;
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
            animation: pulse 1.5s infinite;
        }
        h1 {
            color: #e91e63;
            font-size: 3em;
            margin-top: 20px;
            margin-bottom: 10px;
        }
        p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 20px 0;
        }
        .signature {
            margin-top: 30px;
            font-style: italic;
            font-weight: bold;
            color: #880e4f;
        }
        .button-link {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background-color: #ff80ab; /* Bright pink button */
            color: white;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: transform 0.3s ease;
        }
        .button-link:hover {
            transform: scale(1.1);
        }
        @keyframes pulse {
            0% { transform: translateX(-50%) scale(1); }
            50% { transform: translateX(-50%) scale(1.1); }
            100% { transform: translateX(-50%) scale(1); }
        }
    </style>
</head>
<body>

<div class="container">
    <span class="heart">💖</span>
    <h1>For You</h1>
    <p>
        Hi there! I wanted to send this to you because... well, I really enjoy our chats. 
        Every time we talk, I find myself smiling a little more than usual. 
        You have a way of making my day a whole lot brighter.
    </p>
    <p>
        Thinking about you is easy, and I just wanted you to know that you're on my mind. 
        I think you're pretty amazing, and I’d love to get to know you even better, if you'd be open to it.
    </p>
    <p>
        No pressure at all, just wanted to let you know how I feel.
    </p>
    <p class="signature">
        — Someone who thinks you're great
    </p>
    <a href="#" class="button-link">Click Me!</a>
</div>

</body>
</html>
