<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Smoczy Bestiariusz</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="hero">
    <div class="hero-content">
        <h1>Smoczy Bestiariusz</h1>
        <p>Poznaj najciekawsze gatunki smoków: od klasycznych europejskich po majestatyczne smoki wschodu.</p>
        <a href="gatunki.html" class="btn-primary">Poznaj gatunki</a>
    </div>

.hero {
    min-height: 60vh;
    background-image: linear-gradient(to bottom right, #050816, #1b2144);
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 40px 20px;
}

.hero-content h1 {
    font-size: 3rem;
    letter-spacing: 2px;
    margin-bottom: 20px;
}

.hero-content p {
    max-width: 600px;
    margin: 0 auto 30px auto;
}
    
</header>

<nav class="main-nav">
    <a href="index.html">Strona główna</a>
    <a href="gatunki.html">Gatunki smoków</a>
    <a href="kontakt.html">Kontakt</a>
</nav>

<main class="content">
    <section>
        <h2>Wstęp</h2>
        <p>
            Odkryj świat smoków – znajdziesz tu opis kilku popularnych gatunków,
            ich cechy, legendy.
        </p>
    </section>

    <section>
        <h2>Co znajdziesz na stronie?</h2>
        <ul>
            <li><strong>Gatunki smoków</strong> – podział na smoki europejskie, azjatyckie i fantastyczne.</li>
            <li><em>Ilustracje</em> smoków z różnych źródeł (lokalne pliki i zewnętrzne URL).</li>
            <li>Krótki opis legend i cech charakterystycznych.</li>
        </ul>
    </section>
    
</main>

<footer class="site-footer">
    <p>Autor: Mia Robert, nr studenta: 123456</p>
</footer>

</body>
</html>
