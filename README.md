Project: Elearning Platform

HTML (index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my personal portfolio. I am a web developer with a passion for creating beautiful and functional websites.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project Title</h3>
                <p>Description of the project.</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html>



CSS (styles.css)
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

section {
    margin-bottom: 2rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: flex;
    flex-direction: column;
}

form label {
    margin-bottom: 0.5rem;
}

form input, form textarea {
    margin-bottom: 1rem;
    padding: 0.5rem;
    border: 1px solid #ccc;
}

form button {
    padding: 0.5rem;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}



JavaScript (scripts.js)
document.addEventListener("DOMContentLoaded", () => {
    console.log("Document loaded");
}); 

 

 

 

 

 

 

