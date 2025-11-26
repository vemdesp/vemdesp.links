# vemdesp.links
Assessoria de compras em geral · SP Você pede, nos resolvemos. vemdesp
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>vemdesp - Links</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #f5f5dc 0%, #e8e4d0 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            max-width: 680px;
            width: 100%;
            text-align: center;
        }

        .profile {
            margin-bottom: 30px;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #4a5d3f;
            margin: 0 auto 20px;
            background: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 48px;
            color: #4a5d3f;
            font-weight: bold;
        }

        .profile h1 {
            color: #4a5d3f;
            font-size: 32px;
            margin-bottom: 10px;
            font-weight: 600;
        }

        .profile p {
            color: #5a6d4f;
            font-size: 16px;
            line-height: 1.5;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .link-button {
            background: white;
            color: #4a5d3f;
            text-decoration: none;
            padding: 18px 24px;
            border-radius: 12px;
            font-size: 16px;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 2px solid #4a5d3f;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .link-button:hover {
            background: #4a5d3f;
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(74, 93, 63, 0.3);
        }

        .link-button:active {
            transform: translateY(0);
        }

        .icon {
            font-size: 20px;
        }

        footer {
            margin-top: 40px;
            color: #5a6d4f;
            font-size: 14px;
        }

        @media (max-width: 480px) {
            .profile h1 {
                font-size: 28px;
            }

            .link-button {
                padding: 16px 20px;
                font-size: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <div class="profile-img">🛍️</div>
            <h1>vemdesp</h1>
            <p>Assessoria em compras em geral · SP<br>Você pede, eu resolvo.</p>
        </div>

        <div class="links">
            <a href="https://wa.me/551193554547" class="link-button" target="_blank">
                <span class="icon">💬</span>
                <span>WhatsApp - Faça seu pedido</span>
            </a>

            <a href="https://instagram.com/vemdesp" class="link-button" target="_blank">
                <span class="icon">📸</span>
                <span>Instagram</span>
            </a>

            <a href="mailto:vemdesp@gmail.com" class="link-button">
                <span class="icon">📧</span>
                <span>E-mail</span>
            </a>

            <a href="#" class="link-button">
                <span class="icon">📋</span>
                <span>Como funciona</span>
            </a>

            <a href="#" class="link-button">
                <span class="icon">⭐</span>
                <span>Depoimentos</span>
            </a>
        </div>

        <footer>
            <p>© 2025 vemdesp · São Paulo</p>
        </footer>
    </div>
</body>
</html>
