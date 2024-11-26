# haley-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haley Clancy Inyart Inspired</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Hero Section -->
    <header class="hero">
        <div class="hero-content">
            <h1>Haley Clancy Inyart</h1>
            <p>Explore my creative journey through art and design.</p>
            <a href="#gallery" class="btn">View My Work</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>I am an artist who blends creativity with storytelling...</p>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-grid">
            <img src="images/artwork1.jpg" alt="Artwork 1">
            <img src="images/artwork2.jpg" alt="Artwork 2">
            <img src="images/artwork3.jpg" alt="Artwork 3">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit" class="btn">Send</button>
        </form>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Haley Clancy Inyart Inspired</p>
    </footer>
</body>
</html>
 
