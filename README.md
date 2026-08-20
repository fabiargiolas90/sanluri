<html lang="it">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homepage | Fabio Argiolas pagina</title>
    <style>
        /* Reset di base e impostazioni dello sfondo */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: white;
        }

        /* Contenitore principale */
        .container {
            width: 100%;
            max-width: 500px;
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            border: 1px solid rgba(255, 255, 255, 0.18);
            margin: 20px;
        }

        /* Profilo utente */
        .profile-img {
            width: 170px;
            object-fit: cover;
            margin-bottom: 20px;
        }

        h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        p {
            font-size: 16px;
            opacity: 0.9;
            margin-bottom: 30px;
        }

        /* Area pulsanti */
        .links {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .btn {
            background-color: white;
            color: #a24b4b;
            padding: 15px 20px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
            background-color: #a24b4b;
            color: white;
        }
    </style>
</head>

<body>
<div class="container">
<!-- Foto profilo (inserisci qui il link alla tua immagine) --> 
<img class="profile-img" src="/img/zero.png" alt="Foto Profilo" width="178" height="88" /> <!-- Lista dei bottoni per i link -->
<div class="links"><a class="btn" href="https://fabioargiolaspagina.altervista.org/newspaper.html" target="_blank" rel="noopener">Newspaper</a> <a class="btn" href="https://www.fabioargiolas.me/" target="_blank" rel="noopener">Sito Web</a> <a class="btn" href="https://www.facebook.com/fabioargiolas.paginapersonale" target="_blank" rel="noopener">Facebook</a> <a class="btn" href="https://www.instagram.com/fabiargiolas90" target="_blank" rel="noopener">Instagram</a> <a class="btn" href="mailto:web@fabioargiolas.me">Contattami</a></div>
</div>
</body>

</html>
