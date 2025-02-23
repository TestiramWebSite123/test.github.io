# test.github.io

<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karaoke Request Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #222;
            color: white;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 50%;
            margin: auto;
            background: #333;
            padding: 20px;
            border-radius: 10px;
            margin-top: 50px;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: none;
            border-radius: 5px;
        }
        button {
            background-color: #ff5733;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background-color: #e74c3c;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Karaoke Request Form</h2>
    <form action="submit_request.php" method="POST">
        <label for="name">Vaše ime:</label>
        <input type="text" id="name" name="name" required>

        <label for="song">Naziv pjesme:</label>
        <input type="text" id="song" name="song" required>

        <label for="artist">Izvođač:</label>
        <input type="text" id="artist" name="artist" required>

        <label for="key">Željena tonalitet (opcionalno):</label>
        <select id="key" name="key">
            <option value="original">Original</option>
            <option value="viši">Viši</option>
            <option value="niži">Niži</option>
        </select>

        <button type="submit">Pošalji zahtjev</button>
    </form>
</div>

</body>
</html>
