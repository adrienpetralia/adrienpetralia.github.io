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
            <p class="mt-3 text-gray-600">Current open internships position in my research group.</p>
        </header>

        <div class="bg-white rounded-xl shadow-md overflow-hidden p-6 md:p-8 pb-10 mb-10">
            <p class="text-lg text-gray-700">
                My research group at EDF Lab Paris-Saclay (Palaiseau, France) regularly hosts internship projects at the interface between 
                data mining, machine learning, and energy systems. We work on real-world challenges using advanced AI methods, and we welcome 
                motivated students who want to contribute to impactful research on time series and energy data.
            </p>
        </div>

            

        <!-- 2026 -->
<section class="mb-12" aria-labelledby="y2026">
    <div class="space-y-4">

    <!-- Anomaly detection -->
    <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
        <div class="flex flex-wrap items-center gap-2 mb-2">
            <span class="chip">Time Series</span>
            <span class="chip">Anomaly Detection</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            Détection d'anomalies et de dérives dans les consommations énergétiques par méthodes d’IA
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Développement et évaluation de méthodes d’apprentissage automatique pour détecter automatiquement
            les dérives lentes, anomalies et comportements atypiques dans les courbes de consommation énergétique,
            à partir de grandes bases de séries temporelles issues de compteurs communicants.
        </p>
        <a
            href="https://github.com/adrienpetralia/adrienpetralia.github.io/raw/master/_internships/EDF-RD-E7C-Stage-2026-DETECTION_ANOMALIES.pdf"
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
            <span class="chip">Gen AI</span>
        </div>
        <h3 class="font-semibold text-gray-900">
            IA génératives adaptées aux données tabulaires pour la génération de données synthétiques
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Conception et mise en œuvre de modèles d’IA générative pour produire des jeux de données tabulaires
            synthétiques réalistes (profil clients, équipements, contextes), tout en respectant la confidentialité
            et les contraintes statistiques des données utilisées dans le secteur de l’énergie.
        </p>
        <a
            href="https://github.com/adrienpetralia/adrienpetralia.github.io/raw/master/_internships/EDF-RD-E7C-Stage-2026-IA_GENERATIVE_TABULAIRE.pdf"
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
        </div>
        <h3 class="font-semibold text-gray-900">
            Exploration des courbes de charge par modèles de fondation pour séries temporelles et données tabulaires
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Étude et expérimentation de modèles de fondation pour séries temporelles et données tabulaires afin de
            apprendre des représentations générales des courbes de charge, réutilisables pour diverses tâches aval
            (prédiction, segmentation, détection d’événements, caractérisation des usages).
        </p>
        <a
            href="https://github.com/adrienpetralia/adrienpetralia.github.io/raw/master/_internships/EDF-RD-E7C-Stage-2026-EXPLORATION_COURBE_DE_CHARGE_PRO_PAR_IA.pdf"
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
        </div>
        <h3 class="font-semibold text-gray-900">
            Estimer la part d’autoconsommation solaire dans la consommation électrique résidentielle à l’aide de méthodes d’inférence causale
        </h3>
        <p class="mt-2 text-gray-600 text-sm md:text-base">
            Application de méthodes d’inférence causale pour estimer, à partir de données de comptage et de contexte,
            la part d’autoconsommation photovoltaïque dans la consommation de logements équipés de panneaux solaires,
            en présence de signaux bruités et de multiples facteurs confondants.
        </p>
        <a
            href="https://github.com/adrienpetralia/adrienpetralia.github.io/raw/master/_internships/EDF-RD-E7C-Stage-2026-INFERENCE_CAUSALE_PV.pdf"
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
                    <h3 class="text-xl font-bold mb-4">Adrien Petralia</h3>
                    <p class="text-gray-400">PhD, AI Researcher specializing in time series analytics and deep learning.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="https://adrienpetralia.github.io/#about" class="text-gray-400 hover:text-white transition">About</a></li>
                        <li><a href="https://adrienpetralia.github.io/publications/" class="text-gray-400 hover:text-white transition">Publications</a></li>
                        <li><a href="https://adrienpetralia.github.io/talks/" class="text-gray-400 hover:text-white transition">Talks</a></li>
                    </ul>
                </div>
            </div>
            <div class="mt-8 text-center text-gray-500">&copy; {{ site.time | date: '%Y' }} Adrien Petralia</div>
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
