# index.HTML
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моё био</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #0f0c29, #302b63, #24243e);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }
        .card {
            background: rgba(255,255,255,0.08);
            backdrop-filter: blur(15px);
            border-radius: 24px;
            padding: 40px 25px;
            width: 90%;
            max-width: 400px;
            border: 1px solid rgba(255,255,255,0.15);
        }
        .avatar {
            width: 90px;
            height: 90px;
            border-radius: 50%;
            background: linear-gradient(135deg, #f093fb, #f5576c);
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
        }
        h1 { font-size: 1.8rem; margin-bottom: 8px; }
        p { opacity: 0.8; margin-bottom: 20px; line-height: 1.5; }
        .btn {
            display: inline-block;
            padding: 12px 30px;
            background: #f5576c;
            color: #fff;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin: 5px;
        }
        .btn.outline {
            background: transparent;
            border: 2px solid #f5576c;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="avatar">👤</div>
        <h1>Артём В.</h1>
        <p>Привет! Это моя страница-визитка, опубликованная прямо с телефона.</p>
        <a class="btn" href="#">Мои проекты</a>
        <a class="btn outline" href="#">Связаться</a>
    </div>
</body>
</html>
