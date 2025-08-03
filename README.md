<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shrihan Rudra Biswas | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8fafc;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #6b21a8 0%, #3b82f6 100%);
        }
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="text-2xl font-bold">Shrihan Rudra Biswas</div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="hover:text-purple-200">Home</a>
                    <a href="#about" class="hover:text-purple-200">About</a>
                    <a href="#skills" class="hover:text-purple-200">Skills</a>
                    <a href="#projects" class="hover:text-purple-200">Projects</a>
                    <a href="#contact" class="hover:text-purple-200">Contact</a>
                </div>
                <div class="md:hidden">
                    <button class="mobile-menu-button">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-6xl font-bold mb-4">Hi, I'm <span class="text-yellow-300">Shrihan Rudra Biswas</span></h1>
                <p class="text-xl mb-6">Web Developer | Designer | Tech Enthusiast</p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-white text-purple-800 px-6 py-2 rounded-full font-semibold hover:bg-purple-100 transition">Hire Me</a>
                    <a href="#projects" class="border-2 border-white px-6 py-2 rounded-full font-semibold hover:bg-white hover:text-purple-800 transition">Projects</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative w-64 h-64 rounded-full overflow-hidden border-4 border-white shadow-xl">
                    <img src="https://placehold.co/400" alt="Shrihan Rudra Biswas's profile picture" class="w-full h-full object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">About Me</h2>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/3 mb-8 md:mb-0 flex justify-center">
                    <img src="https://placehold.co/300x400" alt="About me illustration" class="rounded-lg shadow-lg w-64 md:w-full">
                </div>
                <div class="md:w-2/3 md:pl-12">
                    <p class="text-gray-700 mb-6 leading-relaxed">
                        Hello! I'm Shrihan, a passionate student from Barguna. I graduated from Barguna Zilla School in 2026 and currently studying.
                    </p>
                    <p class="text-gray-700 mb-6 leading-relaxed">
                        My journey in web development began when I started exploring coding in high school. Since then, I've developed skills in HTML, CSS, JavaScript, and worked on projects like my personal portfolio and various web applications.
                    </p>
                    <div class="grid grid-cols-2 gap-4 mb-6">
                        <div>
                            <p class="font-semibold">Name:</p>
                            <p>Shrihan Rudra Biswas</p>
                        </div>
                        <div>
                            <p class="font-semibold">Email:</p>
                            <p>shrihanrudrabiswas@gmail.com</p>
                        </div>
                        <div>
                            <p class="font-semibold">From:</p>
                            <p>Barguna</p>
                        </div>
                        <div>
                            <p class="font-semibold">Phone:</p>
                            <p>01779990701</p>
                        </div>
                    </div>
                    <a href="#" class="inline-block gradient-bg text-white px-6 py-2 rounded-full font-semibold hover:opacity-90 transition">Download CV</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">My Skills</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Skill Card 1 -->
                <div class="bg-white p-6 rounded-xl shadow-md card-hover transition">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-code text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Web Development</h3>
                    <p class="text-gray-600">HTML, CSS, JavaScript, React, Node.js</p>
                    <div class="mt-4">
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="gradient-bg h-2.5 rounded-full" style="width: 90%"></div>
                        </div>
                        <span class="text-sm text-gray-500">90%</span>
                    </div>
                </div>

                <!-- Skill Card 2 -->
                <div class="bg-white p-6 rounded-xl shadow-md card-hover transition">
                    <div class="text-blue-500 mb-4">
                        <i class="fas fa-paint-brush text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">UI/UX Design</h3>
                    <p class="text-gray-600">Figma, Adobe XD, Wireframing, Prototyping</p>
                    <div class="mt-4">
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="gradient-bg h-2.5 rounded-full" style="width: 80%"></div>
                        </div>
                        <span class="text-sm text-gray-500">80%</span>
                    </div>
                </div>

                <!-- Skill Card 3 -->
                <div class="bg-white p-6 rounded-xl shadow-md card-hover transition">
                    <div class="text-green-500 mb-4">
                        <i class="fas fa-mobile-alt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Mobile Development</h3>
                    <p class="text-gray-600">React Native, Flutter, Android</p>
                    <div class="mt-4">
                        <div class="w-full bg-gray-200 rounded-full h-2.5">
                            <div class="gradient-bg h-2.5 rounded-full" style="width: 75%"></div>
                        </div>
                        <span class="text-sm text-gray-500">75%</span>
                    </div>
                </div>
            </div>
            <div class="flex justify-center mt-10">
                <img src="https://placehold.co/300x200" alt="Gaming" class="rounded-lg shadow-lg mx-4">
                <img src="https://placehold.co/300x200" alt="Web Development" class="rounded-lg shadow-lg mx-4">
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">My Projects</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg card-hover transition">
                    <img src="https://placehold.co/600x400" alt="Project 1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">E-Commerce Website</h3>
                        <p class="text-gray-600 mb-4">A full-featured online store with payment gateway integration.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">React</span>
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Node.js</span>
                            <span class="px-3 py-1 bg-gray-100 text-gray-800 rounded-full text-sm">MongoDB</span>
                        </div>
                        <a href="#" class="text-purple-600 font-medium hover:underline">View Project →</a>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg card-hover transition">
                    <img src="https://placehold.co/600x400" alt="Project 2" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Portfolio Dashboard</h3>
                        <p class="text-gray-600 mb-4">A personal dashboard to showcase work and manage projects.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">Vue.js</span>
                            <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">Firebase</span>
                        </div>
                        <a href="#" class="text-purple-600 font-medium hover:underline">View Project →</a>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg card-hover transition">
                    <img src="https://placehold.co/600x400" alt="Project 3" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Mobile Weather App</h3>
                        <p class="text-gray-600 mb-4">Real-time weather forecasting application with location tracking.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">Flutter</span>
                            <span class="px-3 py-1 bg-yellow-100 text-yellow-800 rounded-full text-sm">API</span>
                        </div>
                        <a href="#" class="text-purple-600 font-medium hover:underline">View Project →</a>
                    </div>
                </div>
            </div>
            <div class="text-center mt-10">
                <a href="#" class="gradient-bg text-white px-6 py-3 rounded-full font-semibold hover:opacity-90 transition inline-block">View All Projects</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="gradient-bg text-white py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Get In Touch</h2>
            <div class="flex flex-col md:flex-row gap-10">
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-semibold mb-6">Contact Information</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="mr-4 text-xl">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Email</h4>
                                <p>shrihanrudrabiswas@gmail.com</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="mr-4 text-xl">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Phone</h4>
                                <p>01779990701</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="mr-4 text-xl">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div>
                                <h4 class="font-medium">Location</h4>
                                <p>Barguna, Bangladesh</p>
                            </div>
                        </div>
                    </div>
                    <div class="mt-8">
                        <h4 class="text-xl font-semibold mb-4">Follow Me</h4>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 rounded-full bg-white text-purple-800 flex items-center justify-center hover:bg-purple-100 transition">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="w-10 h-10 rounded-full bg-white text-purple-800 flex items-center justify-center hover:bg-purple-100 transition">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="w-10 h-10 rounded-full bg-white text-purple-800 flex items-center justify-center hover:bg-purple-100 transition">
                                <i class="fab fa-linkedin-in"></i>
                            </a>
                            <a href="#" class="w-10 h-10 rounded-full bg-white text-purple-800 flex items-center justify-center hover:bg-purple-100 transition">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2">
                    <form class="space-y-4">
                        <div>
                            <label for="name" class="block mb-2">Your Name </label>
                            <input type="text" id="name" class="w-full px-4 py-2 rounded-lg bg-purple-900 bg-opacity-30 border border-purple-300 focus:outline-none focus:ring-2 focus:ring-purple-400" placeholder="Enter your name">
                        </div>
                        <div>
                            <label for="email" class="block mb-2">Email </label>
                            <input type="email" id="email" class="w-full px-4 py-2 rounded-lg bg-purple-900 bg-opacity-30 border border-purple-300 focus:outline-none focus:ring-2 focus:ring-purple-400" placeholder="Enter your email">
                        </div>
                        <div>
                            <label for="subject" class="block mb-2">Education </label>
                            <input type="text" id="subject" class="w-full px-4 py-2 rounded-lg bg-purple-900 bg-opacity-30 border border-purple-300 focus:outline-none focus:ring-2 focus:ring-purple-400" placeholder="Enter subject">
                        </div>
                        <div>
                            <label for="message" class="block mb-2">Message</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 rounded-lg bg-purple-900 bg-opacity-30 border border-purple-300 focus:outline-none focus:ring-2 focus:ring-purple-400" placeholder="Enter your message"></textarea>
                        </div>
                        <button type="submit" class="gradient-bg text-white px-6 py-3 rounded-full font-semibold hover:opacity-90 transition w-full">Send Message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>© 2023 Shrihan Rudra Biswas. All rights reserved.</p>
            <p class="mt-2 text-gray-400">Designed with ❤️ by Shrihan Rudra Biswas</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.querySelector('.mobile-menu-button');
        const mobileMenu = document.querySelector('.mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            document.querySelector('.md\\:flex').classList.toggle('hidden');
        });
    </script>
</body>
</html>
