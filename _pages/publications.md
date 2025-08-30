---
layout: none
title: "Publications"
permalink: /publications/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adrien Petralia - Publications</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #8b5cf6);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: translateY(-3px);
        }
        .bg-pattern {
            background-image: radial-gradient(rgba(59, 130, 246, 0.1) 2px, transparent 2px);
            background-size: 40px 40px;
        }
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
                    <a href="https://adrienpetralia.github.io/talks/" class="text-gray-700 hover:text-blue-600 transition">Talks</a>
                    <a href="https://adrienpetralia.github.io/teaching/" class="text-gray-700 hover:text-blue-600 transition">Service</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="menu-toggle" class="text-gray-700">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="https://adrienpetralia.github.io/#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">About</a>
                <a href="https://adrienpetralia.github.io/publications/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Publications</a>
                <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Talks</a>
                <a href="https://adrienpetralia.github.io/teaching/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Service</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <h1 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12 text-center">Publications</h1>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">Journals</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    Adrien Petralia, Philippe Charpentier, Themis Palpanas. <span class="font-semibold">ADF & TransApp: A Transformer-Based Framework for Appliance Detection Using Smart Meter Consumption Series.</span> Proceedings of the VLDB Endowment (PVLDB) Journal, 2024. <a href="https://arxiv.org/pdf/2401.05381" class="text-blue-600 hover:underline">pdf</a>
                </li>
            </ol>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">Conferences</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    Adrien Petralia, Philippe Charpentier, Youssef Kadhi, Themis Palpanas. <span class="font-semibold">NILMFormer: Non-Intrusive Load Monitoring that Accounts for Non-Stationarity.</span> In ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), Toronto, ON, Canada, 2025. <a href="https://arxiv.org/pdf/2506.05880" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Adrien Petralia, Paul Boniol, Philippe Charpentier, Themis Palpanas. <span class="font-semibold">Few Labels are all you need: A Weakly Supervised Framework for Appliance Localization in Smart-Meter Series.</span> In IEEE International Conference on Data Engineering (ICDE), Hong Kong SAR, China, May 2025. <a href="https://arxiv.org/pdf/2506.05895" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Adrien Petralia, Paul Boniol, Philippe Charpentier, Themis Palpanas. <span class="font-semibold">DeviceScope: An Interactive App to Detect and Localize Appliance Patterns in Electricity Consumption Time Series.</span> In IEEE International Conference on Data Engineering (ICDE), Hong Kong SAR, China, 2025. <a href="https://arxiv.org/pdf/2506.05912" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Adrien Petralia. <span class="font-semibold">Time Series Analytics for Electricity Consumption Data.</span> Very Large Data Bases (VLDB) PhD Workshop, Guangzhou, China, August 2024. <a href="https://hal.science/hal-04706310v1/file/Time%20Series%20Analytics%20for%20Electricity%20Consumption%20Data.pdf" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Adrien Petralia, Philippe Charpentier, Paul Boniol, Themis Palpanas. <span class="font-semibold">Appliance Detection Using Very Low-Frequency Smart Meter Time Series.</span> BDA 2023 - 39ème Conférence sur la Gestion de Données Principes Technologies et Applications. <a href="https://hal-lirmm.ccsd.cnrs.fr/lirmm-04627853v1/file/actesBDA2023.pdf" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Adrien Petralia, Philippe Charpentier, Paul Boniol, Themis Palpanas. <span class="font-semibold">Appliance Detection Using Very Low-Frequency Smart Meter Time Series.</span> ACM International Conference on Future Energy Systems (e-Energy), Orlando, FL, USA, June 2023. <a href="https://arxiv.org/pdf/2305.10352" class="text-blue-600 hover:underline">pdf</a>
                </li>
                <li>
                    Florent Taccone, Cédric Goeury, Fabrice Zaoui, Adrien Petralia. <span class="font-semibold">Pumping station design based on shape optimization process.</span> Proceedings of the TELEMAC-MASCARET User Conference, Online, October 2020. <a href="https://research.bangor.ac.uk/portal/files/36456769/Proceedings_TUC_2020_v1.0.pdf#page=99" class="text-blue-600 hover:underline">pdf</a>
                </li>
            </ol>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">Patents</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    Adrien Petralia, Paul Boniol, Themis Palpanas, Philippe Charpentier. <span class="font-semibold">Determination d'une activation au cours du temps d'un equipement donne au sein d'un ensemble d'equipements a partir de donnees collectees.</span> French Patent FR2504769, 2025.
                </li>
                <li>
                    Adrien Petralia, Themis Palpanas, Philippe Charpentier, Claire Lambert. <span class="font-semibold">Extraction de la consommation electrique d'un equipement individuel au sein d'un ensemble d'equipements connectes a un reseau electrique.</span> French Patent FR2410061, 2024.
                </li>
                <li>
                    Luc Dufour, Pascal Chaussumier, Adrien Petralia, Philippe Charpentier, Themis Palpanas, Justin Capik. <span class="font-semibold">Caracterisation pour l'optimisation de la consommation electrique d'un ensemble d'equipements connectes a un reseau electrique.</span> French Patent FR2314217, 2023.
                </li>
            </ol>
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
            <div class="mt-8 text-center text-gray-500">
                &copy; {{ site.time | date: '%Y' }} Adrien Petralia
            </div>
        </div>
    </footer>

    <script>
        const menuToggle = document.getElementById('menu-toggle');
        const mobileMenu = document.getElementById('mobile-menu');
        menuToggle.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>

