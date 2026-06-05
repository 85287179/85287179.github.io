<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title> </title>
    <style>
        body {
            background: black;
            color: #0f0;
            font-family: monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        form {
            text-align: center;
        }
        input {
            background: #111;
            border: 1px solid #0f0;
            color: #0f0;
            padding: 10px;
            font-size: 16px;
            font-family: monospace;
            width: 250px;
            margin-bottom: 15px;
            display: block;
        }
        button {
            background: #0f0;
            border: none;
            color: black;
            padding: 10px 20px;
            font-size: 16px;
            font-family: monospace;
            cursor: pointer;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <form action="https://api.web3forms.com/submit" method="POST">
        <input type="hidden" name="access_key" value="8b682941-c200-4497-b42e-86a501ca7a3d">
        <!-- ТОЛЬКО ПОЧТА -->
        <input type="email" name="email" placeholder=" " required>
        <button type="submit">Отправить</button>
    </form>
</body>
</html>
