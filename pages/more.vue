<template>
	<!-- Navigation -->
	<nav class="bg-purple-800 p-4">
		<div class="container mx-auto flex justify-between items-center">
			<div class="gap-2 flex-row flex justify-center items-center">
				<img
					src="https://v1skm.vip/build/assets/img/brand/logo.png"
					class="w-11 h-11"
				/>
				<div class="text-white text-xl font-semibold">V One</div>
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

	<!-- About Us Section -->
	<section id="about-us" class="py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
				About V One
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				At V One, we are passionate about providing exceptional dining
				experiences to our customers. Our restaurant is known for its cozy
				atmosphere, friendly staff, and delicious cuisine. Whether you're
				craving traditional dishes or innovative creations, we have something to
				satisfy every palate. We source fresh, high-quality ingredients and
				strive to deliver impeccable service with every visit. Join us at V One
				and indulge in a culinary journey like no other.
			</p>
		</div>
	</section>

	<!-- Image Gallery Section -->
	<section id="image-gallery" class="px-6 py-16">
		<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-center">
			Restaurant Gallery
		</h2>
		<div
			class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 mt-8"
		>
			<img
				src="/images/Empty chairs Copenhagen.jpg"
				alt="Restaurant Image 1"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="/images/Empty restaurant Copenhagen.jpg"
				alt="Restaurant Image 2"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="/images/Restaurant HQ Image.jpg"
				alt="Restaurant Image 3"
				class="w-full h-64 object-cover rounded-md"
			/>
			<img
				src="/images/Restaurant Tables Photo.jpg"
				alt="Restaurant Image 4"
				class="w-full h-64 object-cover rounded-md"
			/>
			<!-- Add more images as needed -->
		</div>
	</section>

	<!-- Footer -->
	<footer class="bg-gray-800 text-white text-center py-4">
		<p>&copy; 2024 V One. All rights reserved.</p>
	</footer>
</template>
