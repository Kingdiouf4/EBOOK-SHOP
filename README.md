# EBOOK-SHOP
Vente de ebook interressant 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vente d'eBooks</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur notre site de vente d'eBooks</h1>
        <nav>
            <a href="#ebooks">Nos eBooks</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    
    <main>
        <section id="ebooks">
            <h2>Nos eBooks</h2>
            <div class="ebook-list">
                <div class="ebook">
                    <h3>eBook 1</h3>
                    <p>Auteur: Auteur 1</p>
                    <p>Prix: 10€</p>
                    <button onclick="showDetails('eBook 1')">Détails</button>
                </div>
                <div class="ebook">
                    <h3>eBook 2</h3>
                    <p>Auteur: Auteur 2</p>
                    <p>Prix: 15€</p>
                    <button onclick="showDetails('eBook 2')">Détails</button>
                </div>
                <!-- Ajoutez plus d'eBooks ici -->
            </div>
        </section>

        <section id="details" class="hidden">
            <h2>Détails de l'eBook</h2>
            <p id="ebook-details"></p>
            <button onclick="hideDetails()">Retour</button>
        </section>

        <section id="contact">
            <h2>Contactez-nous</h2>
            <form>
                <label for="name">Nom:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Envoyer</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Vente d'eBooks. Tous droits réservés.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
