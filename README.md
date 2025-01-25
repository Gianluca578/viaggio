<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Viaggio Senza Confini</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            font-size: 2.8rem;
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #222;
            padding: 1rem 0;
        }
        nav a {
            color: white;
            margin: 0 1.5rem;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #00f2fe;
        }
        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 65vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3.5rem;
        }
        .content {
            padding: 3rem 1.5rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .section {
            margin-bottom: 3rem;
        }
        .section h2 {
            font-size: 2.2rem;
            color: #4facfe;
            border-bottom: 3px solid #00f2fe;
            display: inline-block;
            margin-bottom: 1rem;
        }
        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            margin: 1.5rem 0;
            display: flex;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.03);
        }
        .card img {
            width: 200px;
            height: auto;
            object-fit: cover;
        }
        .card-content {
            padding: 1.5rem;
        }
        .card-content h3 {
            margin: 0 0 0.8rem;
            font-size: 1.6rem;
            color: #333;
        }
        .card-content a {
            text-decoration: none;
            color: #4facfe;
            font-weight: bold;
            transition: color 0.3s;
        }
        .card-content a:hover {
            color: #00f2fe;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 3rem;
        }
        footer p {
            margin: 0;
            font-size: 0.9rem;
        }
        form {
            background: white;
            border: 1px solid #ddd;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        form label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        form input, form textarea, form button {
            width: 100%;
            padding: 0.8rem;
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        form button {
            background: #4facfe;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.3s;
        }
        form button:hover {
            background: #00f2fe;
        }
    </style>
</head>
<body>
    <header>
        <h1>Viaggio Senza Confini</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#destinations">Destinazioni</a>
        <a href="#activities">Cosa Vedere e Fare</a>
        <a href="#tips">Consigli Pratici</a>
        <a href="#about">Chi Siamo</a>
        <a href="#contact">Contatti</a>
    </nav>
    <div class="hero">
        <h1>Dove vuoi andare?</h1>
    </div>
    <div class="content">
        <div id="home" class="section">
            <h2>Introduzione Generale</h2>
            <p>Benvenuti su "Viaggio Senza Confini", la tua guida per esplorare il mondo. Scopri le migliori destinazioni, consigli utili e attività imperdibili.</p>
        </div>
        <div id="destinations" class="section">
            <h2>Destinazioni</h2>
            <div class="card">
                <img src="https://via.placeholder.com/200" alt="Mykonos">
                <div class="card-content">
                    <h3>Mykonos</h3>
                    <p>Vivi la bellezza delle spiagge greche e la vita notturna vibrante.</p>
                    <a href="mykonos.html">Scopri di più</a>
                </div>
            </div>
            <div class="card">
                <img src="https://via.placeholder.com/200" alt="Tokyo">
                <div class="card-content">
                    <h3>Tokyo</h3>
                    <p>Esplora la fusione di tradizione e modernità.</p>
                    <a href="tokyo.html">Scopri di più</a>
                </div>
            </div>
        </div>
        <div id="activities" class="section">
            <h2>Cosa Vedere e Fare</h2>
            <p>Scopri le attività imperdibili in ogni destinazione.</p>
        </div>
        <div id="tips" class="section">
            <h2>Consigli Pratici</h2>
            <p>Consigli utili per rendere il tuo viaggio indimenticabile.</p>
        </div>
        <div id="about" class="section">
            <h2>Chi Siamo</h2>
            <p>Siamo un team di appassionati viaggiatori che condividono esperienze e consigli per aiutarti a pianificare il tuo prossimo viaggio.</p>
        </div>
        <div id="contact" class="section">
            <h2>Contatti</h2>
            <form>
                <label for="name">Nome:</label>
                <input type="text" id="name" name="name">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="message">Messaggio:</label>
                <textarea id="message" name="message" rows="5"></textarea>
                <button type="submit">Invia</button>
            </form>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Viaggio Senza Confini. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
