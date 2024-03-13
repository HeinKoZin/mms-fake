<template>
	<!-- Navigation -->
	<nav class="bg-purple-800 p-4">
		<div class="container mx-auto flex justify-between items-center">
			<div class="gap-2 flex-row flex justify-center items-center">
				<img
					src="https://v1skm.vip/build/assets/img/brand/logo.png"
					class="w-11 h-11"
				/>
				<div class="text-white text-xl font-semibold">V1 - SKM</div>
			</div>
			<ul class="flex space-x-4">
				<li>
					<a href="/" class="text-white hover:text-gray-300">Home</a>
				</li>
				<li>
					<a
						href="/more"
						class="text-purple-800 hover:text-gray-300 bg-white p-2 rounded-md"
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
				About V1 - SKM
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				V1 - SKM has a rich history and passionate fan base. From local
				tournaments to international competitions, Shan Koe Mee holds a special
				place in the hearts of Myanmar's people. Learn more about the players,
				tournaments, and events that shape the Shan Koe Mee landscape.
			</p>
		</div>
	</section>

	<!-- Events Section -->
	<section id="events" class="py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
				V1 - SKM Events
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Explore the exciting Shan Koe Mee events that take place throughout
				Myanmar. From local tournaments to national competitions, there's always
				something happening in the world of Shan Koe Mee. Stay updated with the
				latest scores, schedules, and highlights.
			</p>
		</div>
	</section>

	<!-- Players Section -->
	<section id="players" class="py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
				V1 - SKM Players
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Meet the top Shan Koe Mee players. From seasoned veterans to rising
				stars, these players showcase the skill and passion that define Shan Koe
				Mee. Learn about their backgrounds, achievements, and future prospects.
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
				src="https://v1skm.vip/build/assets/img/brand/logo.png"
				alt="Shan Koe Mee Culture 1"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="https://v1skm.vip/build/assets/img/brand/logo.png"
				alt="Shan Koe Mee Culture 2"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="https://v1skm.vip/build/assets/img/brand/logo.png"
				alt="Shan Koe Mee Culture 3"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="https://v1skm.vip/build/assets/img/brand/logo.png"
				alt="Shan Koe Mee Culture 3"
				class="w-full h-64 object-cover rounded-md"
			/>
			<!-- Add more images as needed -->
		</div>
	</section>

	<!-- Contact Section -->
	<section id="contact" class="bg-gray-200 py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-gray-800">
				Contact V1 - SKM
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Have questions or want to learn more about Shan Koe Mee in Myanmar?
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
		<p>&copy; 2024 V1 - SKM. All rights reserved.</p>
	</footer>
</template>
