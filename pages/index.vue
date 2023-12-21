<template>
    <!-- Navigation -->
    <nav class="bg-red-800 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-white text-xl font-semibold">ရိုးရာ - Yoe Yar</div>
            <ul class="flex space-x-4">
                <li>
                    <a href="/" class="text-red-800 hover:text-gray-300 bg-white p-2 rounded-md">Home</a>
                </li>
                <li>
                    <a href="/more" class="text-white hover:text-gray-300">About</a>
                </li>
                <li>
                    <a href="/contact-us" class="text-white hover:text-gray-300">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-cover bg-center h-screen flex items-center text-white" style="
			background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Bagan_panorama2.jpg/2880px-Bagan_panorama2.jpg');
		">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl md:text-6xl lg:text-8xl font-bold leading-tight mb-4">
                Discover the Rich Heritage of ရိုးရာ - Yoe Yar
            </h1>
            <p class="text-lg md:text-xl lg:text-2xl mb-8">
                Explore the ancient city known for its historical temples and cultural
                significance.
            </p>
            <a href="/more" class="bg-yellow-500 text-gray-800 hover:bg-yellow-400 py-2 px-4 rounded-full text-lg">Learn
                More</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
                About ရိုးရာ - Yoe Yar
            </h2>
            <p class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl">
                ရိုးရာ - Yoe Yar, situated in the Mandalay Region of Myanmar, embodies the ancient legacy as the capital of
                the Pagan Kingdom from the 9th to 13th centuries. Renowned for its extensive collection of Buddhist temples,
                pagodas, and stupas, Bagan captivates visitors with its historical richness. Recognized as a UNESCO World
                Heritage Site, it draws a global audience to marvel at its architectural and cultural wonders.

                During the zenith of Bagan's splendor in the 11th and 13th centuries, over 10,000 temples and religious
                structures graced the landscape. Each temple carries a distinctive design and historical significance.
                Noteworthy landmarks such as the Ananda Temple, Shwezigon Pagoda, and Thatbyinnyu Temple contribute to
                Bagan's cultural tapestry.

                Beyond being a testament to Myanmar's spiritual and artistic achievements, Bagan offers awe-inspiring views
                of the landscape. Particularly enchanting during sunrise and sunset, the sky is adorned with hot air
                balloons, creating a magical ambiance.

                Today, ရိုးရာ - Yoe Yar stands as a symbol of Myanmar's vibrant cultural heritage. It beckons history
                enthusiasts, photographers, and travelers eager to glimpse into the country's glorious past.
            </p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-gray-200 py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-gray-800">Contact ရိုးရာ - Yoe Yar</h2>
            <p class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl">
                Have questions or want to learn more about ရိုးရာ - Yoe Yar's cultural wonders? Contact our team at the
                information below.
            </p>
            <div class="mt-8">
                <a href="contact-us" class="bg-red-800 text-white hover:bg-red-700 py-2 px-4 rounded-full text-lg">Contact
                    Now</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>&copy; 2023 ရိုးရာ - Yoe Yar. All rights reserved.</p>
    </footer>
</template>
