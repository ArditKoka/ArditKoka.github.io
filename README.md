<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="google-site-verification" content="0hJ8jug-XxHPrRFzH_mslLafvPpysxxd8O42VJ3PwuM">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ardit Koka | Economics</title>

    <meta
        name="description"
        content="Academic website of Ardit Koka, PhD Candidate at the University of Insubria. Research in macroeconomics, monetary economics, banking, monetary policy and central bank digital currencies."
    >

    <style>
        :root {
            --primary-color: #006699;
            --primary-dark: #004d73;
            --accent-color: #2980b9;
            --text-color: #333333;
            --muted-color: #66727c;
            --white: #ffffff;
            --page-bg: #f9f9f9;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.65;
            color: var(--text-color);
            background-color: var(--page-bg);
        }

        a {
            color: var(--accent-color);
        }

        a:hover {
            text-decoration-thickness: 2px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 18px;
        }

        header {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 40px 0;
            margin-bottom: 32px;
            border-bottom: 1px solid var(--primary-dark);
        }

        .profile {
            display: flex;
            align-items: center;
            gap: 40px;
        }

        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid var(--white);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .profile-info {
            flex: 1;
        }

        .profile-info h1 {
            font-size: 2.8rem;
            margin-bottom: 8px;
        }

        .profile-info .subtitle {
            font-size: 1.3rem;
            opacity: 0.95;
            margin-bottom: 8px;
        }

        .profile-info .institution {
            font-size: 1.05rem;
            opacity: 0.9;
        }

        .tabs {
            display: flex;
            flex-wrap: wrap;
            border-bottom: 2px solid var(--primary-color);
            margin-bottom: 30px;
        }

        .tab {
            padding: 15px 32px;
            cursor: pointer;
            background-color: #e1e5e9;
            color: #23364d;
            font: inherit;
            font-weight: 600;
            border: none;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
            margin-right: 10px;
            transition: background-color 0.2s ease, color 0.2s ease;
        }

        .tab.active {
            background-color: var(--primary-color);
            color: var(--white);
        }

        .tab:hover:not(.active) {
            background-color: #d1d7de;
        }

        .tab-content {
            display: none;
            padding: 8px 18px 50px;
        }

        .tab-content.active {
            display: block;
        }

        h2 {
            color: var(--primary-dark);
            font-size: 1.75rem;
            margin-bottom: 14px;
        }

        h2:not(:first-child) {
            margin-top: 34px;
        }

        h3 {
            color: var(--primary-color);
            font-size: 1.15rem;
            margin-top: 24px;
            margin-bottom: 7px;
        }

        p {
            max-width: 1000px;
        }

        p + p {
            margin-top: 14px;
        }

        ul {
            margin-top: 10px;
            padding-left: 25px;
        }

        li {
            margin-bottom: 8px;
        }

        .research-interests {
            font-size: 1.05rem;
            line-height: 1.8;
        }

        .paper {
            margin-top: 16px;
        }

        .paper-title {
            font-size: 1.08rem;
            font-weight: 700;
        }

        .presentation {
            margin-bottom: 22px;
        }

        .presentation-title {
            font-weight: 700;
        }

        .presentation-place {
            color: #4f5d68;
        }

        .role {
            margin-bottom: 25px;
        }

        .role-title {
            font-weight: 700;
            font-size: 1.08rem;
        }

        .role-place {
            color: #4f5d68;
            margin-bottom: 6px;
        }

        .contact-links {
            margin-top: 15px;
            display: flex;
            flex-wrap: wrap;
            gap: 18px;
        }

        .contact-links a {
            font-weight: 600;
            text-decoration: none;
        }

        .contact-links a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            color: var(--muted-color);
            padding: 25px 0 35px;
            font-size: 0.9rem;
        }

        @media (max-width: 700px) {
            header {
                padding: 30px 0;
            }

            .profile {
                flex-direction: column;
                text-align: center;
                gap: 20px;
            }

            .profile-img {
                width: 160px;
                height: 160px;
            }

            .profile-info h1 {
                font-size: 2.2rem;
            }

            .profile-info .subtitle {
                font-size: 1.1rem;
            }

            .tabs {
                gap: 5px;
            }

            .tab {
                flex: 1;
                margin-right: 0;
                padding: 13px 15px;
            }

            .tab-content {
                padding-left: 5px;
                padding-right: 5px;
            }

            .contact-links {
                justify-content: center;
            }
        }
    </style>
</head>

