<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Шешорська гімназія імені В'ячеслава Чорновола</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #72aae3;
            color: #333;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 30px 0;
        }
        h1 {
            font-size: 36px;
            text-align: center;
            color: #2d3a3f;
            margin-bottom: 20px;
        }
        .school-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }
        .school-image {
            width: 100%;
            max-width: 500px;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .school-image:hover {
            transform: scale(1.05);
        }
        .info-card {
            background-color: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            width: 100%;
            flex-grow: 1;
        }
        .info-card h2 {
            font-size: 28px;
            color: #020c10;
            margin-bottom: 20px;
        }
        .info-card p {
            font-size: 16px;
            line-height: 1.6;
            color: #555;
        }
        .info-card p strong {
            color: #2d3a3f;
        }
        .footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            background-color: #2d3a3f;
            color: #fff;
            border-top: 5px solid #f9a825;
        }
        @media (max-width: 768px) {
            .school-info {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Шешорська гімназія імені В'ячеслава Чорновола</h1>
    
    <div class="school-info">
        <!-- Фото школи -->
        <img src="IMG_20191017_112903.jpeg" alt="Шешорська гімназія" class="school-image">
        
        <!-- Інформаційна картка -->
        <div class="info-card">
            <h2>Про школу</h2>
            <p>Шешорська гімназія імені В'ячеслава Чорновола – це навчальний заклад, який поєднує сучасний підхід до навчання та глибоке шанування національних традицій. Ми надаємо учням високоякісну освіту, що включає різноманітні академічні програми, а також курси з мистецтва, спорту та розвитку лідерських якостей.</p>
            <p><strong>Місія школи</strong> – сформувати активних громадян, які готові змінювати світ на краще, поважають своє коріння та мають широкі знання і навички для успішного життя.</p>
        </div>
    </div>
</div>

<div class="footer">
    <p>&copy; 2024 Шешорська гімназія імені В'ячеслава Чорновола | Всі права захищені</p>
</div>

</body>
</html>
