<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shinwari Webpage - Download Apps</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">Shinwari Webpage</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Apps</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="app-section">
        <h2>Download Our Apps</h2>
        <div class="app-container">
            <div class="app">
                <img src="app1.c:\Users\Dawood Shinwari\Pictures\1200x630-bandicam-icon.png" alt="bandicam The best screen recorder">
                <h3>bandicam The best screen recorder</h3>
            
                <a href="https://www.bandicam.com/downloads/" class="download-button">Download</a>
            </div>
            <div class="app">
                <img src="app2.png" alt="Gta 5">
                <h3>Gta 5</h3>
                <a href="https://www.gta5app.mobi/" class="download-button">Download</a>
            </div>
            <div class="app">
                <img src="app3.png" alt="mancraft">
                <h3>mancraft</h3>
                <a href="https://play.google.com/store/apps/details?id=com.craftsman.go&hl=en" class="download-button">Download</a>
            </div>
            <!-- Add more apps as needed -->
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Shinwari Webpage. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
<style class="css">
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f00; /* Red color for header, you can change it */
    padding: 10px;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

.app-section {
    padding: 20px;
}

.app-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.app {
    width: calc(33.33% - 20px);
    margin-bottom: 20px;
    text-align: center;
}

.app img {
    width: 100%;
    max-width: 200px;
    margin-bottom: 10px;
}

.download-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    border: none;
    color: #fff;
    border-radius: 5px;
    text-decoration: none;
}

.download-button:hover {
    background-color: #0056b3;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}

</style>
</html>
