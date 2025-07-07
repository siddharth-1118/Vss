<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Datta Ganesh Home Products - Premium Spices & Agarbattis</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8f8f8;
        }
        
        .logo-text {
            font-family: 'Poppins', sans-serif;
            font-weight: 600;
            color: #2c3e50;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #f5f7fa 0%, #e4e7eb 100%);
        }
        
        .quantity-badge {
            background-color: #f59e0b;
        }
        
        .agarbatti-card {
            transition: all 0.3s ease;
        }
        
        .agarbatti-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }
        
        .footer-links a:hover {
            color: #f59e0b;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between">
                <div class="flex space-x-7">
                    <div>
                        <a href="#" class="flex items-center py-4 px-2">
                            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/21056523-4aaa-4294-9df5-441eb4ca3b51.png" alt="Datta Ganesh Home Products logo featuring a traditional Indian motif with saffron and green colors" class="h-10 w-10 rounded-full mr-2">
                            <span class="logo-text text-xl">Datta Ganesh Home Products</span>
                        </a>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-3">
                    <a href="#spices" class="py-4 px-2 text-gray-700 hover:text-orange-500 font-medium">Spices</a>
                    <a href="#agarbattis" class="py-4 px-2 text-gray-700 hover:text-orange-500 font-medium">Agarbattis</a>
                    <a href="#about" class="py-4 px-2 text-gray-700 hover:text-orange-500 font-medium">About Us</a>
                    <a href="#contact" class="py-4 px-2 text-gray-700 hover:text-orange-500 font-medium">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-gradient py-20 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-6">Authentic Indian Spices & Agarbattis</h1>
            <p class="text-xl text-gray-600 mb-8">Premium quality turmeric, mirchi, coriander powders and sandalwood agarbatti since 2005</p>
            <div class="flex justify-center space-x-4">
                <a href="#spices" class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-lg">Shop Spices</a>
                <a href="#agarbattis" class="bg-gray-800 hover:bg-gray-900 text-white font-bold py-3 px-6 rounded-lg">Shop Agarbattis</a>
            </div>
        </div>
    </div>

    <!-- Spices Section -->
    <section id="spices" class="py-16 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Premium Spice Powders</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Turmeric Powder -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="card-image h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/c2389d49-0ca1-4743-b0b4-cfdd6ef51361.png" alt="Fresh turmeric powder in a wooden bowl with turmeric roots in background, golden yellow color" class="w-full h-full object-cover"/>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Turmeric Powder</h3>
                        <p class="text-gray-600 mb-4">Pure, organic turmeric powder with rich golden color and aromatic flavor.</p>
                        
                        <div class="space-y-2">
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">50 grams</span>
                                <span class="font-semibold">₹50</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">100 grams</span>
                                <span class="font-semibold">₹90</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">200 grams</span>
                                <span class="font-semibold">₹160</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">500 grams</span>
                                <span class="font-semibold">₹350</span>
                            </div>
                        </div>
                        
                        <button class="mt-4 w-full bg-orange-500 hover:bg-orange-600 text-white py-2 rounded-lg">Add to Cart</button>
                    </div>
                </div>
                
                <!-- Mirchi Powder -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="card-image h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f97e695e-9913-4593-a801-fd2cb8d8168d.png" alt="Bright red chili powder in a brass bowl with whole dried red chilies around it" class="w-full h-full object-cover"/>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Mirchi Powder</h3>
                        <p class="text-gray-600 mb-4">Premium red chili powder with perfect balance of heat and flavor.</p>
                        
                        <div class="space-y-2">
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">50 grams</span>
                                <span class="font-semibold">₹40</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">100 grams</span>
                                <span class="font-semibold">₹75</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">200 grams</span>
                                <span class="font-semibold">₹140</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">500 grams</span>
                                <span class="font-semibold">₹320</span>
                            </div>
                        </div>
                        
                        <button class="mt-4 w-full bg-orange-500 hover:bg-orange-600 text-white py-2 rounded-lg">Add to Cart</button>
                    </div>
                </div>
                
                <!-- Coriander Powder -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="card-image h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/28a7bf73-a176-4524-8776-d30dfd13febc.png" alt="Freshly ground coriander powder in a mortar with coriander seeds and leaves" class="w-full h-full object-cover"/>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Coriander Powder</h3>
                        <p class="text-gray-600 mb-4">Aromatic coriander powder for authentic flavor in your dishes.</p>
                        
                        <div class="space-y-2">
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">50 grams</span>
                                <span class="font-semibold">₹45</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">100 grams</span>
                                <span class="font-semibold">₹80</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">200 grams</span>
                                <span class="font-semibold">₹150</span>
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-gray-700">500 grams</span>
                                <span class="font-semibold">₹340</span>
                            </div>
                        </div>
                        
                        <button class="mt-4 w-full bg-orange-500 hover:bg-orange-600 text-white py-2 rounded-lg">Add to Cart</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Agarbattis Section -->
    <section id="agarbattis" class="py-16 bg-gray-50">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Sandalwood Agarbatti</h2>
            
            <div class="flex justify-center">
                <div class="agarbatti-card bg-white rounded-lg shadow-md overflow-hidden">
                    <div class="card-image h-48 overflow-hidden">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/65704596-5ed6-4547-8f2c-65f41728f1ee.png" alt="Premium Sandalwood agarbatti sticks with traditional packaging" class="w-full h-full object-cover"/>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Sandalwood Agarbatti</h3>
                        <p class="text-gray-600 mb-4">Pure sandalwood fragrance for daily worship and rituals.</p>
                        <div class="grid grid-cols-2 gap-4 mb-4">
                            <div>
                                <span class="font-bold text-lg">Small Pack</span>
                                <span class="block bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm font-semibold">₹40</span>
                            </div>
                            <div>
                                <span class="font-bold text-lg">Large Pack</span>
                                <span class="block bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm font-semibold">₹50</span>
                            </div>
                        </div>
                        <button class="w-full bg-gray-800 hover:bg-gray-900 text-white py-2 rounded-lg">Add to Cart</button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="md:flex items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/473acbe9-fd69-4b4d-b194-84260e5f00da.png" alt="Datta Ganesh Home Products owner packaging spices in traditional Indian store setting" class="rounded-lg shadow-lg w-full"/>
                </div>
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-800 mb-6">About Datta Ganesh Home Products</h2>
                    <p class="text-gray-600 mb-4">
                        Founded in 2005, Datta Ganesh Home Products has been providing premium quality spices and agarbattis to households across anantapur disrict. We take pride in sourcing the finest ingredients and processing them with traditional methods to preserve their authentic flavors and aromas.
                    </p>
                    <p class="text-gray-600 mb-4">
                        Our turmeric, mirchi, and coriander powders are freshly ground in small batches to ensure maximum freshness and potency. The agarbattis are hand-rolled using age-old techniques passed down through generations.
                    </p>
                    <p class="text-gray-600">
                        We believe in providing pure, unadulterated products that bring health and happiness to your home.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-50">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Contact Us</h2>
            
            <div class="md:flex">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4">Get in Touch</h3>
                    <p class="text-gray-600 mb-6">Have questions about our products or want to place a bulk order? Reach out to us!</p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="text-gray-500 mr-3 mt-1">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                                </svg>
                            </span>
                            <div>
                                <h4 class="font-semibold text-gray-800">Address</h4>
                                <p class="text-gray-600">datta ganesh home products,kota bhasavanna katta street, Dharmavaram, andhrapradesh- 515671</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="text-gray-500 mr-3 mt-1">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                                </svg>
                            </span>
                            <div>
                                <h4 class="font-semibold text-gray-800">Phone</h4>
                                <p class="text-gray-600">+91 9866707883</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="text-gray-500 mr-3 mt-1">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                                </svg>
                            </span>
                            <div>
                                <h4 class="font-semibold text-gray-800">Email</h4>
                                <p class="text-gray-600">saisiddharthvooka@gmail.com.com</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2">
                    <form class="bg-white p-6 rounded-lg shadow-lg">
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="name">Name</label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-orange-500" id="name" type="text" placeholder="Your Name">
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="email">Email</label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-orange-500" id="email" type="email" placeholder="Your Email">
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="phone">Phone</label>
                            <input class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-orange-500" id="phone" type="tel" placeholder="Your Phone Number">
                        </div>
                        <div class="mb-4">
                            <label class="block text-gray-700 text-sm font-bold mb-2" for="message">Message</label>
                            <textarea class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-orange-500" id="message" rows="4" placeholder="Your Message"></textarea>
                        </div>
                        <button class="w-full bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-4 rounded-md focus:outline-none focus:ring-2 focus:ring-orange-500 focus:ring-offset-2" type="button">
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-6xl mx-auto px-4">
            <div class="md:flex md:justify-between">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/dcf0cac2-cb8a-4c90-bfcb-2c619c634511.png" alt="Datta Ganesh Home Products small logo" class="h-10 w-10 rounded-full mr-3">
                        <span class="text-xl font-semibold">Datta Ganesh Home Products</span>
                    </div>
                    <p class="mt-4 text-gray-300">Making homes happier with authentic Indian spices and fragrances since 1995.</p>
                </div>
                
                <div class="grid grid-cols-2 md:grid-c
