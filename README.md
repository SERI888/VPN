# VPN<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VPN Client</title>
</head>
<body>
    <h1>VPN Client</h1>
    <label for="serverInput">VPN Server:</label>
    <input type="text" id="serverInput" placeholder="Enter VPN server address">

    <label for="usernameInput">Username:</label>
    <input type="text" id="usernameInput" placeholder="Enter your username">

    <label for="passwordInput">Password:</label>
    <input type="password" id="passwordInput" placeholder="Enter your password">

    <button onclick="connectVPN()">Connect</button>

    <script>
        function connectVPN() {
            var serverAddress = document.getElementById('serverInput').value;
            var username = document.getElementById('usernameInput').value;
            var password = document.getElementById('passwordInput').value;

            // 这里可以添加实际连接VPN服务器的逻辑，可能需要使用Ajax请求或其他方式
            // 例如，你可能会使用WebSocket或HTTP请求与后端进行通信

            // 示例：使用console.log输出连接信息
            console.log('Connecting to VPN server:', serverAddress);
            console.log('Username:', username);
            console.log('Password:', password);
            
            // 此处缺少实际连接VPN服务器的代码，需要根据具体情况实现
        }
    </script>
</body>
</html>
