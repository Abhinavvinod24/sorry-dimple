<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I'm Sorry, Dimple</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Georgia', serif;
            background-image: url('https://images.unsplash.com/photo-1499346030926-9a72daac6c63?auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
        }
        .container {
            text-align: center;
            padding: 30px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 20px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            max-width: 600px;
            animation: fadeIn 2s ease-in;
        }
        h1 {
            font-size: 4em;
            color: #ff6b6b;
            animation: bounce 1.5s infinite;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.5em;
            margin: 10px 0;
            line-height: 1.6;
            color: #fff;
        }
        .heart {
            color: #ff6b6b;
            font-size: 5em;
            margin: 20px 0;
            animation: heartbeat 1.5s infinite;
        }
        button {
            padding: 10px 20px;
            font-size: 1.2em;
            border: none;
            background-color: #ff6b6b;
            color: white;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #ff4b4b;
        }
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-20px); }
            60% { transform: translateY(-10px); }
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>I'm Sorry, Dimple</h1>
        <p>Please forgive me . I never meant to hurt you.</p>
        <p>You mean the world to me, and I want to make it right GOOD NIGHT🥰.</p>
        <div class="heart">❤️</div>
        <button onclick="showMessage()">Click here for a surprise!</button>
        <p id="surpriseMessage" style="display:none;">You're the best thing that ever happened to me!</p>
    </div>

    <script>
        // JavaScript to show surprise message
        function showMessage() {
            document.getElementById('surpriseMessage').style.display = 'block';
        }
    </script>
</body>
</html>
