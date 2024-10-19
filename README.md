<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feras site</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .game-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .game-box {
            width: 200px;
            height: 150px;
            background-color: #fff;
            border: 2px solid #ccc;
            border-radius: 8px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .game-box:hover {
            background-color: #e0e0e0;
        }
    </style>
</head>
<body>
    <h1>مرحبا بكم في موقع فراس </h1>
    <div class="game-container">
        <div class="game-box" onclick="window.location.href='snake game.html'">
            <h3>لعبة الثعبان</h3>
        </div>
        <div class="game-box" onclick="window.location.href='num.html'">
            <h3>لعبة تخمين الرقم </h3>
        </div>
        <div class="game-box" onclick="window.location.href='hh.html'">
            <h3>لعبة مدري وش اسميها</h3>
        </div>
        <!-- يمكنك إضافة المزيد من الألعاب هنا -->
    </div>
</body>
</html>
