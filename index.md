<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #333;
            padding: 20px;
            text-align: center;
        }
        .btn {
            background-color: #4CAF50;
            border: none;
            color: white;
            padding: 15px 32px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
        }
        main {
            flex: 1;
            padding: 20px;
        }
        .language-icons {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .language-icons img {
            width: 50px;
            height: 50px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <button class="btn">Home</button>
        <button class="btn">About</button>
        <button class="btn">Projects</button>
        <button class="btn">Contact</button>
    </header>

    <main>
        <h1>Welcome to My Portfolio</h1>
        <p>This is a wall of text describing my skills, experience, and projects. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor, nunc id aliquam tincidunt, nisl nunc tincidunt nunc, vitae aliquam nunc nunc vitae nunc. Sed euismod, nunc id aliquam tincidunt, nisl nunc tincidunt nunc, vitae aliquam nunc nunc vitae nunc.</p>
        
        <div class="language-icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
        </div>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
