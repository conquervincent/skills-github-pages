<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PSP Games Portal - Your Ultimate Source for PlayStation Portable Games</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#5271ff',secondary:'#ff5252'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Inter', sans-serif;
        }
        .game-card:hover .game-actions {
            opacity: 1;
        }
        .game-card:hover .game-image {
            transform: scale(1.05);
        }
        .game-image {
            transition: transform 0.3s ease;
        }
        .category-tab.active {
            color: #5271ff;
            border-color: #5271ff;
        }
        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
        .custom-checkbox {
            position: relative;
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 2px solid #d1d5db;
            border-radius: 4px;
            cursor: pointer;
        }
        .custom-checkbox.checked {
            background-color: #5271ff;
            border-color: #5271ff;
        }
        .custom-checkbox.checked::after {
            content: '';
            position: absolute;
            left: 6px;
            top: 2px;
            width: 6px;
            height: 10px;
            border: solid white;
            border-width: 0 2px 2px 0;
            transform: rotate(45deg);
        }
        .custom-radio {
            position: relative;
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 2px solid #d1d5db;
            border-radius: 50%;
            cursor: pointer;
        }
        .custom-radio.checked {
            border-color: #5271ff;
        }
        .custom-radio.checked::after {
            content: '';
            position: absolute;
            left: 4px;
            top: 4px;
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background-color: #5271ff;
        }
        .custom-switch {
            position: relative;
            display: inline-block;
            width: 44px;
            height: 24px;
            background-color: #e5e7eb;
            border-radius: 12px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .custom-switch.checked {
            background-color: #5271ff;
        }
        .custom-switch::after {
            content: '';
            position: absolute;
            top: 2px;
            left: 2px;
            width: 20px;
            height: 20px;
            background-color: white;
            border-radius: 50%;
            transition: transform 0.3s;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        }
        .custom-switch.checked::after {
            transform: translateX(20px);
        }
        .custom-range {
            -webkit-appearance: none;
            width: 100%;
            height: 6px;
            background: #e5e7eb;
            border-radius: 3px;
            outline: none;
        }
        .custom-range::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 18px;
            height: 18px;
            background: #5271ff;
            border-radius: 50%;
            cursor: pointer;
        }
        .custom-range::-moz-range-thumb {
            width: 18px;
            height: 18px;
            background: #5271ff;
            border-radius: 50%;
            cursor: pointer;
            border: none;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header Section -->
    <header class="sticky top-0 z-50 bg-white shadow-sm">
        <div class="container mx-auto px-4 py-3 flex items-center justify-between">
            <div class="flex items-center">
                <a href="#" class="text-2xl font-['Pacifico'] text-primary mr-8">logo</a>
                <nav class="hidden md:flex space-x-6">
                    <a href="#" class="font-medium text-primary">Home</a>
                    <a href="#" class="font-medium text-gray-700 hover:text-primary transition">Games</a>
                    <a href="#" class="font-medium text-gray-700 hover:text-primary transition">News</a>
                    <a href="#" class="font-medium text-gray-700 hover:text-primary transition">Community</a>
                    <a href="#" class="font-medium text-gray-700 hover:text-primary transition">About</a>
                </nav>
            </div>
            
            <div class="flex items-center space-x-4">
                <div class="relative w-64 hidden md:block">
                    <input type="text" placeholder="Search games..." class="w-full pl-10 pr-4 py-2 rounded-full bg-gray-100 border-none focus:ring-2 focus:ring-primary focus:outline-none text-sm">
                    <div class="absolute left-3 top-2.5 w-5 h-5 flex items-center justify-center text-gray-500">
                        <i class="ri-search-line"></i>
                    </div>
                </div>
                
                <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
                    <span class="hidden md:inline">Sign In</span>
                    <span class="md:hidden flex items-center justify-center">
                        <i class="ri-user-line"></i>
                    </span>
                </button>
                
                <button class="md:hidden w-10 h-10 flex items-center justify-center text-gray-700">
                    <i class="ri-menu-line text-xl"></i>
                </button>
            </div>
        </div>
    </header>
    <!-- Hero Banner Section -->
    <section class="relative bg-gradient-to-r from-gray-900 to-primary overflow-hidden" style="background-image: url('https://readdy.ai/api/search-image?query=Futuristic%20gaming%20setup%20with%20PlayStation%20Portable%20console%2C%20glowing%20blue%20light%20effects%2C%20high-tech%20gaming%20environment%2C%20multiple%20PSP%20games%20displayed%2C%20dramatic%20lighting%2C%20sleek%20modern%20design%2C%20digital%20interface%20elements%2C%20high%20resolution%20detailed%20image&width=1600&height=600&seq=1&orientation=landscape'); background-size: cover; background-position: center;">
        <div class="absolute inset-0 bg-gradient-to-r from-gray-900 to-transparent opacity-90"></div>
        <div class="container mx-auto px-4 py-16 md:py-24 relative z-10">
            <div class="max-w-2xl text-white">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Discover the Ultimate PSP Gaming Experience</h1>
                <p class="text-lg md:text-xl mb-8 text-gray-200">Explore thousands of classic and modern PSP games. Download, play, and connect with the community.</p>
                <div class="flex flex-wrap gap-4">
                    <button class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap font-semibold hover:bg-opacity-90 transition">Browse Games</button>
                    <button class="bg-white text-gray-900 px-6 py-3 !rounded-button whitespace-nowrap font-semibold hover:bg-opacity-90 transition">Join Community</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Game Categories -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold mb-8 text-gray-900">Browse by Category</h2>
            
            <div class="flex overflow-x-auto pb-4 gap-4 hide-scrollbar">
                <button class="category-tab active flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-primary bg-opacity-10 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-gamepad-line text-xl text-primary"></i>
                    </div>
                    <span class="text-sm font-medium">All Games</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-sword-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Action</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-user-star-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">RPG</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-steering-2-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Racing</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-basketball-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Sports</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-chess-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Strategy</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-ghost-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Horror</span>
                </button>
                
                <button class="category-tab flex flex-col items-center min-w-[80px] p-3 border-b-2 border-transparent hover:text-primary transition whitespace-nowrap">
                    <div class="w-12 h-12 bg-gray-100 rounded-full flex items-center justify-center mb-2">
                        <i class="ri-flight-takeoff-line text-xl text-gray-700"></i>
                    </div>
                    <span class="text-sm font-medium">Simulation</span>
                </button>
            </div>
        </div>
    </section>

    <!-- Popular Games Section -->
    <section class="py-12 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-900">Popular Games</h2>
                <a href="#" class="text-primary font-medium flex items-center hover:underline">
                    View All
                    <i class="ri-arrow-right-line ml-1"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Game Card 1 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=God%20of%20War:%20Chains%20of%20Olympus%20game%20cover%20art%20for%20PSP%2C%20featuring%20Kratos%20with%20blades%20of%20chaos%2C%20epic%20mythological%20setting%2C%20dramatic%20lighting%2C%20official%20PlayStation%20Portable%20game%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=2&orientation=landscape" alt="God of War: Chains of Olympus" class="game-image w-full h-full object-cover object-top">
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">God of War: Chains of Olympus</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.8</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Action-adventure game featuring Kratos in a prequel to the original God of War.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Mar 4, 2008</span>
                            <span class="text-xs font-medium px-2 py-1 bg-green-100 text-green-800 rounded-full">Action</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 2 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Final%20Fantasy%20VII:%20Crisis%20Core%20game%20cover%20art%20for%20PSP%2C%20featuring%20Zack%20Fair%20with%20buster%20sword%2C%20Midgar%20in%20background%2C%20blue%20color%20scheme%2C%20official%20Square%20Enix%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=3&orientation=landscape" alt="Crisis Core: Final Fantasy VII" class="game-image w-full h-full object-cover object-top">
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Crisis Core: Final Fantasy VII</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.7</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Action RPG that follows Zack Fair, a young member of the paramilitary organization SOLDIER.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Sep 13, 2007</span>
                            <span class="text-xs font-medium px-2 py-1 bg-blue-100 text-blue-800 rounded-full">RPG</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 3 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Monster%20Hunter%20Freedom%20Unite%20game%20cover%20art%20for%20PSP%2C%20featuring%20various%20monsters%20and%20hunters%20with%20weapons%2C%20fantasy%20setting%2C%20vibrant%20colors%2C%20official%20Capcom%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=4&orientation=landscape" alt="Monster Hunter Freedom Unite" class="game-image w-full h-full object-cover object-top">
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Monster Hunter Freedom Unite</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.6</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Action RPG where players take on the role of a hunter to complete quests and slay monsters.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Jun 22, 2009</span>
                            <span class="text-xs font-medium px-2 py-1 bg-purple-100 text-purple-800 rounded-full">Action RPG</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 4 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Gran%20Turismo%20PSP%20game%20cover%20art%2C%20featuring%20realistic%20sports%20cars%20on%20a%20race%20track%2C%20professional%20photography%20style%2C%20sleek%20design%2C%20official%20PlayStation%20Portable%20game%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=5&orientation=landscape" alt="Gran Turismo" class="game-image w-full h-full object-cover object-top">
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Gran Turismo</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.5</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Racing simulator featuring over 800 cars and 35 tracks with stunning graphics for a portable console.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Oct 1, 2009</span>
                            <span class="text-xs font-medium px-2 py-1 bg-red-100 text-red-800 rounded-full">Racing</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- New Releases Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-900">New Releases</h2>
                <a href="#" class="text-primary font-medium flex items-center hover:underline">
                    View All
                    <i class="ri-arrow-right-line ml-1"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Game Card 1 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Persona%203%20Portable%20game%20cover%20art%20for%20PSP%2C%20featuring%20anime-style%20characters%2C%20blue%20color%20scheme%2C%20moon%20imagery%2C%20official%20Atlus%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=6&orientation=landscape" alt="Persona 3 Portable" class="game-image w-full h-full object-cover object-top">
                        <div class="absolute top-2 right-2 bg-yellow-400 text-xs font-bold px-2 py-1 rounded-full text-gray-900">NEW</div>
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Persona 3 Portable</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.9</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">JRPG that follows a group of high school students who use a special power called "Persona".</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: May 15, 2025</span>
                            <span class="text-xs font-medium px-2 py-1 bg-blue-100 text-blue-800 rounded-full">RPG</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 2 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Metal%20Gear%20Solid:%20Peace%20Walker%20game%20cover%20art%20for%20PSP%2C%20featuring%20Snake%20in%20tactical%20gear%2C%20military%20setting%2C%20stealth%20elements%2C%20official%20Konami%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=7&orientation=landscape" alt="Metal Gear Solid: Peace Walker" class="game-image w-full h-full object-cover object-top">
                        <div class="absolute top-2 right-2 bg-yellow-400 text-xs font-bold px-2 py-1 rounded-full text-gray-900">NEW</div>
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Metal Gear Solid: Peace Walker</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.7</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Stealth action game set in 1974 featuring Big Boss as he establishes Militaires Sans Frontières.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Apr 28, 2025</span>
                            <span class="text-xs font-medium px-2 py-1 bg-green-100 text-green-800 rounded-full">Action</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 3 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Tekken%206%20game%20cover%20art%20for%20PSP%2C%20featuring%20martial%20arts%20fighters%20in%20combat%20poses%2C%20dynamic%20action%2C%20official%20Bandai%20Namco%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=8&orientation=landscape" alt="Tekken 6" class="game-image w-full h-full object-cover object-top">
                        <div class="absolute top-2 right-2 bg-yellow-400 text-xs font-bold px-2 py-1 rounded-full text-gray-900">NEW</div>
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Tekken 6</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.5</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Fighting game featuring over 40 characters, customization options, and a scenario campaign mode.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Apr 10, 2025</span>
                            <span class="text-xs font-medium px-2 py-1 bg-orange-100 text-orange-800 rounded-full">Fighting</span>
                        </div>
                    </div>
                </div>
                
                <!-- Game Card 4 -->
                <div class="game-card bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="relative overflow-hidden h-48">
                        <img src="https://readdy.ai/api/search-image?query=Dissidia%20Final%20Fantasy%20game%20cover%20art%20for%20PSP%2C%20featuring%20Cloud%20Strife%20and%20other%20Final%20Fantasy%20characters%2C%20fantasy%20battle%20scene%2C%20official%20Square%20Enix%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=250&seq=9&orientation=landscape" alt="Dissidia Final Fantasy" class="game-image w-full h-full object-cover object-top">
                        <div class="absolute top-2 right-2 bg-yellow-400 text-xs font-bold px-2 py-1 rounded-full text-gray-900">NEW</div>
                        <div class="game-actions absolute inset-0 bg-black bg-opacity-60 flex items-center justify-center opacity-0 transition-opacity">
                            <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium mr-2">
                                <i class="ri-download-line mr-1"></i> Download
                            </button>
                            <button class="bg-white text-gray-900 px-4 py-2 !rounded-button whitespace-nowrap font-medium">
                                <i class="ri-information-line mr-1"></i> Details
                            </button>
                        </div>
                    </div>
                    <div class="p-4">
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="font-semibold text-lg">Dissidia Final Fantasy</h3>
                            <div class="flex items-center">
                                <i class="ri-star-fill text-yellow-400"></i>
                                <span class="ml-1 text-sm font-medium">4.6</span>
                            </div>
                        </div>
                        <p class="text-sm text-gray-600 mb-3">Fighting game that features characters from various Final Fantasy titles in a battle of gods.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs text-gray-500">Released: Mar 22, 2025</span>
                            <span class="text-xs font-medium px-2 py-1 bg-purple-100 text-purple-800 rounded-full">Fighting RPG</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Editor's Choice Section -->
    <section class="py-12 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-2xl md:text-3xl font-bold text-gray-900">Editor's Choice</h2>
                <a href="#" class="text-primary font-medium flex items-center hover:underline">
                    View All
                    <i class="ri-arrow-right-line ml-1"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <!-- Featured Game -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="flex flex-col md:flex-row h-full">
                        <div class="md:w-2/5 relative">
                            <img src="https://readdy.ai/api/search-image?query=Patapon%20game%20for%20PSP%2C%20featuring%20silhouette%20tribal%20characters%20with%20spears%20and%20weapons%2C%20rhythmic%20gameplay%20elements%2C%20colorful%20background%2C%20official%20Sony%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=500&seq=10&orientation=portrait" alt="Patapon" class="w-full h-full object-cover object-top">
                            <div class="absolute top-2 right-2 bg-primary text-xs font-bold px-2 py-1 rounded-full text-white">EDITOR'S PICK</div>
                        </div>
                        <div class="md:w-3/5 p-6 flex flex-col justify-between">
                            <div>
                                <div class="flex items-center mb-2">
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <span class="ml-2 text-sm font-medium">5.0</span>
                                </div>
                                <h3 class="text-2xl font-bold mb-3">Patapon</h3>
                                <p class="text-gray-600 mb-4">A unique rhythm-based action game where players control an army of tribal warriors called Patapons through drumbeats. The innovative gameplay combines music, strategy, and action in a visually striking 2D world.</p>
                                <div class="flex flex-wrap gap-2 mb-4">
                                    <span class="text-xs font-medium px-2 py-1 bg-purple-100 text-purple-800 rounded-full">Rhythm</span>
                                    <span class="text-xs font-medium px-2 py-1 bg-blue-100 text-blue-800 rounded-full">Strategy</span>
                                    <span class="text-xs font-medium px-2 py-1 bg-green-100 text-green-800 rounded-full">Action</span>
                                </div>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-sm text-gray-500">Released: Dec 20, 2007</span>
                                <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
                                    Download Now
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Featured Game -->
                <div class="bg-white rounded-lg shadow-sm overflow-hidden hover:shadow-md transition">
                    <div class="flex flex-col md:flex-row h-full">
                        <div class="md:w-2/5 relative">
                            <img src="https://readdy.ai/api/search-image?query=LocoRoco%20game%20for%20PSP%2C%20featuring%20colorful%20blob%20characters%2C%20vibrant%20playful%20environment%2C%20cheerful%20aesthetic%2C%20official%20Sony%20art%20style%2C%20high%20quality%20detailed%20image&width=400&height=500&seq=11&orientation=portrait" alt="LocoRoco" class="w-full h-full object-cover object-top">
                            <div class="absolute top-2 right-2 bg-primary text-xs font-bold px-2 py-1 rounded-full text-white">EDITOR'S PICK</div>
                        </div>
                        <div class="md:w-3/5 p-6 flex flex-col justify-between">
                            <div>
                                <div class="flex items-center mb-2">
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <i class="ri-star-fill text-yellow-400"></i>
                                    <span class="ml-2 text-sm font-medium">5.0</span>
                                </div>
                                <h3 class="text-2xl font-bold mb-3">LocoRoco</h3>
                                <p class="text-gray-600 mb-4">A charming platform game where players control colorful blob-like creatures called LocoRoco. Using the PSP's shoulder buttons to tilt the environment, players guide these joyful creatures through vibrant worlds filled with obstacles and enemies.</p>
                                <div class="flex flex-wrap gap-2 mb-4">
                                    <span class="text-xs font-medium px-2 py-1 bg-yellow-100 text-yellow-800 rounded-full">Platform</span>
                                    <span class="text-xs font-medium px-2 py-1 bg-pink-100 text-pink-800 rounded-full">Puzzle</span>
                                    <span class="text-xs font-medium px-2 py-1 bg-indigo-100 text-indigo-800 rounded-full">Casual</span>
                                </div>
                            </div>
                            <div class="flex items-center justify-between">
                                <span class="text-sm text-gray-500">Released: Jul 13, 2006</span>
                                <button class="bg-primary text-white px-4 py-2 !rounded-button whitespace-nowrap font-medium hover:bg-opacity-90 transition">
                                    Download Now
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Community Section -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-2xl md:text-3xl font-bold mb-8 text-gray-900">Community Hub</h2>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <!-- Forum Discussions -->
                <div class="bg-white rounded-lg shadow-sm p-6 border border-gray-100">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-xl font-semibold">Latest Discussions</h3>
                        <a href="#" class="text-primary text-sm font-medium hover:underline">View All</a>
                    </div>
                    
                    <div class="space-y-4">
                        <div class="border-b border-gray-100 pb-4">
                            <a href="#" class="font-medium text-gray-900 hover:text-primary">Best PSP emulators for Android in 2025?</a>
                            <div class="flex items-center mt-2 text-sm text-gray-500">
                                <span class="flex items-center">
                                    <i class="ri-user-line mr-1"></i> GameMaster42
                                </span>
                                <span class="mx-2">•</span>
                                <span>2 hours ago</span>
                                <span class="mx-2">•</span>
                                <span class="flex items-center">
                                    <i class="ri-message-2-line mr-1"></i> 24
                                </span>
                            </div>
                        </div>
                        
                        <div class="border-b border-gray-100 pb-4">
                            <a href="#" class="font-medium text-gray-900 hover:text-primary">How to fix UMD drive issues on PSP 1000?</a>
                            <div class="flex items-center mt-2 text-sm text-gray-500">
                                <span class="flex items-center">
                                    <i class="ri-user-line mr-1"></i> TechWizard
                                </span>
                                <span class="mx-2">•</span>
                                <span>5 hours ago</span>
                                <span class="mx-2">•</span>
                                <span class="flex items-center">
                                    <i class="ri-message-2-line mr-1"></i> 18
                                </span>
                            </div>
                        </div>
                        
                        <div class="border-b border-gray-100 pb-4">
                            <a href="#" class="font-medium text-gray-900 hover:text-primary">Top 10 hidden gems for PSP you might have missed</a>
                            <div class="flex items-center mt-2 text-sm text-gray-500">
                                <span class="flex items-center">
                                    <i class="ri-user-line mr-1"></i> RetroGamerX
                                </span>
                                <span class="mx-2">•</span>
                                <span>8 hours ago</span>
                                <span class="mx-2">•</span>
                                <span class="flex items-center">
                                    <i class="ri-message-2-line mr-1"></i> 42
                                </span>
                            </div>
                        </div>
                        
                        <div class="pb-2">
                            <a href="#" class="font-medium text-gray-900 hover:text-primary">Custom firmware guide for PSP 3000 (2025 update)</a>
                            <div class="flex items-center mt-2 text-sm text-gray-500">
                                <span class="flex items-center">
                                    <i class="ri-user-line mr-1"></i> ModdingPro
                                </span>
                                <span class="mx-2">•</span>
                                <span>12 hours ago</span>
                                <span class="mx-2">•</span>
                                <span class="flex items-center">
                                    <i class="ri-message-2-line mr-1"></i> 56
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- User Reviews -->
                <div class="bg-white rounded-lg shadow-sm p-6 border border-gray-100">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-xl font-semibold">Recent Reviews</h3>
                        <a href="#" class="text-primary text-sm font-medium hover:underline">View All</a>
                    </div>
                    
                    <div class="space-y-4">
                        <div class="border-b border-gray-100 pb-4">
                            <div class="flex items-center mb-2">
                                <span class="font-medium text-gray-900 mr-2">God of War: Ghost of Sparta</span>
                                <div class="flex">
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-half-fill text-yellow-400 text-sm"></i>
                                </div>
                            </div>
                            <p class="text-sm text-gray-600 mb-2">"Amazing graphics for the PSP. The combat is fluid and the story is engaging. One of the best action games on the platform."</p>
                            <div class="text-xs text-gray-500">
                                By RPGLover88 • May 19, 2025
                            </div>
                        </div>
                        
                        <div class="border-b border-gray-100 pb-4">
                            <div class="flex items-center mb-2">
                                <span class="font-medium text-gray-900 mr-2">Tactics Ogre: Let Us Cling Together</span>
                                <div class="flex">
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                </div>
                            </div>
                            <p class="text-sm text-gray-600 mb-2">"A masterpiece of tactical RPG. Deep character customization, branching storylines, and challenging gameplay. Worth every minute spent."</p>
                            <div class="text-xs text-gray-500">
                                By StrategyMaster • May 18, 2025
                            </div>
                        </div>
                        
                        <div class="pb-2">
                            <div class="flex items-center mb-2">
                                <span class="font-medium text-gray-900 mr-2">Lumines</span>
                                <div class="flex">
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-fill text-yellow-400 text-sm"></i>
                                    <i class="ri-star-line text-yellow-400 text-sm"></i>
                                </div>
                            </div>
                            <p class="text-sm text-gray-600 mb-2">"Addictive puzzle gameplay with fantastic music integration. The perfect pick-up-and-play game for short sessions. Visually stunning."</p>
                            <div class="text-xs text-gray-500">
                                By CasualGamer25 • May 17, 2025
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Screenshots Gallery -->
                <div class="bg-white rounded-lg shadow-sm p-6 border border-gray-100">
                    <div class="flex items-center justify-between mb-4">
                        <h3 class="text-xl font-semibold">Community Screenshots</h3>
                        <a href="#" class="text-primary text-sm font-medium hover:underline">View All</a>
                    </div>
                    
                    <div class="grid grid-cols-2 gap-3">
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=God%20of%20War%20PSP%20gameplay%20screenshot%2C%20action%20scene%20with%20Kratos%20fighting%20mythological%20creatures%2C%20detailed%20graphics%2C%20in-game%20UI%20elements%20visible&width=200&height=150&seq=12&orientation=landscape" alt="Screenshot 1" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=Final%20Fantasy%20PSP%20gameplay%20screenshot%2C%20turn-based%20battle%20scene%20with%20characters%20and%20monsters%2C%20menu%20interface%20visible%2C%20Japanese%20RPG%20style&width=200&height=150&seq=13&orientation=landscape" alt="Screenshot 2" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=Racing%20game%20PSP%20screenshot%2C%20sports%20car%20on%20racetrack%2C%20speedometer%20and%20lap%20information%20visible%2C%20high-speed%20motion%20blur%20effects&width=200&height=150&seq=14&orientation=landscape" alt="Screenshot 3" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=Monster%20Hunter%20PSP%20gameplay%20screenshot%2C%20hunter%20character%20fighting%20large%20dragon%20monster%2C%20action%20combat%20scene%2C%20weapon%20and%20health%20UI%20visible&width=200&height=150&seq=15&orientation=landscape" alt="Screenshot 4" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=Puzzle%20game%20PSP%20screenshot%2C%20colorful%20block-matching%20gameplay%2C%20score%20counter%20visible%2C%20vibrant%20visual%20effects&width=200&height=150&seq=16&orientation=landscape" alt="Screenshot 5" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                        
                        <div class="relative rounded overflow-hidden group">
                            <img src="https://readdy.ai/api/search-image?query=Strategy%20game%20PSP%20screenshot%2C%20tactical%20battlefield%20view%20with%20units%20and%20terrain%2C%20command%20interface%20visible%2C%20turn-based%20gameplay&width=200&height=150&seq=17&orientation=landscape" alt="Screenshot 6" class="w-full h-24 object-cover object-top">
                            <div class="absolute inset-0 bg-black bg-opacity-60 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                                <button class="text-white">
                                    <i class="ri-zoom-in-line text-xl"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-4 pt-4 border-t border-gray-100">
                        <h4 class="font-medium text-sm mb-2">Download Statistics</h4>
                        <div class="flex justify-between text-sm">
                            <div>
                                <div class="text-gray-900 font-medium">1.2M+</div>
                                <div class="text-gray-500">Downloads Today</div>
                            </div>
                            <div>
                                <div class="text-gray-900 font-medium">28.5M+</div>
                                <div class="text-gray-500">Downloads This Month</div>
                            </div>
                            <div>
                                <div class="text-gray-900 font-medium">342M+</div>
                                <div class="text-gray-500">Total Downloads</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-primary bg-opacity-5">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-2xl md:text-3xl font-bold mb-4 text-gray-900">Stay Updated with PSP Gaming News</h2>
                <p class="text-gray-600 mb-8">Subscribe to our newsletter to receive the latest updates on new game releases, community events, and exclusive content.</p>
                
                <div class="flex flex-col sm:flex-row gap-3 max-w-lg mx-auto">
                    <input type="email" placeholder="Enter your email address" class="flex-grow px-4 py-3 rounded-lg bg-white border border-gray-200 focus:outline-none focus:ring-2 focus:ring-primary">
                    <button class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap font-semibold hover:bg-opacity-90 transition">
                        Subscribe
                    </button>
                </div>
                
                <p class="text-xs text-gray-500 mt-4">By subscribing, you agree to our Privacy Policy and consent to receive updates from our company.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white pt-12 pb-6">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-8">
                <div>
                    <a href="#" class="text-2xl font-['Pacifico'] text-white mb-4 inline-block">logo</a>
                    <p class="text-gray-400 mb-4">Your ultimate source for PlayStation Portable games, community, and resources.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-facebook-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-twitter-x-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-instagram-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-gray-800 flex items-center justify-center hover:bg-primary transition">
                            <i class="ri-discord-fill"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">News</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Community</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">About Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Categories</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Action Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">RPG Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Racing Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Sports Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Strategy Games</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">All Categories</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-semibold mb-4">Support</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Help Center</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">FAQs</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Download Guides</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">PSP Hardware</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Report Issues</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Privacy Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="pt-8 border-t border-gray-800 text-center text-gray-400 text-sm">
                <div class="flex justify-center space-x-6 mb-4">
                    <i class="ri-visa-fill text-2xl"></i>
                    <i class="ri-mastercard-fill text-2xl"></i>
                    <i class="ri-paypal-fill text-2xl"></i>
                    <i class="ri-apple-fill text-2xl"></i>
                    <i class="ri-google-play-fill text-2xl"></i>
                </div>
                <p>&copy; 2025 PSP Games Portal. All rights reserved. PlayStation Portable is a trademark of Sony Interactive Entertainment Inc.</p>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Category tabs functionality
            const categoryTabs = document.querySelectorAll('.category-tab');
            categoryTabs.forEach(tab => {
                tab.addEventListener('click', function() {
                    categoryTabs.forEach(t => t.classList.remove('active'));
                    this.classList.add('active');
                });
            });
        });
        
        document.addEventListener('DOMContentLoaded', function() {
            // Custom checkbox functionality
            const customCheckboxes = document.querySelectorAll('.custom-checkbox');
            customCheckboxes.forEach(checkbox => {
                checkbox.addEventListener('click', function() {
                    this.classList.toggle('checked');
                });
            });
            
            // Custom radio functionality
            const customRadios = document.querySelectorAll('.custom-radio');
            customRadios.forEach(radio => {
                radio.addEventListener('click', function() {
                    const name = this.getAttribute('data-name');
                    document.querySelectorAll(`.custom-radio[data-name="${name}"]`).forEach(r => {
                        r.classList.remove('checked');
                    });
                    this.classList.add('checked');
                });
            });
            
            // Custom switch functionality
            const customSwitches = document.querySelectorAll('.custom-switch');
            customSwitches.forEach(switchEl => {
                switchEl.addEventListener('click', function() {
                    this.classList.toggle('checked');
                });
            });
        });
    </script>
</body>
</html>
