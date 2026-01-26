---
layout: none
title: "Publications"
permalink: /publications/
---

<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adrien Petralia – Publications</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
    <style>
        .gradient-text { background: linear-gradient(90deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .hover-scale { transition: transform 0.3s ease; }
        .hover-scale:hover { transform: translateY(-3px); }
        .bg-pattern { background-image: radial-gradient(rgba(59,130,246,0.08) 2px, transparent 2px); background-size: 40px 40px; }
        /* Use plain CSS so it works with Tailwind CDN (no @apply at runtime) */
        .chip { display:inline-flex; align-items:center; border-radius:9999px; padding:0.125rem 0.625rem; font-size:0.75rem; line-height:1rem; font-weight:500; background-color:#f3f4f6; color:#374151; }
        .btn { display:inline-flex; align-items:center; gap:0.5rem; padding:0.5rem 0.75rem; border-radius:0.5rem; background:#f3f4f6; color:#1f2937; font-weight:500; }
        .btn:hover { background:#e5e7eb; }
        .pub-title a { text-decoration: none; }
    </style>
</head>
<body class="bg-gray-50 font-sans antialiased bg-pattern">
    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="https://adrienpetralia.github.io/" class="text-xl font-bold gradient-text">Adrien Petralia</a>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="https://adrienpetralia.github.io/#about" class="text-gray-700 hover:text-blue-600 transition">About</a>
                    <a href="https://adrienpetralia.github.io/publications/" class="text-blue-600 border-b-2 border-blue-600 pb-1">Publications</a>
                    <a href="https://adrienpetralia.github.io/talks/" class="text-gray-700 hover:text-blue-600 transition">Thesis</a>
                    <a href="https://adrienpetralia.github.io/teaching/" class="text-gray-700 hover:text-blue-600 transition">Service & Teaching</a>
                    <a href="https://adrienpetralia.github.io/internships/" class="text-gray-700 hover:text-blue-600 transition">Internships</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menu-toggle" class="text-gray-700" aria-label="Open menu" aria-expanded="false" aria-controls="mobile-menu">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg" role="region" aria-label="Mobile menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="https://adrienpetralia.github.io/#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">About</a>
                <a href="https://adrienpetralia.github.io/publications/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Publications</a>
                <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Thesis</a>
                <a href="https://adrienpetralia.github.io/teaching/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Service & Teaching</a>
                <a href="https://adrienpetralia.github.io/internships/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Internships</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <header class="text-center mb-12">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-900">Publications</h1>
            <p class="mt-3 text-gray-600">Selected work across journals, conferences, and patents.</p>
        </header>

        <!-- Preprints -->
        <!-- <section class="mb-12" aria-labelledby="preprints"> -->
            <!-- <div class="flex items-center gap-3 mb-4"> -->
                <!-- <i class="fa-solid fa-file-lines text-xl text-blue-600"></i> -->
                <!-- <h2 id="preprints" class="text-2xl font-semibold text-gray-800">Preprints</h2> -->
            <!-- </div> -->
            <!-- <div class="space-y-4"> -->
                <!-- Preprints -->
            <!-- </div> -->
        <!-- </section> -->

        <!-- Journals and Conferences -->
        <section class="mb-12" aria-labelledby="conferences">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-book-open text-xl text-purple-600" aria-hidden="true"></i>
                <h2 id="publications" class="text-2xl font-semibold text-gray-800">Journals and Conferences</h2>
            </div>

            <div class="space-y-4">
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2026</span>
                        <span class="chip">Journal</span>
                        <span class="chip">TMLR</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">
                        Are Time-Indexed Foundation Models the Future of Time Series Imputation?
                    </h3>
                    <p class="text-gray-700 mt-1">
                        Etienne Le Naour*, Tahar Nabil*, Adrien Petralia, Ghislain Agoua
                    </p>
                    <p class="text-gray-600 mt-1 italic">
                        Transaction on Machine Learning Research (TMLR), 2026.
                    </p> 
                    <p class="text-gray-600 mt-1 italic">Presented at NeurIPS 2025, Workshop on Recent Advances in Time Series Foundation Models (BERT2S).</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2511.05980" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_posters/BERT2S_TSFMImputation.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-image"></i> Poster
                        </a>
                    </div>
                </article>
                
                <!-- KDD 2025 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2025</span>
                        <span class="chip">Conference</span>
                        <span class="chip">KDD</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">NILMFormer: Non-Intrusive Load Monitoring that Accounts for Non-Stationarity</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Philippe Charpentier, Youssef Kadhi, Themis Palpanas</p>
                    <p class="text-gray-600 mt-1 italic">ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), Toronto, ON, Canada, August 2025</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2506.05880" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://helios2.mi.parisdescartes.fr/~themisp/publications/kdd25-nilmformer-slides.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-person-chalkboard"></i> Slides
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_posters/KDD2025_NILMFormer.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-image"></i> Poster
                        </a>
                        <a class="btn" href="https://github.com/adrienpetralia/NILMFormer/" target="_blank" rel="noopener">
                            <i class="fa-brands fa-github"></i> Code
                        </a>
                    </div>
                </article>

                <!-- ICDE 2025 (Weakly Supervised) -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2025</span>
                        <span class="chip">Conference</span>
                        <span class="chip">ICDE</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Few Labels are all you need: A Weakly Supervised Framework for Appliance Localization in Smart-Meter Series</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Paul Boniol, Philippe Charpentier, Themis Palpanas</p>
                    <p class="text-gray-600 mt-1 italic">IEEE International Conference on Data Engineering (ICDE), Hong Kong SAR, China, May 2025</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2506.05895" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://helios2.mi.parisdescartes.fr/~themisp/publications/icde25-camal-slides.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-person-chalkboard"></i> Slides
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_posters/ICDE2025_CamAL.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-image"></i> Poster
                        </a>
                        <a class="btn" href="https://github.com/adrienpetralia/CamAL/" target="_blank" rel="noopener">
                            <i class="fa-brands fa-github"></i> Code
                        </a>
                    </div>
                </article>

                <!-- ICDE 2025 (DeviceScope) -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2025</span>
                        <span class="chip">Conference</span>
                        <span class="chip">ICDE</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">DeviceScope: An Interactive App to Detect and Localize Appliance Patterns in Electricity Consumption Time Series</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Paul Boniol, Philippe Charpentier, Themis Palpanas</p>
                    <p class="text-gray-600 mt-1 italic">IEEE International Conference on Data Engineering (ICDE), Hong Kong SAR, China, May 2025</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2506.05912" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_posters/ICDE2025_DeviceScope.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-image"></i> Poster
                        </a>
                        <a class="btn" href="https://github.com/adrienpetralia/CamAL/" target="_blank" rel="noopener">
                            <i class="fa-brands fa-github"></i> Code
                        </a>
                        <a class="btn" href="https://devicescope.streamlit.app/" target="_blank" rel="noopener">
                            <i class="fa-solid fa-desktop"></i> Demo
                        </a>
                    </div>
                </article>

                <!-- VLDB PhD Workshop 2024 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2024</span>
                        <span class="chip">Conference</span>
                        <span class="chip">VLDB PhD Workshop</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Time Series Analytics for Electricity Consumption Data</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia</p>
                    <p class="text-gray-600 mt-1 italic">Very Large Data Bases (VLDB) PhD Workshop, Guangzhou, China, August 2024</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://hal.science/hal-04706310v1/file/Time%20Series%20Analytics%20for%20Electricity%20Consumption%20Data.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_slides/VLDB24_TimeSeriesAnalyticsforElectricityConsumptionData.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-person-chalkboard"></i> Slides
                        </a>
                    </div>
                </article>

                <!-- PVLDB Journal 2024 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2024</span>
                        <span class="chip">Journal</span>
                        <span class="chip">PVLDB</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">
                        ADF & TransApp: A Transformer-Based Framework for Appliance Detection Using Smart Meter Consumption Series
                    </h3>
                    <p class="text-gray-700 mt-1">
                        Adrien Petralia, Philippe Charpentier, Themis Palpanas
                    </p>
                    <p class="text-gray-600 mt-1 italic">
                        Proceedings of the VLDB Endowment (PVLDB) Journal, December 2023
                    </p> 
                    <p class="text-gray-600 mt-1 italic">
                        Presented at the 50th International Conference on Very Large DataBases (VLDB), Guangzhou, China, August 2024
                    </p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2401.05381" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_slides/VLDB24_ADFTransApp.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-person-chalkboard"></i> Slides
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_posters/VLDB2024_TransApp.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-image"></i> Poster
                        </a>
                        <a class="btn" href="https://github.com/adrienpetralia/TransApp/" target="_blank" rel="noopener">
                            <i class="fa-brands fa-github"></i> Code
                        </a>
                    </div>
                </article>

                <!-- BDA 2023 (French) -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2023</span>
                        <span class="chip">Conference</span>
                        <span class="chip">BDA</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Détection d’appareils électriques à partir de séries temporelles de consommation très basse fréquence</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Philippe Charpentier, Paul Boniol, Themis Palpanas</p>
                    <p class="text-gray-600 mt-1 italic">39ème Conférence sur la Gestion de Données (BDA), Montpellier, France, October 2023</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://hal-lirmm.ccsd.cnrs.fr/lirmm-04627853v1/file/actesBDA2023.pdf" target="_blank" rel="noopener"><i class="fa-solid fa-file-pdf"></i> PDF</a>
                    </div>
                </article>

                <!-- e-Energy 2023 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2023</span>
                        <span class="chip">Conference</span>
                        <span class="chip">e-Energy</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Appliance Detection Using Very Low-Frequency Smart Meter Time Series</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Philippe Charpentier, Paul Boniol, Themis Palpanas</p>
                    <p class="text-gray-600 mt-1 italic">ACM International Conference on Future Energy Systems (e‑Energy), Orlando, FL, USA, June 2023</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://arxiv.org/pdf/2305.10352" target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> PDF
                        </a>
                        <a class="btn" href="https://adrienpetralia.github.io/_slides/eEnergy23_ApplianceDetectionUsingVeryLowFrequencyTimeSeries.pdf" target="_blank" rel="noopener">
                            <i class="fa-solid fa-person-chalkboard"></i> Slides
                        </a>
                        <a class="btn" href="https://github.com/adrienpetralia/ApplianceDetectionBenchmark/" target="_blank" rel="noopener">
                                <i class="fa-brands fa-github"></i> Code
                        </a>
                    </div>
                </article>

                <!-- TELEMAC 2020 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2020</span>
                        <span class="chip">Proceedings</span>
                        <span class="chip">TELEMAC</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Pumping station design based on shape optimization process</h3>
                    <p class="text-gray-700 mt-1">Florent Taccone, Cédric Goeury, Fabrice Zaoui, Adrien Petralia</p>
                    <p class="text-gray-600 mt-1 italic">Proceedings of the TELEMAC‑MASCARET User Conference, Online, October 2020</p>
                    <div class="mt-3 flex flex-wrap gap-2">
                        <a class="btn" href="https://research.bangor.ac.uk/portal/files/36456769/Proceedings_TUC_2020_v1.0.pdf#page=99" target="_blank" rel="noopener"><i class="fa-solid fa-file-pdf"></i> PDF</a>
                    </div>
                </article>
            </div>
        </section>

        <!-- Patents -->
        <section class="mb-12" aria-labelledby="patents">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-lightbulb text-xl text-amber-500" aria-hidden="true"></i>
                <h2 id="patents" class="text-2xl font-semibold text-gray-800">Patents</h2>
            </div>

            <div class="space-y-4">
                <!-- Patent 2025 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2025</span>
                        <span class="chip">FR</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Détermination d'une activation au cours du temps d'un équipement donné au sein d'un ensemble d'équipements à partir de données collectées</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Paul Boniol, Themis Palpanas, Philippe Charpentier</p>
                    <p class="text-gray-600 mt-1 italic">French Patent FR2504769</p>
                </article>

                <!-- Patent 2024 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2024</span>
                        <span class="chip">FR</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Extraction de la consommation électrique d'un équipement individuel au sein d'un ensemble d'équipements connectés a un réseau électrique</h3>
                    <p class="text-gray-700 mt-1">Adrien Petralia, Themis Palpanas, Philippe Charpentier, Claire Lambert</p>
                    <p class="text-gray-600 mt-1 italic">French Patent FR2410061</p>
                </article>

                <!-- Patent 2023 -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">2023</span>
                        <span class="chip">FR</span>
                        <span class="chip">EU</span>
                    </div>
                    <h3 class="pub-title font-semibold text-gray-900">Caracterisation pour l'optimisation de la consommation électrique d'un ensemble d'équipements connectés a un réseau électrique</h3>
                    <p class="text-gray-700 mt-1">Luc Dufour, Pascal Chaussumier, Adrien Petralia, Philippe Charpentier, Themis Palpanas, Justin Capik</p>
                    <p class="text-gray-600 mt-1 italic">French Patent FR3156961 - European Patent EP4571461</p>
                </article>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Connect</h3>
                    <div class="flex space-x-4">
                        <a href="https://github.com/adrienpetralia" class="text-gray-400 hover:text-white text-2xl transition">
                            <i class="fab fa-github"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/adrien-petralia" class="text-gray-400 hover:text-white text-2xl transition">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="https://scholar.google.com/citations?user=-5WG3n0AAAAJ&hl=en" class="text-gray-400 hover:text-white text-2xl transition">
                            <i class="fas fa-graduation-cap"></i>
                        </a>
                    </div>
                    <p class="text-gray-400 mt-4">
                        <a href="mailto:adrien.petralia@gmail.com" class="hover:text-white transition">firstname[dot]name[at]gmail.com</a>
                    </p>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
                <p>© 2025 Adrien Petralia.</p>
            </div>
        </div>
    </footer>

    <script>
        const menuToggle = document.getElementById('menu-toggle');
        const mobileMenu = document.getElementById('mobile-menu');
        menuToggle.addEventListener('click', () => {
            const isHidden = mobileMenu.classList.toggle('hidden');
            menuToggle.setAttribute('aria-expanded', String(!isHidden));
        });
    </script>
</body>
</html>
