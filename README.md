<html lang="en">

<head>

    <meta name="google-site-verification" content="0hJ8jug-XxHPrRFzH_mslLafvPpysxxd8O42VJ3PwuM">

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ardit Koka | Economics</title>

    <meta
        name="description"
        content="Academic website of Ardit Koka, PhD Candidate in Economics at the University of Insubria. Research in macroeconomics, monetary economics, banking, financial intermediation and central bank digital currencies."
    >

    <style>

        :root {
            --blue: #006699;
            --blue-dark: #004b70;
            --blue-light: #eef6fa;
            --ink: #24313b;
            --text: #36434d;
            --muted: #697782;
            --line: #dce4e8;
            --paper: #ffffff;
            --background: #f7f9fa;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            scroll-padding-top: 90px;
        }

        body {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            color: var(--text);
            background: var(--background);
            line-height: 1.7;
        }

        a {
            color: var(--blue);
        }

        .container {
            width: min(1060px, calc(100% - 44px));
            margin: 0 auto;
        }

        .navbar {
            position: sticky;
            top: 0;
            z-index: 100;
            background: rgba(255, 255, 255, 0.97);
            border-bottom: 1px solid var(--line);
        }

        .nav-inner {
            min-height: 67px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 25px;
        }

        .nav-name {
            color: var(--ink);
            font-size: 1.08rem;
            font-weight: 700;
            text-decoration: none;
        }

        .nav-links {
            display: flex;
            align-items: center;
            gap: 25px;
        }

        .nav-links a {
            color: var(--text);
            font-size: 0.95rem;
            font-weight: 600;
            text-decoration: none;
        }

        .nav-links a:hover {
            color: var(--blue);
        }

        .hero {
            background: var(--blue);
            color: white;
            padding: 72px 0 68px;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1fr 190px;
            align-items: center;
            gap: 65px;
        }

        .eyebrow {
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 0.11em;
            opacity: 0.8;
            margin-bottom: 10px;
        }

        .hero h1 {
            font-family: Georgia, "Times New Roman", serif;
            font-weight: 500;
            font-size: clamp(3rem, 7vw, 4.6rem);
            line-height: 1;
            margin-bottom: 17px;
        }

        .hero-role {
            font-size: 1.32rem;
            line-height: 1.45;
            margin-bottom: 7px;
        }

        .hero-institution {
            font-size: 1.04rem;
            opacity: 0.9;
        }

        .hero-fields {
            margin-top: 27px;
            max-width: 710px;
            font-size: 1rem;
            line-height: 1.7;
            opacity: 0.95;
        }

        .hero-links {
            display: flex;
            flex-wrap: wrap;
            gap: 11px;
            margin-top: 28px;
        }

        .hero-button {
            display: inline-block;
            padding: 9px 16px;
            border: 1px solid rgba(255, 255, 255, 0.55);
            border-radius: 5px;
            color: white;
            text-decoration: none;
            font-size: 0.93rem;
            font-weight: 600;
        }

        .hero-button:hover {
            background: white;
            color: var(--blue-dark);
        }

        .profile-photo {
            width: 180px;
            height: 180px;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid white;
            box-shadow: 0 10px 28px rgba(0, 0, 0, 0.2);
        }

        main {
            background: var(--paper);
        }

        .section {
            padding: 66px 0;
            border-bottom: 1px solid var(--line);
        }

        .section:last-child {
            border-bottom: 0;
        }

        .section-heading {
            margin-bottom: 30px;
        }

        .section-label {
            color: var(--blue);
            text-transform: uppercase;
            letter-spacing: 0.1em;
            font-size: 0.78rem;
            font-weight: 700;
            margin-bottom: 6px;
        }

        .section h2 {
            font-family: Georgia, "Times New Roman", serif;
            color: var(--ink);
            font-size: 2.15rem;
            font-weight: 500;
            line-height: 1.2;
        }

        .about-text {
            max-width: 800px;
            font-size: 1.06rem;
        }

        .about-text p + p {
            margin-top: 15px;
        }

        .research-fields {
            display: flex;
            flex-wrap: wrap;
            gap: 9px;
            margin-bottom: 42px;
        }

        .research-field {
            padding: 7px 12px;
            background: var(--blue-light);
            border: 1px solid #d6e8f1;
            border-radius: 4px;
            color: var(--blue-dark);
            font-size: 0.91rem;
            font-weight: 600;
        }

        .paper-card {
            max-width: 920px;
            padding: 28px 30px;
            border: 1px solid var(--line);
            border-left: 4px solid var(--blue);
            background: #fcfdfd;
        }

        .paper-top {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            gap: 20px;
            margin-bottom: 18px;
        }

        .paper-title {
            font-family: Georgia, "Times New Roman", serif;
            color: var(--ink);
            font-size: 1.43rem;
            line-height: 1.35;
        }

        .paper-status {
            white-space: nowrap;
            padding: 5px 9px;
            background: var(--blue-light);
            color: var(--blue-dark);
            border-radius: 4px;
            font-size: 0.8rem;
            font-weight: 700;
        }

        .abstract-label {
            color: var(--ink);
            font-weight: 700;
            margin-bottom: 6px;
        }

        .abstract {
            color: #46535c;
            text-align: justify;
        }

        .soon {
            margin-top: 17px;
            color: var(--blue);
            font-size: 0.92rem;
            font-weight: 600;
        }

        .timeline {
            max-width: 920px;
        }

        .timeline-item {
            display: grid;
            grid-template-columns: 115px 1fr;
            gap: 25px;
            padding: 23px 0;
            border-bottom: 1px solid var(--line);
        }

        .timeline-item:first-child {
            padding-top: 0;
        }

        .timeline-item:last-child {
            border-bottom: 0;
        }

        .timeline-date {
            color: var(--blue);
            font-weight: 700;
            font-size: 0.92rem;
        }

        .timeline-title {
            color: var(--ink);
            font-weight: 700;
            line-height: 1.45;
            margin-bottom: 4px;
        }

        .timeline-event {
            color: #52616b;
        }

        .timeline-place {
            color: var(--muted);
            font-size: 0.94rem;
            margin-top: 2px;
        }

        .teaching-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 24px;
            max-width: 920px;
        }

        .teaching-card {
            padding: 25px 27px;
            border: 1px solid var(--line);
            background: #fcfdfd;
        }

        .teaching-card h3 {
            color: var(--ink);
            font-family: Georgia, "Times New Roman", serif;
            font-size: 1.3rem;
            font-weight: 500;
            margin-bottom: 3px;
        }

        .teaching-university {
            color: var(--blue);
            font-size: 0.92rem;
            font-weight: 600;
            margin-bottom: 12px;
        }

        .student-note {
            max-width: 920px;
            margin-top: 26px;
            padding: 21px 24px;
            background: var(--blue-light);
            border-left: 4px solid var(--blue);
        }

        .student-note-title {
            color: var(--blue-dark);
            font-weight: 700;
            margin-bottom: 5px;
        }

        .student-note p {
            margin-bottom: 10px;
        }

        .student-email {
            display: block;
            margin-top: 4px;
        }

        .student-email a {
            font-weight: 600;
            text-decoration: none;
        }

        .cv-panel {
            max-width: 780px;
            padding: 30px;
            border: 1px solid var(--line);
            background: #fcfdfd;
        }

        .cv-panel p {
            margin-bottom: 10px;
        }

        .cv-coming {
            color: var(--blue);
            font-weight: 700;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 35px;
            max-width: 800px;
        }

        .contact-title {
            color: var(--ink);
            font-weight: 700;
            margin-bottom: 5px;
        }

        .contact-grid a {
            text-decoration: none;
            font-weight: 600;
        }

        footer {
            background: #f3f6f7;
            border-top: 1px solid var(--line);
            padding: 26px 0;
            color: var(--muted);
            font-size: 0.88rem;
        }

        .footer-inner {
            display: flex;
            justify-content: space-between;
            gap: 25px;
        }

        @media (max-width: 760px) {

            .container {
                width: min(100% - 30px, 1060px);
            }

            .nav-inner {
                min-height: 60px;
            }

            .nav-name {
                display: none;
            }

            .nav-links {
                width: 100%;
                justify-content: space-between;
                gap: 10px;
            }

            .nav-links a {
                font-size: 0.87rem;
            }

            .hero {
                padding: 46px 0;
            }

            .hero-grid {
                grid-template-columns: 1fr;
                text-align: center;
                gap: 28px;
            }

            .hero-photo {
                order: -1;
            }

            .profile-photo {
                width: 145px;
                height: 145px;
            }

            .hero-fields {
                margin-left: auto;
                margin-right: auto;
            }

            .hero-links {
                justify-content: center;
            }

            .section {
                padding: 48px 0;
            }

            .paper-top {
                display: block;
            }

            .paper-status {
                display: inline-block;
                margin-top: 10px;
            }

            .abstract {
                text-align: left;
            }

            .timeline-item {
                grid-template-columns: 1fr;
                gap: 4px;
            }

            .teaching-grid {
                grid-template-columns: 1fr;
            }

            .contact-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .footer-inner {
                flex-direction: column;
                text-align: center;
                gap: 4px;
            }

        }

    </style>

