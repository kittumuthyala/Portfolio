# Portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible"="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishnapriya's Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #121212;
            color: #ffffff;
            font-family: 'Roboto', sans-serif;
        }

        header {
            padding: 15px;
            background: #1e1e1e;
            border-bottom: 1px solid #333;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: #ffffff;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #ffffff;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #cccccc;
        }

        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 50px 20px;
        }

        .intro {
            text-align: center;
            margin-bottom: 60px;
        }

        .intro h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        .intro p {
            font-size: 1.2rem;
            color: #aaaaaa;
        }

        .profile-photo {
            display: block;
            margin: 20px auto;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }

        .sections {
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
        }

        .section {
            background: #1e1e1e;
            padding: 30px;
            border-radius: 10px;
            margin-bottom: 40px;
            width: 80%;
            max-width: 900px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: z-index 0.3s ease; /* Added transition for smooth effect */
            position: relative;
            z-index: 1; /* Initially set z-index */
        }

        .section:hover {
            z-index: 2; /* Increase z-index on hover to bring section to front */
        }

        .section h2 {
            margin-bottom: 20px;
            font-size: 1.8rem;
            color: #ffffff;
            text-align: center;
        }

        .about p {
            font-size: 1rem;
            color: #cccccc;
            text-align: center;
        }

        .skills ul {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            list-style: none;
        }

        .skills ul li {
            background: #ffffff;
            color: #121212;
            padding: 10px 20px;
            border-radius: 5px;
            margin: 5px;
            font-size: 0.9rem;
        }

        .internships,
        .projects {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .internships .internship,
        .projects .project {
            background: #333;
            padding: 20px;
            border-radius: 5px;
            margin: 10px 0;
            width: 100%;
        }

        .internships .internship-title,
        .projects .project-title {
            font-weight: 500;
            color: #ffffff;
            text-align: center;
        }

        .internships .internship p,
        .projects .project p {
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #1e1e1e;
            border-top: 1px solid #333;
        }

        footer p {
            color: #aaaaaa;
        }

        .contact p {
            text-align: center;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="logo">Krishnapriya's Portfolio</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="intro">
            <h1>Hello, I'm Krishnapriya</h1>
            <img src="pic.jpg" alt="Profile Photo" class="profile-photo">
            <p>Creative Developer | Problem Solver | Tech Enthusiast</p>
        </section>

        <div class="sections">
            <section id="about" class="section about">
                <h2>About Me</h2>
                <p>I am a dedicated developer with a passion for creating innovative solutions. My journey in tech is driven by curiosity and a love for learning. I thrive on challenges and am committed to continuous improvement.</p>
            </section>

            <section id="skills" class="section skills">
                <h2>Skills</h2>
                <ul>
                    <li>Python</li>
                    <li>JavaScript</li>
                    <li>React</li>
                    <li>Node.js</li>
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>SQL</li>
                </ul>
            </section>

            <section id="internships" class="section internships">
                <h2>Internships</h2>
                <div class="internship">
                    <div class="internship-title">AI/ML Internship</div>
                    <p>Company: Amazon Web Services</p>
                    <p>Year: 2023</p>
                </div>
                <div class="internship">
                    <div class="internship-title">Android Development Internship</div>
                    <p>Company: Google</p>
                    <p>Year: 2023</p>
                </div>
                <div class="internship">
                    <div class="internship-title">Networking Internship</div>
                    <p>Company: Juniper Networks</p>
                    <p>Year: 2024</p>
                </div>
                <div class="internship">
                    <div class="internship-title">Web Development Internship</div>
                    <p>Company: Oasis Infobyte</p>
                    <p>Year: 2024</p>
                </div>
            </section>

            <section id="projects" class="section projects">
                <h2>Projects</h2>
                <div class="project">
                    <div class="project-title">Airline Reservation System using Machine Learning</div>
                    <p>A machine learning project aimed at facilitating faster flight ticket bookings through voice recognition, designed to enhance accessibility for handicapped individuals.</p>
                </div>
                <div class="project">
                    <div class="project-title">Egg Catcher Game using python</div>
                    <p>Egg Catcher is a classic arcade-style game where the player controls a basket moving horizontally at the bottom of the screen to catch falling eggs before they hit the ground.</p>
                </div>
            </section>

            <section id="contact" class="section contact">
                <h2>Contact Me</h2>
                <p>Email: muthyalakrishnapriya@gmail.com</p>
                <p>Phone: +91 9346277098</p>
                <center><a href="https://www.linkedin.com/in/krishnapriyamuthyala08/">LinkedIn</a> </center>
                <center><a href="https://github.com/kittumuthyala">Github</a> </center>
            </section>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Krishnapriya's Portfolio. All rights reserved.</p>
    </footer>
</body>

</html>
