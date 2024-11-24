<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Abdulla Abdukulov</title>
</head>
<body>
  <svg fill="none" viewBox="0 0 800 100" width="800" height="100" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
      <div xmlns="http://www.w3.org/1999/xhtml">
        <style>
          @keyframes gradientText {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
          }
          .snowflake {
            font-size: 1.5em;
            font-family: Arial;
            text-shadow: 0 0 1px #000;
          }
          h1 {
            font-family: 'Inter', sans-serif;
            margin: 0;
            font-size: 4em;
            font-weight: 900;
            letter-spacing: -.05em;
            text-align: center;
            background: linear-gradient(270deg, #f2f3f4, #000, #f2f3f4, #000);
            background-size: 400%;
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: gradientText 3s ease infinite;
          }
          @keyframes snowflakes-fall { 0% { top: -10%; } 100% { top: 100%; } }
          @keyframes snowflakes-shake {
            0% { transform: translateX(0px); }
            50% { transform: translateX(80px); }
            100% { transform: translateX(0px); }
          }
          .snowflake {
            position: fixed;
            top: -10%;
            animation: snowflakes-fall 10s linear infinite, snowflakes-shake 3s ease-in-out infinite;
          }
          .snowflake:nth-of-type(1) { left: 10%; animation-delay: 1s; }
          .snowflake:nth-of-type(2) { left: 20%; animation-delay: 6s; }
          .snowflake:nth-of-type(3) { left: 30%; animation-delay: 4s; }
          .snowflake:nth-of-type(4) { left: 40%; animation-delay: 2s; }
          .snowflake:nth-of-type(5) { left: 50%; animation-delay: 8s; }
          .snowflake:nth-of-type(6) { left: 60%; animation-delay: 6s; }
          .snowflake:nth-of-type(7) { left: 70%; animation-delay: 2.5s; }
          .snowflake:nth-of-type(8) { left: 80%; animation-delay: 1s; }
          .snowflake:nth-of-type(9) { left: 90%; animation-delay: 3s; }
        </style>
        <h1>Behruz Ikromiddinov</h1>
        <div class="snowflake">💻</div>
        <div class="snowflake">💰</div>
        <div class="snowflake">💻</div>
        <div class="snowflake">💰</div>
        <div class="snowflake">💻</div>
        <div class="snowflake">💰</div>
        <div class="snowflake">💻</div>
        <div class="snowflake">💰</div>
        <div class="snowflake">💻</div>
      </div>
    </foreignObject>
  </svg>
</body>
</html>
