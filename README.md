# R-T-F
Raising Together Fondation 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raising Together Foundation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <h1>Raising Together Foundation</h1>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#programs">Programs</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <div class="hero">
            <h2>Empowering Teenage Mothers with Life Skills</h2>
            <p>Join us in supporting young mothers to build a better future.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>The Raising Together Foundation is dedicated to empowering teenage mothers by providing them with essential life skills, vocational training, and emotional support. We aim to help them regain their confidence, create a stable future for themselves and their children, and reintegrate into society.</p>
    </section>

    <!-- Programs Section -->
    <section id="programs">
        <h2>Our Programs</h2>
        <div class="program">
            <h3>Vocational Training</h3>
            <p>We offer training in various skills such as tailoring, baking, and hairdressing, helping mothers become self-reliant.</p>
        </div>
        <div class="program">
            <h3>Entrepreneurship Workshops</h3>
            <p>Our entrepreneurship workshops teach young mothers how to start and manage their own small businesses.</p>
        </div>
        <div class="program">
            <h3>Mental Health Support</h3>
            <p>We provide counseling and support services to address the emotional and psychological needs of teenage mothers.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you'd like to learn more about our work or get involved, please reach out to us:</p>
        <p>Email: info@raisingtogether.org</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Raising Together Foundation. All rights reserved.</p>
    </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #333;
    color: #fff;
    padding: 10px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

nav .logo h1 {
    font-size: 24px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.hero {
    background: url('hero-image.jpg') no-repeat center center/cover;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    text-align: center;
}

.hero h2 {
    font-size: 36px;
}

#about, #programs, #contact {
    padding: 40px 20px;
    text-align: center;
}

#about h2, #programs h2, #contact h2 {
    font-size: 28px;
    margin-bottom: 20px;
}

.program {
    margin-bottom: 20px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}
