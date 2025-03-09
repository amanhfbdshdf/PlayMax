<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PlayMax - Unlimited Movies & TV Shows</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: white;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background-color: #000;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: red;
        }
        .menu a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        .hero {
            height: 60vh;
            background: url('https://source.unsplash.com/1600x900/?movie') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }
        .hero button {
            padding: 15px 30px;
            font-size: 20px;
            background: red;
            border: none;
            color: white;
            cursor: pointer;
        }
        .movies {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .movie-card {
            width: 200px;
            margin: 10px;
            text-align: center;
        }
        .movie-card img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s;
        }
        .movie-card img:hover {
            transform: scale(1.1);
        }
        .download-link {
            margin-top: 10px;
        }
        .download-link a {
            color: yellow;
            text-decoration: none;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="logo">PlayMax</div>
        <div class="menu">
            <a href="#">Home</a>
            <a href="#">Movies</a>
            <a href="#">TV Shows</a>
            <a href="#">Categories</a>
        </div>
    </div>
    <div class="hero">
        <h1>Welcome to PlayMax</h1>
        <p>Unlimited Movies, TV Shows & More</p>
        <button>Start Watching</button>
    </div>
    <div class="movies">
        <div class="movie-card">
            <img src="https://source.unsplash.com/200x300/?action-movie" alt="Movie 1">
            <p>Action Movie</p>
            <div class="download-link"><a href="#">Download</a></div>
        </div>
        <div class="movie-card">
            <img src="https://source.unsplash.com/200x300/?horror-movie" alt="Movie 2">
            <p>Horror Movie</p>
            <div class="download-link"><a href="#">Download</a></div>
        </div>
        <div class="movie-card">
            <img src="https://source.unsplash.com/200x300/?comedy-movie" alt="Movie 3">
            <p>Comedy Movie</p>
            <div class="download-link"><a href="#">Download</a></div>
        </div>
    </div>
</body>
</html>
