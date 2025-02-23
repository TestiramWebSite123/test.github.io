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

