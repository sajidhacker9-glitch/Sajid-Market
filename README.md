<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sajid's Marketplace</title>
    <!-- SEO Meta Tags -->
    <meta name="description" content="Sajid's Marketplace offers daily fresh fruits and professional video, photo, and graphic design services. We provide high-quality mangoes, grapes, oranges, and editing services in Pakistan.">
    <meta name="keywords" content="Sajid's Marketplace, fresh fruits, fruit delivery, online marketplace, video editing, photo editing, graphic design, Pakistan, mangoes, grapes, oranges, freelance services, professional services">

    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🍏</text></svg>">
    
    <!-- Google Fonts & Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- AOS CSS for Animations -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <!-- Swiper CSS for Testimonial Slider -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
    <!-- Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_GA_TRACKING_ID"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        gtag('config', 'YOUR_GA_TRACKING_ID');
    </script>
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            transition: background-color 0.3s ease;
        }
        .dark body {
            background-color: #1a202c;
            color: #e2e8f0;
        }
        .dark .bg-white { background-color: #2d3748; color: #e2e8f0; }
        .dark .bg-gray-50 { background-color: #4a5568; }
        .dark .bg-gray-200 { background-color: #4a5568; }
        .dark .text-gray-800 { color: #e2e8f0; }
        .dark .text-gray-900 { color: #e2e8f0; }
        .dark .text-gray-600 { color: #a0aec0; }
        .dark .shadow-lg { box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.5), 0 4px 6px -2px rgba(0, 0, 0, 0.2); }
        .dark .border-gray-200 { border-color: #4a5568; }
        .dark .whatsapp-button { box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1), 0 1px 3px rgba(0, 0, 0, 0.08); }
        .dark .product-card, .dark .service-card, .dark .testimonial-card, .dark .faq-accordion-item {
            background-color: #2d3748;
        }
        .dark .faq-accordion-header { border-bottom: 1px solid #4a5568; }
        .hero-bg {
            background-image: url('https://placehold.co/1920x1080/4299e1/ffffff?text=Fresh+Fruits+%2B+Creative+Services');
            background-size: cover;
            background-position: center;
        }
        .faq-accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }
        .faq-accordion-content.open {
            max-height: 200px; /* Adjust as needed */
        }
        /* Style for the pricing table */
        .pricing-table th, .pricing-table td {
            padding: 1rem;
            text-align: left;
            border-bottom: 1px solid #e5e7eb;
        }
        .dark .pricing-table th, .dark .pricing-table td {
            border-bottom: 1px solid #4a5568;
        }
        .pricing-table th {
            background-color: #f9fafb;
            font-weight: 600;
        }
        .dark .pricing-table th {
            background-color: #4a5568;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Header -->
    <header class="sticky top-0 z-50 bg-white shadow-md rounded-b-lg p-4 transition-all duration-300">
        <div class="container mx-auto flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-gray-900 flex items-center">
                <img src="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🍏</text></svg>" alt="Logo" class="h-8 w-8 mr-2">
                Sajid's Marketplace
            </a>
            <!-- Desktop Navigation -->
            <nav class="hidden md:flex space-x-6 items-center">
                <a href="#home" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="home">Home</a>
                <a href="#fruits" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="fruits">Fruits</a>
                <a href="#services" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="services">Services</a>
                <a href="#blog" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="blog">Blog</a>
                <a href="#reviews" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="reviews">Reviews</a>
                <a href="#faq" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="faq">FAQ</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600 font-medium transition-colors" data-lang="contact">Contact</a>
                <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="text-gray-600 hover:text-pink-500 font-medium transition-colors" aria-label="Instagram Profile">
                    <i class="fab fa-instagram text-2xl"></i>
                </a>
                <button id="cart-button" class="text-blue-600 hover:text-blue-700 font-bold py-2 px-4 rounded-full border-2 border-blue-600 hover:border-blue-700 transition-colors" data-lang="cart">Cart (<span id="cart-count">0</span>)</button>
                <button id="dark-mode-toggle" class="p-2 rounded-full bg-gray-100 hover:bg-gray-200 transition-colors">
                    <i class="fas fa-moon text-gray-800"></i>
                </button>
                <button id="lang-toggle" class="p-2 rounded-full bg-gray-100 hover:bg-gray-200 transition-colors text-sm font-semibold text-gray-800">
                    UR
                </button>
            </nav>
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-600 focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <!-- Mobile Navigation -->
        <div id="mobile-menu" class="hidden md:hidden mt-4 text-center">
            <a href="#home" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="home">Home</a>
            <a href="#fruits" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="fruits">Fruits</a>
            <a href="#services" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="services">Services</a>
            <a href="#blog" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="blog">Blog</a>
            <a href="#reviews" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="reviews">Reviews</a>
            <a href="#faq" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="faq">FAQ</a>
            <a href="#contact" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" data-lang="contact">Contact</a>
            <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="block py-2 text-gray-600 hover:bg-gray-100 transition-colors" aria-label="Instagram Profile">Instagram</a>
            <button id="mobile-cart-button" class="w-full mt-4 text-blue-600 hover:text-blue-700 font-bold py-2 px-4 rounded-full border-2 border-blue-600 hover:border-blue-700 transition-colors" data-lang="cart">Cart (<span id="mobile-cart-count">0</span>)</button>
            <button id="mobile-dark-mode-toggle" class="mt-4 p-2 rounded-full bg-gray-100 hover:bg-gray-200 transition-colors">
                <i class="fas fa-moon text-gray-800"></i>
            </button>
            <button id="mobile-lang-toggle" class="mt-2 p-2 rounded-full bg-gray-100 hover:bg-gray-200 transition-colors text-sm font-semibold text-gray-800">
                UR
            </button>
        </div>
    </header>

    <main class="container mx-auto p-4 sm:p-8">

        <!-- Hero Section -->
        <section id="home" class="hero-bg relative text-white rounded-xl shadow-lg h-[500px] flex items-center justify-center p-6 mb-12" data-aos="fade-up">
            <div class="absolute inset-0 bg-black bg-opacity-50 rounded-xl"></div>
            <div class="relative text-center max-w-3xl">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold mb-4 animate-fade-in" data-lang="hero-headline">Fresh Fruits & Professional Editing</h1>
                <p class="text-lg sm:text-xl lg:text-2xl mb-8 font-light animate-fade-in-up" data-lang="hero-subheadline">Your one-stop shop for premium quality produce and top-notch digital creativity. Quality and speed, every time.</p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4 justify-center">
                    <a href="#fruits" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-transform transform hover:scale-105 animate-bounce-in" data-lang="shop-fruits-btn">Shop Fruits</a>
                    <a href="#services" class="bg-white hover:bg-gray-200 text-blue-600 font-bold py-3 px-8 rounded-full shadow-lg transition-transform transform hover:scale-105 animate-bounce-in" data-lang="get-editing-btn">Get Editing Services</a>
                </div>
            </div>
        </section>

        <!-- Products Section (Fruits) -->
        <section id="fruits" class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up" data-aos-delay="100">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="fruits-headline">Our Fresh Fruits</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
                <!-- Product Card 1: Mangoes -->
                <div class="product-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105" data-product-id="mangoes" data-name="White Chaunsa Mango" data-price="270">
                    <img src="https://placehold.co/400x300/FACC15/ffffff?text=Mangoes" alt="White Chaunsa Mango" class="w-full h-48 object-cover rounded-md mb-4" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                    <h3 class="text-2xl font-semibold mb-2" data-lang="mangoes">White Chaunsa Mango</h3>
                    <p class="text-lg text-gray-600 mb-4" data-lang="price">Rs. 270/kg</p>
                    <button class="add-to-cart-btn bg-blue-600 text-white font-bold py-2 px-6 rounded-full hover:bg-blue-700 transition-colors" data-lang="add-to-cart">Add to Cart</button>
                </div>
                <!-- Product Card 2: Grapes -->
                <div class="product-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105" data-product-id="grapes" data-name="Grapes" data-price="350">
                    <img src="https://placehold.co/400x300/4CAF50/ffffff?text=Grapes" alt="Grapes" class="w-full h-48 object-cover rounded-md mb-4" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                    <h3 class="text-2xl font-semibold mb-2" data-lang="grapes">Grapes (Green/Black)</h3>
                    <p class="text-lg text-gray-600 mb-4" data-lang="price">Rs. 350/kg</p>
                    <button class="add-to-cart-btn bg-blue-600 text-white font-bold py-2 px-6 rounded-full hover:bg-blue-700 transition-colors" data-lang="add-to-cart">Add to Cart</button>
                </div>
                 <!-- Product Card 3: Oranges -->
                 <div class="product-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105" data-product-id="oranges" data-name="Oranges" data-price="250">
                    <img src="https://placehold.co/400x300/FFB74D/ffffff?text=Oranges" alt="Oranges" class="w-full h-48 object-cover rounded-md mb-4" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                    <h3 class="text-2xl font-semibold mb-2" data-lang="oranges">Kinnow Orange</h3>
                    <p class="text-lg text-gray-600 mb-4" data-lang="price">Rs. 250/kg</p>
                    <button class="add-to-cart-btn bg-blue-600 text-white font-bold py-2 px-6 rounded-full hover:bg-blue-700 transition-colors" data-lang="add-to-cart">Add to Cart</button>
                </div>
                <!-- Product Card 4: Peaches -->
                <div class="product-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105" data-product-id="peaches" data-name="Peaches" data-price="310">
                    <img src="https://placehold.co/400x300/FF9966/ffffff?text=Peaches" alt="Peaches" class="w-full h-48 object-cover rounded-md mb-4" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                    <h3 class="text-2xl font-semibold mb-2" data-lang="peaches">Peach</h3>
                    <p class="text-lg text-gray-600 mb-4" data-lang="price">Rs. 300-320/kg</p>
                    <button class="add-to-cart-btn bg-blue-600 text-white font-bold py-2 px-6 rounded-full hover:bg-blue-700 transition-colors" data-lang="add-to-cart">Add to Cart</button>
                </div>
            </div>
        </section>

        <!-- Price List Table Section -->
        <section id="price-list" class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="price-list-headline">Current Fruit Price List</h2>
            <div class="overflow-x-auto">
                <table class="w-full pricing-table rounded-xl">
                    <thead>
                        <tr>
                            <th class="rounded-tl-lg" data-lang="table-header-fruit">Fruit</th>
                            <th data-lang="table-header-price">Price (per kg)</th>
                            <th class="rounded-tr-lg" data-lang="table-header-availability">Availability</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td data-lang="mangoes">White Chaunsa Mango</td>
                            <td>Rs. 270</td>
                            <td class="text-green-500 font-semibold" data-lang="available">Available</td>
                        </tr>
                        <tr>
                            <td data-lang="grapes">Grapes (Green/Black)</td>
                            <td>Rs. 350</td>
                            <td class="text-green-500 font-semibold" data-lang="available">Available</td>
                        </tr>
                        <tr>
                            <td data-lang="oranges">Kinnow Orange</td>
                            <td>Rs. 250</td>
                            <td class="text-yellow-500 font-semibold" data-lang="limited">Limited</td>
                        </tr>
                        <tr>
                            <td data-lang="peaches">Peach</td>
                            <td>Rs. 300-320</td>
                            <td class="text-green-500 font-semibold" data-lang="available">Available</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <!-- Services Section with Pricing Cards -->
        <section id="services" class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up" data-aos-delay="200">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="services-headline">Professional Editing Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Service Card 1: Video Editing -->
                <div class="service-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105">
                    <i class="fas fa-video text-5xl text-blue-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2" data-lang="video-editing">Pro Video Editing</h3>
                    <p class="text-gray-600 mb-4" data-lang="video-editing-desc">Transform your raw footage into cinematic masterpieces for social media, YouTube, and more.</p>
                    <p class="text-xl font-bold text-gray-900" data-lang="video-editing-price">Pricing starts at Rs. 2000</p>
                </div>
                <!-- Service Card 2: Graphic Design -->
                <div class="service-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105">
                    <i class="fas fa-paint-brush text-5xl text-blue-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2" data-lang="graphic-design">Logo & Graphic Design</h3>
                    <p class="text-gray-600 mb-4" data-lang="graphic-design-desc">Create a strong brand identity with custom logos, flyers, banners, and social media graphics.</p>
                    <p class="text-xl font-bold text-gray-900" data-lang="graphic-design-price">Pricing starts at Rs. 1500</p>
                </div>
                <!-- Service Card 3: Photo Editing -->
                <div class="service-card bg-gray-50 rounded-xl shadow-lg p-6 text-center transition-transform transform hover:scale-105">
                    <i class="fas fa-image text-5xl text-blue-600 mb-4"></i>
                    <h3 class="text-2xl font-semibold mb-2" data-lang="photo-editing">Image Editing</h3>
                    <p class="text-gray-600 mb-4" data-lang="photo-editing-desc">Professional retouching, color correction, and photo manipulation to make your images stand out.</p>
                    <p class="text-xl font-bold text-gray-900" data-lang="photo-editing-price">Pricing starts at Rs. 500</p>
                </div>
            </div>
        </section>
        
        <!-- Cart Modal -->
        <div id="cart-modal" class="fixed inset-0 bg-gray-900 bg-opacity-75 z-[100] flex justify-center items-center hidden">
            <div class="bg-white p-6 rounded-xl shadow-lg w-full max-w-lg overflow-y-auto max-h-[80vh]">
                <div class="flex justify-between items-center mb-4">
                    <h3 class="text-2xl font-bold text-gray-900" data-lang="shopping-cart">Shopping Cart</h3>
                    <button id="close-cart-modal" class="text-gray-500 hover:text-gray-800 text-2xl">&times;</button>
                </div>
                <div id="cart-items-container" class="space-y-4">
                    <!-- Cart items will be rendered here by JS -->
                </div>
                <div class="mt-6 pt-4 border-t border-gray-200">
                    <div class="flex justify-between items-center text-lg font-bold">
                        <span data-lang="total">Total:</span>
                        <span id="cart-total">Rs. 0</span>
                    </div>
                    <button id="checkout-button" class="w-full mt-4 bg-green-500 text-white font-bold py-2 px-4 rounded-full hover:bg-green-600 transition-colors" data-lang="checkout">Checkout</button>
                </div>
            </div>
        </div>
        
        <!-- Checkout Modal -->
        <div id="checkout-modal" class="fixed inset-0 bg-gray-900 bg-opacity-75 z-[101] flex justify-center items-center hidden">
            <div class="bg-white p-8 rounded-xl shadow-lg w-full max-w-md">
                <div class="flex justify-between items-center mb-4">
                    <h3 class="text-2xl font-bold text-gray-900" data-lang="checkout-form">Checkout</h3>
                    <button id="close-checkout-modal" class="text-gray-500 hover:text-gray-800 text-2xl">&times;</button>
                </div>
                <form id="checkout-form">
                    <div class="mb-4">
                        <label for="name" class="block text-gray-700 font-medium mb-1" data-lang="full-name">Full Name</label>
                        <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required>
                    </div>
                    <div class="mb-4">
                        <label for="address" class="block text-gray-700 font-medium mb-1" data-lang="delivery-address">Delivery Address</label>
                        <input type="text" id="address" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required>
                    </div>
                    <div class="mb-4">
                        <label for="phone" class="block text-gray-700 font-medium mb-1" data-lang="phone-number">Phone Number</label>
                        <input type="tel" id="phone" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required>
                    </div>
                    <button type="submit" class="w-full bg-blue-600 text-white font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors" data-lang="confirm-order">Confirm Order</button>
                </form>
            </div>
        </div>

        <!-- Discount Popup (Hidden by default) -->
        <div id="discount-popup" class="fixed inset-0 bg-gray-900 bg-opacity-75 z-[102] flex justify-center items-center hidden">
            <div class="bg-blue-600 text-white rounded-xl shadow-lg p-8 w-full max-w-sm text-center animate-pulse">
                <button id="close-popup" class="absolute top-2 right-2 text-white text-2xl">&times;</button>
                <h3 class="text-3xl font-bold mb-2" data-lang="popup-headline">10% OFF Your First Order!</h3>
                <p class="mb-4" data-lang="popup-subheadline">Use code: FIRSTORDER10</p>
                <a href="#fruits" class="bg-white text-blue-600 font-bold py-2 px-6 rounded-full hover:bg-gray-200 transition-colors" data-lang="shop-now">Shop Now</a>
            </div>
        </div>

        <!-- Video Section -->
        <section id="blog" class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up" data-aos-delay="300">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="blog-headline">Blog & Videos</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-2xl font-semibold mb-4 text-center" data-lang="promo-video-title">🍹 Watch Our Mango Promo Video</h3>
                    <!-- Note: This video URL is a placeholder. You should replace it with your own MP4 file hosted in a repository for production. -->
                    <video controls muted class="mx-auto rounded-2xl shadow-lg w-full max-w-3xl">
                        <source src="https://assets.mixkit.co/videos/preview/mixkit-healthy-food-and-fruits-on-the-table-5484-large.mp4" type="video/mp4">
                        Your browser does not support video playback.
                    </video>
                    <p class="mt-4 text-gray-600 text-center" data-lang="promo-video-desc">Enjoy fresh mangoes directly from our farms to your home!</p>
                </div>
                 <!-- Blog Post Cards -->
                <div class="mt-12 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                    <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden transition-transform transform hover:scale-105">
                        <img src="https://placehold.co/400x300/FACC15/ffffff?text=Mango+Article" alt="Mangoes" class="w-full h-48 object-cover" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                        <div class="p-4">
                            <h4 class="text-xl font-bold" data-lang="blog-title1">5 Benefits of Eating Mangoes Daily</h4>
                            <p class="text-gray-600 text-sm mt-2" data-lang="blog-desc1">Mangoes are not just delicious; they are packed with vitamins and minerals that boost your health. Learn more here!</p>
                            <a href="#" class="mt-4 inline-block text-blue-600 hover:underline" data-lang="read-more">Read More &rarr;</a>
                        </div>
                    </div>
                    <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden transition-transform transform hover:scale-105">
                        <img src="https://placehold.co/400x300/4CAF50/ffffff?text=Editing+Article" alt="Video Editing" class="w-full h-48 object-cover" onerror="this.src='https://placehold.co/400x300/CCCCCC/000000?text=Image+Unavailable'">
                        <div class="p-4">
                            <h4 class="text-xl font-bold" data-lang="blog-title2">Why Professional Editing is Important</h4>
                            <p class="text-gray-600 text-sm mt-2" data-lang="blog-desc2">In today's digital world, a professional image can make or break your brand. Discover why expert editing is a must.</p>
                            <a href="#" class="mt-4 inline-block text-blue-600 hover:underline" data-lang="read-more">Read More &rarr;</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Newsletter Section -->
        <section class="bg-blue-600 text-white rounded-xl shadow-lg p-6 sm:p-8 mb-12 text-center" data-aos="fade-up">
            <h2 class="text-3xl sm:text-4xl font-extrabold" data-lang="newsletter-headline">Get Exclusive Discounts & Offers!</h2>
            <p class="mt-2 text-lg" data-lang="newsletter-desc">Subscribe to our newsletter for the latest deals and updates.</p>
            <form action="https://google.com" method="post" target="_blank" class="mt-6 flex flex-col sm:flex-row items-center justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <input type="email" placeholder="Enter your email" required class="w-full sm:w-auto px-4 py-2 rounded-full text-gray-900 border-2 border-transparent focus:outline-none focus:border-white transition-colors">
                <button type="submit" class="bg-white text-blue-600 font-bold py-2 px-6 rounded-full hover:bg-gray-200 transition-colors" data-lang="subscribe-btn">Subscribe</button>
            </form>
        </section>

        <!-- Customer Testimonials Section -->
        <section id="reviews" class="bg-gray-200 rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up" data-aos-delay="400">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="testimonials-headline">What Our Customers Say</h2>
            <!-- Slider main container -->
            <div class="swiper">
                <div class="swiper-wrapper">
                    <!-- Slides -->
                    <div class="swiper-slide testimonial-card bg-white rounded-lg p-6 shadow-md text-center hover:shadow-xl transition-shadow">
                        <div class="flex items-center justify-center mb-2">
                            <div class="w-16 h-16 rounded-full overflow-hidden bg-gray-200 flex items-center justify-center">
                                <img src="https://placehold.co/64x64/333/fff?text=SK" alt="Customer Profile" class="rounded-full w-full h-full object-cover" onerror="this.src='https://placehold.co/64x64/CCCCCC/000000?text=SK'">
                            </div>
                        </div>
                        <div class="flex justify-center text-yellow-400 mb-2">
                            <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                        </div>
                        <p class="text-lg text-gray-700 italic mb-4" data-lang="review-1">"The fruits were incredibly fresh and the delivery was so fast! A game-changer for my weekly shopping."</p>
                        <p class="text-sm font-semibold text-gray-600">- Sarah K.</p>
                    </div>
                    <div class="swiper-slide testimonial-card bg-white rounded-lg p-6 shadow-md text-center hover:shadow-xl transition-shadow">
                        <div class="flex items-center justify-center mb-2">
                            <div class="w-16 h-16 rounded-full overflow-hidden bg-gray-200 flex items-center justify-center">
                                <img src="https://placehold.co/64x64/444/fff?text=AR" alt="Customer Profile" class="rounded-full w-full h-full object-cover" onerror="this.src='https://placehold.co/64x64/CCCCCC/000000?text=AR'">
                            </div>
                        </div>
                        <div class="flex justify-center text-yellow-400 mb-2">
                            <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i>
                        </div>
                        <p class="text-lg text-gray-700 italic mb-4" data-lang="review-2">"Sajid's editing services are top-notch. He transformed my dull video clips into a professional and engaging video."</p>
                        <p class="text-sm font-semibold text-gray-600">- Ali R.</p>
                    </div>
                    <div class="swiper-slide testimonial-card bg-white rounded-lg p-6 shadow-md text-center hover:shadow-xl transition-shadow">
                        <div class="flex items-center justify-center mb-2">
                            <div class="w-16 h-16 rounded-full overflow-hidden bg-gray-200 flex items-center justify-center">
                                <img src="https://placehold.co/64x64/555/fff?text=ZA" alt="Customer Profile" class="rounded-full w-full h-full object-cover" onerror="this.src='https://placehold.co/64x64/CCCCCC/000000?text=ZA'">
                            </div>
                        </div>
                        <div class="flex justify-center text-yellow-400 mb-2">
                            <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="far fa-star"></i>
                        </div>
                        <p class="text-lg text-gray-700 italic mb-4" data-lang="review-3">"The team at Sajid's Marketplace delivered my bulk fruit order perfectly. The quality was outstanding."</p>
                        <p class="text-sm font-semibold text-gray-600">- Zoya A.</p>
                    </div>
                </div>
                 <div class="swiper-pagination"></div>
            </div>
        </section>

        <!-- FAQ Section -->
        <section id="faq" class="bg-white rounded-xl shadow-lg p-6 sm:p-8 mb-12" data-aos="fade-up" data-aos-delay="600">
            <h2 class="text-3xl font-bold text-gray-900 text-center mb-8" data-lang="faq-headline">Frequently Asked Questions</h2>
            <div class="max-w-3xl mx-auto space-y-4">
                <div class="faq-accordion-item border rounded-lg overflow-hidden border-gray-200">
                    <div class="faq-accordion-header py-4 px-6 flex justify-between items-center cursor-pointer">
                        <span class="text-lg font-semibold text-gray-800" data-lang="faq-q1">What are your delivery charges?</span>
                        <i class="fas fa-chevron-down text-gray-500 transform transition-transform duration-300"></i>
                    </div>
                    <div class="faq-accordion-content px-6 pb-4">
                        <p class="text-gray-700" data-lang="faq-a1">Delivery charges are based on your location. We offer free home delivery on all orders above Rs. 1000.</p>
                    </div>
                </div>
                <div class="faq-accordion-item border rounded-lg overflow-hidden border-gray-200">
                    <div class="faq-accordion-header py-4 px-6 flex justify-between items-center cursor-pointer">
                        <span class="text-lg font-semibold text-gray-800" data-lang="faq-q2">How long does editing take?</span>
                        <i class="fas fa-chevron-down text-gray-500 transform transition-transform duration-300"></i>
                    </div>
                    <div class="faq-accordion-content px-6 pb-4">
                        <p class="text-gray-700" data-lang="faq-a2">Editing time varies depending on the project's complexity. We'll provide an estimated timeline when you contact us.</p>
                    </div>
                </div>
                <div class="faq-accordion-item border rounded-lg overflow-hidden border-gray-200">
                    <div class="faq-accordion-header py-4 px-6 flex justify-between items-center cursor-pointer">
                        <span class="text-lg font-semibold text-gray-800" data-lang="faq-q3">How do I pay for my order?</span>
                        <i class="fas fa-chevron-down text-gray-500 transform transition-transform duration-300"></i>
                    </div>
                    <div class="faq-accordion-content px-6 pb-4">
                        <p class="text-gray-700" data-lang="faq-a3">We currently accept Cash on Delivery (COD). We're working on adding more payment options in the future.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="mt-12 text-center bg-gray-900 text-white rounded-xl shadow-lg p-6 sm:p-8" data-aos="fade-up" data-aos-delay="800">
            <h2 class="text-3xl sm:text-4xl font-bold mb-4" data-lang="contact-headline">Get in Touch</h2>
            <p class="text-sm sm:text-base text-gray-400 mb-6" data-lang="contact-subheadline">Contact us for orders, inquiries, or custom project quotes!</p>
            <div class="flex justify-center space-x-6">
                <!-- Email -->
                <a href="mailto:tffaforextrade@gmail.com" target="_blank" class="text-4xl hover:text-blue-500 transition-colors duration-300" aria-label="Send an email">
                    <i class="fas fa-envelope"></i>
                </a>
                <!-- WhatsApp -->
                <a href="https://wa.me/923485231698?text=Hi%20Sajid!%20I'd%20like%20to%20place%20an%20order." target="_blank" class="text-4xl hover:text-green-500 transition-colors duration-300" aria-label="Chat on WhatsApp">
                    <i class="fab fa-whatsapp"></i>
                </a>
                <!-- Instagram -->
                <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="text-4xl hover:text-pink-500 transition-colors duration-300" aria-label="Visit Instagram Profile">
                    <i class="fab fa-instagram"></i>
                </a>
            </div>
            <p class="mt-8 text-lg sm:text-xl font-mono tracking-wide mb-4" data-lang="phone">Phone: 03485231698</p>
        </section>

    </main>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/923485231698?text=Hi%20Sajid!%20I'd%20like%20to%20place%20an%20order." target="_blank" class="whatsapp-button fixed bottom-6 right-6 z-50 bg-green-500 text-white rounded-full p-4 shadow-xl hover:bg-green-600 transition-transform transform hover:scale-110">
        <i class="fab fa-whatsapp text-2xl"></i>
    </a>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-8 mt-12 rounded-t-xl">
        <div class="container mx-auto px-4 sm:px-8 text-center">
            <div class="flex flex-col sm:flex-row justify-center sm:space-x-8 mb-4">
                <a href="#home" class="hover:text-white transition-colors" data-lang="home">Home</a>
                <a href="#fruits" class="hover:text-white transition-colors" data-lang="fruits">Fruits</a>
                <a href="#services" class="hover:text-white transition-colors" data-lang="services">Services</a>
                <a href="#contact" class="hover:text-white transition-colors" data-lang="contact">Contact</a>
            </div>
            <div class="flex justify-center space-x-4 mb-4">
                <a href="https://www.instagram.com/ffwithsajid" target="_blank" class="text-xl hover:text-white"><i class="fab fa-instagram"></i></a>
                <a href="https://wa.me/923485231698" target="_blank" class="text-xl hover:text-white"><i class="fab fa-whatsapp"></i></a>
                <a href="#" target="_blank" class="text-xl hover:text-white"><i class="fab fa-facebook"></i></a>
            </div>
            <p class="text-sm">&copy; <span id="current-year"></span> Sajid's Marketplace. <span data-lang="rights-reserved">All rights reserved.</span></p>
            <p class="text-xs mt-2 text-gray-500">User ID: <span id="user-id-display">N/A</span></p>
        </div>
    </footer>

    <!-- All JavaScript is bundled here for a single file app -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

    <script type="module">
        // Firebase imports
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, getDoc, setDoc, updateDoc, deleteDoc, onSnapshot, collection, addDoc, serverTimestamp, getDocs, query, where } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";
        import { setLogLevel } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Initialize AOS
        window.onload = function() {
            AOS.init({ duration: 800, once: true });
            new Swiper('.swiper', {
                loop: true,
                pagination: {
                    el: '.swiper-pagination',
                    clickable: true,
                },
                autoplay: {
                    delay: 5000,
                    disableOnInteraction: false,
                },
            });
        };

        // UI Elements
        const cartButton = document.getElementById('cart-button');
        const mobileCartButton = document.getElementById('mobile-cart-button');
        const cartModal = document.getElementById('cart-modal');
        const closeCartModalButton = document.getElementById('close-cart-modal');
        const checkoutButton = document.getElementById('checkout-button');
        const checkoutModal = document.getElementById('checkout-modal');
        const closeCheckoutModalButton = document.getElementById('close-checkout-modal');
        const checkoutForm = document.getElementById('checkout-form');
        const cartItemsContainer = document.getElementById('cart-items-container');
        const cartTotalDisplay = document.getElementById('cart-total');
        const cartCountDisplay = document.getElementById('cart-count');
        const mobileCartCountDisplay = document.getElementById('mobile-cart-count');
        const discountPopup = document.getElementById('discount-popup');
        const closePopupBtn = document.getElementById('close-popup');
        const userIdDisplay = document.getElementById('user-id-display');

        // Language & Dark Mode
        const darkModeToggle = document.getElementById('dark-mode-toggle');
        const mobileDarkModeToggle = document.getElementById('mobile-dark-mode-toggle');
        const langToggle = document.getElementById('lang-toggle');
        const mobileLangToggle = document.getElementById('mobile-lang-toggle');
        const translations = {
            'en': {
                'home': 'Home', 'fruits': 'Fruits', 'services': 'Services', 'blog': 'Blog', 'reviews': 'Reviews', 'faq': 'FAQ', 'contact': 'Contact', 'cart': 'Cart',
                'hero-headline': 'Fresh Fruits & Professional Editing', 'hero-subheadline': 'Your one-stop shop for premium quality produce and top-notch digital creativity. Quality and speed, every time.', 'shop-fruits-btn': 'Shop Fruits', 'get-editing-btn': 'Get Editing Services',
                'price-list-headline': 'Current Fruit Price List', 'table-header-fruit': 'Fruit', 'table-header-price': 'Price (per kg)', 'table-header-availability': 'Availability', 'available': 'Available', 'limited': 'Limited',
                'services-headline': 'Professional Editing Services',
                'video-editing': 'Pro Video Editing', 'video-editing-desc': 'Transform your raw footage into cinematic masterpieces for social media, YouTube, and more.', 'video-editing-price': 'Pricing starts at Rs. 2000',
                'graphic-design': 'Logo & Graphic Design', 'graphic-design-desc': 'Create a strong brand identity with custom logos, flyers, banners, and social media graphics.', 'graphic-design-price': 'Pricing starts at Rs. 1500',
                'photo-editing': 'Image Editing', 'photo-editing-desc': 'Professional retouching, color correction, and photo manipulation to make your images stand out.', 'photo-editing-price': 'Pricing starts at Rs. 500',
                'fruits-headline': 'Our Fresh Fruits',
                'mangoes': 'White Chaunsa Mango', 'grapes': 'Grapes (Green/Black)', 'oranges': 'Kinnow Orange', 'peaches': 'Peach', 'price': 'Rs. /kg', 'add-to-cart': 'Add to Cart',
                'shopping-cart': 'Shopping Cart', 'total': 'Total:', 'checkout': 'Checkout', 'checkout-form': 'Checkout',
                'full-name': 'Full Name', 'delivery-address': 'Delivery Address', 'phone-number': 'Phone Number', 'confirm-order': 'Confirm Order',
                'popup-headline': '10% OFF Your First Order!', 'popup-subheadline': 'Use code: FIRSTORDER10', 'shop-now': 'Shop Now',
                'blog-headline': 'Blog & Videos', 'promo-video-title': '🍹 Watch Our Mango Promo Video', 'promo-video-desc': 'Enjoy fresh mangoes directly from our farms to your home!', 'editing-demo-title': '🎬 Editing Demo',
                'blog-title1': '5 Benefits of Eating Mangoes Daily', 'blog-desc1': 'Mangoes are not just delicious; they are packed with vitamins and minerals that boost your health. Learn more here!',
                'blog-title2': 'Why Professional Editing is Important', 'blog-desc2': 'In today\'s digital world, a professional image can make or break your brand. Discover why expert editing is a must.', 'read-more': 'Read More &rarr;',
                'newsletter-headline': 'Get Exclusive Discounts & Offers!', 'newsletter-desc': 'Subscribe to our newsletter for the latest deals and updates.', 'subscribe-btn': 'Subscribe',
                'testimonials-headline': 'What Our Customers Say',
                'review-1': '"The fruits were incredibly fresh and the delivery was so fast! A game-changer for my weekly shopping."', 'review-2': '"Sajid\'s editing services are top-notch. He transformed my dull video clips into a professional and engaging video."', 'review-3': '"The team at Sajid\'s Marketplace delivered my bulk fruit order perfectly. The quality was outstanding."',
                'faq-headline': 'Frequently Asked Questions', 'faq-q1': 'What are your delivery charges?', 'faq-a1': 'Delivery charges are based on your location. We offer free home delivery on all orders above Rs. 1000.',
                'faq-q2': 'How long does editing take?', 'faq-a2': 'Editing time varies depending on the project\'s complexity. We\'ll provide an estimated timeline when you contact us.', 'faq-q3': 'How do I pay for my order?', 'faq-a3': 'We currently accept Cash on Delivery (COD). We\'re working on adding more payment options in the future.',
                'contact-headline': 'Get in Touch', 'contact-subheadline': 'Contact us for orders, inquiries, or custom project quotes!', 'phone': 'Phone:',
                'rights-reserved': 'All rights reserved.'
            },
            'ur': {
                'home': 'صفحہ اول', 'fruits': 'پھل', 'services': 'خدمات', 'blog': 'بلاگ', 'reviews': 'جائزے', 'faq': 'اکثر پوچھے گئے سوالات', 'contact': 'رابطہ کریں', 'cart': 'کارٹ',
                'hero-headline': 'تازہ پھل اور پروفیشنل ایڈیٹنگ', 'hero-subheadline': 'تازہ ترین معیاری پیداوار اور اعلیٰ درجے کی ڈیجیٹل تخلیقی صلاحیت کے لیے آپ کی ایک جگہ کی دکان۔ ہر وقت معیاری اور تیز۔', 'shop-fruits-btn': 'پھل خریدیں', 'get-editing-btn': 'ایڈیٹنگ کی خدمات حاصل کریں',
                'price-list-headline': 'پھلوں کی قیمت کی فہرست', 'table-header-fruit': 'پھل', 'table-header-price': 'قیمت (فی کلو)', 'table-header-availability': 'دستیابی', 'available': 'دستیاب', 'limited': 'محدود',
                'services-headline': 'پروفیشنل ایڈیٹنگ کی خدمات',
                'video-editing': 'پرو ویڈیو ایڈیٹنگ', 'video-editing-desc': 'اپنے خام فوٹیج کو سوشل میڈیا، یوٹیوب، اور مزید کے لیے سینما کے شاہکار میں تبدیل کریں۔', 'video-editing-price': 'قیمتیں 2000 روپے سے شروع ہوتی ہیں',
                'graphic-design': 'لوگو اور گرافک ڈیزائن', 'graphic-design-desc': 'کسٹم لوگو، فلائرز، بینرز، اور سوشل میڈیا گرافکس کے ساتھ ایک مضبوط برانڈ کی شناخت بنائیں۔', 'graphic-design-price': 'قیمتیں 1500 روپے سے شروع ہوتی ہیں',
                'photo-editing': 'تصویر ایڈیٹنگ', 'photo-editing-desc': 'آپ کی تصاویر کو نمایاں کرنے کے لیے پروفیشنل ری ٹچنگ، رنگ کی اصلاح، اور فوٹو مینیپولیشن۔', 'photo-editing-price': 'قیمتیں 500 روپے سے شروع ہوتی ہیں',
                'fruits-headline': 'ہمارے تازہ پھل',
                'mangoes': 'سفید چونسہ آم', 'grapes': 'انگور (سبز/سیاہ)', 'oranges': 'کینو مالٹا', 'peaches': 'آڑو', 'price': 'روپے/کلو', 'add-to-cart': 'کارٹ میں شامل کریں',
                'shopping-cart': 'شاپنگ کارٹ', 'total': 'کل:', 'checkout': 'آرڈر کریں', 'checkout-form': 'آرڈر فارم',
                'full-name': 'پورا نام', 'delivery-address': 'ترسیل کا پتہ', 'phone-number': 'فون نمبر', 'confirm-order': 'آرڈر کی تصدیق کریں',
                'popup-headline': 'اپنے پہلے آرڈر پر 10% رعایت!', 'popup-subheadline': 'کوڈ استعمال کریں: FIRSTORDER10', 'shop-now': 'ابھی خریدیں',
                'blog-headline': 'بلاگ اور ویڈیوز', 'promo-video-title': '🍹 ہماری آم پروموشنل ویڈیو دیکھیں', 'promo-video-desc': 'ہمارے فارموں سے براہ راست آپ کے گھر تک پہنچائے جانے والے تازہ آموں کا لطف اٹھائیں!', 'editing-demo-title': '🎬 ایڈیٹنگ ڈیمو',
                'blog-title1': 'روزانہ آم کھانے کے 5 فوائد', 'blog-desc1': 'آم نہ صرف لذیذ ہوتے ہیں بلکہ وٹامنز اور معدنیات سے بھی بھرپور ہوتے ہیں جو آپ کی صحت کو بہتر بناتے ہیں۔ یہاں مزید جانیں!',
                'blog-title2': 'پیشہ ورانہ ایڈیٹنگ کیوں اہم ہے', 'blog-desc2': 'آج کی ڈیجیٹل دنیا میں، ایک پیشہ ورانہ تصویر آپ کے برانڈ کو بنا یا بگاڑ سکتی ہے۔ دریافت کریں کہ ماہر ایڈیٹنگ کیوں ضروری ہے۔', 'read-more': 'مزید پڑھیں &rarr;',
                'newsletter-headline': 'خصوصی رعایتیں اور پیشکشیں حاصل کریں!', 'newsletter-desc': 'تازہ ترین سودوں اور اپ ڈیٹس کے لیے ہمارے نیوز لیٹر کو سبسکرائب کریں۔', 'subscribe-btn': 'سبسکرائب کریں',
                'testimonials-headline': 'ہمارے صارفین کیا کہتے ہیں',
                'review-1': '"پھل ناقابل یقین حد تک تازہ تھے اور ترسیل بہت تیز تھی! میری ہفتہ وار خریداری کے لیے ایک گیم چینجر۔"', 'review-2': '"ساجد کی ایڈیٹنگ کی خدمات اعلیٰ درجے کی ہیں۔ اس نے میرے سست ویڈیو کلپس کو ایک پروفیشنل اور دلکش ویڈیو میں تبدیل کر دیا۔"', 'review-3': '"The team at Sajid\'s Marketplace delivered my bulk fruit order perfectly. The quality was outstanding."',
                'faq-headline': 'اکثر پوچھے گئے سوالات', 'faq-q1': 'آپ کے ترسیل کے چارجز کیا ہیں؟', 'faq-a1': 'ترسیل کے چارجز آپ کے مقام پر منحصر ہیں۔ ہم 1000 روپے سے زیادہ کے تمام آرڈرز پر مفت ہوم ڈیلیوری کی پیشکش کرتے ہیں۔',
                'faq-q2': 'ایڈیٹنگ میں کتنا وقت لگتا ہے؟', 'faq-a2': 'ایڈیٹنگ کا وقت پروجیکٹ کی پیچیدگی پر منحصر ہوتا ہے۔ جب آپ اپنی مخصوص ضروریات کے ساتھ ہم سے رابطہ کریں گے تو ہم ایک تخمینہ شدہ ٹائم لائن فراہم کریں گے۔', 'faq-q3': 'میں اپنے آرڈر کی ادائیگی کیسے کروں؟', 'faq-a3': 'ہم فی الحال کیش آن ڈیلیوری (COD) قبول کرتے ہیں۔ ہم آپ کی سہولت کے لیے مستقبل میں مزید ادائیگی کے اختیارات شامل کرنے پر کام کر رہے ہیں۔',
                'contact-headline': 'رابطہ کریں', 'contact-subheadline': 'آرڈرز، پوچھ گچھ، یا کسٹم پروجیکٹ کے قیمتوں کے لیے ہم سے رابطہ کریں!', 'phone': 'فون:',
                'rights-reserved': 'تمام حقوق محفوظ ہیں'
            }
        };

        let currentLang = 'en';

        function updateContent() {
            document.querySelectorAll('[data-lang]').forEach(el => {
                const key = el.getAttribute('data-lang');
                if (translations[currentLang][key]) {
                    el.textContent = translations[currentLang][key];
                }
            });
            const priceElements = document.querySelectorAll('.product-card p[data-lang="price"]');
            priceElements.forEach(el => {
                const productCard = el.closest('.product-card');
                const price = productCard.getAttribute('data-price');
                const langPrice = currentLang === 'ur' ? 'روپے' : 'Rs.';
                el.textContent = `${langPrice}. ${price}/kg`;
            });
            langToggle.textContent = currentLang === 'en' ? 'UR' : 'EN';
            mobileLangToggle.textContent = currentLang === 'en' ? 'UR' : 'EN';
        }

        langToggle.addEventListener('click', () => {
            currentLang = currentLang === 'en' ? 'ur' : 'en';
            updateContent();
        });
        mobileLangToggle.addEventListener('click', () => {
            currentLang = currentLang === 'en' ? 'ur' : 'en';
            updateContent();
        });
        updateContent();

        // Dark Mode Toggle
        const body = document.body;
        const toggleDarkMode = () => {
            body.classList.toggle('dark');
            const isDarkMode = body.classList.contains('dark');
            darkModeToggle.querySelector('i').className = isDarkMode ? 'fas fa-sun text-yellow-500' : 'fas fa-moon text-gray-800';
            mobileDarkModeToggle.querySelector('i').className = isDarkMode ? 'fas fa-sun text-yellow-500' : 'fas fa-moon text-gray-800';
        };
        darkModeToggle.addEventListener('click', toggleDarkMode);
        mobileDarkModeToggle.addEventListener('click', toggleDarkMode);

        // Mobile Menu Toggle
        document.getElementById('mobile-menu-button').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // FAQ Accordion
        document.querySelectorAll('.faq-accordion-header').forEach(header => {
            header.addEventListener('click', () => {
                const content = header.nextElementSibling;
                const icon = header.querySelector('i');
                const isOpen = content.classList.contains('open');
                
                // Close all other accordions
                document.querySelectorAll('.faq-accordion-content.open').forEach(item => {
                    item.classList.remove('open');
                    item.previousElementSibling.querySelector('i').style.transform = 'rotate(0deg)';
                });

                // Open the clicked one
                if (!isOpen) {
                    content.classList.add('open');
                    icon.style.transform = 'rotate(180deg)';
                }
            });
        });

        // Discount Popup
        let discountShown = false;
        const showPopup = () => {
            if (!discountShown) {
                setTimeout(() => {
                    discountPopup.classList.remove('hidden');
                    discountShown = true;
                }, 3000);
            }
        };
        closePopupBtn.addEventListener('click', () => {
            discountPopup.classList.add('hidden');
        });
        window.addEventListener('scroll', showPopup);

        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
        
        // --- Firebase Firestore E-Commerce Logic ---
        setLogLevel('Debug');
        
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app-id';
        const firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : {};
        const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;

        let db, auth, userId = null;

        const initializeFirebase = async () => {
            try {
                const app = initializeApp(firebaseConfig);
                auth = getAuth(app);
                db = getFirestore(app);

                onAuthStateChanged(auth, async (user) => {
                    if (user) {
                        userId = user.uid;
                        userIdDisplay.textContent = userId;
                        // Start listening to the cart when authenticated
                        listenToCart();
                    } else {
                        try {
                            if (initialAuthToken) {
                                await signInWithCustomToken(auth, initialAuthToken);
                            } else {
                                await signInAnonymously(auth);
                            }
                        } catch (error) {
                            console.error("Firebase Auth Error:", error);
                        }
                    }
                });
            } catch (error) {
                console.error("Firebase Initialization Error:", error);
            }
        };

        const showMessage = (message, type = 'success') => {
            const popup = document.createElement('div');
            popup.className = `fixed bottom-8 left-1/2 -translate-x-1/2 px-6 py-3 rounded-lg text-white shadow-xl text-center z-[103] transition-all duration-300`;
            if (type === 'success') {
                popup.classList.add('bg-green-500');
            } else {
                popup.classList.add('bg-red-500');
            }
            popup.textContent = message;
            document.body.appendChild(popup);
            setTimeout(() => {
                popup.style.opacity = '0';
                popup.style.transform = 'translate(-50%, 20px)';
                setTimeout(() => popup.remove(), 300);
            }, 3000);
        };

        const listenToCart = () => {
            if (!db || !userId) { return; }
            const cartRef = collection(db, `artifacts/${appId}/users/${userId}/cart`);
            onSnapshot(cartRef, (snapshot) => {
                let cartItems = [];
                let cartTotal = 0;
                snapshot.forEach(doc => {
                    const item = doc.data();
                    cartItems.push({ id: doc.id, ...item });
                    cartTotal += item.price * item.quantity;
                });
                renderCart(cartItems, cartTotal);
            }, (error) => {
                console.error("Error listening to cart:", error);
                showMessage("Failed to load cart. Please try again.", "error");
            });
        };

        const renderCart = (items, total) => {
            cartItemsContainer.innerHTML = '';
            let totalItems = 0;
            if (items.length === 0) {
                cartItemsContainer.innerHTML = `<p class="text-center text-gray-500" data-lang="cart-empty">Your cart is empty.</p>`;
            } else {
                items.forEach(item => {
                    const itemElement = document.createElement('div');
                    itemElement.className = 'flex items-center justify-between p-4 bg-gray-100 rounded-lg shadow-sm';
                    itemElement.innerHTML = `
                        <div class="flex-1">
                            <h4 class="font-bold text-gray-900">${item.name}</h4>
                            <p class="text-gray-600">Rs. ${item.price} x ${item.quantity}</p>
                        </div>
                        <div class="flex items-center space-x-2">
                            <button class="update-quantity-btn bg-gray-300 text-gray-800 px-2 py-1 rounded-full text-lg" data-id="${item.id}" data-action="decrease">-</button>
                            <span class="font-semibold text-xl">${item.quantity}</span>
                            <button class="update-quantity-btn bg-gray-300 text-gray-800 px-2 py-1 rounded-full text-lg" data-id="${item.id}" data-action="increase">+</button>
                            <button class="remove-from-cart-btn text-red-500 hover:text-red-700 ml-4" data-id="${item.id}">
                                <i class="fas fa-trash-alt"></i>
                            </button>
                        </div>
                    `;
                    cartItemsContainer.appendChild(itemElement);
                    totalItems += item.quantity;
                });
            }
            cartTotalDisplay.textContent = `Rs. ${total}`;
            cartCountDisplay.textContent = totalItems;
            mobileCartCountDisplay.textContent = totalItems;

            document.querySelectorAll('.update-quantity-btn').forEach(button => {
                button.addEventListener('click', handleUpdateQuantity);
            });
            document.querySelectorAll('.remove-from-cart-btn').forEach(button => {
                button.addEventListener('click', handleRemoveFromCart);
            });
            updateContent();
        };

        const handleAddToCart = async (event) => {
            if (!userId) {
                showMessage("Please wait, initializing...", "error");
                return;
            }
            const productCard = event.target.closest('.product-card');
            const productId = productCard.getAttribute('data-product-id');
            const productName = productCard.getAttribute('data-name');
            const productPrice = parseFloat(productCard.getAttribute('data-price'));

            const itemRef = doc(db, `artifacts/${appId}/users/${userId}/cart`, productId);
            try {
                const docSnap = await getDoc(itemRef);
                if (docSnap.exists()) {
                    const currentQuantity = docSnap.data().quantity;
                    await updateDoc(itemRef, {
                        quantity: currentQuantity + 1
                    });
                } else {
                    await setDoc(itemRef, {
                        name: productName,
                        price: productPrice,
                        quantity: 1,
                        timestamp: serverTimestamp()
                    });
                }
                showMessage(`${productName} added to cart!`);
            } catch (error) {
                console.error("Error adding to cart:", error);
                showMessage("Failed to add to cart. Please try again.", "error");
            }
        };

        const handleUpdateQuantity = async (event) => {
            const button = event.target.closest('.update-quantity-btn');
            const itemId = button.getAttribute('data-id');
            const action = button.getAttribute('data-action');
            const itemRef = doc(db, `artifacts/${appId}/users/${userId}/cart`, itemId);
            try {
                const docSnap = await getDoc(itemRef);
                if (docSnap.exists()) {
                    let currentQuantity = docSnap.data().quantity;
                    if (action === 'increase') {
                        currentQuantity += 1;
                    } else if (action === 'decrease' && currentQuantity > 1) {
                        currentQuantity -= 1;
                    } else {
                        return;
                    }
                    await updateDoc(itemRef, { quantity: currentQuantity });
                }
            } catch (error) {
                console.error("Error updating quantity:", error);
            }
        };

        const handleRemoveFromCart = async (event) => {
            const button = event.target.closest('.remove-from-cart-btn');
            const itemId = button.getAttribute('data-id');
            const itemRef = doc(db, `artifacts/${appId}/users/${userId}/cart`, itemId);
            try {
                await deleteDoc(itemRef);
                showMessage("Item removed from cart.");
            } catch (error) {
                console.error("Error removing item:", error);
                showMessage("Failed to remove item. Please try again.", "error");
            }
        };

        // Event listeners
        document.querySelectorAll('.add-to-cart-btn').forEach(button => {
            button.addEventListener('click', handleAddToCart);
        });

        cartButton.addEventListener('click', () => cartModal.classList.remove('hidden'));
        mobileCartButton.addEventListener('click', () => cartModal.classList.remove('hidden'));
        closeCartModalButton.addEventListener('click', () => cartModal.classList.add('hidden'));

        checkoutButton.addEventListener('click', () => {
            cartModal.classList.add('hidden');
            checkoutModal.classList.remove('hidden');
        });
        closeCheckoutModalButton.addEventListener('click', () => checkoutModal.classList.add('hidden'));
        checkoutModal.addEventListener('click', (e) => {
            if (e.target === checkoutModal) {
                checkoutModal.classList.add('hidden');
            }
        });
        
        checkoutForm.addEventListener('submit', async (e) => {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const address = document.getElementById('address').value;
            const phone = document.getElementById('phone').value;
            
            const cartRef = collection(db, `artifacts/${appId}/users/${userId}/cart`);
            const cartSnapshot = await getDocs(cartRef);
            
            const orderItems = [];
            let orderTotal = 0;
            let orderSummaryText = "New Order from Sajid's Marketplace:\n\n";

            cartSnapshot.forEach(doc => {
                const item = doc.data();
                orderItems.push({ id: doc.id, ...item });
                orderTotal += item.price * item.quantity;
                orderSummaryText += `${item.name} (Qty: ${item.quantity}) - Rs. ${item.price * item.quantity}\n`;
            });
            
            if (orderItems.length === 0) {
                showMessage("Your cart is empty!", "error");
                checkoutModal.classList.add('hidden');
                return;
            }

            orderSummaryText += `\nTotal: Rs. ${orderTotal}\n\n`;
            orderSummaryText += `Customer Details:\nName: ${name}\nAddress: ${address}\nPhone: ${phone}\n\n`;
            orderSummaryText += `Thank you for your order! We will confirm soon.`;

            // Open WhatsApp with pre-filled message
            const whatsappUrl = `https://wa.me/923485231698?text=${encodeURIComponent(orderSummaryText)}`;
            window.open(whatsappUrl, '_blank');

            try {
                const ordersRef = collection(db, `artifacts/${appId}/users/${userId}/orders`);
                const orderData = {
                    name,
                    address,
                    phone,
                    items: JSON.stringify(orderItems), // Serialize to JSON string
                    total: orderTotal,
                    status: 'Pending',
                    timestamp: serverTimestamp()
                };
                await addDoc(ordersRef, orderData);

                // Clear the cart
                const deletePromises = orderItems.map(item => deleteDoc(doc(db, `artifacts/${appId}/users/${userId}/cart`, item.id)));
                await Promise.all(deletePromises);

                showMessage("Order placed successfully!", "success");
                checkoutModal.classList.add('hidden');
                checkoutForm.reset();
            } catch (error) {
                console.error("Error placing order:", error);
                showMessage("Failed to place order. Please try again.", "error");
            }
        });

        // Initialize Firebase
        initializeFirebase();
    </script>
</body>
</html>
