# project.github.io
<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Moja jednoduchá stránka</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f7fb;
      color: #222;
<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moja One-Page Stránka</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255, 255, 255, 0.9);
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            z-index: 1000;
        }
        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }
        nav h1 {
            margin: 0;
            color: #667eea;
        }
        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin-left: 2rem;
        }
        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #667eea;
        }
        section {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        #uvod {
            background: url('https://via.placeholder.com/1200x600/667eea/ffffff?text=Vitajte') no-repeat center center/cover;
            color: white;
            text-align: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        #uvod h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        #uvod p {
            font-size: 1.5rem;
            margin-bottom: 2rem;
        }
        #uvod a {
            background: #764ba2;
            color: white;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        #uvod a:hover {
            background: #5a3d7a;
        }
        #o-mne, #sluzby, #kontakt {
            background: white;
            margin-top: 0;
        }
        #o-mne h2, #sluzby h2, #kontakt h2 {
            text-align: center;
            color: #667eea;
            margin-bottom: 2rem;
        }
        #o-mne p {
            text-align: center;
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto;
        }
        #sluzby .sluzba {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .sluzba-item {
            background: #f4f4f4;
            padding: 2rem;
            margin: 1rem;
            border-radius: 10px;
            text-align: center;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .sluzba-item:hover {
            transform: translateY(-10px);
        }
        .sluzba-item h3 {
            color: #667eea;
        }
        #kontakt form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
        }
        #kontakt input, #kontakt textarea {
            padding: 1rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        #kontakt button {
            padding: 1rem;
            background: #667eea;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }
        #kontakt button:hover {
            background: #5a3d7a;
        }
        footer {
            text-align: center;
            padding: 2rem;
            background: #333;
            color: white;
        }
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            nav ul li {
                margin: 0.5rem 0;
            }
            #uvod h1 {
                font-size: 2rem;
            }
            #uvod p {
                font-size: 1.2rem;
            }
            .sluzba-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <h1>Moja Stránka</h1>
            <ul>
                <li><a href="#uvod">Úvod</a></li>
                <li><a href="#o-mne">O mne</a></li>
                <li><a href="#sluzby">Služby</a></li>
                <li><a href="#kontakt">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <section id="uvod">
        <h1>Vitajte na mojej stránke</h1>
        <p>Objavte, čo ponúkam a kontaktujte ma.</p>
        <a href="#o-mne">Začnite objavovať</a>
    </section>

    <section id="o-mne">
        <h2>O mne</h2>
        <p>Som profesionál v oblasti [vaša oblasť]. Mám skúsenosti s [vaše skúsenosti]. Rád pomáham klientom dosiahnuť ich ciele.</p>
    </section>

    <section id="sluzby">
        <h2>Služby</h2>
        <div class="sluzba">
            <div class="sluzba-item">
                <h3>Služba 1</h3>
                <p>Popis prvej služby.</p>
            </div>
            <div class="sluzba-item">
                <h3>Služba 2</h3>
                <p>Popis druhej služby.</p>
            </div>
            <div class="sluzba-item">
                <h3>Služba 3</h3>
                <p>Popis tretej služby.</p>
            </div>
        </div>
    </section>

    <section id="kontakt">
        <h2>Kontakt</h2>
        <form action="#" method="post">
            <input type="text" name="meno" placeholder="Vaše meno" required>
            <input type="email" name="email" placeholder="Váš email" required>
            <textarea name="sprava" placeholder="Vaša správa" rows="5" required></textarea>
            <button type="submit">Odoslať</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Moja Stránka. Všetky práva vyhradené.</p>
    </footer>
</body>
</html>
