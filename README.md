<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đăng nhập Facebook</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: #18191A;
            color: #E4E6EB;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .login-container {
            text-align: center;
            width: 90%;
            max-width: 400px;
        }
        .login-container img {
            width: 80px;
            margin-bottom: 20px;
        }
        .login-container input {
            width: 100%;
            padding: 12px;
            margin: 10px 0;
            border-radius: 8px;
            border: none;
            font-size: 16px;
        }
        .login-container input[type="text"],
        .login-container input[type="password"] {
            background: #3A3B3C;
            color: #E4E6EB;
        }
        .login-container button {
            width: 100%;
            padding: 12px;
            background: #1877F2;
            color: white;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }
        .login-container a {
            color: #2D88FF;
            text-decoration: none;
            display: block;
            margin: 10px 0;
        }
        .create-account {
            background: #42B72A;
        }
        .meta-logo {
            margin-top: 20px;
            font-size: 14px;
            color: #B0B3B8;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo">
        <input type="text" placeholder="Số di động hoặc email">
        <input type="password" placeholder="Mật khẩu">
        <button>Đăng nhập</button>
        <a href="#">Bạn quên mật khẩu ư?</a>
        <button class="create-account">Tạo tài khoản mới</button>
        <div class="meta-logo">© Meta</div>
    </div>
</body>
</html>