</head>

<body>

    <nav class="navbar">

        <div class="container nav-inner">

            <a class="nav-name" href="#home">
                Ardit Koka
            </a>

            <div class="nav-links">

                <a href="#home">
                    Home
                </a>

                <a href="#research">
                    Research
                </a>

                <a href="#presentations">
                    Presentations
                </a>

                <a href="#teaching">
                    Teaching
                </a>

                <a href="#cv">
                    CV
                </a>

            </div>

        </div>

    </nav>

    <header class="hero" id="home">

        <div class="container hero-grid">

            <div>

                <div class="eyebrow">
                    Economist · PhD Candidate
                </div>

                <h1>
                    Ardit Koka
                </h1>

                <div class="hero-role">
                    PhD Candidate in Methods and Models for Economic Decisions
                </div>

                <div class="hero-institution">
                    Department of Economics · University of Insubria
                </div>

                <div class="hero-fields">
                    Macroeconomics · Monetary Economics · Banking & Financial Intermediation ·
                    Central Bank Digital Currencies · Monetary Policy Transmission
                </div>

                <div class="hero-links">

                    <a class="hero-button" href="#research">
                        Research
                    </a>

                    <a class="hero-button" href="mailto:akoka@uninsubria.it">
                        Email
                    </a>

                    <a
                        class="hero-button"
                        href="https://www.linkedin.com/in/arditkoka"
                        target="_blank"
                        rel="noopener noreferrer"
                    >
                        LinkedIn
                    </a>

                </div>

            </div>

            <div class="hero-photo">

                <img
                    src="Photo.jpeg"
                    alt="Ardit Koka"
                    class="profile-photo"
                >

            </div>

        </div>

    </header>

    <main>

        <section class="section">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        About
                    </div>

                    <h2>
                        Researching money, banking and monetary policy
                    </h2>

                </div>

                <div class="about-text">

                    <p>
                        I am a PhD Candidate in
                        <a
                            href="https://www.phd.eco.uninsubria.it/methods-and-models-for-economic-decisions/phd-students/"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            Methods and Models for Economic Decisions
                        </a>
                        at the University of Insubria.
                    </p>

                    <p>
                        My research examines how changes in money and payment systems
                        interact with bank funding, prudential liquidity, financial
                        intermediation, and monetary-policy transmission.
                    </p>

                    <p>
                        From September 2025 to May 2026, I was a Visiting PhD Researcher
                        at Lancaster University Management School.
                    </p>

                </div>

            </div>

        </section>

        <section class="section" id="research">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        Research
                    </div>

                    <h2>
                        Current research
                    </h2>

                </div>

                <div class="research-fields">

                    <span class="research-field">
                        Macroeconomics
                    </span>

                    <span class="research-field">
                        Monetary Economics
                    </span>

                    <span class="research-field">
                        Banking & Financial Intermediation
                    </span>

                    <span class="research-field">
                        Central Bank Digital Currencies
                    </span>

                    <span class="research-field">
                        Monetary Policy Transmission
                    </span>

                </div>

                <div class="paper-card">

                    <div class="paper-top">

                        <div class="paper-title">
                            When Funding Neutrality Fails:
                            CBDC, Refinancing, and Prudential Liquidity
                        </div>

                        <div class="paper-status">
                            Working paper
                        </div>

                    </div>

                    <div class="abstract-label">
                        Abstract
                    </div>

                    <p class="abstract">
                        This paper studies whether central-bank refinancing can neutralise
                        the bank-credit effects of deposit displacement caused by a capped,
                        non-remunerated retail CBDC. I develop a nonlinear New Keynesian
                        model in which deposits and central-bank refinancing have different
                        implications for prudential liquidity. One-for-one refinancing
                        restores bank funding exactly, but does not generally preserve bank
                        credit. The credit-minimising refinancing ratio can lie above, at,
                        or below one depending on the liquidity transformation generated by
                        refinancing and the persistence of liquidity stress. Quantitatively,
                        one-for-one refinancing is nearly credit-neutral under short-lived
                        stress when refinancing supplies sufficient prudential liquidity,
                        but remains materially non-neutral when stress persists. Credit
                        stabilisation and welfare can also favour different refinancing
                        intensities. Funding neutrality is therefore not sufficient to
                        guarantee equivalence in bank intermediation.
                    </p>

                    <div class="soon">
                        Manuscript available soon
                    </div>

                </div>

            </div>

        </section>

        <section class="section" id="presentations">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        Research communication
                    </div>

                    <h2>
                        Presentations & seminars
                    </h2>

                </div>

                <div class="timeline">

                    <div class="timeline-item">

                        <div class="timeline-date">
                            May 2026
                        </div>

                        <div>

                            <div class="timeline-title">
                                CBDC and Monetary Policy Transmission:
                                A Two-Tier Design with Bank Intermediation Frictions
                            </div>

                            <div class="timeline-event">
                                SoFiE Summer School and Conference on Structural Macro Modelling
                            </div>

                            <div class="timeline-place">
                                National Bank of Belgium · Brussels
                            </div>

                        </div>

                    </div>

                    <div class="timeline-item">

                        <div class="timeline-date">
                            18 May 2026
                        </div>

                        <div>

                            <div class="timeline-title">
                                CBDC and Monetary Policy Transmission:
                                A Two-Tier Design with Bank Intermediation Frictions
                            </div>

                            <div class="timeline-event">
                                Departmental Research Presentation · Department of Economics
                            </div>

                            <div class="timeline-place">
                                Lancaster University
                            </div>

                        </div>

                    </div>

                    <div class="timeline-item">

                        <div class="timeline-date">
                            13 May 2026
                        </div>

                        <div>

                            <div class="timeline-title">
                                CBDC and Monetary Policy Transmission:
                                A Two-Tier Design with Bank Intermediation Frictions
                            </div>

                            <div class="timeline-event">
                                Workshop on Applied Economic Methods ·
                                PhD Programme in Methods and Models for Economic Decisions
                            </div>

                            <div class="timeline-place">
                                Department of Economics · University of Insubria
                            </div>

                        </div>

                    </div>

                    <div class="timeline-item">

                        <div class="timeline-date">
                            30 Apr 2024
                        </div>

                        <div>

                            <div class="timeline-title">
                                From Cryptocurrencies to Central Bank Digital Currencies
                            </div>

                            <div class="timeline-event">
                                Guest Lecture · Postgraduate Course in Monetary and Credit Economics
                            </div>

                            <div class="timeline-place">
                                University of Insubria
                            </div>

                        </div>

                    </div>

                </div>

            </div>

        </section>

        <section class="section" id="teaching">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        Teaching
                    </div>

                    <h2>
                        Economics & quantitative methods
                    </h2>

                </div>

                <div class="teaching-grid">

                    <div class="teaching-card">

                        <h3>
                            Statistics
                        </h3>

                        <div class="teaching-university">
                            Università degli Studi di Milano
                        </div>

                        <p>
                            I teach undergraduate Statistics, covering probability,
                            estimation, statistical inference, hypothesis testing,
                            and regression. Teaching combines theoretical concepts
                            with guided exercises and structured quantitative
                            problem solving.
                        </p>

                    </div>

                    <div class="teaching-card">

                        <h3>
                            Economics & Quantitative Methods
                        </h3>

                        <div class="teaching-university">
                            University of Insubria
                        </div>

                        <p>
                            As an Honorary Fellow and Academic Tutor, I contribute
                            to teaching, examination activities, and student support
                            in Macroeconomics, Monetary and Credit Economics,
                            Statistics, Applied Statistics, Mathematics, and
                            quantitative methods.
                        </p>

                    </div>

                </div>

                <div class="student-note">

                    <div class="student-note-title">
                        Are you one of my students?
                    </div>

                    <p>
                        Questions are welcome — preferably before the evening
                        before the exam. For course-related matters, please use
                        the institutional email for your university.
                    </p>

                    <span class="student-email">
                        University of Insubria:
                        <a href="mailto:akoka@uninsubria.it">
                            akoka@uninsubria.it
                        </a>
                    </span>

                    <span class="student-email">
                        Università degli Studi di Milano:
                        <a href="mailto:ardit.koka@unimi.it">
                            ardit.koka@unimi.it
                        </a>
                    </span>

                </div>

            </div>

        </section>

        <section class="section" id="cv">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        Curriculum Vitae
                    </div>

                    <h2>
                        Academic CV
                    </h2>

                </div>

                <div class="cv-panel">

                    <p>
                        My academic curriculum vitae will be available here shortly.
                    </p>

                    <div class="cv-coming">
                        Academic CV coming soon
                    </div>

                </div>

            </div>

        </section>

        <section class="section" id="contact">

            <div class="container">

                <div class="section-heading">

                    <div class="section-label">
                        Contact
                    </div>

                    <h2>
                        Get in touch
                    </h2>

                </div>

                <div class="contact-grid">

                    <div>

                        <div class="contact-title">
                            University of Insubria
                        </div>

                        <div>
                            Department of Economics<br>
                            Varese, Italy
                        </div>

                        <a href="mailto:akoka@uninsubria.it">
                            akoka@uninsubria.it
                        </a>

                    </div>

                    <div>

                        <div class="contact-title">
                            Online
                        </div>

                        <a
                            href="https://www.linkedin.com/in/arditkoka"
                            target="_blank"
                            rel="noopener noreferrer"
                        >
                            LinkedIn
                        </a>

                    </div>

                </div>

            </div>

        </section>

    </main>

    <footer>

        <div class="container footer-inner">

            <div>
                © <span id="year"></span> Ardit Koka
            </div>

            <div>
                Economics · Monetary Policy · Banking
            </div>

        </div>

    </footer>

    <script>

        document.getElementById("year").textContent =
            new Date().getFullYear();

    </script>

</body>

</html>
