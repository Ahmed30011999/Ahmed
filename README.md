<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ISA - Ingenieur- und Sachverständigenbüro Aref</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px 10%;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
            margin-top: 5px;
        }
        nav {
            text-align: center;
            background-color: #ffd700;
            padding: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #000;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 50px 10%;
        }
        .hero {
            text-align: center;
            background: #fff;
            padding: 50px 10%;
            border-bottom: 5px solid #ffd700;
        }
        .hero h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.2em;
            line-height: 1.6;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .service {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            flex: 1;
            min-width: 250px;
            padding: 20px;
            text-align: center;
        }
        .service h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .contact {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            border: 1px solid #ddd;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        .contact input, .contact textarea, .contact button {
            padding: 10px;
            font-size: 1em;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact button {
            background: #ffd700;
            border: none;
            cursor: pointer;
        }
        .contact button:hover {
            background: #e5c200;
        }
        footer {
            text-align: center;
            background: #000;
            color: #fff;
            padding: 20px 10%;
        }
    </style>
</head>
<body>
    <header>
        <h1>ISA - Ingenieur- und Sachverständigenbüro Aref</h1>
        <p>Ihr Partner für professionelle Kfz-Gutachten und technische Expertise</p>
    </header>
    <nav>
        <a href="#about">Über uns</a>
        <a href="#services">Leistungen</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <section id="about" class="hero">
        <h2>Über uns</h2>
        <p>Das Ingenieur- und Sachverständigenbüro Aref bietet Ihnen umfassende Expertise im Bereich Kfz-Gutachten. Unser erfahrenes Team steht Ihnen mit modernster Technik und fundiertem Wissen zur Seite, um Ihre Anliegen schnell und professionell zu bearbeiten.</p>
    </section>
    <section id="services">
        <h2>Unsere Leistungen</h2>
        <div class="services">
            <div class="service">
                <h3>Kfz-Schadensgutachten</h3>
                <p>Professionelle Begutachtung und Dokumentation von Unfallschäden.</p>
            </div>
            <div class="service">
                <h3>Wertgutachten</h3>
                <p>Ermittlung des Fahrzeugwertes für Käufer, Verkäufer oder Versicherungen.</p>
            </div>
            <div class="service">
                <h3>Unfallanalysen</h3>
                <p>Technische Analyse und Rekonstruktion von Verkehrsunfällen.</p>
            </div>
            <div class="service">
                <h3>Beweissicherung</h3>
                <p>Sichern von technischen Beweisen bei Streitfällen oder Gutachten.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Kontakt</h2>
        <div class="contact">
            <form>
                <input type="text" placeholder="Ihr Name" required>
                <input type="email" placeholder="Ihre E-Mail-Adresse" required>
                <textarea placeholder="Ihre Nachricht" rows="5" required></textarea>
                <button type="submit">Nachricht senden</button>
            </form>
        </div>
    </section>
    <footer>
        <p>© 2024 ISA - Ingenieur- und Sachverständigenbüro Aref. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
