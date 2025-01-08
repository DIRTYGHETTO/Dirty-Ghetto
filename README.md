# Dirty-Ghetto
mi-portafolio/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── images/
    └── (tu imagen de portafolio)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio de [Tu Nombre], fotógrafo y filmmaker">
    <title>Portafolio | [Tu Nombre]</title>
    <link rel="stylesheet" href="css/styles.css">
    <script src="https://kit.fontawesome.com/a076d05399.js"></script> <!-- Font Awesome para íconos -->
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">
            <h1>[Tu Nombre]</h1>
            <p>Fotógrafo y Filmmaker</p>
        </div>
        <nav>
            <ul>
                <li><a href="#about">Sobre mí</a></li>
                <li><a href="#portfolio">Portafolio</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Bienvenido a mi portafolio</h2>
        <p>Explora mi trabajo como fotógrafo y filmmaker</p>
        <a href="#portfolio" class="btn">Ver Mi Trabajo</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2>Sobre mí</h2>
            <p>¡Hola! Soy [Tu Nombre], un apasionado fotógrafo y filmmaker con experiencia en [detalles de tu especialización].</p>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Portafolio</h2>
            <div class="gallery">
                <div class="image-item">
                    <img src="images/photo1.jpg" alt="Trabajo 1">
                </div>
                <div class="image-item">
                    <img src="images/photo2.jpg" alt="Trabajo 2">
                </div>
                <div class="image-item">
                    <img src="images/photo3.jpg" alt="Trabajo 3">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contacto</h2>
            <p>Para más información, no dudes en contactarme.</p>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Tu nombre" required>
                <input type="email" name="email" placeholder="Tu email" required>
                <textarea name="message" placeholder="Tu mensaje" required></textarea>
                <button type="submit">Enviar Mensaje</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 [Tu Nombre]. Todos los derechos reservados.</p>
        <div class="socials">
            <a href="https://www.instagram.com/tuusuario" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://www.facebook.com/tuusuario" target="_blank"><i class="fab fa-facebook"></i></a>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
/* Reset de márgenes y bordes */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f8f8f8;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background-color: #222;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    font-size: 2.5rem;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

header nav ul li {
    margin: 0 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
    transition: color 0.3s ease;
}

header nav ul li a:hover {
    color: #ff6347;
}

/* Hero Section */
.hero {
    background-image: url('images/hero.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    padding: 100px 0;
    text-align: center;
}

.hero h2 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero .btn {
    background-color: #ff6347;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    font-size: 1.1rem;
    border-radius: 5px;
}

.hero .btn:hover {
    background-color: #e55347;
}

/* About Section */
.about {
    padding: 60px 0;
    background-color: #fff;
}

.about h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
    text-align: center;
}

.about p {
    text-align: center;
    font-size: 1.1rem;
}

/* Portfolio Section */
.portfolio {
    padding: 60px 0;
    background-color: #f4f4f4;
}

.portfolio h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
    text-align: center;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin-top: 30px;
}

.image-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

/* Contact Section */
.contact {
    padding: 60px 0;
    background-color: #fff;
}

.contact h2 {
    font-size: 2.5rem;
    text-align: center;
    margin-bottom: 20px;
}

.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contact input,
.contact textarea {
    width: 80%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact button {
    background-color: #ff6347;
    color: #fff;
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact button:hover {
    background-color: #e55347;
}

/* Footer */
footer {
    background-color: #222;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

footer .socials {
    margin-top: 10px;
}

footer .socials a {
    color: #fff;
    margin: 0 10px;
    font-size: 1.5rem;
    text-decoration: none;
}

footer .socials a:hover {
    color: #ff6347;
}
// Script para scroll suave (por ejemplo, para la navegación)
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();

        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
