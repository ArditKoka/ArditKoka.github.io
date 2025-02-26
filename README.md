<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="google-site-verification" content="0hJ8jug-XxHPrRFzH_mslLafvPpysxxd8O42VJ3PwuM" />
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ardit Koka | Ph.D. Candidate in Economic Decisions</title>
    
    <!-- SEO Meta Tags -->
    <meta name="description" content="Official website of Ardit Koka, Ph.D. Candidate in Methods and Models for Economic Decisions at the University of Insubria. Researcher in Macroeconomics and Central Bank Digital Currencies.">
    <meta name="keywords" content="Ardit Koka, Economics, Macroeconomics, PhD, DSGE Models, Central Bank Digital Currency, Research, University of Insubria">
    <meta name="author" content="Ardit Koka">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph for Social Media -->
    <meta property="og:title" content="Ardit Koka | Academic Profile">
    <meta property="og:description" content="Ph.D. Candidate in Economic Decisions, Researcher in DSGE Models and Macroeconomics.">
    <meta property="og:image" content="https://yourgithubpage.com/Photo.jpeg">
    <meta property="og:url" content="https://yourgithubpage.com">
    <meta property="og:site_name" content="Ardit Koka">
    
    <!-- Structured Data for Google -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Person",
      "name": "Ardit Koka",
      "jobTitle": "Ph.D. Candidate in Economic Decisions",
      "affiliation": {
        "@type": "Organization",
        "name": "University of Insubria"
      },
      "url": "https://yourgithubpage.com",
      "sameAs": [
        "https://www.linkedin.com/in/ardit-koka-7758941aa",
        "https://www.phd.eco.uninsubria.it/methods-and-models-for-economic-decisions/phd-students/",
        "https://archive.uninsubria.eu/hpp/ardit.koka"
      ],
      "image": "https://yourgithubpage.com/Photo.jpeg"
    }
    </script>
    
    <style>
        :root {
            --primary-color: #006699;
            --secondary-color: #0077AA;
            --accent-color: #3498db;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --text-color: #333;
            --link-color: #2980b9;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: #f9f9f9;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        .tabs {
            display: flex;
            border-bottom: 2px solid var(--primary-color);
            margin-bottom: 2rem;
        }
        
        .tab {
            padding: 1rem 2rem;
            cursor: pointer;
            background-color: #e1e5e9;
            color: var(--dark-color);
            font-weight: 600;
            border: none;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;
            margin-right: 0.5rem;
            transition: all 0.3s;
        }
        
        .tab.active {
            background-color: var(--primary-color);
            color: white;
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="profile">
                <img src="Photo.jpeg" alt="Ardit Koka" class="profile-img">
                <div class="profile-info">
                    <h1>Ardit Koka</h1>
                    <div class="subtitle">Ph.D. Candidate in Methods and Models for Economic Decisions</div>
                </div>
            </div>
        </div>
    </header>
    
    <main class="container">
        <div class="tabs">
            <button class="tab active" onclick="openTab(event, 'home')">Home</button>
            <button class="tab" onclick="openTab(event, 'research')">Research</button>
            <button class="tab" onclick="openTab(event, 'teaching')">Teaching</button>
            <button class="tab" onclick="openTab(event, 'cv')">CV</button>
        </div>
        
        <div id="home" class="tab-content active">
            <h2>Welcome</h2>
            <p>I am a Ph.D. Candidate in <a href="https://www.phd.eco.uninsubria.it/methods-and-models-for-economic-decisions/phd-students/" target="_blank">Methods and Models for Economic Decisions</a> at the University of Insubria. Previously, I worked as an auditor for Deloitte. My research focuses on Macroeconomics, Monetary Economics, Central Bank Digital Currency, Money, and Banking.</p>
        </div>
    </main>
    
    <script>
        function openTab(evt, tabName) {
            var tabContents = document.querySelectorAll(".tab-content");
            tabContents.forEach(content => content.classList.remove("active"));
            
            var tabs = document.querySelectorAll(".tab");
            tabs.forEach(tab => tab.classList.remove("active"));
            
            document.getElementById(tabName).classList.add("active");
            evt.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>
