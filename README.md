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
            text-align: left;
            display: flex;
            align-items: flex-start;
            justify-content: space-between;
            padding-top: 30px;
        }

        /* Header Styling */
        header {
            background: linear-gradient(to right, #005f92, #0099cc);
            text-align: center;
            padding: 50px 20px;
            color: white;
            position: relative;
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
            margin-top: 20px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
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

        /* Welcome Section */
        .welcome {
            flex: 1;
            padding: 50px 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .welcome h2 {
            color: #005f92;
        }

        .welcome p {
            font-size: 1.2rem;
        }

        /* Profile Image */
        .profile-img {
            width: 200px;
            height: auto;
            border-radius: 10px;
        }

        /* Contact Section */
        .contact {
            margin-top: 40px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        .contact h2 {
            color: #005f92;
        }

        .contact p {
            font-size: 1.1rem;
        }

        .contact-box {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 5px;
            font-family: monospace;
            color: #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ardit Koka</h1>
        <p>PhD Candidate in Macroeconomics, Monetary Policy, Banking</p>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="research.html">Research</a></li>
                <li><a href="teaching.html">Teaching</a></li>
                <li><a href="cv.html">CV</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <div class="welcome">
            <h2>Welcome</h2>
            <p>I am a PhD candidate with a strong research focus on Macroeconomics, Monetary Policy, Central Bank Digital Currency (CBDC), Banking, and Money. My work aims to contribute to the understanding of financial systems, the evolving role of central banks, and the implications of digital currency innovations in modern economies.</p>
            <p>I hold a Master’s degree in International Economics and Commerce from Università Politecnica delle Marche, where I developed a deep understanding of global economic dynamics, trade policies, and financial markets. My academic background equips me with a strong analytical foundation to explore key economic issues related to monetary policy and banking stability.</p>
        </div>
        <img src="profile.jpg" alt="Ardit Koka" class="profile-img">
    </div>

    <div class="container contact">
        <h2>Contact Details</h2>
        <div class="contact-box">
            Via Monte Generoso 71,<br>
            Varese 21100, Italy<br>
            Università degli Studi dell'Insubria<br>
            Dipartimento di Economia<br>
            Dipartimento di Eccellenza
        </div>
        <p>Email: <a href="mailto:akoka@uninsubria.it">akoka@uninsubria.it</a></p>
    </div>
</body>
</html>
