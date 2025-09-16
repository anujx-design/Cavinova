<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cavinova - Revolutionizing Online Shopping</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .category-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .feature-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
    </style>
</head>
<body class="font-sans antialiased bg-gray-50">
    <div id="vanta-globe" class="fixed inset-0 -z-10"></div>

    <!-- Navigation -->
    <nav class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <i data-feather="shopping-bag" class="text-indigo-600 h-8 w-8"></i>
                        <span class="ml-2 text-xl font-bold text-indigo-600">Cavinova</span>
                    </div>
                    <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                        <a href="#" class="border-indigo-500 text-gray-900 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Home</a>
                        <a href="#" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Categories</a>
                        <a href="#" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">Deals</a>
                        <a href="#" class="border-transparent text-gray-500 hover:border-gray-300 hover:text-gray-700 inline-flex items-center px-1 pt-1 border-b-2 text-sm font-medium">About</a>
                    </div>
                </div>
                <div class="hidden sm:ml-6 sm:flex sm:items-center">
                    <div class="relative mx-4">
                        <input type="text" class="h-10 w-64 pr-8 pl-5 rounded-full border border-gray-300 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Search...">
                        <button class="absolute right-3 top-2.5 text-gray-400 hover:text-gray-600">
                            <i data-feather="search"></i>
                        </button>
                    </div>
                    <button class="p-1 rounded-full text-gray-400 hover:text-gray-500">
                        <i data-feather="heart"></i>
                    </button>
                    <button class="ml-3 p-1 rounded-full text-gray-400 hover:text-gray-500">
                        <i data-feather="shopping-cart"></i>
                    </button>
                    <button class="ml-3 p-1 rounded-full text-gray-400 hover:text-gray-500">
                        <i data-feather="user"></i>
                    </button>
                </div>
                <div class="-mr-2 flex items-center sm:hidden">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-gradient text-white">
        <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
            <div class="text-center" data-aos="fade-up">
                <h1 class="text-4xl font-extrabold tracking-tight sm:text-5xl lg:text-6xl mb-6">
                    Revolutionizing Your Online Shopping Experience
                </h1>
                <p class="max-w-xl mx-auto text-xl opacity-90">
                    Discover a world of products at your fingertips with Cavinova - where shopping is a joy.
                </p>
                <div class="mt-10 flex justify-center space-x-4">
                    <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md text-indigo-700 bg-white hover:bg-gray-100">
                        Shop Now
                    </a>
                    <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-800 bg-opacity-60 hover:bg-opacity-70">
                        Learn More
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Categories -->
    <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-extrabold text-gray-900 mb-12 text-center" data-aos="fade-up">Shop by Categories</h2>
        <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 lg:grid-cols-4">
            <div class="bg-white rounded-lg overflow-hidden shadow-md category-card transition-all duration-300" data-aos="fade-up" data-aos-delay="100">
                <img src="http://static.photos/technology/640x360/1" alt="Electronics" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-medium text-gray-900">Electronics</h3>
                    <p class="mt-2 text-gray-600">Latest gadgets and devices</p>
                    <a href="#" class="mt-4 inline-flex items-center text-indigo-600 hover:text-indigo-800">
                        Explore <i data-feather="arrow-right" class="ml-1 h-4 w-4"></i>
                    </a>
                </div>
            </div>
            <div class="bg-white rounded-lg overflow-hidden shadow-md category-card transition-all duration-300" data-aos="fade-up" data-aos-delay="200">
                <img src="http://static.photos/fashion/640x360/2" alt="Fashion" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-medium text-gray-900">Fashion</h3>
                    <p class="mt-2 text-gray-600">Trendy clothes and accessories</p>
                    <a href="#" class="mt-4 inline-flex items-center text-indigo-600 hover:text-indigo-800">
                        Explore <i data-feather="arrow-right" class="ml-1 h-4 w-4"></i>
                    </a>
                </div>
            </div>
            <div class="bg-white rounded-lg overflow-hidden shadow-md category-card transition-all duration-300" data-aos="fade-up" data-aos-delay="300">
                <img src="http://static.photos/home/640x360/3" alt="Home Appliances" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-medium text-gray-900">Home Appliances</h3>
                    <p class="mt-2 text-gray-600">Make your home smarter</p>
                    <a href="#" class="mt-4 inline-flex items-center text-indigo-600 hover:text-indigo-800">
                        Explore <i data-feather="arrow-right" class="ml-1 h-4 w-4"></i>
                    </a>
                </div>
            </div>
            <div class="bg-white rounded-lg overflow-hidden shadow-md category-card transition-all duration-300" data-aos="fade-up" data-aos-delay="400">
                <img src="http://static.photos/beauty/640x360/4" alt="Beauty" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-medium text-gray-900">Beauty</h3>
                    <p class="mt-2 text-gray-600">Skincare and cosmetics</p>
                    <a href="#" class="mt-4 inline-flex items-center text-indigo-600 hover:text-indigo-800">
                        Explore <i data-feather="arrow-right" class="ml-1 h-4 w-4"></i>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Features -->
    <div class="bg-gray-100 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:text-center" data-aos="fade-up">
                <h2 class="text-base text-indigo-600 font-semibold tracking-wide uppercase">Features</h2>
                <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">
                    A better way to shop online
                </p>
            </div>

            <div class="mt-10">
                <div class="grid grid-cols-1 gap-10 sm:grid-cols-2 lg:grid-cols-4">
                    <div class="bg-white p-6 rounded-lg shadow-sm" data-aos="fade-up" data-aos-delay="100">
                        <div class="feature-icon rounded-full flex items-center justify-center mb-4">
                            <i data-feather="truck" class="text-white h-6 w-6"></i>
                        </div>
                        <h3 class="text-lg font-medium text-gray-900 mb-2">Fast Delivery</h3>
                        <p class="text-gray-600">Get your products delivered swiftly with our reliable logistics network.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-sm" data-aos="fade-up" data-aos-delay="200">
                        <div class="feature-icon rounded-full flex items-center justify-center mb-4">
                            <i data-feather="shield" class="text-white h-6 w-6"></i>
                        </div>
                        <h3 class="text-lg font-medium text-gray-900 mb-2">Secure Payments</h3>
                        <p class="text-gray-600">Shop with confidence using our 100% secure payment methods.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-sm" data-aos="fade-up" data-aos-delay="300">
                        <div class="feature-icon rounded-full flex items-center justify-center mb-4">
                            <i data-feather="refresh-cw" class="text-white h-6 w-6"></i>
                        </div>
                        <h3 class="text-lg font-medium text-gray-900 mb-2">Easy Returns</h3>
                        <p class="text-gray-600">Not satisfied? Return your items with our hassle-free policy.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-sm" data-aos="fade-up" data-aos-delay="400">
                        <div class="feature-icon rounded-full flex items-center justify-center mb-4">
                            <i data-feather="headphones" class="text-white h-6 w-6"></i>
                        </div>
                        <h3 class="text-lg font-medium text-gray-900 mb-2">24/7 Support</h3>
                        <p class="text-gray-600">Our customer service team is always ready to assist you.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Trending Products -->
    <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-extrabold text-gray-900 mb-12 text-center" data-aos="fade-up">Trending Products</h2>
        <div class="grid grid-cols-1 gap-y-10 gap-x-6 sm:grid-cols-2 lg:grid-cols-4 xl:gap-x-8">
            <div class="group relative" data-aos="fade-up" data-aos-delay="100">
                <div class="w-full min-h-80 bg-gray-200 aspect-w-1 aspect-h-1 rounded-md overflow-hidden group-hover:opacity-75 lg:h-80 lg:aspect-none">
                    <img src="http://static.photos/electronics/640x360/5" alt="Smartphone" class="w-full h-full object-center object-cover lg:w-full lg:h-full">
                </div>
                <div class="mt-4 flex justify-between">
                    <div>
                        <h3 class="text-sm text-gray-700">
                            <a href="#">
                                <span aria-hidden="true" class="absolute inset-0"></span>
                                Galaxy Z Fold 4
                            </a>
                        </h3>
                        <p class="mt-1 text-sm text-gray-500">Smartphone</p>
                    </div>
                    <p class="text-sm font-medium text-gray-900">$1,799</p>
                </div>
            </div>
            <div class="group relative" data-aos="fade-up" data-aos-delay="200">
                <div class="w-full min-h-80 bg-gray-200 aspect-w-1 aspect-h-1 rounded-md overflow-hidden group-hover:opacity-75 lg:h-80 lg:aspect-none">
                    <img src="http://static.photos/fashion/640x360/6" alt="Sneakers" class="w-full h-full object-center object-cover lg:w-full lg:h-full">
                </div>
                <div class="mt-4 flex justify-between">
                    <div>
                        <h3 class="text-sm text-gray-700">
                            <a href="#">
                                <span aria-hidden="true" class="absolute inset-0"></span>
                                Air Jordan 1 Retro
                            </a>
                        </h3>
                        <p class="mt-1 text-sm text-gray-500">Sneakers</p>
                    </div>
                    <p class="text-sm font-medium text-gray-900">$175</p>
                </div>
            </div>
            <div class="group relative" data-aos="fade-up" data-aos-delay="300">
                <div class="w-full min-h-80 bg-gray-200 aspect-w-1 aspect-h-1 rounded-md overflow-hidden group-hover:opacity-75 lg:h-80 lg:aspect-none">
                    <img src="http://static.photos/technology/640x360/7" alt="Smartwatch" class="w-full h-full object-center object-cover lg:w-full lg:h-full">
                </div>
                <div class="mt-4 flex justify-between">
                    <div>
                        <h3 class="text-sm text-gray-700">
                            <a href="#">
                                <span aria-hidden="true" class="absolute inset-0"></span>
                                Apple Watch Series 8
                            </a>
                        </h3>
                        <p class="mt-1 text-sm text-gray-500">Smartwatch</p>
                    </div>
                    <p class="text-sm font-medium text-gray-900">$399</p>
                </div>
            </div>
            <div class="group relative" data-aos="fade-up" data-aos-delay="400">
                <div class="w-full min-h-80 bg-gray-200 aspect-w-1 aspect-h-1 rounded-md overflow-hidden group-hover:opacity-75 lg:h-80 lg:aspect-none">
                    <img src="http://static.photos/home/640x360/8" alt="Air Fryer" class="w-full h-full object-center object-cover lg:w-full lg:h-full">
                </div>
                <div class="mt-4 flex justify-between">
                    <div>
                        <h3 class="text-sm text-gray-700">
                            <a href="#">
                                <span aria-hidden="true" class="absolute inset-0"></span>
                                Ninja Air Fryer
                            </a>
                        </h3>
                        <p class="mt-1 text-sm text-gray-500">Kitchen Appliance</p>
                    </div>
                    <p class="text-sm font-medium text-gray-900">$129</p>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA Section -->
    <div class="bg-indigo-700">
        <div class="max-w-2xl mx-auto text-center py-16 px-4 sm:py-20 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-extrabold text-white sm:text-4xl" data-aos="fade-up">
                <span class="block">Ready to start shopping?</span>
                <span class="block">Join Cavinova today.</span>
            </h2>
            <p class="mt-4 text-lg leading-6 text-indigo-200" data-aos="fade-up" data-aos-delay="100">
                Sign up now and get 15% off your first order.
            </p>
            <a href="#" class="mt-8 w-full inline-flex items-center justify-center px-5 py-3 border border-transparent text-base font-medium rounded-md text-indigo-600 bg-white hover:bg-indigo-50 sm:w-auto" data-aos="fade-up" data-aos-delay="200">
                Sign up for free
            </a>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-gray-800">
        <div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-sm font-semibold text-gray-300 tracking-wider uppercase">
                        Shop
                    </h3>
                    <ul class="mt-4 space-y-4">
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Electronics</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Fashion</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Home & Kitchen</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Beauty</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-gray-300 tracking-wider uppercase">
                        Customer Service
                    </h3>
                    <ul class="mt-4 space-y-4">
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Contact Us</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">FAQs</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Shipping Policy</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Returns & Refunds</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-gray-300 tracking-wider uppercase">
                        Company
                    </h3>
                    <ul class="mt-4 space-y-4">
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">About Us</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Careers</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Blog</a></li>
                        <li><a href="#" class="text-base text-gray-400 hover:text-white">Press</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-sm font-semibold text-gray-300 tracking-wider uppercase">
                        Connect With Us
                    </h3>
                    <div class="mt-4 flex space-x-6">
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="facebook" class="h-6 w-6"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="instagram" class="h-6 w-6"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="twitter" class="h-6 w-6"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-white">
                            <i data-feather="youtube" class="h-6 w-6"></i>
                        </a>
                    </div>
                    <div class="mt-6">
                        <p class="text-gray-400 text-sm">
                            Subscribe to our newsletter
                        </p>
                        <div class="mt-2 flex">
                            <input type="email" class="flex-1 bg-gray-700 border border-gray-600 rounded-l-md px-4 py-2 text-white focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Your email">
                            <button class="bg-indigo-600 hover:bg-indigo-700 text-white px-4 py-2 rounded-r-md">
                                <i data-feather="send" class="h-4 w-4"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="mt-8 pt-8 border-t border-gray-700">
                <p class="text-gray-400 text-sm text-center">
                    &copy; 2023 Cavinova. All rights reserved.
                </p>
            </div>
        </div>
    </footer>

    <script>
        VANTA.GLOBE({
            el: "#vanta-globe",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0x5b6abf,
            backgroundColor: 0xf8fafc,
            size: 0.80
        });
    </script>
    <script>AOS.init();</script>
    <script>feather.replace();</script>
</body>
</html>
