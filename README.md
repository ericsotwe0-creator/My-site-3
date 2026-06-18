<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anime World</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #0f172a;
    color: white;
}

header {
    background: linear-gradient(90deg, #ff004f, #6a00ff);
    padding: 15px;
    text-align: center;
    font-size: 24px;
    font-weight: bold;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #1e293b;
    padding: 10px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

nav a:hover {
    color: #ff004f;
}

.hero {
    text-align: center;
    padding: 40px;
}

.hero h1 {
    font-size: 40px;
}

.anime-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background-color: #1e293b;
    margin: 15px;
    padding: 15px;
    border-radius: 10px;
    width: 200px;
    text-align: center;
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #020617;
    margin-top: 20px;
}
</style>
</head>

<body>

<header>🔥 Anime World 🔥</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Popular</a>
    <a href="#">Genres</a>
    <a href="#">Contact</a>
</nav>

<div class="hero">
    <h1>Welcome to Anime World</h1>
    <p>Explore your favorite anime shows!</p>
</div>

<div class="anime-container">

    <div class="card">
        <img src="https://via.placeholder.com/200x300" alt="Naruto">
        <h3>Naruto</h3>
        <p>Ninja adventures and epic battles.</p>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/200x300" alt="Attack on Titan">
        <h3>Attack on Titan</h3>
        <p>Humanity vs giant Titans.</p>
    </div>

    <div class="card">
        <img src="https://via.placeholder.com/200x300" alt="Demon Slayer">
        <h3>Demon Slayer</h3>
        <p>A journey to defeat demons.</p>
    </div>

</div>

<footer>
    © 2026 Anime World | Made by You 💻
</footer>

</body>
</html># My-site-3
