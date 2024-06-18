<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beastwear</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Beastwear</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Produkter</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Velkommen til Beastwear</h2>
        <p>Find de nyeste tøj, tasker og sko her!</p>
    </section>

    <section id="products">
        <h2>Produkter</h2>
        <div class="product">
            <img src="images/tshirt.jpg" alt="T-Shirt">
            <h3>T-Shirt</h3>
            <p>Pris: 199 DKK</p>
        </div>
        <div class="product">
            <img src="images/bag.jpg" alt="Taske">
            <h3>Taske</h3>
            <p>Pris: 299 DKK</p>
        </div>
        <div class="product">
            <img src="images/shoes.jpg" alt="Sko">
            <h3>Sko</h3>
            <p>Pris: 399 DKK</p>
        </div>
        <!-- Tilføj flere produkter efter behov -->
    </section>

    <section id="contact">
        <h2>Kontakt os</h2>
        <form action="mailto:gustav060212@gmail.com" method="post" enctype="text/plain">
            <label for="name">Navn:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Besked:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Beastwear. Alle rettigheder forbeholdes.</p>
    </footer>
</body>
</html>
