<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>約吃飯 App</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #f8f9fa;
            text-align: center;
            padding: 50px 20px;
            color: #333;
        }
        h1 {
            color: #ff6b6b;
            font-size: 36px;
            margin-bottom: 10px;
        }
        p {
            color: #666;
            font-size: 18px;
            margin-bottom: 40px;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            max-width: 400px;
            margin: 0 auto;
        }
        button {
            background-color: #ff6b6b;
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 18px;
            border-radius: 30px;
            cursor: pointer;
            transition: 0.3s;
            width: 100%;
        }
        button:hover {
            background-color: #fa5252;
        }
        .input-group {
            margin-bottom: 20px;
            text-align: left;
        }
        input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-sizing: border-box;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <h1>約吃飯 App 🍽️</h1>
    <p>解決群組約時間的各種痛點</p >

    <div class="card">
        <div class="input-group">
            <label>活動名稱</label>
            <input type="text" placeholder="例如：期末慶功宴">
        </div>
        <div class="input-group">
            <label>預算限制</label>
            <input type="text" placeholder="例如：每人 500 元">
        </div>
        <button onclick="alert('系統已產生邀請連結！請複製並貼到 LINE 群組！')">
            產生邀請連結 🚀
        </button>
    </div>
</body>
</html>
