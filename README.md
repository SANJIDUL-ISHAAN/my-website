# my-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IHSBD-like Editable Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>IHSBD-like Editable Website</h1>
            <p>Your tagline goes here</p>
        </div>
    </header>
    <nav>
        <div class="container">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    <main>
        <section id="home">
            <h2>Home Section</h2>
            <p>Welcome to our website. You can edit this content as you like!</p>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>This section can contain details about your organization or purpose.</p>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <p>Provide a list of the services or features your website offers here.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Add your contact information here.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Your Website Name. All rights reserved.</p>
    </footer>
</body>
</html>
/* Reset Styles */
body, h1, h2, p, a {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Body and Layout */
body {
    background-color: #f9f9f9;
    line-height: 1.6;
}

/* Header */
header {
    background: #007bff;
    color: white;
    padding: 20px 0;
    text-align: center;
}

/* Navigation */
nav {
    background: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* Main Content */
main {
    padding: 20px;
}

section {
    margin-bottom: 30px;
}

h2 {
    color: #007bff;
    margin-bottom: 10px;
}

p {
    color: #333;
    line-height: 1.6;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}
