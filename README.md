# Meu-projeto-alura
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Projeto Alura</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
            background-color: #f0f0f0;
        }

        h1 {
            color: #333;
        }

        p {
            color: #666;
            font-size: 18px;
        }

        img {
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }

        button {
            margin-top: 30px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Bem-vindo ao meu projeto!</h1>
    <p>Este é um projeto simples para a atividade da Alura.</p>
    <img src="https://placekitten.com/300/200" alt="Gatinho fofo">

    <br>

    <button onclick="mostrarMensagem()">Clique aqui!</button>

    <script>
        function mostrarMensagem() {
            alert("Obrigado por visitar meu projeto!");
        }
    </script>
</body>
</html>
