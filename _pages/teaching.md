---
layout: none
title: "Teaching"
permalink: /teaching/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adrien Petralia - Talks</title>
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
                    <a href="https://adrienpetralia.github.io/publications/" class="text-gray-700 hover:text-blue-600 transition">Publications</a>
                    <a href="https://adrienpetralia.github.io/talks/" class="text-blue-600 border-b-2 border-blue-600 pb-1">Talks</a>
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
                <a href="https://adrienpetralia.github.io/publications/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Publications</a>
                <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Talks</a>
                <a href="https://adrienpetralia.github.io/sitemap/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Sitemap</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <h1 class="text-3xl md:text-4xl font-bold text-gray-900 mb-12 text-center">Talks and Presentations</h1>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">2025</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    "CamAL: A Weakly Supervised Framework for Appliance Localization in Smart-Meter Series" (ICDE, Hong Kong SAR, China, May 2025)
                </li>
                <li>
                    "DeviceScope: An Interactive App to Detect and Localize Appliance Patterns in Electricity Consumption Time Series" (ICDE, Hong Kong SAR, China, May 2025)
                </li>
            </ol>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">2024</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    "ADF & TransApp: A Transformer-Based Framework for Appliance Detection Using Smart Meter Consumption Series" (VLDB, Guangzhou, China, August 2024)
                </li>
                <li>
                    "Time Series Analytics for Electricity Consumption Data" (VLDB PhD Workshop, Guangzhou, China, August 2024)
                </li>
                <li>
                    "L'intelligence artificielle au service de la compréhension de la consommation d'électricité/How Can Artificial Intelligence Help Us Understand Electricity Consumption?" (Festival Double•Science, Paris, France, June 2024)
                </li>
                <li>
                    "Time Series Classification for Electricity Consumption Analysis" (LIPADE Open Day, Université Paris Cité, Paris, France, June 2024)
                </li>
            </ol>
        </section>

        <section class="mb-12">
            <h2 class="text-2xl font-semibold text-gray-800 mb-4">2023</h2>
            <ol class="list-decimal list-inside space-y-4 text-gray-700">
                <li>
                    "Electricity Consumption Time Series Classification and Non-Intrusive Load Monitoring" (CentraleSupelec, Metz, France, November 2023)
                </li>
                <li>
                    "Détection de présence d'appareils dans les courbes de consommation très basse fréquences/Appliance Detection Using Very Low-Frequency Time Series" (BDA, Montpellier, France, October 2023)
                </li>
                <li>
                    "Appliance Detection Using Very Low-Frequency Time Series" (ACM e-Energy, Orlando, FL, USA, June 2023)
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


