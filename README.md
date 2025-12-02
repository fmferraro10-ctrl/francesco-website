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

        /* NAV BAR */
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
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 4px solid #ff3333;
            object-fit: cover;
            margin-bottom: 20px;
        }

        header h1 {
            color: #ff3333;
            margin-bottom: 10px;
        }

        .container {
            width: 90%;
            max-width: 900px;
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
            <li><a href="#projects">Projects</a></li>
            <li><a href="#socials">Socials</a></li>
        </ul>
    </nav>

    <!-- HEADER / HOME -->
    <header id="home">
        <img src="profile.jpg" alt="Francesco Ferraro" />
        <h1>Francesco Ferraro</h1>
        <p>York University Student • Aspiring Teacher • Creative Builder</p>
    </header>

    <div class="container">

        <!-- ABOUT -->
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hi! My name is <strong>Francesco Ferraro</strong>, and I'm a student at York University.  
                I’m passionate about education, creativity, and building meaningful connections with others.
            </p>
        </section>

        <!-- HOBBIES -->
        <section id="hobbies">
            <h2>Hobbies & Interests</h2>
            <ul>
                <li><strong>Soccer</strong> — my favorite sport to play and watch.</li>
                <li><strong>Karate</strong> — 2nd degree black belt.</li>
                <li><strong>Video Games</strong> — a great way to relax.</li>
                <li><strong>Streaming</strong> — I enjoy interacting with viewers while gaming.</li>
            </ul>
        </section>

        <!-- PROJECTS -->
        <section id="projects">
            <h2>Projects</h2>
            <p>
                One of the creative things I enjoy doing is making unique designs and structures using 
                <strong>old Monster cans</strong>.  
                Instead of throwing them out, I turn them into cool miniature models, shapes, and display pieces.  
            </p>
            <p>
                It started as something fun I tried once, but over time I realized how much I enjoy 
                taking something ordinary and transforming it into something artistic.  
                Every build is differentsometimes I stack the cans, sometimes I cut and reshape them,
                and other times I try to make objects like figures or logos out of the materials.
            </p>
            <p>
                It’s become a fun hobby that mixes creativity, recycling, and problem-solving.  
                I’m always experimenting with new ideas and ways to improve my designs.
            </p>
        </section>

        <!-- SOCIALS -->
        <section id="socials">
            <h2>Socials</h2>
            <ul>
                <li><strong>Email:</strong> <a href="mailto:fmf2007@my.yorku.ca">fmf2007@my.yorku.ca</a></li>
                <li><strong>Instagram:</strong> <a href="https://instagram.com/fmferraro10" target="_blank">@fmferraro10</a></li>
                <li><strong>Twitch:</strong> <a href="https://twitch.tv/XDFallenlegacy" target="_blank">XDFallenlegacy</a></li>
            </ul>
        </section>

    </div>

    <div class="footer">
        © 2025 Francesco Ferraro — All Rights Reserved  
    </div>

</body>
</html>
