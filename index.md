<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rainbow Button</title>
    <style>
        .rainbow-button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #f0f0f0;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .rainbow-button:focus {
            outline: none;
            animation: rainbow 2s linear infinite;
        }

        @keyframes rainbow {
            0% { background-color: red; }
            14% { background-color: orange; }
            28% { background-color: yellow; }
            42% { background-color: green; }
            57% { background-color: blue; }
            71% { background-color: indigo; }
            85% { background-color: violet; }
            100% { background-color: red; }
        }
    </style>
</head>
<body>
    <button class="rainbow-button">Click me!</button>
</body>
</html>
