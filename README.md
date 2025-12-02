<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Francesco Ferraro | Personal Website</title>

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Arial, sans-serif;
            background-color: #0d0d0d;
            color: #ffffff;
        }

        nav {
            background: #1a1a1a;
            padding: 15px 20px;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 5px rgba(255, 0, 0, 0.3);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 35px;
            padding: 0;
            margin: 0;
        }

        nav ul li a {
            color: #ff3333;
            text-decoration: none;
            font-size: 18px;
            font-weight: 600;
        }

        nav ul li a:hover {
            color: #ffffff;
        }

        header {
            text-align: center;
            padding: 50px 20px;
        }

        header img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 4px solid #ff3333;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .container {
            width: 90%;
            max-width: 950px;
            margin: 30px auto;
            background: #1a1a1a;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0px 3px 12px rgba(255, 0, 0, 0.2);
        }

        h2 {
            color: #ff3333;
            border-left: 5px solid #ff3333;
            padding-left: 10px;
            margin-top: 20px;
        }

        ul {
            line-height: 1.8;
            font-size: 17px;
        }

        a {
            color: #ff3333;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
            color: #ffffff;
        }

        /* Images in sections */
        .section-img {
            width: 100%;
            max-width: 500px;
            border-radius: 10px;
            margin: 15px 0;
            border: 3px solid #ff3333;
        }

        form input, form textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            border-radius: 8px;
            border: none;
            background: #333;
            color: #fff;
            font-size: 15px;
        }

        form button {
            margin-top: 15px;
            padding: 12px 15px;
            background: #ff3333;
            color: #fff;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
        }

        form button:hover {
            background: #cc0000;
        }

        .footer {
            text-align: center;
            padding: 25px;
            background: #0d0d0d;
            color: white;
            margin-top: 40px;
            font-size: 15px;
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#hobbies">Hobbies</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#socials">Socials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- HEADER / HOME -->
    <header id="home">
        <!-- Your real profile picture -->
        <img src="IMG_5965.jpeg" alt="Francesco Ferraro" />
        <h1>Francesco Ferraro</h1>
        <p>York University Student • Aspiring Teacher • 2nd Degree Black Belt</p>
    </header>

    <div class="container">

        <!-- ABOUT -->
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hi! My name is <strong>Francesco Ferraro</strong>, and I'm a current student at
                <strong>York University</strong>. I’m passionate about becoming a future teacher and creating a positive,
                supportive learning environment for students. Education inspires me, and my goal is to guide future students
                the same way my own teachers motivated me.
            </p>
        </section>

        <!-- HOBBIES -->
        <section id="hobbies">
            <h2>Hobbies & Skills</h2>
            <ul>
                <li><strong>Soccer</strong> — my favorite sport to play and watch.</li>
                <li><strong>Video Games</strong> — a fun way to relax and connect.</li>
                <li><strong>Karate</strong> — I am a <strong>2nd degree black belt</strong>, achieved through years of dedication.</li>
                <li><strong>Streaming</strong> — I enjoy gaming and interacting with viewers.</li>
            </ul>
        </section>

        <!-- ACHIEVEMENTS -->
        <section id="achievements">
            <h2>Achievements</h2>
            <ul>
                <li><strong>Co-op Placement at an Elementary School (Grades 11 & 12)</strong>  
                    - Assisted teachers, worked with students, and gained real classroom experience.
                </li>
                <li>2nd Degree Black Belt in Karate — discipline, leadership, and commitment.</li>
            </ul>

            <!-- Your karate belt image placed here -->
            <img src="IMG_6062.jpeg" class="section-img" alt="Francesco's Karate Belt">
        </section>

        <!-- PROJECTS -->
        <section id="projects">
            <h2>Projects</h2>
            <p>
                One of my creative hobbies is making fun shapes or designs using old cans.  
                I enjoy turning something simple like empty Monster cans into unique little creations.
            </p>

            <!-- Monster can structure image -->
            <img src="IMG_6170.jpg" class="section-img" alt="Monster Can Project">
        </section>

        <!-- SOCIALS -->
        <section id="socials">
            <h2>Socials & Contact Info</h2>
            <ul>
                <li><strong>Email (YorkU):</strong> <a href="mailto:fmf2007@my.yorku.ca">fmf2007@my.yorku.ca</a></li>
                <li><strong>Instagram:</strong> <a href="https://instagram.com/fmferraro10" target="_blank">@fmferraro10</a></li>
                <li><strong>Twitch:</strong> <a href="https://twitch.tv/XDFallenlegacy" target="_blank">XDFallenlegacy</a></li>
                <li><strong>Online Username:</strong> Fmferraro10</li>
            </ul>
        </section>

        <!-- CONTACT FORM -->
        <section id="contact">
            <h2>Contact Me</h2>
            <p>You can send me a message below:</p>
            <form>
                <input type="text" placeholder="Your Name" required />
                <input type="email" placeholder="Your Email" required />
                <textarea rows="4" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>

    </div>

    <div class="footer">
        © 2025 Francesco Ferraro — All Rights Reserved  
    </div>

</body>
</html>
