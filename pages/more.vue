<template>
    <!-- Navigation -->
    <nav class="bg-green-800 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-white text-xl font-semibold">Myanmar Soccer</div>
            <ul class="flex space-x-4">
                <li>
                    <a href="/" class="text-white hover:text-gray-300">Home</a>
                </li>
                <li>
                    <a
                        href="/more"
                        class="text-green-800 hover:text-gray-300 bg-white p-2 rounded-md"
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

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                About Myanmar Soccer
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Myanmar Soccer has a rich history and passionate fan base. From
                local tournaments to international competitions, soccer holds a
                special place in the hearts of Myanmar's people. Learn more
                about the teams, players, and events that shape the soccer
                landscape in Myanmar.
            </p>
        </div>
    </section>

    <!-- Events Section -->
    <section id="events" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                Soccer Events in Myanmar
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Explore the exciting soccer events that take place throughout
                Myanmar. From local league matches to national tournaments,
                there's always something happening in the world of Myanmar
                Soccer. Stay updated with the latest scores, schedules, and
                highlights.
            </p>
        </div>
    </section>

    <!-- Teams Section -->
    <section id="teams" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                Soccer Teams in Myanmar
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Get to know the prominent soccer teams in Myanmar. From
                traditional powerhouses to up-and-coming challengers, each team
                brings its own unique style and talent to the field. Explore
                player profiles, team histories, and fan communities.
            </p>
        </div>
    </section>

    <!-- Players Section -->
    <section id="players" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                Soccer Players in Myanmar
            </h2>
            <p
                class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
            >
                Meet the top soccer players in Myanmar. From seasoned veterans
                to rising stars, these players showcase the skill and passion
                that define Myanmar Soccer. Learn about their backgrounds,
                achievements, and future prospects.
            </p>
        </div>
    </section>

    <!-- Image Gallery Section -->
    <section id="image-gallery" class="px-6">
        <h3 class="text-2xl md:text-3xl font-bold mb-4 text-center">
            Image Gallery
        </h3>
        <div
            class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 mt-8"
        >
            <img
                src="https://i1.wp.com/www.aseanfootball.org/v2/wp-content/uploads/2017/02/mff-3.jpg"
                alt="Bagan Culture 1"
                class="w-full h-64 object-cover rounded-md"
            />
            <img
                src="https://i0.wp.com/www.aseanfootball.org/v3/wp-content/uploads/2019/08/Myan-VN-Wmns-1.jpg"
                alt="Bagan Culture 2"
                class="w-full h-64 object-cover rounded-md"
            />
            <img
                src="https://www.aseanfootball.org/v3/wp-content/uploads/2018/11/myanmar-laos-1-800x400.jpg"
                alt="Bagan Culture 3"
                class="w-full h-64 object-cover rounded-md"
            />
            <img
                src="https://www.aseanfootball.org/v3/wp-content/uploads/2019/04/MFF-Jockey-1-800x400.jpg"
                alt="Bagan Culture 3"
                class="w-full h-64 object-cover rounded-md"
            />
            <!-- Add more images as needed -->
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
