<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AllergieVrij Food Plaza - Vind Allergievriendelijke Food Tents</title>
    <!-- Tailwind CSS for modern responsive utility styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        // Custom Tailwind configuration for theme colors
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        emerald: {
                            50: '#ecfdf5',
                            100: '#d1fae5',
                            600: '#059669',
                            700: '#047857',
                            800: '#065f46',
                        },
                        amber: {
                            50: '#fffbeb',
                            100: '#fef3c7',
                            500: '#f59e0b',
                            600: '#d97706',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom smooth scrollbar & transition utilities */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
        .modal-backdrop {
            background-color: rgba(15, 23, 42, 0.6);
            backdrop-filter: blur(4px);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased min-h-screen flex flex-col selection:bg-emerald-200">

    <header class="sticky top-0 z-30 bg-white/90 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <div class="flex items-center space-x-3 cursor-pointer" onclick="resetFilters()">
                    <div class="w-11 h-11 bg-emerald-600 rounded-2xl flex items-center justify-center text-white shadow-md shadow-emerald-600/30">
                        <i class="fa-solid fa-shield-halved text-2xl"></i>
                    </div>
                    <div>
                        <span class="text-xl font-bold bg-gradient-to-r from-emerald-700 to-teal-600 bg-clip-text text-transparent block leading-none">
                            AllergieVrij
                        </span>
                        <span class="text-xs font-semibold tracking-wider text-amber-600 uppercase">
                            Food Plaza
                        </span>
                    </div>
                </div>

                <!-- Action Buttons -->
                <div class="flex items-center space-x-3">
                    <button onclick="toggleFavoritesOnly()" id="fav-toggle-btn" class="flex items-center space-x-2 px-4 py-2.5 rounded-xl border border-slate-200 text-slate-700 hover:border-amber-400 hover:text-amber-600 transition-all font-medium text-sm">
                        <i class="fa-solid fa-heart text-amber-500" id="fav-icon"></i>
                        <span class="hidden sm:inline">Favorieten</span>
                        <span id="fav-count-badge" class="bg-amber-100 text-amber-800 text-xs px-2 py-0.5 rounded-full font-bold">0</span>
                    </button>

                    <button onclick="openAddModal()" class="flex items-center space-x-2 bg-emerald-600 hover:bg-emerald-700 text-white px-4 py-2.5 rounded-xl shadow-md shadow-emerald-600/20 transition-all font-medium text-sm">
                        <i class="fa-solid fa-plus"></i>
                        <span class="hidden md:inline">Kraampje Aanmelden</span>
                    </button>
                </div>
            </div>
        </div>
    </header>

    <main class="flex-grow">
        <section class="relative bg-gradient-to-b from-emerald-50 via-teal-50/30 to-slate-50 pt-12 pb-16 border-b border-emerald-100/60">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 text-center">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-emerald-100/80 text-emerald-800 text-xs font-semibold mb-4 border border-emerald-200">
                    <i class="fa-solid fa-leaf text-emerald-600"></i> Veilig, Onbezorgd & Transparant
                </span>
                <h1 class="text-3xl sm:text-4xl md:text-5xl font-extrabold text-slate-900 tracking-tight leading-tight mb-4">
                    Zorgeloos Eten & Genieten <br class="hidden sm:inline">
                    <span class="text-emerald-700">Vind Allergievriendelijke Food Tents</span>
                </h1>
                <p class="text-slate-600 text-base sm:text-lg max-w-2xl mx-auto mb-8">
                    Ontdek eetkraampjes die speciaal zijn uitgerust met strenge protocollen tegen kruisbesmetting en een helder overzicht van alle ingrediënten.
                </p>

                <!-- Main Search Bar -->
                <div class="max-w-2xl mx-auto relative group">
                    <div class="absolute inset-y-0 left-0 pl-4 flex items-center pointer-events-none text-slate-400 group-focus-within:text-emerald-600 transition-colors">
                        <i class="fa-solid fa-magnifying-glass text-lg"></i>
                    </div>
                    <input type="text" id="search-input" oninput="handleSearch()" placeholder="Zoek op naam of eten (bijv. 'Pannenkoeken', 'Patat', 'IJs', 'Burgers', 'Aziatisch')..." class="w-full pl-11 pr-24 py-4 rounded-2xl border border-slate-200 bg-white shadow-lg shadow-slate-200/50 focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:border-emerald-500 text-slate-800 placeholder-slate-400 text-base">
                    <button onclick="clearSearch()" id="clear-search-btn" class="hidden absolute right-3 top-1/2 -translate-y-1/2 bg-slate-100 hover:bg-slate-200 text-slate-600 text-xs font-semibold px-3 py-1.5 rounded-lg transition-colors">
                        Wis
                    </button>
                </div>
            </div>
        </section>

        <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 -mt-6 z-20 relative">
            <div class="bg-white rounded-3xl p-6 shadow-xl shadow-slate-200/60 border border-slate-100">
                <div class="flex flex-col md:flex-row md:items-center justify-between gap-4 mb-4 pb-4 border-b border-slate-100">
                    <div>
                        <h2 class="text-lg font-bold text-slate-900 flex items-center gap-2">
                            <i class="fa-solid fa-filter text-emerald-600"></i> Selecteer Jouw Allergieën & Wensen
                        </h2>
                        <p class="text-xs text-slate-500">
                            Selecteer een of meerdere opties. Alleen kraampjes die aan <strong>ALLES</strong> voldoen worden getoond.
                        </p>
                    </div>
                    <button onclick="resetFilters()" class="text-xs text-slate-500 hover:text-emerald-700 underline font-medium self-start md:self-auto">
                        Reset alle filters
                    </button>
                </div>

                <!-- Filter Matrix Grid -->
                <div id="allergy-filter-grid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2.5">
                    <!-- Dynamic rendering of filter buttons will happen via JS -->
                </div>
            </div>
        </section>

        <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">
            <!-- Results Counter & Status Bar -->
            <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between mb-6 gap-3">
                <div class="flex items-center space-x-2">
                    <h3 class="text-xl font-bold text-slate-900">Aanbevolen Food Tents</h3>
                    <span id="results-count" class="bg-emerald-100 text-emerald-800 text-xs font-bold px-2.5 py-1 rounded-full">
                        6 kraampjes
                    </span>
                </div>
                <div id="active-filter-tags" class="flex flex-wrap gap-1.5 text-xs">
                    <!-- Active filter pills will appear here -->
                </div>
            </div>

            <!-- Food Stalls Cards Grid -->
            <div id="tents-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Food Tent Cards generated dynamically -->
            </div>

            <!-- Empty State Placeholder -->
            <div id="empty-state" class="hidden text-center py-16 bg-white rounded-3xl border border-dashed border-slate-300 p-8">
                <div class="w-16 h-16 bg-amber-50 text-amber-500 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl">
                    <i class="fa-solid fa-triangle-exclamation"></i>
                </div>
                <h3 class="text-lg font-bold text-slate-800 mb-1">Geen kraampjes gevonden</h3>
                <p class="text-slate-500 text-sm max-w-md mx-auto mb-6">
                    Er zijn momenteel geen food tents die aan alle geselecteerde allergiefilters of zoektermen voldoen. Probeer een filter uit te vinken.
                </p>
                <button onclick="resetFilters()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-medium text-sm px-5 py-2.5 rounded-xl shadow-md transition-all">
                    Reset alle zoekcriteria
                </button>
            </div>
        </section>

        <section class="bg-emerald-900 text-white py-12 mt-8">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-start">
                    
                    <!-- Tips Column -->
                    <div class="lg:col-span-2">
                        <div class="flex items-center space-x-3 mb-6">
                            <div class="p-3 bg-emerald-800/80 rounded-2xl text-emerald-300">
                                <i class="fa-solid fa-lightbulb text-2xl"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold">Tips voor Veilig Eten op Evenementen</h3>
                                <p class="text-emerald-200 text-sm">Zo geniet je met een gerust hart van elk festival of markt.</p>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div class="bg-emerald-800/40 border border-emerald-700/50 p-4 rounded-2xl">
                                <div class="font-semibold text-emerald-200 text-sm mb-1 flex items-center gap-2">
                                    <i class="fa-solid fa-comments text-amber-400"></i> 1. Dubbelcheck bij de kraam
                                </div>
                                <p class="text-xs text-slate-300">Meld jouw specifieke allergie altijd mondeling vóór het bestellen, ook als er 'Glutenvrij' op het bord staat.</p>
                            </div>

                            <div class="bg-emerald-800/40 border border-emerald-700/50 p-4 rounded-2xl">
                                <div class="font-semibold text-emerald-200 text-sm mb-1 flex items-center gap-2">
                                    <i class="fa-solid fa-clock text-amber-400"></i> 2. Vermijd de ergste spits
                                </div>
                                <p class="text-xs text-slate-300">Tijdens rustigere uren heeft het personeel extra tijd en aandacht om schone spullen te pakken.</p>
                            </div>

                            <div class="bg-emerald-800/40 border border-emerald-700/50 p-4 rounded-2xl">
                                <div class="font-semibold text-emerald-200 text-sm mb-1 flex items-center gap-2">
                                    <i class="fa-solid fa-utensils text-amber-400"></i> 3. Vraag naar bereidingswijzen
                                </div>
                                <p class="text-xs text-slate-300">Vraag of patat in een aparte frituur wordt gebakken waarin geen allergenen (zoals kroketten) gaan.</p>
                            </div>

                            <div class="bg-emerald-800/40 border border-emerald-700/50 p-4 rounded-2xl">
                                <div class="font-semibold text-emerald-200 text-sm mb-1 flex items-center gap-2">
                                    <i class="fa-solid fa-kit-medical text-amber-400"></i> 4. Neem Noodmedicatie Mee
                                </div>
                                <p class="text-xs text-slate-300">Houd je Epipen of antihistamine altijd bij de hand op het terrein voor noodgevallen.</p>
                            </div>
                        </div>
                    </div>

                    <!-- Disclaimer Box -->
                    <div class="bg-amber-500/10 border border-amber-500/30 p-6 rounded-3xl text-amber-100">
                        <div class="flex items-center space-x-2 text-amber-400 font-bold mb-3">
                            <i class="fa-solid fa-triangle-exclamation text-xl"></i>
                            <span>Belangrijke Disclaimer</span>
                        </div>
                        <p class="text-xs leading-relaxed text-amber-200/90 mb-4">
                            AllergieVrij Food Plaza dient als een informatief platform. Hoewel kraampjes hun best doen kruisbesmetting te voorkomen, wijzigen recepturen en leveranciers soms. 
                        </p>
                        <p class="text-xs leading-relaxed text-amber-200/90 font-medium">
                            <strong class="text-amber-300">Onthoud:</strong> Controleer ter plekke altijd direct met de kok of de ingrediënten op dat moment 100% veilig zijn voor jouw allergie.
                        </p>
                    </div>

                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-8 border-t border-slate-800 text-xs">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-shield-halved text-emerald-500"></i>
                <span class="font-semibold text-slate-200">AllergieVrij Food Plaza</span>
                <span>&copy; 2026 - Samen veilig genieten</span>
            </div>
            <p>Ontwikkeld met zorg voor een allergieneutraal evenement.</p>
        </div>
    </footer>

    <div id="detail-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 hidden">
        <!-- Backdrop -->
        <div class="absolute inset-0 modal-backdrop" onclick="closeModal()"></div>
        
        <!-- Modal Body -->
        <div class="relative bg-white rounded-3xl shadow-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto z-10 overflow-hidden flex flex-col">
            <!-- Modal Header Image -->
            <div class="relative h-48 sm:h-56 w-full">
                <img id="modal-image" src="" alt="Food stall image" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-t from-slate-900/80 via-slate-900/20 to-transparent"></div>
                <button onclick="closeModal()" class="absolute top-4 right-4 bg-white/80 hover:bg-white text-slate-700 w-9 h-9 rounded-full flex items-center justify-center shadow-md transition-all">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
                <div class="absolute bottom-4 left-6 right-6 text-white">
                    <span id="modal-stand-location" class="inline-block bg-emerald-600 text-white text-xs font-semibold px-2.5 py-1 rounded-md mb-2 shadow"></span>
                    <h3 id="modal-title" class="text-2xl font-extrabold leading-tight"></h3>
                </div>
            </div>

            <!-- Modal Content Padding -->
            <div class="p-6 space-y-6 flex-grow">
                <!-- Safety Protocol Block -->
                <div class="bg-emerald-50 border border-emerald-200 rounded-2xl p-4">
                    <h4 class="font-bold text-emerald-900 text-sm mb-2 flex items-center gap-2">
                        <i class="fa-solid fa-shield-virus text-emerald-600"></i> Kruisbesmettings-protocol & Veiligheid
                    </h4>
                    <p id="modal-safety-info" class="text-xs text-emerald-800 leading-relaxed"></p>
                </div>

                <!-- Safe Allergies Badges -->
                <div>
                    <h4 class="text-xs font-bold uppercase tracking-wider text-slate-400 mb-2">Geschikt Voor Allergieën / Dieet:</h4>
                    <div id="modal-allergies-list" class="flex flex-wrap gap-2"></div>
                </div>

                <!-- Menu Section -->
                <div>
                    <h4 class="font-bold text-slate-900 text-base mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-utensils text-amber-500"></i> Menu & Ingrediënten
                    </h4>
                    <div id="modal-menu-list" class="space-y-3">
                        <!-- Menu items loaded dynamically -->
                    </div>
                </div>

                <!-- Contact & Certification -->
                <div class="pt-4 border-t border-slate-100 flex flex-col sm:flex-row justify-between text-xs text-slate-500 gap-2">
                    <div>
                        <span class="font-semibold text-slate-700">Certificering:</span> <span id="modal-certificate"></span>
                    </div>
                    <div>
                        <span class="font-semibold text-slate-700">Contactpersoon:</span> <span id="modal-contact"></span>
                    </div>
                </div>
            </div>
            
            <div class="bg-slate-50 px-6 py-4 border-t border-slate-100 flex justify-end">
                <button onclick="closeModal()" class="bg-slate-800 hover:bg-slate-900 text-white font-medium text-sm px-5 py-2.5 rounded-xl transition-colors">
                    Sluiten
                </button>
            </div>
        </div>
    </div>

    <div id="add-modal" class="fixed inset-0 z-50 flex items-center justify-center p-4 hidden">
        <div class="absolute inset-0 modal-backdrop" onclick="closeAddModal()"></div>
        <div class="relative bg-white rounded-3xl shadow-2xl max-w-xl w-full max-h-[90vh] overflow-y-auto z-10 p-6 sm:p-8">
            <button onclick="closeAddModal()" class="absolute top-5 right-5 text-slate-400 hover:text-slate-600 text-xl">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <div class="mb-6">
                <h3 class="text-2xl font-bold text-slate-900">Meld een Food Tent Aan</h3>
                <p class="text-xs text-slate-500 mt-1">Voeg een allergievriendelijk kraampje toe aan het platform.</p>
            </div>

            <form id="add-tent-form" onsubmit="handleAddTent(event)" class="space-y-4">
                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Naam van het Kraampje *</label>
                    <input type="text" required id="input-name" placeholder="bijv. De Veilige Snackkraam" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-semibold text-slate-700 mb-1">Stand / Zone Locatie *</label>
                        <input type="text" required id="input-location" placeholder="bijv. Stand B04 - Zone Blauw" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-slate-700 mb-1">Eten Type / Categorie *</label>
                        <input type="text" required id="input-category" placeholder="bijv. Patat & Snacks" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Afbeelding URL (Optioneel)</label>
                    <input type="url" id="input-image" placeholder="https://images.unsplash.com/..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none">
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-2">Geschikt voor welke allergieën? *</label>
                    <div id="add-modal-allergies" class="grid grid-cols-2 gap-2 text-xs">
                        <!-- Dynamic checkboxes from allergy list -->
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Kruisbesmettingsmaatregelen *</label>
                    <textarea required id="input-safety" rows="2" placeholder="Beschrijf bijvoorbeeld: Gescheiden frituur, schone snijplanken, allergenen-analyse..." class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none"></textarea>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Voorbeeld Menu & Ingrediënten</label>
                    <textarea id="input-menu" rows="2" placeholder="bijv. Glutenvrije Frites - 100% Aardappel, Friteuse-olie (geen glutenbesmetting)" class="w-full px-3.5 py-2.5 rounded-xl border border-slate-300 text-sm focus:ring-2 focus:ring-emerald-500 focus:outline-none"></textarea>
                </div>

                <div class="pt-4 flex justify-end gap-3">
                    <button type="button" onclick="closeAddModal()" class="px-4 py-2.5 rounded-xl border border-slate-300 text-slate-600 text-sm font-medium hover:bg-slate-50">Annuleren</button>
                    <button type="submit" class="px-5 py-2.5 rounded-xl bg-emerald-600 hover:bg-emerald-700 text-white text-sm font-semibold shadow-md">Kraam Toevoegen</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 bg-slate-900 text-white px-5 py-3 rounded-2xl shadow-xl flex items-center space-x-3 pointer-events-none">
        <i id="toast-icon" class="fa-solid fa-circle-check text-emerald-400"></i>
        <span id="toast-message" class="text-sm font-medium">Bericht</span>
    </div>

    <script>
        // MASTER ALLERGY DATA & DEFINITIONS
        const ALLERGIES = [
            { id: 'glutenvrij', name: 'Glutenvrij', icon: 'fa-wheat-awn-circle-exclamation' },
            { id: 'lactosevrij', name: 'Lactosevrij', icon: 'fa-cow' },
            { id: 'notenvrij', name: 'Notenvrij', icon: 'fa-seedling' },
            { id: 'pindavrij', name: 'Pindavrij', icon: 'fa-ban' },
            { id: 'sojavrij', name: 'Sojavrij', icon: 'fa-leaf' },
            { id: 'eivrij', name: 'Eivrij', icon: 'fa-egg' },
            { id: 'schaaldier', name: 'Schaaldieren-vrij', icon: 'fa-shrimp' },
            { id: 'sesamvrij', name: 'Sesamvrij', icon: 'fa-mortar-pestle' },
            { id: 'vegan', name: '100% Vegan', icon: 'fa-plant-wilt' }
        ];

        // INITIAL FOOD STALLS DATA
        const DEFAULT_FOOD_TENTS = [
            {
                id: 'tent-1',
                name: 'De Glutenvrije Pannenkoekenbakker',
                category: 'Pannenkoeken & Poffertjes',
                location: 'Stand A04 - Zone Groen',
                certificate: '🛡️ 100% Kruisbesmettingsvrij Gecertificeerd',
                image: 'https://images.unsplash.com/photo-1565299585323-38d6b0865b47?auto=format&fit=crop&w=800&q=80',
                allergies: ['glutenvrij', 'lactosevrij', 'notenvrij', 'eivrij', 'vegan'],
                safetyInfo: 'Wij werken met een volledig glutenvrije en melkvrije bakplaat. Beslag wordt vers gemaakt in een afgesloten ruimte met gecertificeerd teff- en boekweitmeel.',
                contact: 'Jan & Ellen (06-12345678)',
                menu: [
                    { item: 'Oud-Hollandse Pannenkoek Appel & Kaneel', price: '€ 7,50', ingredients: 'Boekweitmeel, teffmeel, havermelk, verse appel, kaneel', tags: ['Glutenvrij', 'Lactosevrij', 'Vegan'] },
                    { item: 'Poffertjes met Poedersuiker (10st)', price: '€ 6,00', ingredients: 'Glutenvrije meelmix, kokosmelk, plantaardige boter, poedersuiker', tags: ['Glutenvrij', 'Lactosevrij'] }
                ]
            },
            {
                id: 'tent-2',
                name: 'Nut-Free Burger & Fries Shack',
                category: 'Burgers & Patat',
                location: 'Stand B12 - Zone Geel',
                certificate: '🌿 Aparte Bereidingskeuken',
                image: 'https://images.unsplash.com/photo-1550547660-d9450f859349?auto=format&fit=crop&w=800&q=80',
                allergies: ['notenvrij', 'pindavrij', 'glutenvrij', 'lactosevrij'],
                safetyInfo: 'Absolute nul-tolerantie voor noten en pinda’s in ons hele assortiment. Frituur wordt uitsluitend gebruikt voor ons glutenvrij assortiment patat en allergenen-vrije snacks.',
                contact: 'Chef Marco (info@nutfreeburgers.nl)',
                menu: [
                    { item: 'Smokey Bacon Burger (Glutenvrij Bolletje)', price: '€ 11,50', ingredients: '100% rundvlees, glutenvrij briochebol, vegan mayo, glutenvrije bacon', tags: ['Glutenvrij', 'Notenvrij', 'Pindavrij'] },
                    { item: 'Ambachtelijke Verse Frites', price: '€ 4,50', ingredients: 'Verse aardappelen, 100% zonnebloemolie, zeezout', tags: ['Glutenvrij', 'Lactosevrij', 'Notenvrij', 'Vegan'] }
                ]
            },
            {
                id: 'tent-3',
                name: 'LactoseVrij IJs & Wafel Paleis',
                category: 'IJs & Desserts',
                location: 'Stand C01 - Zone Rood',
                certificate: '🍦 100% Melk- en Lactosevrij',
                image: 'https://images.unsplash.com/photo-1563805042-7684c019e1cb?auto=format&fit=crop&w=800&q=80',
                allergies: ['lactosevrij', 'notenvrij', 'eivrij', 'vegan'],
                safetyInfo: 'Al onze ijssoorten worden bereid op basis van haver-, amandel- of kokosbasis in een melkvrije ijsmakerij. Schepscheppen worden apart gedesinfecteerd.',
                contact: 'Sanne (IJsmeester)',
                menu: [
                    { item: 'Vers Baked Wafel met Erdbeeren', price: '€ 6,50', ingredients: 'Havermeel, kokosolie, verse aardbeien, poedersuiker', tags: ['Lactosevrij', 'Vegan'] },
                    { item: 'Ambachtelijk Mango Sorbet & Choco-Dip', price: '€ 4,00', ingredients: 'Verse mango, rietsuiker, vegan pure chocolade (vrij van sporen)', tags: ['Lactosevrij', 'Eivrij'] }
                ]
            },
            {
                id: 'tent-4',
                name: 'SafeBites Asian Streetfood',
                category: 'Aziatisch & Rice Bowls',
                location: 'Stand D08 - Zone Groen',
                certificate: '🛡️ Gecontroleerde Kruidenmixen',
                image: 'https://images.unsplash.com/photo-1541696432-82c6da8ce7bf?auto=format&fit=crop&w=800&q=80',
                allergies: ['glutenvrij', 'sojavrij', 'notenvrij', 'schaaldier'],
                safetyInfo: 'Wij gebruiken tamari zonder tarwe en kokos-aminos in plaats van traditionele sojasaus. Geen pinda’s of schaaldieren toegestaan in de keukencabine.',
                contact: 'Team SafeBites',
                menu: [
                    { item: 'Coconut Curry Chicken Rice Bowl', price: '€ 12,00', ingredients: 'Kipfilet, kokosmelk, gele currypasta (zonder schaaldieren/gluten), jasmijnrijst, verse koriander', tags: ['Glutenvrij', 'Sojavrij', 'Schaaldier-vrij'] },
                    { item: 'Krokante Rijstvel Lente-rolletjes', price: '€ 7,00', ingredients: 'Rijstpapier, glasmie, wortel, komkommer, zoetzure dipsaus zonder soja', tags: ['Glutenvrij', 'Sojavrij', 'Vegan'] }
                ]
            },
            {
                id: 'tent-5',
                name: 'De Vrij-Van Ambachtelijke Bakkerij',
                category: 'Brood & Gebak',
                location: 'Stand A10 - Zone Geel',
                certificate: '🍞 ISO Allergenen Gecertificeerd',
                image: 'https://images.unsplash.com/photo-1509440159596-0249088772ff?auto=format&fit=crop&w=800&q=80',
                allergies: ['glutenvrij', 'lactosevrij', 'notenvrij', 'pindavrij', 'sesamvrij', 'vegan'],
                safetyInfo: 'Alle producten worden verpakt in verzegelde allergenenvrije folies om besmetting op het terrein door de lucht of handen te voorkomen.',
                contact: 'Bakker Lucas',
                menu: [
                    { item: 'Versgebakken Kaneelbroodje', price: '€ 3,80', ingredients: 'Glutenvrije haver, tapiocazetmeel, kokosbloesemsuiker, ceylon kaneel', tags: ['Glutenvrij', 'Lactosevrij', 'Sesamvrij', 'Vegan'] },
                    { item: 'Hartig Zadenbroodje Hummus', price: '€ 5,50', ingredients: 'Zonnebloempitten, pompoenpitten, kikkererwten, citroen, olijfolie', tags: ['Glutenvrij', 'Notenvrij', 'Sesamvrij'] }
                ]
            },
            {
                id: 'tent-6',
                name: 'De Veilige Frituur & Snacks',
                category: 'Patat & Snacks',
                location: 'Stand B02 - Zone Groen',
                certificate: '🛡️ 100% Gescheiden Frituurketels',
                image: 'https://images.unsplash.com/photo-1576107232684-1279f3908594?auto=format&fit=crop&w=800&q=80',
                allergies: ['glutenvrij', 'pindavrij', 'lactosevrij', 'eivrij'],
                safetyInfo: 'Onze frituurovens zijn fysiek van elkaar gescheiden met strikte kleurcodes. Frituur A is uitsluitend voor glutenvrije patat en B voor allergievrije kalfskroketten.',
                contact: 'Karel (Frituurmeester)',
                menu: [
                    { item: 'Glutenvrije & Lactosevrije Kalfskroket', price: '€ 3,50', ingredients: 'Kalfsvlees, glutenvrije paneermeel, bouillon, plantaardige vulling', tags: ['Glutenvrij', 'Lactosevrij'] },
                    { item: 'Zoete Aardappel Frites + Vegan Mayo', price: '€ 5,00', ingredients: 'Zoete aardappel, plantaardige olie, sojavrije en eivrije mayonaise', tags: ['Glutenvrij', 'Eivrij', 'Pindavrij'] }
                ]
            }
        ];

        // STATE MANAGEMENT
        let foodTents = [];
        let selectedFilters = new Set();
        let searchQuery = '';
        let favorites = new Set();
        let favoritesOnly = false;

        // Initialize App State
        function initApp() {
            // Load saved favorites
            try {
                const savedFavs = localStorage.getItem('allergievrij_favorites');
                if (savedFavs) favorites = new Set(JSON.parse(savedFavs));
            } catch (e) {
                favorites = new Set();
            }

            // Load saved food tents or default
            try {
                const savedTents = localStorage.getItem('allergievrij_custom_tents');
                if (savedTents) {
                    foodTents = [...DEFAULT_FOOD_TENTS, ...JSON.parse(savedTents)];
                } else {
                    foodTents = [...DEFAULT_FOOD_TENTS];
                }
            } catch (e) {
                foodTents = [...DEFAULT_FOOD_TENTS];
            }

            renderFilterButtons();
            renderAddModalCheckboxes();
            renderTents();
            updateFavBadge();
        }

        // Save State Helpers
        function saveFavorites() {
            try {
                localStorage.setItem('allergievrij_favorites', JSON.stringify([...favorites]));
            } catch(e) {}
            updateFavBadge();
        }

        function updateFavBadge() {
            document.getElementById('fav-count-badge').textContent = favorites.size;
        }

        // Render Filter Matrix Buttons
        function renderFilterButtons() {
            const grid = document.getElementById('allergy-filter-grid');
            grid.innerHTML = ALLERGIES.map(allergy => {
                const isActive = selectedFilters.has(allergy.id);
                return `
                    <button onclick="toggleFilter('${allergy.id}')" 
                        class="flex items-center space-x-2 px-3 py-2.5 rounded-2xl border text-xs sm:text-sm font-medium transition-all duration-200 text-left ${
                            isActive 
                            ? 'bg-emerald-600 text-white border-emerald-600 shadow-md shadow-emerald-600/20' 
                            : 'bg-slate-50 text-slate-700 border-slate-200 hover:border-emerald-300 hover:bg-emerald-50/50'
                        }">
                        <i class="fa-solid ${allergy.icon} ${isActive ? 'text-white' : 'text-emerald-600'} text-base"></i>
                        <span class="truncate">${allergy.name}</span>
                    </button>
                `;
            }).join('');

            updateActiveFilterTags();
        }

        function toggleFilter(allergyId) {
            if (selectedFilters.has(allergyId)) {
                selectedFilters.delete(allergyId);
            } else {
                selectedFilters.add(allergyId);
            }
            renderFilterButtons();
            renderTents();
        }

        function resetFilters() {
            selectedFilters.clear();
            searchQuery = '';
            favoritesOnly = false;
            document.getElementById('search-input').value = '';
            document.getElementById('clear-search-btn').classList.add('hidden');
            
            // Reset Fav button UI
            const favBtn = document.getElementById('fav-toggle-btn');
            favBtn.classList.remove('bg-amber-500', 'text-white', 'border-amber-500');
            favBtn.classList.add('border-slate-200', 'text-slate-700');

            renderFilterButtons();
            renderTents();
            showToast('Alle zoekfilters zijn gewist.');
        }

        function updateActiveFilterTags() {
            const container = document.getElementById('active-filter-tags');
            if (selectedFilters.size === 0 && !favoritesOnly && !searchQuery) {
                container.innerHTML = '';
                return;
            }

            let tagsHtml = '';
            selectedFilters.forEach(id => {
                const item = ALLERGIES.find(a => a.id === id);
                if (item) {
                    tagsHtml += `
                        <span class="inline-flex items-center gap-1 bg-emerald-100 text-emerald-800 px-2 py-0.5 rounded-md font-semibold">
                            ${item.name}
                            <i class="fa-solid fa-xmark text-xs cursor-pointer hover:text-emerald-900" onclick="toggleFilter('${id}')"></i>
                        </span>
                    `;
                }
            });

            if (favoritesOnly) {
                tagsHtml += `
                    <span class="inline-flex items-center gap-1 bg-amber-100 text-amber-800 px-2 py-0.5 rounded-md font-semibold">
                        Alleen Favorieten
                        <i class="fa-solid fa-xmark text-xs cursor-pointer hover:text-amber-900" onclick="toggleFavoritesOnly()"></i>
                    </span>
                `;
            }

            container.innerHTML = tagsHtml;
        }

        function handleSearch() {
            const val = document.getElementById('search-input').value.trim();
            searchQuery = val.toLowerCase();
            const clearBtn = document.getElementById('clear-search-btn');
            
            if (val.length > 0) {
                clearBtn.classList.remove('hidden');
            } else {
                clearBtn.classList.add('hidden');
            }

            renderTents();
        }

        function clearSearch() {
            document.getElementById('search-input').value = '';
            handleSearch();
        }

        function toggleFavoritesOnly() {
            favoritesOnly = !favoritesOnly;
            const favBtn = document.getElementById('fav-toggle-btn');
            if (favoritesOnly) {
                favBtn.classList.add('bg-amber-500', 'text-white', 'border-amber-500');
                favBtn.classList.remove('border-slate-200', 'text-slate-700');
                showToast('Toont nu alleen jouw bewaarde favorieten.');
            } else {
                favBtn.classList.remove('bg-amber-500', 'text-white', 'border-amber-500');
                favBtn.classList.add('border-slate-200', 'text-slate-700');
            }
            updateActiveFilterTags();
            renderTents();
        }

        function toggleFavorite(id, event) {
            if (event) event.stopPropagation();
            if (favorites.has(id)) {
                favorites.delete(id);
                showToast('Kraampje verwijderd uit favorieten');
            } else {
                favorites.add(id);
                showToast('Kraampje opgeslagen als favoriet!');
            }
            saveFavorites();
            renderTents();
        }

        // Filter Logic & Rendering Cards
        function renderTents() {
            const container = document.getElementById('tents-container');
            const emptyState = document.getElementById('empty-state');

            // Apply Filters
            const filtered = foodTents.filter(tent => {
                if (favoritesOnly && !favorites.has(tent.id)) return false;

                if (searchQuery) {
                    const matchName = tent.name.toLowerCase().includes(searchQuery);
                    const matchCat = tent.category.toLowerCase().includes(searchQuery);
                    const matchMenu = tent.menu.some(m => m.item.toLowerCase().includes(searchQuery) || m.ingredients.toLowerCase().includes(searchQuery));
                    if (!matchName && !matchCat && !matchMenu) return false;
                }

                if (selectedFilters.size > 0) {
                    for (let allergy of selectedFilters) {
                        if (!tent.allergies.includes(allergy)) return false;
                    }
                }

                return true;
            });

            document.getElementById('results-count').textContent = `${filtered.length} ${filtered.length === 1 ? 'kraampje' : 'kraampjes'}`;

            if (filtered.length === 0) {
                container.innerHTML = '';
                emptyState.classList.remove('hidden');
                return;
            }

            emptyState.classList.add('hidden');

            container.innerHTML = filtered.map(tent => {
                const isFav = favorites.has(tent.id);
                
                const allergyBadges = tent.allergies.map(aId => {
                    const item = ALLERGIES.find(a => a.id === aId);
                    if (!item) return '';
                    return `
                        <span class="inline-flex items-center gap-1 bg-slate-100 border border-slate-200 text-slate-700 text-[11px] font-semibold px-2 py-0.5 rounded-md">
                            <i class="fa-solid ${item.icon} text-emerald-600"></i> ${item.name}
                        </span>
                    `;
                }).join('');

                return `
                    <div class="bg-white rounded-3xl overflow-hidden border border-slate-200/80 shadow-md hover:shadow-xl transition-all duration-300 flex flex-col group">
                        <!-- Image Header -->
                        <div class="relative h-48 overflow-hidden bg-slate-100">
                            <img src="${tent.image}" alt="${tent.name}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" onerror="this.src='https://images.unsplash.com/photo-1555396273-367ea4eb4db5?auto=format&fit=crop&w=800&q=80'">
                            
                            <span class="absolute top-3 left-3 bg-slate-900/80 backdrop-blur-md text-white text-xs font-semibold px-3 py-1 rounded-full shadow">
                                <i class="fa-solid fa-location-dot text-emerald-400 mr-1"></i> ${tent.location}
                            </span>

                            <button onclick="toggleFavorite('${tent.id}', event)" class="absolute top-3 right-3 w-9 h-9 bg-white/90 backdrop-blur-md rounded-full flex items-center justify-center shadow hover:scale-110 transition-transform">
                                <i class="fa-solid fa-heart ${isFav ? 'text-amber-500' : 'text-slate-300'} text-base"></i>
                            </button>
                        </div>

                        <!-- Card Body -->
                        <div class="p-5 flex-grow flex flex-col justify-between">
                            <div>
                                <div class="text-xs font-semibold text-emerald-600 uppercase tracking-wider mb-1">${tent.category}</div>
                                <h3 class="text-lg font-bold text-slate-900 leading-snug mb-2 group-hover:text-emerald-700 transition-colors">${tent.name}</h3>

                                <div class="inline-block bg-emerald-50 text-emerald-800 text-xs font-semibold px-2.5 py-1 rounded-lg border border-emerald-200 mb-3">
                                    ${tent.certificate}
                                </div>

                                <div class="flex flex-wrap gap-1.5 mb-4">
                                    ${allergyBadges}
                                </div>
                            </div>

                            <button onclick="openModal('${tent.id}')" class="w-full mt-2 bg-slate-100 hover:bg-emerald-600 hover:text-white text-slate-800 font-semibold text-xs py-3 rounded-xl transition-all flex items-center justify-center space-x-2 group/btn">
                                <span>Bekijk Menu & Veiligheid</span>
                                <i class="fa-solid fa-arrow-right text-xs group-hover/btn:translate-x-1 transition-transform"></i>
                            </button>
                        </div>
                    </div>
                `;
            }).join('');
        }

        // Modal Controls
        function openModal(tentId) {
            const tent = foodTents.find(t => t.id === tentId);
            if (!tent) return;

            document.getElementById('modal-image').src = tent.image;
            document.getElementById('modal-title').textContent = tent.name;
            document.getElementById('modal-stand-location').textContent = tent.location;
            document.getElementById('modal-safety-info').textContent = tent.safetyInfo;
            document.getElementById('modal-certificate').textContent = tent.certificate;
            document.getElementById('modal-contact').textContent = tent.contact || 'Evenementenbalie';

            const allergiesContainer = document.getElementById('modal-allergies-list');
            allergiesContainer.innerHTML = tent.allergies.map(aId => {
                const item = ALLERGIES.find(a => a.id === aId);
                return item ? `
                    <span class="bg-emerald-100 text-emerald-800 text-xs font-semibold px-2.5 py-1 rounded-lg flex items-center gap-1.5">
                        <i class="fa-solid ${item.icon}"></i> ${item.name}
                    </span>
                ` : '';
            }).join('');

            const menuContainer = document.getElementById('modal-menu-list');
            menuContainer.innerHTML = tent.menu.map(m => `
                <div class="bg-slate-50 border border-slate-200/70 p-3.5 rounded-2xl">
                    <div class="flex justify-between items-start mb-1">
                        <span class="font-bold text-slate-800 text-sm">${m.item}</span>
                        <span class="font-extrabold text-emerald-700 text-sm">${m.price}</span>
                    </div>
                    <p class="text-xs text-slate-500 mb-2"><strong>Ingrediënten:</strong> ${m.ingredients}</p>
                    <div class="flex flex-wrap gap-1">
                        ${m.tags.map(t => `<span class="bg-amber-100 text-amber-800 text-[10px] font-bold px-2 py-0.5 rounded">${t}</span>`).join('')}
                    </div>
                </div>
            `).join('');

            document.getElementById('detail-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            document.getElementById('detail-modal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        function renderAddModalCheckboxes() {
            const container = document.getElementById('add-modal-allergies');
            container.innerHTML = ALLERGIES.map(a => `
                <label class="flex items-center space-x-2 p-2 bg-slate-50 rounded-xl border border-slate-200 cursor-pointer hover:bg-slate-100">
                    <input type="checkbox" name="add-allergy" value="${a.id}" class="rounded text-emerald-600 focus:ring-emerald-500">
                    <span class="truncate">${a.name}</span>
                </label>
            `).join('');
        }

        function openAddModal() {
            document.getElementById('add-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeAddModal() {
            document.getElementById('add-modal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        function handleAddTent(event) {
            event.preventDefault();

            const name = document.getElementById('input-name').value.trim();
            const location = document.getElementById('input-location').value.trim();
            const category = document.getElementById('input-category').value.trim();
            const image = document.getElementById('input-image').value.trim() || 'https://images.unsplash.com/photo-1555396273-367ea4eb4db5?auto=format&fit=crop&w=800&q=80';
            const safetyInfo = document.getElementById('input-safety').value.trim();
            const menuRaw = document.getElementById('input-menu').value.trim();

            const selectedCheckboxes = document.querySelectorAll('input[name="add-allergy"]:checked');
            const allergies = Array.from(selectedCheckboxes).map(cb => cb.value);

            if (allergies.length === 0) {
                showToast('Selecteer minimaal één allergie-optie.', true);
                return;
            }

            const newTent = {
                id: 'custom-' + Date.now(),
                name,
                category,
                location,
                certificate: '🛡️ Handmatig Toegevoegd & Verified',
                image,
                allergies,
                safetyInfo,
                contact: 'Aangemeld door Bezoeker',
                menu: [
                    {
                        item: 'Specialiteit van de Kraam',
                        price: 'Prijs op locatie',
                        ingredients: menuRaw || 'Zie bord op locatie voor exacte ingrediënten.',
                        tags: ['Vers bereid']
                    }
                ]
            };

            foodTents.unshift(newTent);
            
            try {
                const savedTents = JSON.parse(localStorage.getItem('allergievrij_custom_tents') || '[]');
                savedTents.unshift(newTent);
                localStorage.setItem('allergievrij_custom_tents', JSON.stringify(savedTents));
            } catch(e) {}

            closeAddModal();
            document.getElementById('add-tent-form').reset();
            renderTents();
            showToast('Nieuwe food tent succesvol toegevoegd!');
        }

        // Toast Messages
        function showToast(message, isError = false) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toast-message');
            const toastIcon = document.getElementById('toast-icon');

            toastMsg.textContent = message;
            if (isError) {
                toastIcon.className = 'fa-solid fa-circle-xmark text-red-400';
            } else {
                toastIcon.className = 'fa-solid fa-circle-check text-emerald-400';
            }

            toast.classList.remove('translate-y-20', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.remove('translate-y-0', 'opacity-100');
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 3000);
        }

        window.addEventListener('keydown', (e) => {
            if (e.key === 'Escape') {
                closeModal();
                closeAddModal();
            }
        });

        window.onload = initApp;
    </script>
</body>
</html>
