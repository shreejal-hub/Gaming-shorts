# Gaming-shorts
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Shorts Collection</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e1e;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333333;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            padding: 20px;
        }
        .category {
            margin-bottom: 40px;
        }
        .category h2 {
            border-bottom: 2px solid #444444;
            padding-bottom: 10px;
        }
        .shorts-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
        }
        .short-item {
            background-color: #292929;
            padding: 10px;
            border-radius: 8px;
            text-align: center;
        }
        .short-item img {
            max-width: 100%;
            border-radius: 8px;
        }
        .short-item p {
            margin: 10px 0 0;
            font-size: 1.1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Shorts Collection</h1>
    </header>
    <div class="container">
        <div class="category">
            <h2>Casual Shorts</h2>
            <div class="shorts-grid">
                <div class="short-item">
                    <img src="casual1.jpg" alt="Casual Short 1">
                    <p>Casual Short 1</p>
                </div>
                <div class="short-item">
                    <img src="casual2.jpg" alt="Casual Short 2">
                    <p>Casual Short 2</p>
                </div>
                <!-- Add more casual shorts as needed -->
            </div>
        </div>
        <div class="category">
            <h2>Sports Shorts</h2>
            <div class="shorts-grid">
                <div class="short-item">
                    <img src="sports1.jpg" alt="Sports Short 1">
                    <p>Sports Short 1</p>
                </div>
                <div class="short-item">
                    <img src="sports2.jpg" alt="Sports Short 2">
                    <p>Sports Short 2</p>
                </div>
                <!-- Add more sports shorts as needed -->
            </div>
        </div>
        <div class="category">
            <h2>Beach Shorts</h2>
            <div class="shorts-grid">
                <div class="short-item">
                    <img src="beach1.jpg" alt="Beach Short 1">
                    <p>Beach Short 1</p>
                </div>
                <div class="short-item">
                    <img src="beach2.jpg" alt="Beach Short 2">
                    <p>Beach Short 2</p>
                </div>
                <!-- Add more beach shorts as needed -->
            </div>
        </div>
    </div>
</body>
</html>
