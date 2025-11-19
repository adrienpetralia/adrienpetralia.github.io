---
layout: none
title: "Thesis"
permalink: /talks/
---

<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Adrien Petralia – PhD Thesis</title>
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
                    <a href="https://adrienpetralia.github.io/talks/" class="text-blue-600 border-b-2 border-blue-600 pb-1">Thesis</a>
                    <a href="https://adrienpetralia.github.io/teaching/" class="text-gray-700 hover:text-blue-600 transition">Service & Teaching</a>
                    <a href="https://adrienpetralia.github.io/internships/" class="text-gray-700 hover:text-blue-600 transition">Internships</a>
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
                <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Thesis</a>
                <a href="https://adrienpetralia.github.io/teaching/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Service & Teaching</a>
                <a href="https://adrienpetralia.github.io/internships/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Internships</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <!-- Page header -->
        <header class="text-center mb-12">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-900">PhD Thesis Overview</h1>
            <p class="mt-3 text-gray-600">Defended on May 7th, Paris, France.</p>
        </header>

        <!-- Overview / Abstract -->
        <section class="mb-12" aria-labelledby="overview">
        <p class="mt-3 text-gray-600 max-w-2xl">
            My PhD work focuses on deep learning for large-scale electricity consumption time series,
            with applications to smart-meter analytics, Non-Intrusive Load Monitoring (NILM), and
            consumer-facing energy feedback at EDF.
        </p>
        <p class="mt-2 text-sm text-gray-500">
            PhD in Artificial Intelligence, Université Paris Cité &amp; EDF R&amp;D – supervised by Prof. Themis Palpanas.
        </p>
        </section>
        
        <section class="mb-12" aria-labelledby="abstract">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-circle-info text-xl text-blue-600" aria-hidden="true"></i>
                <h2 id="overview" class="text-2xl font-semibold text-gray-800">Abstract</h2>
            </div>
            <div class="bg-white rounded-2xl shadow-sm p-6">
                <p class="text-gray-700 mb-4">
                    The thesis investigates how modern deep learning models, in particular Transformer-based architectures,
                    can be used to model household electricity consumption at scale. The goal is twofold:
                    (i) learn robust representations of smart-meter data that transfer across downstream tasks
                    (classification, regression, forecasting), and (ii) design models capable of disaggregating
                    aggregated household load into appliance-level signals (NILM), with direct deployment in
                    EDF’s <em>Mon Suivi Conso</em> service.
                </p>
                <p class="text-gray-700">
                    Beyond methodological contributions, the work is strongly driven by industrial constraints:
                    nationwide deployment on millions of meters, heterogeneous consumption behaviours, and the need
                    for interpretable, actionable feedback to support the energy transition.
                </p>
            </div>
        </section>

        <!-- Key contributions -->
        <section class="mb-12" aria-labelledby="contributions">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-lightbulb text-xl text-purple-600" aria-hidden="true"></i>
                <h2 id="contributions" class="text-2xl font-semibold text-gray-800">Key Contributions</h2>
            </div>
            <article class="bg-white rounded-2xl shadow-sm p-6">
                <ul class="list-disc list-inside space-y-2 text-gray-700">
                    <li>
                        <span class="font-medium">Representation learning for smart-meter time series.</span>
                        Design and training of large deep learning models that serve as foundations for
                        multiple downstream analytics tasks on electricity consumption.
                    </li>
                </ul>
            </article>
        </section>

        <!-- Manuscript & defense materials -->
        <section class="mb-12" aria-labelledby="materials">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-graduation-cap text-xl text-blue-600" aria-hidden="true"></i>
                <h2 id="materials" class="text-2xl font-semibold text-gray-800">Manuscript &amp; Defense</h2>
            </div>

            <div class="space-y-6">
                <!-- Manuscript -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">Manuscript</span>
                        <span class="chip">Université Paris Cité</span>
                        <span class="chip">2025</span>
                    </div>
                    <h3 class="font-semibold text-gray-900 mb-2">
                        Deep Learning for Electricity Consumption Time Series Analytics
                    </h3>
                    <p class="text-gray-700 mb-3">
                        Final PhD thesis manuscript, available on HAL.
                    </p>
                    <div class="mt-1 flex flex-wrap gap-2">
                        <a class="btn"
                           href="https://theses.hal.science/tel-05355201v1/document"
                           target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> Manuscript (HAL)
                        </a>
                    </div>
                </article>

                <!-- Defense -->
                <article class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                    <div class="flex flex-wrap items-center gap-2 mb-2">
                        <span class="chip">Defense</span>
                        <span class="chip">Université Paris Cité</span>
                        <span class="chip">Paris, France</span>
                        <span class="chip">May 2025</span>
                    </div>
                    <h3 class="font-semibold text-gray-900 mb-2">
                        PhD Defense – Deep Learning for Electricity Consumption Time Series Analytics
                    </h3>
                    <p class="text-gray-700 mb-3">
                        Slides used during the public defense, summarizing the main context, methods, and results.
                    </p>
                    <div class="mt-1 flex flex-wrap gap-2">
                        <a class="btn"
                           href="https://adrienpetralia.github.io/_slides/PhDDefenseSlides.pdf"
                           target="_blank" rel="noopener">
                            <i class="fa-solid fa-file-pdf"></i> Defense Slides
                        </a>
                    </div>
                </article>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
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
                        <a href="mailto:adrien.petralia@gmail.com" class="hover:text-white transition">
                            firstname[dot]name[at]gmail.com
                        </a>
                    </p>
                </div>
            </div>

            <div class="mt-4 text-center text-gray-400">
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
