<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lyrics Finder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background: #222;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .search-box {
            margin-top: 10px;
        }
        input[type="text"] {
            width: 60%;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
        button {
            padding: 10px 15px;
            border: none;
            background: #ff6600;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        .song-list {
            list-style: none;
            padding: 0;
        }
        .song-list li {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        .song-list li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .footer {
            text-align: center;
            background: #222;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<div class="header">
    <h1>Lyrics Finder</h1>
    <div class="search-box">
        <input type="text" placeholder="Pretraži pesme ili izvođače...">
        <button>Pretraži</button>
    </div>
</div>

<div class="container">
    <h2>Popularne pesme</h2>
    <ul class="song-list">
        <li><a href="#">Imagine - John Lennon</a></li>
        <li><a href="#">Bohemian Rhapsody - Queen</a></li>
        <li><a href="#">Someone Like You - Adele</a></li>
        <li><a href="#">Shape of You - Ed Sheeran</a></li>
        <li><a href="#">Smells Like Teen Spirit - Nirvana</a></li>
    </ul>

    <h2>Top izvođači</h2>
    <ul class="song-list">
        <li><a href="#">The Beatles</a></li>
        <li><a href="#">Taylor Swift</a></li>
        <li><a href="#">Eminem</a></li>
        <li><a href="#">Beyoncé</a></li>
        <li><a href="#">Michael Jackson</a></li>
    </ul>
</div>

<div class="footer">
    <p>&copy; 2025 Lyrics Finder. Sva prava zadržana.</p>
</div>

</body>
</html>
