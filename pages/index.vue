<template>
    <!-- Navigation -->
    <nav class="bg-green-800 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-white text-xl font-semibold">Myanmar Soccer</div>
            <ul class="flex space-x-4">
                <li>
                    <a
                        href="/"
                        class="text-green-800 hover:text-gray-300 bg-white p-2 rounded-md"
                        >Home</a
                    >
                </li>
                <li>
                    <a href="/more" class="text-white hover:text-gray-300"
                        >About</a
                    >
                </li>
                <li>
                    <a href="/contact-us" class="text-white hover:text-gray-300"
                        >Contact</a
                    >
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <header
        class="bg-cover bg-center h-screen flex items-center text-white"
        style="
            background-image: url(&quot;https://i1.wp.com/www.aseanfootball.org/v2/wp-content/uploads/2017/02/mff-3.jpg&quot;);
        "
    >
        <div class="container mx-auto text-center">
            <h1
                class="text-4xl md:text-6xl lg:text-8xl font-bold leading-tight mb-4"
            >
                Welcome to Myanmar Soccer
            </h1>
            <p class="text-lg md:text-xl lg:text-2xl mb-8">
                Explore the passion, excitement, and talent of Myanmar's soccer
                scene.
            </p>
            <a
                href="/more"
                class="bg-yellow-500 text-gray-800 hover:bg-yellow-400 py-2 px-4 rounded-full text-lg"
                >Learn More</a
            >
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                About Myanmar Soccer
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Myanmar has a rich history and passion for soccer, with a
                thriving league and enthusiastic fan base. Learn more about the
                teams, players, and tournaments that make up the soccer
                landscape in Myanmar.
            </p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-200 py-16">
        <div class="container mx-auto text-center">
            <h2
                class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-gray-800"
            >
                Contact Myanmar Soccer
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Have questions or want to learn more about soccer in Myanmar?
                Contact our team at the information below.
            </p>
            <div class="mt-8">
                <a
                    href="contact-us"
                    class="bg-green-800 text-white hover:bg-green-700 py-2 px-4 rounded-full text-lg"
                    >Contact Now</a
                >
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>&copy; 2024 Myanmar Soccer. All rights reserved.</p>
    </footer>
</template>
