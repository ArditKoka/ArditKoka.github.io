<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Ardit Koka | Academic</title>
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
        
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-bottom: 2rem;
            border-bottom: 1px solid #004d73;
        }
        
        .profile {
            display: flex;
            align-items: center;
            gap: 2rem;
            flex-wrap: wrap;
        }
        
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        
        .profile-info h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .profile-info .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 1rem;
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
        
        .tab:hover:not(.active) {
            background-color: #d1d7de;
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
                    <div class="subtitle">Ph.D. Candidate in <a href="https://www.phd.eco.uninsubria.it/methods-and-models-for-economic-decisions/phd-students/" target="_blank">Methods and Models for Economic Decisions</a></div>
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
            <p>I am a Ph.D. Candidate in <a href="https://www.phd.eco.uninsubria.it/methods-and-models-for-economic-decisions/phd-students/" target="_blank">Methods and Models for Economic Decisions</a> at the University of Insubria. Previously, I worked as an auditor for Deloitte. I hold a Master's degree in International Economics and Commerce from Università Politecnica delle Marche. My research focuses on Macroeconomics, Monetary Economics, Central Bank Digital Currency, Money, and Banking.</p>
            <h2>Contact Details</h2>
            <p>Via Monte Generoso, 71<br>21100 Varese VA<br>Italy</p>
            <p>Email: <a href="mailto:akoka@uninsubria.it">akoka@uninsubria.it</a></p>
        </div>
        
        <div id="research" class="tab-content">
            <h2>Research Interests</h2>
            <p>Macroeconomics, Monetary Economics, DSGE Models, and Central Bank Digital Currencies.</p>
            <h2>Working Papers</h2>
        </div>
        
        <div id="teaching" class="tab-content">
            <h2>Teaching</h2>
            <h3>Courses</h3>
            <p>Statistics - Università degli Studi di Milano</p>
            <h3>Member of the Examination Committee and Tutor for the Following Courses - Department of Economics - University of Insubria</h3>
            <ul>
                <li>Macroeconomics</li>
                <li>Monetary and Credit Economics</li>
                <li>Statistics</li>
                <li>Mathematics</li>
                <li>Mathematics for Finance</li>
            </ul>
            <h3>Talks, Seminars, Open Lectures</h3>
            <p>From Crypto Currencies to Central Bank Digital Currencies - Guest Lecturer Postgraduate Course in Monetary and Credit Economics - 30/04/2024 - University of Insubria</p>
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
