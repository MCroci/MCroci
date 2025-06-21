<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profilo Professionale - Dr. Michele Croci</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* slate-50 */
        }
        .section-title {
            font-size: 1.75rem; /* text-2xl */
            font-weight: 700; /* font-bold */
            color: #1e3a8a; /* blue-900 */
            border-bottom: 3px solid #60a5fa; /* blue-400 */
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
        }
        .card {
            background-color: white;
            border-radius: 0.75rem; /* rounded-xl */
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1); /* shadow-md */
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1); /* shadow-lg */
        }
        .tag {
            display: inline-block;
            background-color: #e0e7ff; /* indigo-100 */
            color: #3730a3; /* indigo-800 */
            padding: 0.25rem 0.75rem;
            border-radius: 9999px; /* rounded-full */
            font-size: 0.875rem; /* text-sm */
            font-weight: 500; /* font-medium */
        }
        .icon-link svg {
            width: 24px;
            height: 24px;
            transition: transform 0.2s;
        }
        .icon-link:hover svg {
            transform: scale(1.2);
        }
    </style>
</head>
<body class="text-slate-700">

    <!-- Contenitore Principale -->
    <div class="max-w-6xl mx-auto p-4 sm:p-6 lg:p-8">

        <!-- Sezione Header -->
        <header class="text-center mb-12">
            <div class="inline-block p-3 bg-white rounded-full shadow-lg mb-4">
                <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" alt="Icona animata" class="w-12 h-12">
            </div>
            <h1 class="text-4xl md:text-5xl font-bold text-slate-900">Dr. Michele Croci</h1>
            <p class="mt-3 text-lg text-slate-600 max-w-3xl mx-auto">Ricercatore in Agronomia, Telerilevamento e Modellistica Colturali. Appassionato di Data Science per l'agricoltura sostenibile e il settore AgriFood.</p>
        </header>

        <!-- Sezione Link Social -->
        <div class="flex justify-center items-center space-x-4 mb-12">
            <a href="https://orcid.org/0000-0001-7356-2774" target="_blank" class="icon-link text-green-600" title="ORCID">
                <svg fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0zM7.365 18.995H5.01V7.99h2.355v11.005zM6.182 6.89C5.35 6.89 4.68 6.22 4.68 5.39c0-.83.67-1.5 1.502-1.5.83 0 1.5.67 1.5 1.5 0 .83-.67 1.5-1.5 1.5zM19 18.995h-2.355v-5.39c0-1.285-.025-2.935-1.79-2.935-1.79 0-2.065 1.4-2.065 2.84V18.995h-2.355V7.99h2.26V9.03h.03c.32-.605 1.1-1.24 2.23-1.24 2.385 0 2.825 1.57 2.825 3.61v7.595z"/></svg>
            </a>
            <a href="https://www.linkedin.com/in/michele-croci-265abb133/" target="_blank" class="icon-link text-blue-700" title="LinkedIn">
                <svg fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
            </a>
            <a href="https://www.researchgate.net/profile/Michele-Croci" target="_blank" class="icon-link text-cyan-500" title="ResearchGate">
                 <svg fill="currentColor" viewBox="0 0 24 24"><path d="M24 12c0 6.627-5.373 12-12 12S0 18.627 0 12 5.373 0 12 0s12 5.373 12 12zM10.163 9.47V15.2h1.616v-3.475c0-.608.38-1.025.862-1.025.483 0 .82.417.82 1.025v3.475h1.615V9.47c0-1.46-1.02-2.4-2.43-2.4-1.412 0-2.483.94-2.483 2.4zM7.525 15.2h1.615V7.875H7.525V15.2z"/></svg>
            </a>
             <a href="https://twitter.com/croci93" target="_blank" class="icon-link text-sky-500" title="Twitter/X">
                <svg fill="currentColor" viewBox="0 0 24 24"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
            </a>
        </div>


        <!-- Sezione Principale a Griglia -->
        <main class="grid grid-cols-1 lg:grid-cols-3 gap-8">

            <!-- Colonna Sinistra -->
            <div class="lg:col-span-2 space-y-8">
                
                <!-- Card: Chi Sono -->
                <section class="card p-6">
                    <h2 class="section-title">Chi Sono</h2>
                    <div class="space-y-4 text-slate-600">
                        <p>🇮🇹 Agronomo e <strong>Ricercatore a Tempo Determinato (RTDa)</strong> presso l'Università Cattolica del Sacro Cuore di Piacenza. La mia ricerca si concentra sull'applicazione del <strong>Telerilevamento</strong> (da satellite e UAV) e della <strong>Modellistica Colturale</strong> per il monitoraggio delle colture, la fenotipizzazione ad alta efficienza e la previsione delle rese.</p>
                        <p>🇩🇪 Ho avuto il piacere di essere <strong>Guest Researcher</strong> per 4.5 mesi presso il prestigioso <strong>Leibniz Centre for Agricultural Landscape Research (ZALF)</strong> in Germania, un'esperienza che ha arricchito profondamente il mio percorso scientifico.</p>
                        <p>🌱 Il mio obiettivo è sviluppare soluzioni <em>data-driven</em> per ottimizzare la gestione agronomica, migliorare la sostenibilità e supportare l'intera filiera agroalimentare, dal campo alla tavola.</p>
                    </div>
                </section>

                <!-- Card: Responsabilità Scientifiche e Progetti -->
                <section class="card p-6">
                    <h2 class="section-title">Responsabilità e Progetti</h2>
                    <p class="mb-6">Sono Responsabile Scientifico e di attività in importanti progetti competitivi, nazionali e internazionali, che guidano l'innovazione in agricoltura.</p>
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <span class="text-blue-600 font-bold mr-3 mt-1">🇪🇺</span>
                            <div>
                                <h3 class="font-semibold text-slate-800">Progetti Europei (Horizon Europe, BBI JU)</h3>
                                <p class="text-slate-600">Responsabile di attività per UCSC in: <strong>ClieNFarms</strong> (neutralità climatica), <strong>Value4Farm</strong> (energie rinnovabili), <strong>MARVIC</strong> (monitoraggio del carbonio) e <strong>GRACE</strong> (bioraffinerie).</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                            <span class="text-green-600 font-bold mr-3 mt-1">🇮🇹</span>
                             <div>
                                <h3 class="font-semibold text-slate-800">Progetti Nazionali (PNRR, ESA)</h3>
                                <p class="text-slate-600">Responsabile di attività per UCSC in: <strong>Agritech (PNRR)</strong>, il Centro Nazionale per le Tecnologie Agrarie, e <strong>EOAgriTwin (ESA)</strong>, per la creazione di un Gemello Digitale per l'agricoltura resiliente.</p>
                            </div>
                        </li>
                         <li class="flex items-start">
                            <span class="text-amber-600 font-bold mr-3 mt-1">🤝</span>
                            <div>
                                <h3 class="font-semibold text-slate-800">Trasferimento Tecnologico e Collaborazioni</h3>
                                <p class="text-slate-600">Collaboro con aziende e consorzi leader come <strong>OROGEL, Roquette, Consorzio CER</strong> per applicare i risultati della ricerca e creare un impatto reale sul settore.</p>
                            </div>
                        </li>
                    </ul>
                </section>
                
                <!-- Card: Progetto in Evidenza -->
                <section class="card p-6">
                    <h2 class="section-title">Progetto in Evidenza</h2>
                    <div class="flex flex-col sm:flex-row gap-6 items-center">
                        <div class="flex-shrink-0 text-blue-500">
                           <svg xmlns="http://www.w3.org/2000/svg" class="h-16 w-16" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.5">
                              <path stroke-linecap="round" stroke-linejoin="round" d="M9.75 3.104l-1.422 2.844a1.125 1.125 0 01-.832.622H4.368a1.125 1.125 0 00-.991 1.664l2.285 4.568a1.125 1.125 0 010 1.002l-2.285 4.568a1.125 1.125 0 00.991 1.664h3.128a1.125 1.125 0 01.832.622l1.422 2.844a1.125 1.125 0 002.042 0l1.422-2.844a1.125 1.125 0 01.832-.622h3.128a1.125 1.125 0 00.991-1.664l-2.285-4.568a1.125 1.125 0 010-1.002l2.285-4.568a1.125 1.125 0 00-.991-1.664h-3.128a1.125 1.125 0 01-.832-.622l-1.422-2.844a1.125 1.125 0 00-2.042 0z" />
                           </svg>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-slate-800">PROSAIL Simulation Shiny App</h3>
                            <p class="mt-2 mb-4 text-slate-600">Uno strumento interattivo in R/Shiny per simulare la riflettanza della vegetazione. Ideale per scopi didattici e di ricerca nel telerilevamento.</p>
                            <a href="https://ucscremotesensing.shinyapps.io/POSITIVE_CRAST/" target="_blank" class="inline-block bg-blue-600 text-white font-bold py-2 px-4 rounded-lg hover:bg-blue-700 transition-colors">
                                Avvia l'App &rarr;
                            </a>
                        </div>
                    </div>
                </section>

            </div>

            <!-- Colonna Destra -->
            <div class="space-y-8">
                
                <!-- Card: Competenze -->
                <section class="card p-6">
                    <h2 class="section-title">Competenze</h2>
                    <div class="space-y-5">
                        <div>
                            <h3 class="font-semibold text-slate-800 mb-2">Programmazione e Dati</h3>
                            <div class="flex flex-wrap gap-2">
                                <span class="tag bg-blue-100 text-blue-800">R</span>
                                <span class="tag bg-blue-100 text-blue-800">RStudio</span>
                                <span class="tag bg-yellow-100 text-yellow-800">Python</span>
                            </div>
                        </div>
                        <div>
                            <h3 class="font-semibold text-slate-800 mb-2">Geospatial e Telerilevamento</h3>
                             <div class="flex flex-wrap gap-2">
                                <span class="tag bg-red-100 text-red-800">Google Earth Engine</span>
                                <span class="tag bg-green-100 text-green-800">QGIS</span>
                                <span class="tag bg-slate-100 text-slate-800">Modelli RTM (es. PROSAIL)</span>
                            </div>
                        </div>
                        <div>
                            <h3 class="font-semibold text-slate-800 mb-2">Altre Competenze</h3>
                             <div class="flex flex-wrap gap-2">
                                <span class="tag">Pilota Droni (APR A1-A3)</span>
                                <span class="tag">Didattica Universitaria</span>
                                <span class="tag">Supervisione Dottorandi</span>
                                <span class="tag">Socio SIA</span>
                             </div>
                        </div>
                    </div>
                </section>

                <!-- Card: Esperienze Chiave -->
                <section class="card p-6">
                    <h2 class="section-title">Didattica e Talks</h2>
                     <ul class="space-y-3 list-disc list-inside text-slate-600">
                        <li><strong>Invited Speaker</strong> alla <em>Summer School "Digital Water Management"</em>.</li>
                        <li><strong>Relatore</strong> al IX Convegno AIT a Firenze.</li>
                        <li><strong>Docente</strong> in corsi professionalizzanti su agricoltura di precisione e telerilevamento.</li>
                        <li><strong>Titolare di incarichi di insegnamento</strong> presso Università Cattolica e Politecnico di Milano.</li>
                    </ul>
                </section>
                
                 <!-- Card: Stats GitHub -->
                <section class="card p-6 overflow-hidden">
                    <h2 class="section-title">Statistiche GitHub</h2>
                    <div class="space-y-4 bg-slate-50 p-4 rounded-lg">
                        <img src="https://github-readme-stats.vercel.app/api?username=mcroci&show_icons=true&theme=transparent&text_color=334155&icon_color=3b82f6" alt="Statistiche GitHub di Michele Croci" class="w-full" />
                        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mcroci&layout=compact&theme=transparent&text_color=334155" alt="Linguaggi più utilizzati" class="w-full" />
                    </div>
                </section>

            </div>

        </main>

    </div>

</body>
</html>
