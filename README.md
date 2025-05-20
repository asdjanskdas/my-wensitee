<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RefCoffe</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f1ee;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #6f4e37;
            color: white;
            padding: 30px;
            text-align: center;
        }
        nav {
            background-color: #a97458;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            padding: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #f0e6dc;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        section:nth-child(even) {
            background-color: #fff;
        }
        section:nth-child(odd) {
            background-color: #f8f4f0;
        }
        h2 {
            color: #6f4e37;
        }
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
        }
        .menu-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.05);
            text-align: center;
            font-size: 1.1em;
        }
        .gallery {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .gallery img {
            width: 200px;
            height: 140px;
            object-fit: cover;
            border-radius: 8px;
        }
        .quote {
            font-style: italic;
            text-align: center;
            margin: 30px auto;
            font-size: 1.2em;
            color: #555;
        }
        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #6f4e37;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #5a3d2d;
        }
        footer {
            background-color: #6f4e37;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <h1>RefCoffe</h1>
        <p>Locul unde poveștile prind gust!</p>
    </header>

    <nav>
        <a href="#despre">Despre</a>
        <a href="#meniu">Meniu</a>
        <a href="#club">Club literar</a>
        <a href="#galerie">Galerie</a>
    </nav>

    <section id="despre">
        <h2>Despre RefCoffe</h2>
        <p>RefCoffe este o oază urbană pentru cei care iubesc lectura și cafeaua. Îți oferim un spațiu primitor unde poți citi, studia sau socializa în timp ce savurezi o băutură caldă. Biblioteca noastră este deschisă tuturor clienților, iar atmosfera este creată special pentru liniște și inspirație.</p>
        <div class="quote">„O ceașcă de cafea și o carte bună pot schimba o zi întreagă.”</div>
    </section>

    <section id="meniu">
        <h2>Meniul nostru ☕🍰</h2>
        <div class="menu">
            <div class="menu-item">☕ Espresso</div>
            <div class="menu-item">☕ Cappuccino</div>
            <div class="menu-item">☕ Latte</div>
            <div class="menu-item">🍵 Ceai</div>
            <div class="menu-item">🧊 Ice Cafe</div>
            <div class="menu-item">🍋 Limonadă</div>
            <div class="menu-item">💧 Apă</div>
            <div class="menu-item">🥐 Croissant</div>
            <div class="menu-item">🍰 Cheesecake</div>
        </div>
    </section>

    <section id="club">
        <h2>Clubul literar RefCoffe 📚</h2>
        <p>Te invităm să faci parte dintr-o comunitate pasionată de cărți. Clubul nostru literar organizează întâlniri săptămânale unde discutăm autori, cărți și idei care ne inspiră. Indiferent dacă ești cititor începător sau veteran, ești binevenit!</p>
        <a href="#" class="btn">Înscrie-te în club</a>
    </section>

    <section id="galerie">
        <h2>Galerie foto</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/200x140?text=Bibliotecă" alt="Bibliotecă">
            <img src="https://via.placeholder.com/200x140?text=Cafenea" alt="Cafenea">
            <img src="https://via.placeholder.com/200x140?text=Club+literar" alt="Club literar">
        </div>
    </section>

    <footer>
        <p>&copy; 2025 RefCoffe. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
