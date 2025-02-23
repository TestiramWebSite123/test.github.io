# test.github.io

<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Esplanade-like Page</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script> <!-- Font Awesome ikone -->
</head>
<body>

    <!-- Video u pozadini -->
    <div class="video-background">
        <video autoplay muted loop id="bg-video">
            <source src="your-video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>

    <!-- Logo u levom kutu -->
    <div class="logo">
        <img src="logo.png" alt="Logo" />
    </div>

    <!-- Linkovi za društvene mreže u desnom kutu -->
    <div class="social-links">
        <a href="https://www.facebook.com" target="_blank" class="social-icon"><i class="fab fa-facebook"></i></a>
        <a href="https://www.tiktok.com" target="_blank" class="social-icon"><i class="fab fa-tiktok"></i></a>
        <a href="mailto:contact@example.com" class="social-icon"><i class="fas fa-envelope"></i></a>
    </div>

</body>
</html>
/* Globalna podešavanja */
body, html {
    margin: 0;
    padding: 0;
    height: 100%;
    font-family: Arial, sans-serif;
}

/* Video u pozadini */
.video-background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
    z-index: -1; /* Stavite video u pozadinu */
}

#bg-video {
    width: 100%;
    height: 100%;
    object-fit: cover; /* Omogućava video da popuni celu pozadinu */
}

/* Logo u levom kutu */
.logo {
    position: absolute;
    top: 20px;
    left: 20px;
    z-index: 10; /* Uverite se da logo bude iznad videa */
}

.logo img {
    width: 150px;
    height: auto;
}

/* Linkovi za društvene mreže */
.social-links {
    position: absolute;
    top: 50%;
    right: 20px;
    transform: translateY(-50%);
    z-index: 10; /* Uverite se da linkovi budu iznad videa */
}

.social-icon {
    display: block;
    margin: 10px 0;
    font-size: 24px;
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

.social-icon:hover {
    color: #ff7f00; /* Promeni boju kad pređeš mišem */
}

.social-icon i {
    font-size: 30px;
}
