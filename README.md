<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jose Flores | Architecture Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    background: #ffffff;
    color: #111;
    line-height: 1.6;
}

nav {
    position: fixed;
    width: 100%;
    padding: 20px 10%;
    background: white;
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #eee;
}

nav a {
    text-decoration: none;
    color: #111;
    margin-left: 30px;
    font-weight: 500;
}

.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    padding: 0 10%;
}

.hero h1 {
    font-size: 60px;
    font-weight: 700;
}

.hero p {
    margin-top: 20px;
    font-size: 18px;
    max-width: 600px;
}

.section {
    padding: 100px 10%;
}

.section h2 {
    font-size: 36px;
    margin-bottom: 40px;
}

.project {
    margin-bottom: 80px;
}

.project img {
    width: 100%;
    border-radius: 10px;
    margin-bottom: 20px;
}

.project h3 {
    font-size: 28px;
    margin-bottom: 10px;
}

.project p {
    max-width: 700px;
    color: #444;
}

.footer {
    padding: 60px 10%;
    border-top: 1px solid #eee;
}

.footer p {
    margin-bottom: 10px;
}
</style>
</head>

<body>

<nav>
    <div><strong>JOSE FLORES</strong></div>
    <div>
        <a href="#work">Work</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<section class="hero">
    <div>
        <h1>Architecture that connects community, culture, and sustainability.</h1>
        <p>
        I am an architecture student focused on multi-generational spaces, mixed-use development,
        and community-centered design. My work explores how architecture can strengthen
        walkability, environmental equity, and cultural identity.
        </p>
    </div>
</section>

<section id="work" class="section">
    <h2>Selected Work</h2>

    <div class="project">
        <h3>Generation Dining | Fall 2025</h3>
        <p>
        A multi-generational building designed to connect elders, adults, teens,
        and children. The project integrates a family restaurant, education space,
        and rooftop garden to support shared daily life and community exchange.
        </p>
    </div>

    <div class="project">
        <h3>The Summit | Fall 2024</h3>
        <p>
        A hybrid housing concept integrating residential units, retail promenade,
        green terraces, and a vertical open lobby. Designed to extend the park
        and enhance pedestrian life through car-free circulation.
        </p>
    </div>

    <div class="project">
        <h3>Carapace Commons | Spring 2025</h3>
        <p>
        Redevelopment of a former parking lot into a multi-family, mixed-use,
        culturally rooted community space. Features include a clinic, cultural center,
        solar panels, bioswales, green roofs, and community gathering spaces.
        </p>
    </div>

</section>

<section id="about" class="section">
    <h2>About</h2>
    <p>
    I am passionate about creating architecture that serves real communities.
    My work emphasizes walkability, sustainability, and multi-generational
    programming. I am particularly interested in higher education, K-12,
    mixed-use, and interior-focused projects.
    </p>
</section>

<section id="contact" class="footer">
    <h2>Contact</h2>
    <p>Email: your@email.com</p>
    <p>LinkedIn: linkedin.com/in/yourprofile</p>
</section>

</body>
</html>
