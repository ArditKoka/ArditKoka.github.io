<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Ardit Koka | Accademico</title>
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
        
        .contact-info {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .contact-info a {
            color: white;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .contact-info a:hover {
            text-decoration: underline;
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
        
        section {
            margin-bottom: 2.5rem;
        }
        
        h2 {
            color: var(--primary-color);
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent-color);
            font-size: 1.8rem;
        }
        
        h3 {
            color: var(--secondary-color);
            margin-bottom: 0.5rem;
            font-size: 1.4rem;
        }
        
        .card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 1.5rem;
            margin-bottom: 1.5rem;
        }
        
        .card-title {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 0.5rem;
        }
        
        .institution {
            color: var(--secondary-color);
            font-weight: 600;
            margin-bottom: 0.5rem;
        }
        
        .date {
            color: #666;
            font-size: 0.9rem;
        }
        
        .location {
            color: #666;
            font-style: italic;
            margin-bottom: 1rem;
        }
        
        ul {
            padding-left: 1.5rem;
            margin-bottom: 1rem;
        }
        
        li {
            margin-bottom: 0.3rem;
        }
        
        footer {
            background-color: var(--dark-color);
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .skill {
            background-color: var(--light-color);
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-size: 0.9rem;
            color: var(--dark-color);
        }
        
        .research-interest {
            margin-bottom: 2rem;
        }
        
        .research-interest h3 {
            margin-bottom: 0.5rem;
        }
        
        @media (max-width: 768px) {
            .profile {
                flex-direction: column;
                text-align: center;
            }
            
            .contact-info {
                justify-content: center;
            }
            
            .tab {
                padding: 0.8rem 1.2rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="profile">
                <img src="/api/placeholder/200/200" alt="Ardit Koka" class="profile-img">
                <div class="profile-info">
                    <h1>Ardit Koka</h1>
                    <div class="subtitle">Ph.D. Candidate in Methods and Models for Economic Decisions</div>
                   
                    
                    <div class="contact-info">
                        <a href="mailto:akoka@uninsubria.it">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
                            </svg>
                            akoka@uninsubria.it
                        </a>
                        <a href="mailto:koka.ardit2@gmail.com">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16">
                                <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"/>
                            </svg>
                            koka.ardit2@gmail.com
                        </a>
                    </div>
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
        
        <!-- Home Section -->
        <div id="home" class="tab-content active">
            <section>
                <h2>Chi sono</h2>
                <div class="card">
                    <p>Sono un PhD Candidate in Methods and Models for Economic Decisions presso l'Università degli Studi dell'Insubria. Attualmente lavoro come Lecturer in Statistics presso l'Università degli Studi di Milano e sono Honorary Fellow presso l'Università degli Studi dell'Insubria.</p>
                    <p>I miei interessi di ricerca includono Macroeconomia, Economia Monetaria e modelli DSGE con un focus particolare sulle valute digitali delle banche centrali.</p>
                </div>
            </section>
            
            <section>
                <h2>Attività Correnti</h2>
                
                <div class="card">
                    <ul>
                        <li>Ricerca sui modelli DSGE con applicazioni in economia monetaria</li>
                        <li>Analisi dell'impatto delle valute digitali delle banche centrali sul sistema finanziario</li>
                        <li>Insegnamento di Statistica agli studenti universitari</li>
                        <li>Tutoraggio in ambito matematico ed economico</li>
                    </ul>
                </div>
            </section>
        </div>
        
        <!-- Research Section -->
        <div id="research" class="tab-content">
            <section>
                <h2>Interessi di Ricerca</h2>
                
                <div class="research-interest">
                    <p>Macroeconomia</p>
                    <p>Economia Monetaria</p>
                    <p>Modelli New Keynesian</p>

                </div>
            </section>
            
            <section>
                <h2>Progetti di Ricerca in Corso</h2>
                
                <div class="card">
                    <h3>From Crypto Currencies to Central Bank Digital Currencies</h3>
                    <p>Analisi del potenziale impatto dell'introduzione dell'Euro digitale sul sistema bancario dell'Eurozona, con particolare attenzione agli aspetti relativi alla stabilità finanziaria.</p>
                </div>
                
                <div class="card">
                    <h3>Innovation Camp for PhD Students (Progetto Vincitore 2024)</h3>
                    <p>Sviluppo di un modello innovativo per l'analisi delle politiche monetarie in un contesto di digitalizzazione del sistema finanziario.</p>
                </div>
            </section>
        </div>
        
        <!-- Teaching Section -->
        <div id="teaching" class="tab-content">
            <section>
                <h2>Insegnamento</h2>
                
                <div class="card">
                    <h3>Corsi</h3>
                    <ul>
                        <li><strong>Statistica</strong> - Università degli Studi di Milano</li>
                        <li><strong>Esercitazioni di Macroeconomia</strong> - Università degli Studi dell'Insubria</li>
                        <li><strong>Supporto didattico in Matematica per l'Economia</strong> - Università degli Studi dell'Insubria</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>Attività Accademica</h3>
                    <ul>
                        <li>Membro della commissione d'esame come Honorary Fellow</li>
                        <li>Tutoraggio individuale per studenti in discipline economiche e statistiche</li>
                        <li>Supervisione di gruppi di studio per corsi di base e avanzati</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>Approccio Didattico</h3>
                    <p>Il mio metodo di insegnamento combina rigore teorico e applicazioni pratiche, con particolare attenzione all'utilizzo di software statistici e modelli matematici per l'analisi economica.</p>
                </div>
            </section>
        </div>
        
        <!-- CV Section -->
        <div id="cv" class="tab-content">
            <section>
                <h2>Curriculum Vitae</h2>
                
                <div class="card">
                    <p>Per informazioni dettagliate sul mio percorso accademico e professionale, puoi scaricare il mio CV completo utilizzando il link qui sotto.</p>
                    <div style="text-align: center; margin: 20px 0;">
                        <a href="#" style="background-color: var(--primary-color); color: white; text-decoration: none; padding: 10px 20px; border-radius: 5px; font-weight: bold;">Scarica CV (PDF)</a>
                    </div>
                </div>
            </section>
            
            <section>
                <h2>Competenze Principali</h2>
                
                <div class="card">
                    <div class="skills-container">
                        <span class="skill">Modelli DSGE</span>
                        <span class="skill">Stima Bayesiana</span>
                        <span class="skill">Analisi statistica</span>
                        <span class="skill">Econometria</span>
                        <span class="skill">Matlab/Dynare</span>
                        <span class="skill">R</span>
                        <span class="skill">Stata</span>
                        <span class="skill">EVIEWS</span>
                        <span class="skill">Inglese C1</span>
                        <span class="skill">Italiano C1</span>
                    </div>
                </div>
            </section>
            
            <section>
                <h2>Riconoscimenti</h2>
                
                <div class="card">
                    <ul>
                        <li><strong>Innovation Camp for PhD Students</strong> - Primo classificato (2024)</li>
                        <li><strong>Borsa di dottorato completa</strong> - Università degli Studi dell'Insubria</li>
                        <li><strong>Laurea Magistrale con lode</strong> - Università Politecnica delle Marche</li>
                    </ul>
                </div>
            </section>
        </div>
    </main>
    
    <footer>
        <div class="container">
            <p>&copy; 2025 Ardit Koka - Tutti i diritti riservati</p>
        </div>
    </footer>
    
    <script>
        function openTab(evt, tabName) {
            // Hide all tab content
            var tabContents = document.getElementsByClassName("tab-content");
            for (var i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }
            
            // Remove active class from all tabs
            var tabs = document.getElementsByClassName("tab");
            for (var i = 0; i < tabs.length; i++) {
                tabs[i].classList.remove("active");
            }
            
            // Show the specific tab content
            document.getElementById(tabName).classList.add("active");
            
            // Add active class to the clicked tab
            evt.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>
