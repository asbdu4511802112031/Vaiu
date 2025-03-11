<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }

        /* Header */
        header {
            background: black;
            color: white;
            padding: 15px;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        /* Sections */
        section {
            padding: 50px;
        }

        /* About Section */
        #about img {
            width: 150px;
            border-radius: 50%;
            margin-top: 10px;
        }

        /* Projects */
        .project {
            background: white;
            padding: 20px;
            margin: 20px auto;
            width: 60%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        /* Contact */
        #contact p {
            font-size: 18px;
        }
    </style>
</head>
<body>

    <!-- Header / Navigation -->
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am [Your Name], a passionate web developer.</p>
        <img src="profile.jpg" alt="Profile Picture">
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of my project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Another project I worked on.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

</body>
</html>
