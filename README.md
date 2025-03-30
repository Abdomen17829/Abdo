[Uploading <!DOCTYPE html><html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إلى مس هالة</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
        }
        .card {
            width: 300px;
            height: 150px;
            background-color: #ff4d4d;
            color: white;
            text-align: center;
            line-height: 150px;
            font-size: 20px;
            font-weight: bold;
            border-radius: 10px;
            cursor: pointer;
            transition: 0.3s;
        }
        .card:hover {
            background-color: #ff3333;
        }
        .message {
            display: none;
            text-align: center;
            font-size: 18px;
            margin-top: 20px;
        }
        .heart {
            color: red;
            font-size: 40px;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }
    </style>
</head>
<body>
    <div class="card" onclick="showMessage()">إلى مس هالة</div>
    <div class="message" id="message">
        <p>كل عام وأنتِ بخير Miss هالة! 🎉🎊<br>أتمنى لك عيد سعيد مليء بالفرح والسعادة! 😊</p>
        <div class="heart">❤️</div>
    </div><script>
    function showMessage() {
        document.querySelector('.card').style.display = 'none';
        document.getElementById('message').style.display = 'block';
    }
</script>

</body>
</html>untile .html…]()
