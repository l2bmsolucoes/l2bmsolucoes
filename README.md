<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Landing page de exemplo para captura de leads">
    <title>Minha Landing Page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
        }

        header {
            background-color: #3498db;
            color: white;
            text-align: center;
            padding: 50px;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .cta {
            text-align: center;
            margin: 40px 0;
        }

        .cta h2 {
            font-size: 28px;
        }

        .cta p {
            font-size: 18px;
            color: #555;
        }

        .cta form input[type="email"] {
            padding: 12px;
            font-size: 16px;
            width: 300px;
            margin-right: 10px;
            border: 2px solid #ccc;
            border-radius: 4px;
        }

        .cta form button {
            padding: 12px 20px;
            font-size: 16px;
            background-color: #e74c3c;
            border: none;
            color: white;
            cursor: pointer;
            border-radius: 4px;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 14px;
        }

    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo à Nossa Página de Ofertas!</h1>
        <p>Receba as melhores promoções diretamente no seu e-mail</p>
    </header>

    <div class="container">
        <section class="cta">
            <h2>Inscreva-se para Receber Novidades</h2>
            <p>Se inscreva na nossa lista e seja o primeiro a saber sobre nossos lançamentos e promoções especiais.</p>
            <form action="https://seuservidor.com/inscricao" method="POST">
                <input type="email" name="email" placeholder="Digite seu e-mail" required>
                <button type="submit">Inscrever-se</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Sua Empresa - Todos os direitos reservados</p>
    </footer>
</body>
</html>
