<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Розыгрыш РОЗЫ | Мой ТГК</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            min-height: 100vh;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            max-width: 700px;
            width: 100%;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 40px 30px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
            animation: fadeIn 0.8s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .logo {
            text-align: center;
            font-size: 60px;
            margin-bottom: 10px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        h1 {
            text-align: center;
            font-size: 32px;
            margin-bottom: 8px;
            background: linear-gradient(90deg, #ff6b6b, #feca57, #ff6b6b);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shine 3s linear infinite;
        }

        @keyframes shine {
            to { background-position: 200% center; }
        }

        .subtitle {
            text-align: center;
            color: #b0b0d0;
            margin-bottom: 30px;
            font-size: 15px;
        }

        .prize-box {
            background: linear-gradient(135deg, rgba(255, 215, 0, 0.15), rgba(255, 107, 107, 0.15));
            border: 1px solid rgba(255, 215, 0, 0.3);
            border-radius: 16px;
            padding: 25px;
            text-align: center;
            margin-bottom: 25px;
        }

        .prize-box .prize-icon {
            font-size: 50px;
            margin-bottom: 10px;
        }

        .prize-box h2 {
            color: #feca57;
            font-size: 22px;
            margin-bottom: 8px;
        }

        .prize-box p {
            color: #ddd;
            font-size: 15px;
        }

        .deadline {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            background: rgba(255, 71, 87, 0.15);
            border: 1px solid rgba(255, 71, 87, 0.4);
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 25px;
            font-size: 16px;
        }

        .deadline strong {
            color: #ff6b6b;
        }

        .steps-title {
            font-size: 20px;
            margin-bottom: 15px;
            text-align: center;
            color: #fff;
        }

        .step {
            display: flex;
            align-items: flex-start;
            gap: 15px;
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 14px;
            padding: 18px;
            margin-bottom: 12px;
            transition: transform 0.2s, border-color 0.2s;
        }

        .step:hover {
            transform: translateX(5px);
            border-color: rgba(254, 202, 87, 0.5);
        }

        .step-number {
            flex-shrink: 0;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            background: linear-gradient(135deg, #ff6b6b, #feca57);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 16px;
            color: #1a1a2e;
        }

        .step-text {
            font-size: 15px;
            line-height: 1.5;
            color: #e0e0e0;
        }

        .step-text b {
            color: #feca57;
        }

        .btn {
            display: block;
            width: 100%;
            text-align: center;
            padding: 18px;
            border-radius: 14px;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            margin-top: 15px;
            transition: transform 0.2s, box-shadow 0.2s;
        }

        .btn-tg {
            background: linear-gradient(135deg, #229ED9, #0088cc);
            color: #fff;
            box-shadow: 0 8px 25px rgba(0, 136, 204, 0.4);
        }

        .btn-tg:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 30px rgba(0, 136, 204, 0.6);
        }

        .btn-admin {
            background: linear-gradient(135deg, #ff6b6b, #ee5a6f);
            color: #fff;
            box-shadow: 0 8px 25px rgba(238, 90, 111, 0.4);
        }

        .btn-admin:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 30px rgba(238, 90, 111, 0.6);
        }

        .rules {
            margin-top: 25px;
            padding: 18px;
            background: rgba(255, 255, 255, 0.03);
            border-left: 3px solid #feca57;
            border-radius: 10px;
            font-size: 14px;
            color: #b0b0d0;
            line-height: 1.6;
        }

        .rules b {
            color: #fff;
        }

        .footer {
            text-align: center;
            margin-top: 25px;
            font-size: 13px;
            color: #666;
        }

        @media (max-width: 480px) {
            .container { padding: 25px 18px; }
            h1 { font-size: 24px; }
            .logo { font-size: 45px; }
            .btn { font-size: 16px; padding: 15px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">🎁</div>
        <h1>РОЗЫГРЫШ РОЗЫ</h1>
        <p class="subtitle">Внутрителеграмный подарок за 25 ⭐</p>

        <div class="prize-box">
            <div class="prize-icon">🌹</div>
            <h2>Приз: РОЗА</h2>
            <p>Внутрителеграмный подарок стоимостью 25 звёзд</p>
        </div>

        <div class="deadline">
            ⏰ <span>Розыгрыш до <strong>11.11.2026</strong></span>
        </div>

        <h3 class="steps-title">📋 Условия участия</h3>

        <div class="step">
            <div class="step-number">1</div>
            <div class="step-text">Пригласи <b>15 человек</b> в мой Telegram-канал</div>
        </div>

        <div class="step">
            <div class="step-number">2</div>
            <div class="step-text">Отправь мне <b>@maratik_hall666</b> юзернеймы или никнеймы всех приглашённых</div>
        </div>

        <div class="step">
            <div class="step-number">3</div>
            <div class="step-text">Я проверю, что все <b>подписались</b> — и выдам тебе РОЗУ 🌹</div>
        </div>

        <a href="https://t.me/maratik_hall666" class="btn btn-admin">✍️ Написать мне в Telegram</a>

        <div class="rules">
            <b>⚠️ Важно:</b> приглашённые должны быть реальными подписчиками. Нарушение условий — дисквалификация. Победитель получает РОЗУ (подарок за 25 ⭐) сразу после проверки.
        </div>

        <div class="footer">Розыгрыш проводит @maratik_hall666</div>
    </div>
</body>
</html>
