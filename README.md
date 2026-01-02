<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NaijaFanHub - Nigeria's Premier Creator Platform</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="components/navbar.js"></script>
    <script src="components/footer.js"></script>
</head>
<body class="bg-gray-100">
    <custom-navbar></custom-navbar>
    <main class="container mx-auto px-4 py-8">
        <!-- Hero Section -->
        <section class="bg-gradient-to-r from-green-600 to-yellow-500 rounded-2xl p-8 text-white mb-12">
            <div class="max-w-3xl mx-auto text-center">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Empowering Nigerian Creators</h1>
                <p class="text-xl mb-8">Connect with your favorite Nigerian content creators and enjoy exclusive content</p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="#" class="bg-white text-green-700 px-6 py-3 rounded-full font-bold hover:bg-gray-100 transition">Join as Fan</a>
                    <a href="#" class="bg-black bg-opacity-30 px-6 py-3 rounded-full font-bold hover:bg-opacity-40 transition">Become Creator</a>
                </div>
            </div>
        </section>
        <!-- Featured Creators -->
        <section class="mb-16">
            <h2 class="text-2xl font-bold mb-6 text-gray-800">Featured Nigerian Creators</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Creator Card 1 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition">
                    <img src="http://static.photos/people/640x360/1" alt="Creator" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/people/200x200/1" alt="Profile" class="w-10 h-10 rounded-full mr-3">
                            <div>
                                <h3 class="font-bold">LagosBabe</h3>
                                <p class="text-sm text-gray-600">Fashion & Lifestyle</p>
                            </div>
                        </div>
                        <p class="text-gray-700 mb-4">Exclusive Nigerian fashion content and behind-the-scenes</p>
                        <a href="#" class="block text-center bg-green-600 text-white py-2 rounded-lg hover:bg-green-700 transition">Subscribe</a>
                    </div>
                </div>
                <!-- Creator Card 2 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition">
                    <img src="http://static.photos/technology/640x360/2" alt="Creator" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/people/200x200/2" alt="Profile" class="w-10 h-10 rounded-full mr-3">
                            <div>
                                <h3 class="font-bold">NaijaTechGuy</h3>
                                <p class="text-sm text-gray-600">Tech & Gadgets</p>
                            </div>
                        </div>
                        <p class="text-gray-700 mb-4">Latest tech reviews from Nigerian perspective</p>
                        <a href="#" class="block text-center bg-green-600 text-white py-2 rounded-lg hover:bg-green-700 transition">Subscribe</a>
                    </div>
                </div>
                <!-- Creator Card 3 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition">
                    <img src="http://static.photos/food/640x360/3" alt="Creator" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/people/200x200/3" alt="Profile" class="w-10 h-10 rounded-full mr-3">
                            <div>
                                <h3 class="font-bold">AbujaChef</h3>
                                <p class="text-sm text-gray-600">Food & Cooking</p>
                            </div>
                        </div>
                        <p class="text-gray-700 mb-4">Authentic Nigerian recipes and cooking tutorials</p>
                        <a href="#" class="block text-center bg-green-600 text-white py-2 rounded-lg hover:bg-green-700 transition">Subscribe</a>
                    </div>
                </div>
                <!-- Creator Card 4 -->
                <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-lg transition">
                    <img src="http://static.photos/sport/640x360/4" alt="Creator" class="w-full h-48 object-cover">
                    <div class="p-4">
                        <div class="flex items-center mb-3">
                            <img src="http://static.photos/people/200x200/4" alt="Profile" class="w-10 h-10 rounded-full mr-3">
                            <div>
                                <h3 class="font-bold">SuperFan9ja</h3>
                                <p class="text-sm text-gray-600">Sports & Fitness</p>
                            </div>
                        </div>
                        <p class="text-gray-700 mb-4">Nigerian football analysis and fitness tips</p>
                        <a href="#" class="block text-center bg-green-600 text-white py-2 rounded-lg hover:bg-green-700 transition">Subscribe</a>
                    </div>
                </div>
            </div>
        </section>
        <!-- Categories -->
        <section class="mb-16">
            <h2 class="text-2xl font-bold mb-6 text-gray-800">Explore Categories</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <a href="#" class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition text-center">
                    <i data-feather="heart" class="w-8 h-8 mx-auto text-pink-500 mb-3"></i>
                    <h3 class="font-bold">Dating & Relationships</h3>
                </a>
                <a href="#" class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition text-center">
                    <i data-feather="music" class="w-8 h-8 mx-auto text-purple-500 mb-3"></i>
                    <h3 class="font-bold">Music & Entertainment</h3>
                </a>
                <a href="#" class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition text-center">
                    <i data-feather="dollar-sign" class="w-8 h-8 mx-auto text-green-500 mb-3"></i>
                    <h3 class="font-bold">Business & Finance</h3>
                </a>
                <a href="#" class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition text-center">
                    <i data-feather="film" class="w-8 h-8 mx-auto text-blue-500 mb-3"></i>
                    <h3 class="font-bold">Movies & TV</h3>
                </a>
            </div>
        </section>
        <!-- Testimonials -->
        <section class="bg-white rounded-xl p-8 shadow-md mb-16">
            <h2 class="text-2xl font-bold mb-8 text-center text-gray-800">What Our Users Say</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden">
                        <img src="http://static.photos/people/200x200/5" alt="User" class="w-full h-full object-cover">
                    </div>
                    <p class="text-gray-700 mb-4">"I've connected with amazing Nigerian creators who share my interests!"</p>
                    <p class="font-bold">- Chinedu, Lagos</p>
                </div>
                <div class="text-center">
                    <div class="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden">
                        <img src="http://static.photos/people/200x200/6" alt="User" class="w-full h-full object-cover">
                    </div>
                    <p class="text-gray-700 mb-4">"Finally a platform that celebrates Nigerian talent and culture!"</p>
                    <p class="font-bold">- Amina, Abuja</p>
                </div>
                <div class="text-center">
                    <div class="w-20 h-20 mx-auto mb-4 rounded-full overflow-hidden">
                        <img src="http://static.photos/people/200x200/7" alt="User" class="w-full h-full object-cover">
                    </div>
                    <p class="text-gray-700 mb-4">"Earning from my content has never been easier with NaijaFanHub."</p>
                    <p class="font-bold">- Tunde, Ibadan</p>
                </div>
            </div>
        </section>
    </main>
    <custom-footer></custom-footer>
    <script>
        feather.replace();
    </script>
    <script src="script.js"></script>
</body>
</html>
