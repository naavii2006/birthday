<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday!</title>
  <style>
    body {
      background-color: #ffebf0;
      color: #d6336c;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
    }

    p {
      font-size: 1.5em;
      margin-bottom: 1em;
    }

    .emoji {
      font-size: 3em;
      animation: bounce 1s infinite;
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
  </style>
</head>
<body>
  <div>
    <div class="emoji">🎉🎂🥳</div>
    <h1>Happy Birthday!</h1>
    <p>Wishing you joy, love, and lots of cake!</p>
    <div class="emoji">🎈🎁🎊</div>
  </div>
</body>
</html>

