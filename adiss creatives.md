<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adiss Creatives - Graphic Designer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #FFD700;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            color: #FFD700;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            color: #FFD700;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .portfolio {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .portfolio-item {
            background-color: #222;
            border: 2px solid #FFD700;
            margin: 15px;
            padding: 20px;
            width: 300px;
        }
        .portfolio-item img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #111;
            color: #FFD700;
            padding: 20px;
            text-align: center;
        }
        footer a {
            color: #FFD700;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Adiss Creatives</h1>
        <p>Graphic Designer | Illustrator</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Adiss Creatives, a passionate graphic designer with a love for drawing and creative expression. I specialize in logo design, video editing, and illustration. Welcome to my portfolio!</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Portfolio Item 1">
                <p>Project 1: Logo Design</p>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Portfolio Item 2">
                <p>Project 2: Social Media Design</p>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/300" alt="Portfolio Item 3">
                <p>Project 3: Illustration</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>If you'd like to work with me or have any questions, feel free to reach out!</p>
        <p>Email: <a href="mailto:adiss@example.com">adiss@example.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Adiss Creatives. All rights reserved.</p>
    </footer>

</body>
</html>
