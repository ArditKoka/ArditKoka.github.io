<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ardit Koka - PhD Candidate</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        .container {
            width: 80%;
            max-width: 1000px;
            margin: 0 auto;
        }

        /* Header Styling */
        header {
            background: linear-gradient(to right, #005f92, #0099cc);
            text-align: center;
            padding: 50px 20px;
            color: white;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
            font-weight: bold;
        }

        header p {
            font-size: 1.2rem;
            margin: 10px 0;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            gap: 15px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            background-color: white;
            color: #005f92;
            padding: 10px 20px;
            border-radius: 5px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav ul li a:hover {
            background-color: #005f92;
            color: white;
        }

        /* Content Sections */
        section {
            padding: 50px 20px;
            background-color: white;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #005f92;
            font-size: 2rem;
        }

        /* Two Column Layout */
        .profile-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 30px;
        }

        .profile-container img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid #005f92;
        }

        /* Contact Info */
        .contact-links a {
            color: #005f92;
            text-decoration: none;
            font-weight: bold;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ardit Koka</h1>
        <p>PhD Candidate in Macroeconomics, Monetary Policy, Banking</p>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#lectures">Lectures</a></li>
                <li><a href="#cv">CV</a></li>
                <li><a href="#announcements">Announcements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <section id="about" class="profile-container">
            <div>
                <h2>About Me</h2>
                <p>I am a PhD candidate specializing in Macroeconomics, Monetary Policy, Central Bank Digital Currency (CBDC), Banking, and Money...</p>
            </div>
            <img src="profile.jpg" alt="Ardit Koka">
        </section>

        <section id="lectures">
            <h2>Lectures</h2>
            <p>Find details about my lectures and courses here.</p>
        </section>

        <section id="cv">
            <h2>Curriculum Vitae</h2>
            <a href="cv.pdf" target="_blank">Download CV (PDF)</a>
        </section>

        <section id="announcements">
            <h2>Announcements</h2>
            <p>Stay updated with recent news, conferences, and publications.</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <div class="contact-links">
                <p>Email: <a href="mailto:akoka@uninsubria.it">akoka@uninsubria.it</a></p>
                <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" target="_blank">View Profile</a></p>
            </div>
        </section>
    </div>
</body>
</html>
