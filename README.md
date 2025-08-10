<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TerminBot – Ihr smarter Telefonassistent</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            margin: 0;
            background-color: #f5f5f7;
            color: #1d1d1f;
        }
        header {
            text-align: center;
            padding: 80px 20px;
            background-color: white;
        }
        header h1 {
            font-size: 3rem;
            font-weight: 600;
            margin-bottom: 20px;
        }
        header p {
            font-size: 1.3rem;
            color: #6e6e73;
            max-width: 600px;
            margin: auto;
        }
        .cta-button {
            display: inline-block;
            background-color: #0071e3;
            color: white;
            padding: 15px 40px;
            border-radius: 25px;
            font-size: 1.2rem;
            text-decoration: none;
            margin-top: 30px;
            transition: background 0.3s;
        }
        .cta-button:hover {
            background-color: #005bb5;
        }
        section {
            max-width: 1100px;
            margin: auto;
            padding: 60px 20px;
        }
        h2 {
            font-size: 2.2rem;
            margin-bottom: 20px;
            text-align: center;
        }
        p {
            font-size: 1.15rem;
            line-height: 1.6;
            color: #3a3a3c;
        }
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 40px;
            margin-top: 40px;
        }
        .feature {
            background: white;
            padding: 30px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 4px 14px rgba(0,0,0,0.05);
        }
        .feature h3 {
            margin-top: 15px;
            font-size: 1.4rem;
        }
        .steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        .step {
            background: white;
            padding: 25px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 4px 14px rgba(0,0,0,0.05);
        }
        .pricing {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        .price-card {
            background: white;
            padding: 30px;
            border-radius: 20px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 14px rgba(0,0,0,0.05);
        }
        .price {
            font-size: 2rem;
            color: #0071e3;
            margin: 20px 0;
        }
        .faq {
            margin-top: 40px;
        }
        .faq-item {
            background: white;
            margin-bottom: 15px;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 14px rgba(0,0,0,0.05);
        }
        footer {
            background-color: white;
            padding: 40px 20px;
            text-align: center;
            color: #6e6e73;
            font-size: 0.95rem;
            margin-top: 60px;
        }
        footer a {
            color: #0071e3;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Hero -->
    <header>
        <h1>TerminBot</h1>
        <p>Ihr smarter KI-Telefonassistent für automatische Terminplanung – modern, zuverlässig und rund um die Uhr verfügbar.</p>
        <a class="cta-button" href="https://calendly.com/geislermax999" target="_blank">Jetzt Termin buchen</a>
    </header>

    <!-- Features -->
    <section>
        <h2>Warum TerminBot?</h2>
        <div class="features">
            <div class="feature">
                <h3>24/7 Erreichbar</h3>
                <p>Keine verpassten Anrufe mehr – TerminBot ist immer für Ihre Kunden da.</p>
            </div>
            <div class="feature">
                <h3>Direkte Terminbuchung</h3>
                <p>Automatische Eintragung in Ihren Kalender in Echtzeit.</p>
            </div>
            <div class="feature">
                <h3>Individuelle Anpassung</h3>
                <p>Passen Sie Begrüßung und Antworten genau an Ihr Unternehmen an.</p>
            </div>
        </div>
    </section>

    <!-- How it works -->
    <section>
        <h2>So funktioniert's</h2>
        <div class="steps">
            <div class="step">
                <h3>1. Anmeldung</h3>
                <p>Registrieren Sie sich in wenigen Minuten und verbinden Sie Ihren Kalender.</p>
            </div>
            <div class="step">
                <h3>2. Einrichtung</h3>
                <p>Passen Sie die Begrüßung und Terminlogik an Ihre Bedürfnisse an.</p>
            </div>
            <div class="step">
                <h3>3. Loslegen</h3>
                <p>TerminBot nimmt ab sofort alle Anrufe für Sie entgegen.</p>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section>
        <h2>Unsere Preise</h2>
        <div class="pricing">
            <div class="price-card">
                <h3>Basic</h3>
                <div class="price">€29/Monat</div>
                <p>Für Einzelunternehmer, die einfache Terminbuchung brauchen.</p>
            </div>
            <div class="price-card">
                <h3>Pro</h3>
                <div class="price">€59/Monat</div>
                <p>Für kleine Teams mit erweiterten Funktionen.</p>
            </div>
            <div class="price-card">
                <h3>Enterprise</h3>
                <div class="price">Auf Anfrage</div>
                <p>Individuelle Lösungen für große Unternehmen.</p>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section>
        <h2>Häufige Fragen</h2>
        <div class="faq">
            <div class="faq-item">
                <strong>Kann TerminBot auch meine bestehenden Termine sehen?</strong>
                <p>Ja, sobald Sie Ihren Kalender verbunden haben, erkennt TerminBot freie und belegte Zeiten.</p>
            </div>
            <div class="faq-item">
                <strong>Ist der Service DSGVO-konform?</strong>
                <p>Ja, alle Daten werden verschlüsselt übertragen und in der EU gespeichert.</p>
            </div>
            <div class="faq-item">
                <strong>Kann ich die Begrüßung ändern?</strong>
                <p>Ja, Sie können jederzeit Texte und Ansagen anpassen.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section>
        <h2>Kontakt</h2>
        <p>Haben Sie Fragen oder möchten Sie mehr erfahren? Melden Sie sich direkt bei uns.</p>
        <p><strong>Email:</strong> <a href="mailto:geislermax999@gmail.com">geislermax999@gmail.com</a></p>
        <p><strong>Telefon:</strong> <a href="tel:01635315433">0163 5315433</a></p>
    </section>

    <footer>
        © 2025 TerminBot – Alle Rechte vorbehalten | <a href="mailto:geislermax999@gmail.com">Kontakt</a>
    </footer>

</body>
</html>
