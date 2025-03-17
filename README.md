# Techknite.com
DO YOU NEED HELP WHIT YOUR COMPUTER? CLICK HERE TO GET HELP! we have all that you need!
<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hjälp med JavaScript</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>JavaScript Hjälpcenter</h1>
        <nav>
            <ul>
                <li><a href="#fråga">Fråga en expert</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#sök">Sök hjälp</a></li>
            </ul>
        </nav>
    </header>

    <section id="introduktion">
        <h2>Välkommen till vårt JavaScript Hjälpcenter!</h2>
        <p>Här kan du få hjälp med alla dina JavaScript-frågor. Skriv din fråga eller använd vår sökfunktion för att hitta lösningar.</p>
    </section>

    <section id="fråga">
        <h2>Fråga en expert</h2>
        <form id="frågeformulär">
            <label for="fråga-input">Din JavaScript-fråga:</label>
            <textarea id="fråga-input" placeholder="Skriv din fråga här..."></textarea>
            <button type="submit">Skicka fråga</button>
        </form>
    </section>

    <section id="faq">
        <h2>Vanliga Frågor (FAQ)</h2>
        <div class="faq-item">
            <h3>Vad är skillnaden mellan `var`, `let` och `const`?</h3>
            <p>`var` deklarerar en variabel som är funktionell, medan `let` och `const` är block-scope variabler. `const` används för att deklarera variabler vars värde inte ska ändras.</p>
        </div>
        <div class="faq-item">
            <h3>Vad är en callback-funktion?</h3>
            <p>En callback är en funktion som skickas som argument till en annan funktion och körs när en viss händelse inträffar.</p>
        </div>
    </section>

    <section id="sök">
        <h2>Sök efter JavaScript-lösningar</h2>
        <input type="text" id="sök-input" placeholder="Sök efter hjälp..." />
        <button id="sök-knapp">Sök</button>
        <ul id="resultat-lista"></ul>
    </section>

    <footer>
        <p>&copy; 2025 JavaScript Hjälpcenter. Alla rättigheter reserverade.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
