---
layout: none
title: "Teaching"
permalink: /teaching/
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adrien Petralia – Service & Teaching</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-text { background: linear-gradient(90deg, #3b82f6, #8b5cf6); -webkit-background-clip: text; background-clip: text; color: transparent; }
        .hover-scale { transition: transform 0.3s ease; }
        .hover-scale:hover { transform: translateY(-3px); }
        .bg-pattern { background-image: radial-gradient(rgba(59,130,246,0.08) 2px, transparent 2px); background-size: 40px 40px; }
        .chip { @apply inline-flex items-center rounded-full px-2.5 py-0.5 text-xs font-medium bg-gray-100 text-gray-700; }
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
                    <a href="https://adrienpetralia.github.io/teaching/" class="text-blue-600 border-b-2 border-blue-600 pb-1">Service & Teaching</a>
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
                <a href="https://adrienpetralia.github.io/publications/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Publications</a>
                <a href="https://adrienpetralia.github.io/talks/" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-blue-600 hover:bg-gray-50">Talks</a>
                <a href="https://adrienpetralia.github.io/teaching/" class="block px-3 py-2 rounded-md text-base font-medium text-blue-600 bg-gray-50">Service & Teaching</a>
            </div>
        </div>
    </nav>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12 md:py-20">
        <header class="text-center mb-12">
            <h1 class="text-3xl md:text-4xl font-bold text-gray-900">Service & Teaching</h1>
            <p class="mt-3 text-gray-600">Academic service and classroom activities.</p>
        </header>

        <!-- Academic Service -->
        <section aria-labelledby="service" class="space-y-6 mb-12">
            <div class="flex items-center gap-3">
                <i class="fa-solid fa-handshake-angle text-xl text-purple-600" aria-hidden="true"></i>
                <h2 id="service" class="text-2xl font-semibold text-gray-800">Academic Service</h2>
            </div>

            <!-- Program Committee -->
            <div class="bg-white rounded-2xl shadow-sm p-6">
                <h3 class="font-semibold text-gray-900 flex items-center gap-2">
                    <i class="fa-solid fa-people-group text-gray-500" aria-hidden="true"></i>
                    Program Committee Member (Reviewer)
                </h3>
                <ul class="mt-3 space-y-2 text-gray-700 list-disc list-inside">
                    <li>
                        ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2026) — Datasets & Benchmarks Track
                        <span class="chip ml-2">2026</span>
                    </li>
                    <li>
                        IEEE International Conference on Big Data (IEEE BigData 2025) — Industrial & Government Track
                        <span class="chip ml-2">2025</span>
                    </li>
                </ul>
            </div>

            <!-- Reviewer -->
            <div class="bg-white rounded-2xl shadow-sm p-6">
                <h3 class="font-semibold text-gray-900 flex items-center gap-2">
                    <i class="fa-regular fa-pen-to-square text-gray-500" aria-hidden="true"></i>
                    Invited External Reviewer for International Conferences & Journals
                </h3>
                <ul class="mt-3 space-y-2 text-gray-700 list-disc list-inside">
                    <li>Information Systems <span class="chip ml-2">2023 & 2025</span></li>
                    <li>ACM Computing Surveys <span class="chip ml-2">2025</span></li>
                    <li>International Conference on Learning Representations (ICLR) <span class="chip ml-2">2024</span></li>
                </ul>
            </div>
        </section>
        
        <!-- Teaching -->
        <section aria-labelledby="teaching" class="mb-12">
            <div class="flex items-center gap-3 mb-4">
                <i class="fa-solid fa-chalkboard-user text-xl text-blue-600" aria-hidden="true"></i>
                <h2 id="teaching" class="text-2xl font-semibold text-gray-800">Teaching</h2>
            </div>

            <div class="bg-white rounded-2xl shadow-sm p-6 hover-scale">
                <div class="flex flex-col md:flex-row md:items-center md:justify-between gap-2">
                    <div>
                        <h3 class="font-medium text-gray-900">Programming Project Group Supervision</h3>
                        <p class="text-gray-600">Université Paris Cité — BSc Mathematics & Computer Science</p>
                    </div>
                    <div class="flex items-center gap-2">
                        <span class="chip">2023 & 2025</span>
                    </div>
                </div>
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
            <div class="mt-8 text-center text-gray-500">
                &copy; {{ site.time | date: '%Y' }} Adrien Petralia
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
