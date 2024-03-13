<template>
    <!-- Navigation -->
    <nav class="bg-purple-800 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <div class="gap-2 flex-row flex justify-center items-center">
                <img src="https://v1skm.vip/build/assets/img/brand/logo.png" class="w-11 h-11" />
                <div class="text-white text-xl font-semibold">
                    V1 - Shan Koe Mee
                </div>
            </div>
            <ul class="flex space-x-4">
                <li>
                    <a href="/" class="text-white hover:text-gray-300">Home</a>
                </li>
                <li>
                    <a href="/more" class="text-white hover:text-gray-300">About</a>
                </li>
                <li>
                    <a href="/contact-us" class="text-purple-800 hover:text-gray-300 bg-white p-2 rounded-md">Contact</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Contact Us Section -->
    <section class="py-16">
        <div class="container mx-auto text-center">
            <h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">Contact V1 - Shan Koe Mee</h2>
            <p class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl">
                Have questions or want to get in touch with V1 - Shan Koe Mee? Feel free to reach out to us using the
                contact information below or by filling out the contact form.

                <!-- Contact Information -->
            <div class="mt-8">
                <p class="text-gray-800 font-bold text-xl">Contact Information:</p>
                <p>Email: yoeyar.info@gmail.com</p>
                <p>Phone: +959950668871</p>
                <p>Address: V1 - Shan Koe Mee, Yangon, Myanmar</p>
            </div>

            <!-- Contact Form -->
            <form action="#" method="post" class="mt-8">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div class="mb-4">
                        <label for="name" class="block text-gray-800 font-bold text-sm mb-2">Your Name:</label>
                        <input type="text" id="name" name="name" class="w-full border rounded-md p-2" required>
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block text-gray-800 font-bold text-sm mb-2">Your Email:</label>
                        <input type="email" id="email" name="email" class="w-full border rounded-md p-2" required>
                    </div>
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-gray-800 font-bold text-sm mb-2">Your Message:</label>
                    <textarea id="message" name="message" rows="4" class="w-full border rounded-md p-2" required></textarea>
                </div>
                <button type="submit" class="bg-purple-800 text-white hover:bg-blue-400 py-2 px-4 rounded-full text-lg">Send
                    Message</button>
            </form>
            </p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>&copy; 2024 V1 - Shan Koe Mee. All rights reserved.</p>
    </footer>
</template>
