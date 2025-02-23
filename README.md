# test.github.io
<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tekstovi Pesama</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Tekstovi Pesama</h1>
        <input type="text" id="searchBar" placeholder="Pretraži pesme..." onkeyup="searchSongs()">
    </header>

    <nav>
        <a href="#">Početna</a>
        <a href="#">Najnoviji Tekstovi</a>
        <a href="#">Dodaj Tekst</a>
        <a href="#">O Nama</a>
        <a href="#">Kontakt</a>
    </nav>

    <div class="container">
        <h2>Lista Tekstova</h2>
        <ul id="songList">
            <li><strong>Bajaga</strong> - Moji drugovi</li>
            <li><strong>Parni Valjak</strong> - Sve još miriše na nju</li>
            <li><strong>Riblja Čorba</strong> - Lutka sa naslovne strane</li>
            <li><strong>Azra</strong> - Balkan</li>
            <li><strong>Željko Joksimović</strong> - Lane moje</li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2025 Tekstovi Pesama. Sva prava pridržana.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f8f8;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

#searchBar {
    width: 60%;
    padding: 10px;
    margin-top: 10px;
    font-size: 16px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

nav {
    background-color: #444;
    overflow: hidden;
    text-align: center;
    padding: 10px 0;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    display: inline-block;
}

nav a:hover {
    background-color: #666;
}

.container {
    width: 80%;
    margin: 20px auto;
    background: white;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    border-radius: 5px;
}

h2 {
    text-align: center;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background: #f4f4f4;
    margin: 5px 0;
    padding: 10px;
    border: 1px solid #ddd;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