<body>

    <header>
        <div class="container">
            <div class="profile">

                <img
                    src="Photo.jpeg"
                    alt="Ardit Koka"
                    class="profile-img"
                >

                <div class="profile-info">

                    <h1>Ardit Koka</h1>

                    <div class="subtitle">
                        PhD Candidate in Economics
                    </div>

                    <div class="institution">
                        Methods and Models for Economic Decisions · University of Insubria
                    </div>

                </div>

            </div>
        </div>
    </header>

    <main class="container">

        <nav
            class="tabs"
            role="tablist"
            aria-label="Academic website sections"
        >

            <button
                class="tab active"
                type="button"
                role="tab"
                aria-selected="true"
                aria-controls="home"
                data-tab="home"
            >
                Home
            </button>

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
                aria-controls="research"
                data-tab="research"
            >
                Research
            </button>

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
                aria-controls="teaching"
                data-tab="teaching"
            >
                Teaching
            </button>

        </nav>

        <section
            id="home"
            class="tab-content active"
            role="tabpanel"
        >

            <h2>Welcome</h2>

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
                My research focuses on macroeconomics, monetary economics,
                money and banking, financial intermediation, central bank digital
                currencies, and monetary-policy transmission.
            </p>

            <p>
                From September 2025 to May 2026, I was a Visiting PhD Researcher
                at Lancaster University Management School, where I developed my
                research in an international academic environment and participated
                in seminars, workshops, and research discussions.
            </p>

            <h2>Current Academic Activities</h2>

            <p>
                Alongside my doctoral research, I teach Statistics at
                Università degli Studi di Milano and serve as Cultore della Materia
                and Academic Tutor at the University of Insubria.
            </p>

            <h2>Contact</h2>

            <p>
                Department of Economics<br>
                University of Insubria<br>
                Varese, Italy
            </p>

            <div class="contact-links">

                <a href="mailto:akoka@uninsubria.it">
                    Email
                </a>

                <a
                    href="https://www.linkedin.com/in/arditkoka"
                    target="_blank"
                    rel="noopener noreferrer"
                >
                    LinkedIn
                </a>

            </div>

        </section>

        <section
            id="research"
            class="tab-content"
            role="tabpanel"
        >

            <h2>Research Interests</h2>

            <p class="research-interests">
                Macroeconomics · Monetary Economics · Money and Banking ·
                Financial Intermediation · Central Bank Digital Currencies ·
                Monetary Policy Transmission · DSGE Models
            </p>

            <h2>Working Papers</h2>

            <div class="paper">
                <div class="paper-title">
                    When Funding Neutrality Fails: CBDC, Refinancing, and Prudential Liquidity
                </div>
            </div>

            <h2>Presentations & Seminars</h2>

            <div class="presentation">

                <div class="presentation-title">
                    CBDC and Monetary Policy Transmission:
                    A Two-Tier Design with Bank Intermediation Frictions
                </div>

                <div class="presentation-place">
                    SoFiE Summer School and Conference on Structural Macro Modelling
                </div>

                <div>
                    National Bank of Belgium, Brussels · May 2026
                </div>

            </div>

            <div class="presentation">

                <div class="presentation-title">
                    CBDC and Monetary Policy Transmission:
                    A Two-Tier Design with Bank Intermediation Frictions
                </div>

                <div class="presentation-place">
                    Departmental Research Presentation, Department of Economics
                </div>

                <div>
                    Lancaster University · 18 May 2026
                </div>

            </div>

            <h2>Invited & Guest Lectures</h2>

            <div class="presentation">

                <div class="presentation-title">
                    From Cryptocurrencies to Central Bank Digital Currencies
                </div>

                <div class="presentation-place">
                    Postgraduate Course in Monetary and Credit Economics
                </div>

                <div>
                    University of Insubria · 30 April 2024
                </div>

            </div>

        </section>

        <section
            id="teaching"
            class="tab-content"
            role="tabpanel"
        >

            <h2>Teaching</h2>

            <div class="role">

                <div class="role-title">
                    Lecturer in Statistics
                </div>

                <div class="role-place">
                    Università degli Studi di Milano · October 2024 – Present
                </div>

                <p>
                    Teaching Statistics to large undergraduate cohorts, covering
                    probability, estimation, statistical inference, hypothesis testing,
                    and regression.
                </p>

            </div>

            <div class="role">

                <div class="role-title">
                    Cultore della Materia and Academic Tutor
                </div>

                <div class="role-place">
                    University of Insubria · 2024 – Present
                </div>

                <p>
                    Member of examination committees and provider of individual
                    and group academic support across economics and quantitative subjects.
                </p>

            </div>

            <h3>Examination Committees</h3>

            <ul>
                <li>Macroeconomics</li>
                <li>Monetary and Credit Economics</li>
                <li>Statistics</li>
                <li>Mathematics</li>
                <li>Mathematics for Economics and Finance</li>
            </ul>

            <h3>Academic Tutoring</h3>

            <p>
                Tutoring activities have included economics, statistics,
                probability, mathematics, quantitative methods, and applied statistics
                across undergraduate and postgraduate programmes at the University
                of Insubria.
            </p>

        </section>

    </main>

    <footer class="container">
        &copy; <span id="year"></span> Ardit Koka
    </footer>

    <script>
        const tabs = document.querySelectorAll(".tab");
        const panels = document.querySelectorAll(".tab-content");

        function activateTab(tabName, updateHash = true) {
            const targetPanel = document.getElementById(tabName);

            if (!targetPanel) {
                return;
            }

            panels.forEach(panel => {
                panel.classList.remove("active");
            });

            tabs.forEach(tab => {
                const isActive = tab.dataset.tab === tabName;
                tab.classList.toggle("active", isActive);
                tab.setAttribute("aria-selected", String(isActive));
            });

            targetPanel.classList.add("active");

            if (updateHash) {
                history.replaceState(null, "", "#" + tabName);
            }
        }

        tabs.forEach(tab => {
            tab.addEventListener("click", () => {
                activateTab(tab.dataset.tab);
            });
        });

        const initialTab = window.location.hash.replace("#", "");

        if (initialTab && document.getElementById(initialTab)) {
            activateTab(initialTab, false);
        }

        document.getElementById("year").textContent = new Date().getFullYear();
    </script>

</body>
</html>
