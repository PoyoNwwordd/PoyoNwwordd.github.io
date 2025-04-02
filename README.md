<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rickroll</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #333;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        h1 {
            font-size: 3rem;
            animation: blink 1.5s infinite;
        }
        @keyframes blink {
            0% { color: white; }
            50% { color: transparent; }
            100% { color: white; }
        }
    </style>
</head>
<body>
    <div>
        <h1>Você foi Rickrolled!</h1>
        <p>Redirecionando...</p>
        <script>
            setTimeout(function() {
                window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
            }, 3000);  // Redireciona após 3 segundos
        </script>
    </div>
</body>
</html>

