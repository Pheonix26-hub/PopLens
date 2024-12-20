# PopLens
PopLens/
│
├── index.html         (Homepage)
├── about.html         (About Us)
├── gallery.html       (Gallery)
├── contact.html       (Contact)
├── css/
│   └── styles.css     (CSS for the website)
└── images/            (Folder for images)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PopLens - Home</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">PopLens</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>See the World Through a New Lens</h1>
        <p>Photography and Fashion That Inspires</p>
        <a href="gallery.html" class="btn">Explore Gallery</a>
    </section>
    <footer>
        <p>© 2024 PopLens. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PopLens - About Us</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">PopLens</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="about">
        <h1>About Us</h1>
        <p>At PopLens, we combine the art of photography with a passion for fashion to create visuals that tell a story. Founded in 2024, we aim to capture the beauty of the world and help others see it through our lens.</p>
    </section>
    <footer>
        <p>© 2024 PopLens. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PopLens - Gallery</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">PopLens</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="gallery">
        <h1>Our Gallery</h1>
        <div class="image-grid">
            <img src="images/photo1.jpg" alt="Sample Photo 1">
            <img src="images/photo2.jpg" alt="Sample Photo 2">
            <img src="images/photo3.jpg" alt="Sample Photo 3">
            <img src="images/photo4.jpg" alt="Sample Photo 4">
        </div>
    </section>
    <footer>
        <p>© 2024 PopLens. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PopLens - Contact</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <div class="logo">PopLens</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section class="contact">
        <h1>Contact Us</h1>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>© 2024 PopLens. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

header nav ul li {
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

header nav ul li a:hover {
    color: #f0a500;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background: url('../images/hero.jpg') no-repeat center center/cover;
    color: white;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero p {
    font-size: 20px;
    margin-bottom: 30px;
}

.hero .btn {
    background-color: #f0a500;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

.hero .btn:hover {
    background-color: #333;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

.image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 10px;
    padding: 20px;
}

.image-grid img {
    width: 100%;
    border-radius: 5px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
