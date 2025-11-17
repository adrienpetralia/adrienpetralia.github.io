---
layout: none
title: "Internships"
permalink: /internships/
---

<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adrien Petralia – Internships</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
    <style>
        .gradient-text { background: linear-gradient(90deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .hover-scale { transition: transform 0.3s ease; }
        .hover-scale:hover { transform: translateY(-3px); }
        .bg-pattern { background-image: radial-gradient(rgba(59,130,246,0.08) 2px, transparent 2px); background-size: 40px 40px; }
        /* Plain CSS so it works with Tailwind CDN */
        .chip { display:inline-flex; align-items:center; border-radius:9999px; padding:0.125rem 0.625rem; font-size:0.75rem; line-height:1rem; font-weight:500; background-color:#f3f4f6; color:#374151; }
        .btn { display:inline-flex; align-items:center; gap:0.5rem; padding:0.5rem 0.75rem; border-radius:0.5rem; background:#f3f4f6; color:#1f2937; font-weight:500; }
        .btn:hover { background:#e5e7eb; }
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
                    <a href="https://adrienpetralia.github.io/publications/" class="text-gray-700 hover:text-blue-600 transition">Publications</a>
                    <a href="https://adrienpetralia.github.io/talks/" class="text-gray-700 hover:text-blue-600 transition">Talks</a>
                    <a href="https://adrienpetralia.github.io/teaching/" class="text-gray-700 hover:text-blue-600 transition">Service & Teaching</a>
                    <a href="https://adrienpetralia.github.io/internships/" class="text-blue-600 border-b-2 border-blue-600 pb-1">Internships</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menu-toggle" class="text-gray-700" aria-label="Open menu" aria-expanded="false" aria-controls="mobile-menu">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg" role="region" aria-label="Mobile menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="https://adrienpetralia.github.io/#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">About</a>
                <a href="https://adrienpetralia.github.io/publications/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Publications</a>
              <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Talks</a>
                <a href="https://adrienpetralia.github.io/teaching/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Service & Teaching</a>
              <a href="https://adrienpetralia.github.io/internships/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Internships</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <header class="text-center mb-12">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-900">Internships</h1>
            <p class="mt-3 text-gray-600">Internship positions in my research group.</p>
        </header>

        <div class="bg-white rounded-xl shadow-md overflow-hidden p-6 md:p-8 pb-10 mb-10">
            <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-6">
        
                <!-- Text -->
                <p class="text-lg text-gray-700 md:w-3/4">
                    My research group at EDF Lab Paris-Saclay (Palaiseau, France) regularly hosts internship projects at the 
                    interface between data mining, machine learning, and energy systems. We work on real-world challenges 
                    using advanced AI methods, and we welcome motivated students who want to contribute to impactful 
                    research applied to the energy domain.
                </p>
        
                <!-- Logo -->
                <img 
                    src="https://adrienpetralia.github.io/images/edf.png" 
                    alt="EDF logo"
                    class="w-24 h-auto md:w-32 object-contain opacity-90"
                />
        
            </div>
        </div>

            

        <!-- 2026 -->
<section class="mb-12" aria-labelledby="y2026">
    <div class="flex items-center gap-3 mb-4">
        <i class="fa-solid fa-calendar-days text-xl text-blue-600" aria-hidden="true"></i>
        <h2 id="y2025" class="text-2xl font-semibold text-gray-800">Open positions for 2026 (starting from February)</h2>
    </div>
    <div class="space-y-4">

    <!-- Anomaly detection -->
    <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
        <div class="flex flex-wrap items-center gap-2 mb-2">
            <span class="chip">Time Series</span>
            <span class="chip">Anomaly Detection</span>
            <span class="chip">Transformer</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            Détection d'anomalies et de dérives dans les consommations énergétiques par méthodes d’IA
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Conception et benchmark de méthodes d’IA de pointe (Transformers, apprentissage auto-supervisé, modèles de fondation) pour détecter automatiquement anomalies, dérives et changements de comportements dans les séries temporelles de consommation électrique (e.g., courbes de charge issues des compteurs Linky). Le stage s’appuiera sur des jeux de données réels et contribuera directement à des cas d’usage métier (fraude, pannes, changements d’usage…) ainsi qu’à une thèse de doctorat en cours sur l’explicabilité des modèles multimodaux.
        </p>
        <a
            href="https://adrienpetralia.github.io/_internships/EDF-RD-E7C-Stage-2026-DETECTION_ANOMALIES.pdf"
            class="inline-flex items-center mt-4 text-sm font-medium text-blue-600 hover:text-blue-700"
            target="_blank" rel="noopener"
        >
            View full internship description (PDF)
            <i class="fa-solid fa-arrow-up-right-from-square ml-2 text-xs" aria-hidden="true"></i>
        </a>
    </article>

    <!-- GenAI tabular -->
    <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
        <div class="flex flex-wrap items-center gap-2 mb-2">
            <span class="chip">Tabular Data</span>
            <span class="chip">Generative AI</span>
            <span class="chip">Diffusion</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            IA génératives adaptées aux données tabulaires pour la génération de données synthétiques
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
        Développement de modèles d’IA générative pour produire des données tabulaires synthétiques réalistes, combinant informations contractuelles, caractéristiques logement/foyer et courbes de consommation. L’objectif est d’évaluer et comparer des modèles récents (diffusion, modèles génératifs tabulaires…) en termes de fidélité, d’utilité et de privacy, afin de fournir des jeux de données exploitables pour la R&D et les équipes métiers dans un cadre RGPD.
        </p>
        <a
            href="https://adrienpetralia.github.io/_internships/EDF-RD-E7C-Stage-2026-IA_GENERATIVE_TABULAIRE.pdf"
            class="inline-flex items-center mt-4 text-sm font-medium text-blue-600 hover:text-blue-700"
            target="_blank" rel="noopener"
        >
            View full internship description (PDF)
            <i class="fa-solid fa-arrow-up-right-from-square ml-2 text-xs" aria-hidden="true"></i>
        </a>
    </article>

    <!-- Foundation models -->
    <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
        <div class="flex flex-wrap items-center gap-2 mb-2">
            <span class="chip">Time Series</span>
            <span class="chip">Foundation Model</span>
            <span class="chip">Scoring</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            Exploration des courbes de charge par modèles de fondation pour séries temporelles et données tabulaires
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Exploration de modèles de fondation pour analyser les courbes de charge de clients professionnels et leurs données associées. Le stage consiste à détecter usages et équipements, réaliser du clustering de profils et de la classification de comportements à l’aide de modèles avancés pour séries temporelles et données tabulaires, afin d’accompagner les entreprises dans la maîtrise de leur consommation et de leur empreinte carbone.
        </p>
        <a
            href="https://adrienpetralia.github.io/_internships/EDF-RD-E7C-Stage-2026-EXPLORATION_COURBE_DE_CHARGE_PRO_PAR_IA.pdf"
            class="inline-flex items-center mt-4 text-sm font-medium text-blue-600 hover:text-blue-700"
            target="_blank" rel="noopener"
        >
            View full internship description (PDF)
            <i class="fa-solid fa-arrow-up-right-from-square ml-2 text-xs" aria-hidden="true"></i>
        </a>
    </article>

    <!-- Causal inference -->
    <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
        <div class="flex flex-wrap items-center gap-2 mb-2">
            <span class="chip">Causal Inference</span>
            <span class="chip">Time Series</span>
            <span class="chip">Electricity Consumption Data</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            Estimer la part d’autoconsommation solaire dans la consommation électrique résidentielle à l’aide de méthodes d’inférence causale
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Mise en œuvre de méthodes d’inférence causale pour estimer la part d’autoconsommation solaire dans la consommation électrique de clients résidentiels équipés de photovoltaïque. Le stage s’appuie sur des données de consommation fines, météo et tarifaires pour adapter et comparer différentes approches (méthodes quasi-expérimentales, modèles modernes de causalité) dans un cadre dynamique avec variables confondantes.
        </p>
        <a
            href="https://adrienpetralia.github.io/_internships/EDF-RD-E7C-Stage-2026-INFERENCE_CAUSALE_PV.pdf
"
            class="inline-flex items-center mt-4 text-sm font-medium text-blue-600 hover:text-blue-700"
            target="_blank" rel="noopener"
        >
            View full internship description (PDF)
            <i class="fa-solid fa-arrow-up-right-from-square ml-2 text-xs" aria-hidden="true"></i>
        </a>
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
