<html lang="en">

<head>

    <meta name="google-site-verification" content="0hJ8jug-XxHPrRFzH_mslLafvPpysxxd8O42VJ3PwuM">

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ardit Koka | Economics</title>

    <meta
        name="description"
        content="Academic website of Ardit Koka, PhD Candidate at the University of Insubria. Research in macroeconomics, monetary economics, banking, financial intermediation and central bank digital currencies."
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
            line-height: 1.15;
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

        .tab:focus-visible {
            outline: 3px solid rgba(41, 128, 185, 0.35);
            outline-offset: 2px;
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
            margin-top: 38px;
        }

        h3 {
            color: var(--primary-color);
            font-size: 1.15rem;
            margin-top: 25px;
            margin-bottom: 8px;
        }

        p {
            max-width: 1000px;
        }

        p + p {
            margin-top: 14px;
        }

        ul {
            margin-top: 10px;
            padding-left: 24px;
            max-width: 1000px;
        }

        li {
            margin-bottom: 8px;
        }

        .research-interests {
            font-size: 1.05rem;
            line-height: 1.8;
        }

        .paper {
            max-width: 1000px;
        }

        .paper-title {
            font-size: 1.17rem;
            font-weight: 700;
            color: #25384b;
        }

        .paper-status {
            color: var(--primary-color);
            font-size: 0.96rem;
            font-weight: 600;
            margin-top: 5px;
            margin-bottom: 18px;
        }

        .abstract-label {
            font-weight: 700;
            margin-bottom: 6px;
        }

        .abstract {
            color: #40484f;
            text-align: justify;
        }

        .presentation {
            margin-bottom: 24px;
            max-width: 1000px;
        }

        .presentation-title {
            font-weight: 700;
            font-size: 1.04rem;
        }

        .presentation-event {
            color: #4f5d68;
            margin-top: 3px;
        }

        .presentation-location {
            margin-top: 1px;
        }

        .teaching-block {
            max-width: 1000px;
            margin-bottom: 32px;
        }

        .teaching-title {
            font-size: 1.15rem;
            font-weight: 700;
            color: #25384b;
            margin-bottom: 2px;
        }

        .teaching-institution {
            color: #4f5d68;
            margin-bottom: 10px;
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

        .cv-box {
            max-width: 720px;
        }

        .cv-status {
            margin-top: 12px;
            color: var(--primary-color);
            font-weight: 600;
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
                flex: 1 1 calc(50% - 5px);
                margin-right: 0;
                padding: 13px 15px;
            }

            .tab-content {
                padding-left: 5px;
                padding-right: 5px;
            }

            .abstract {
                text-align: left;
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
                data-tab="home"
            >
                Home
            </button>

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
                data-tab="research"
            >
                Research
            </button>

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
                data-tab="teaching"
            >
                Teaching
            </button>

            <button
                class="tab"
                type="button"
                role="tab"
                aria-selected="false"
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

            <h2>About</h2>

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
                My research lies at the intersection of macroeconomics,
                monetary economics, banking, and digital finance.
                I am particularly interested in central bank digital currencies,
                bank funding and financial intermediation, prudential liquidity
                regulation, financial stability, and monetary-policy transmission.
            </p>

            <p>
                From September 2025 to May 2026, I was a Visiting PhD Researcher
                at Lancaster University Management School.
            </p>

            <h2>Contact</h2>

            <p>
                Department of Economics<br>
                University of Insubria<br>
                Varese, Italy
            </p>

            <div class="contact-links">

                <a href="mailto:akoka@uninsubria.it">
                    akoka@uninsubria.it
                </a>

                <a
                    href="https://it.linkedin.com/in/ardit-koka-7758941aa"
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
                Monetary Policy Transmission · Financial Stability · DSGE Models
            </p>

            <h2>Working Papers</h2>

            <div class="paper">

                <div class="paper-title">
                    When Funding Neutrality Fails: CBDC, Refinancing, and Prudential Liquidity
                </div>

                <div class="paper-status">
                    Working paper · Manuscript available soon
                </div>

                <div class="abstract-label">
                    Abstract
                </div>

                <p class="abstract">
                    This paper studies whether central-bank refinancing can neutralise
                    the bank-credit effects of deposit displacement caused by a capped,
                    non-remunerated retail CBDC. I develop a nonlinear New Keynesian
                    model with cash, bank deposits, CBDC, central-bank refinancing,
                    marketable liquid assets, and an occasionally binding
                    prudential-liquidity requirement. One-for-one refinancing restores
                    the quantity of bank funding exactly, but it does not generally
                    preserve bank credit because deposits and central-bank borrowing
                    have different implications for prudential liquidity. The
                    credit-minimising refinancing ratio can therefore lie above, at,
                    or below one-for-one depending on the net liquidity transformation
                    generated by refinancing and the persistence of liquidity stress.
                    Quantitatively, one-for-one refinancing is nearly credit-neutral
                    under short-lived stress when refinancing generates sufficient
                    prudential liquidity, but remains materially non-neutral when
                    liquidity stress persists. Moreover, the refinancing ratio that
                    best stabilises credit need not maximise welfare. Replacing the
                    quantity of deposits displaced by CBDC is therefore not sufficient
                    to guarantee equivalence in bank intermediation.
                </p>

            </div>

            <h2>Presentations & Seminars</h2>

            <div class="presentation">

                <div class="presentation-title">
                    CBDC and Monetary Policy Transmission:
                    A Two-Tier Design with Bank Intermediation Frictions
                </div>

                <div class="presentation-event">
                    SoFiE Summer School and Conference on Structural Macro Modelling
                </div>

                <div class="presentation-location">
                    National Bank of Belgium · Brussels · May 2026
                </div>

            </div>

            <div class="presentation">

                <div class="presentation-title">
                    CBDC and Monetary Policy Transmission:
                    A Two-Tier Design with Bank Intermediation Frictions
                </div>

                <div class="presentation-event">
                    Departmental Research Presentation · Department of Economics
                </div>

                <div class="presentation-location">
                    Lancaster University · 18 May 2026
                </div>

            </div>

            <div class="presentation">

                <div class="presentation-title">
                    CBDC and Monetary Policy Transmission:
                    A Two-Tier Design with Bank Intermediation Frictions
                </div>

                <div class="presentation-event">
                    Workshop on Applied Economic Methods ·
                    PhD Programme in Methods and Models for Economic Decisions
                </div>

                <div class="presentation-location">
                    Department of Economics, University of Insubria · 13 May 2026
                </div>

            </div>

            <h2>Invited & Guest Lectures</h2>

            <div class="presentation">

                <div class="presentation-title">
                    From Cryptocurrencies to Central Bank Digital Currencies
                </div>

                <div class="presentation-event">
                    Postgraduate Course in Monetary and Credit Economics
                </div>

                <div class="presentation-location">
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

            <div class="teaching-block">

                <div class="teaching-title">
                    Statistics
                </div>

                <div class="teaching-institution">
                    Università degli Studi di Milano
                </div>

                <p>
                    I teach undergraduate Statistics, covering probability,
                    estimation, statistical inference, hypothesis testing,
                    and regression. Teaching combines theoretical concepts with
                    guided exercises, quantitative problem solving, and preparation
                    of assessment materials.
                </p>

            </div>

            <div class="teaching-block">

                <div class="teaching-title">
                    Economics & Quantitative Methods
                </div>

                <div class="teaching-institution">
                    University of Insubria
                </div>

                <p>
                    As an Honorary Fellow and Academic Tutor, I contribute to
                    teaching, examination activities, and student support in
                    Macroeconomics, Monetary and Credit Economics, Statistics,
                    Applied Statistics, Mathematics, and quantitative methods.
                </p>

            </div>

            <h2>Teaching Approach</h2>

            <p>
                My teaching emphasises economic and statistical intuition alongside
                structured problem solving. I aim to help students understand not
                only how to apply a method, but why it is appropriate and how to
                interpret the result.
            </p>

        </section>

        <section
            id="cv"
            class="tab-content"
            role="tabpanel"
        >

            <div class="cv-box">

                <h2>Curriculum Vitae</h2>

                <p>
                    My academic curriculum vitae will be available here shortly.
                </p>

                <div class="cv-status">
                    Academic CV coming soon
                </div>

            </div>

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

                tab.setAttribute(
                    "aria-selected",
                    String(isActive)
                );

            });

            targetPanel.classList.add("active");

            if (updateHash) {

                history.replaceState(
                    null,
                    "",
                    "#" + tabName
                );

            }

        }

        tabs.forEach(tab => {

            tab.addEventListener("click", () => {
                activateTab(tab.dataset.tab);
            });

        });

        const initialTab =
            window.location.hash.replace("#", "");

        if (
            initialTab &&
            document.getElementById(initialTab)
        ) {

            activateTab(initialTab, false);

        }

        document.getElementById("year").textContent =
            new Date().getFullYear();

    </script>

</body>

</html>
