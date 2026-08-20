<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="google-site-verification" content="0hJ8jug-XxHPrRFzH_mslLafvPpysxxd8O42VJ3PwuM">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ardit Koka | Academic Website</title>

    <meta
        name="description"
        content="Academic website of Ardit Koka, PhD Candidate in Methods and Models for Economic Decisions at the University of Insubria. Research in macroeconomics, monetary economics, banking and central bank digital currencies."
    >

    <style>
        :root {
            --primary-color: #006699;
            --primary-dark: #004d73;
            --accent-color: #2980b9;
            --text-color: #2f3740;
            --muted-color: #66727c;
            --white: #ffffff;
            --page-bg: #f7f9fb;
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
            max-width: 1050px;
            margin: 0 auto;
            padding: 0 24px;
        }

        header {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 42px 0;
            border-bottom: 4px solid var(--primary-dark);
        }

        .profile {
            display: flex;
            align-items: center;
            gap: 32px;
        }

        .profile-img {
            width: 170px;
            height: 170px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--white);
            box-shadow: 0 6px 22px rgba(0, 0, 0, 0.18);
        }

        .profile-info h1 {
            font-size: clamp(2rem, 5vw, 3rem);
            line-height: 1.15;
            margin-bottom: 10px;
        }

        .profile-info .subtitle {
            font-size: 1.15rem;
            opacity: 0.95;
            max-width: 720px;
        }

        main {
            padding-top: 30px;
            padding-bottom: 60px;
        }

        .tabs {
            display: flex;
            flex-wrap: wrap;
            gap: 6px;
            border-bottom: 2px solid var(--primary-color);
            margin-bottom: 28px;
        }

        .tab {
            padding: 12px 22px;
            cursor: pointer;
            background-color: #e4e9ed;
            color: var(--text-color);
            font: inherit;
            font-weight: 650;
            border: none;
            border-radius: 6px 6px 0 0;
            transition: background-color 0.2s ease, color 0.2s ease;
        }

        .tab:hover {
            background-color: #d6dee4;
        }

        .tab.active {
            background-color: var(--primary-color);
            color: var(--white);
        }

        .tab:focus-visible {
            outline: 3px solid rgba(41, 128, 185, 0.35);
            outline-offset: 2px;
        }

        .tab-content {
            display: none;
            background-color: var(--white);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 3px 16px rgba(0, 0, 0, 0.06);
        }

        .tab-content.active {
            display: block;
        }

        h2 {
            color: var(--primary-dark);
            font-size: 1.65rem;
            margin: 0 0 14px;
        }

        h2:not(:first-child) {
            margin-top: 30px;
        }

        h3 {
            color: var(--primary-color);
            font-size: 1.12rem;
            margin: 24px 0 8px;
        }

        p + p {
            margin-top: 14px;
        }

        ul {
            padding-left: 24px;
            margin-top: 10px;
        }

        .research-list {
            margin-top: 8px;
        }

        .cv-button {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 16px;
            background-color: var(--primary-color);
            color: var(--white);
            text-decoration: none;
            border-radius: 6px;
            font-weight: 650;
        }

        .cv-button:hover {
            background-color: var(--primary-dark);
        }

        footer {
            text-align: center;
            color: var(--muted-color);
            padding: 22px 0 35px;
            font-size: 0.9rem;
        }

        @media (max-width: 680px) {
            header {
                padding: 30px 0;
            }

            .profile {
                flex-direction: column;
                text-align: center;
                gap: 18px;
            }

            .profile-img {
                width: 145px;
                height: 145px;
            }

            .tabs {
                gap: 4px;
            }

            .tab {
                flex: 1 1 calc(50% - 4px);
                text-align: center;
                padding: 11px 10px;
            }

            .tab-content {
                padding: 22px;
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
                        PhD Candidate in Methods and Models for Economic Decisions
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

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
                aria-controls="cv"
                data-tab="cv"
            >
                CV
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
                Previously, I worked as an auditor for Deloitte.
                I hold a Master's degree in International Economics and Commerce
                from Università Politecnica delle Marche.
            </p>

            <p>
                My research focuses on macroeconomics, monetary economics,
                central bank digital currencies, money and banking,
                and monetary-policy transmission.
            </p>

            <h2>Contact</h2>

            <p>
                Department of Economics<br>
                University of Insubria<br>
                Via Monte Generoso, 71<br>
                21100 Varese, Italy
            </p>

            <p>
                Email:
                <a href="mailto:akoka@uninsubria.it">
                    akoka@uninsubria.it
                </a>
            </p>

        </section>

        <section
            id="research"
            class="tab-content"
            role="tabpanel"
        >

            <h2>Research Interests</h2>

            <p>
                Macroeconomics, monetary economics, money and banking,
                DSGE models, central bank digital currencies,
                financial intermediation and monetary-policy transmission.
            </p>

            <h2>Working Papers</h2>

            <ul class="research-list">
                <li>
                    <strong>
                        When Funding Neutrality Fails:
                        CBDC, Refinancing, and Prudential Liquidity
                    </strong>
                </li>
            </ul>

        </section>

        <section
            id="teaching"
            class="tab-content"
            role="tabpanel"
        >

            <h2>Teaching</h2>

            <h3>Università degli Studi di Milano</h3>

            <p>
                Statistics
            </p>

            <h3>
                University of Insubria — Examination Committees and Tutoring
            </h3>

            <ul>
                <li>Macroeconomics</li>
                <li>Monetary and Credit Economics</li>
                <li>Statistics</li>
                <li>Mathematics</li>
                <li>Mathematics for Finance</li>
            </ul>

            <h3>Talks, Seminars, and Open Lectures</h3>

            <p>
                <em>
                    From Cryptocurrencies to Central Bank Digital Currencies
                </em>
                — Guest lecture, postgraduate course in Monetary and Credit Economics,
                University of Insubria, 30 April 2024.
            </p>

        </section>

        <section
            id="cv"
            class="tab-content"
            role="tabpanel"
        >

            <h2>Curriculum Vitae</h2>

            <p>
                A PDF version of my curriculum vitae is available below.
            </p>

            <a
                class="cv-button"
                href="cv/Ardit_Koka_CV.pdf"
                target="_blank"
                rel="noopener noreferrer"
            >
                Open CV
            </a>

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
