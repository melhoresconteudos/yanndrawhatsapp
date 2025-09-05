<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecionamento para WhatsApp</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #121212;
            color: white;
            font-family: Arial, sans-serif;
        }
        .message {
            font-size: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="message">
        Redirecionando para o WhatsApp...
    </div>

    <script>
        function randomizeTraffic() {
            const links = [
                "https://api.whatsapp.com/send?phone=554298558559&text=Bora%20se%20divertir%20Yanndra%20%3F",
                "https://api.whatsapp.com/send?phone=554298477669&text=Oi%20Yanndra%2C%20tudo%20bom%20%3F"
            ];

            // Gera um índice aleatório
            const randomIndex = Math.floor(Math.random() * links.length);

            // Redireciona para o link aleatório
            window.location.href = links[randomIndex];
        }

        // Chama a função após 2 segundos (para dar tempo de exibir a mensagem)
        setTimeout(randomizeTraffic, 2000);
    </script>
</body>
</html>
