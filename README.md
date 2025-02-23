# test.github.io
<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wedding Contact Form</title>
    <script src="https://www.google.com/recaptcha/api.js" async defer></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 50%;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            margin-top: 50px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        input, select, button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #ff66b2;
            color: white;
            cursor: pointer;
            border: none;
        }
        button:hover {
            background-color: #e65c9c;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Wedding Contact Form</h2>
    <form action="submit_wedding.php" method="POST">
        <label for="name">Ime i Prezime:</label>
        <input type="text" id="name" name="name" required>

        <label for="location">Lokacija:</label>
        <input type="text" id="location" name="location" required>

        <label for="date">Datum:</label>
        <input type="date" id="date" name="date" required>

        <label for="guests">Broj ljudi:</label>
        <input type="number" id="guests" name="guests" required min="1">

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <div class="g-recaptcha" data-sitekey="TVOJ_RECAPTCHA_SITE_KEY"></div>

        <button type="submit">Pošalji</button>
    </form>
</div>

</body>
</html>
