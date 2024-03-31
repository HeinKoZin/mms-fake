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
					<a
						href="/"
						class="text-purple-800 hover:text-gray-300 bg-white p-2 rounded-md"
						>Home</a
					>
				</li>
				<li>
					<a href="/more" class="text-white hover:text-gray-300">About Us</a>
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
		class="bg-cover bg-purple-800 bg-center h-screen flex items-center text-white"
		style="background-image: url('/images/Pub Set Room Daytime.jpg')">

		<div class="container mx-auto text-center">
			<!-- <img
				src="https://v1skm.vip/build/assets/img/brand/logo.png"
				class="w-40 h-40 mx-auto mb-6"
			/> -->
			<h1 class="text-4xl md:text-6xl lg:text-8xl font-bold leading-tight mb-4">
				Welcome to V One
			</h1>
			<p class="text-lg md:text-xl lg:text-2xl mb-8">
				Experience the finest dining at V One Restaurant.
			</p>
			<a
				href="/more"
				class="bg-yellow-500 text-gray-800 hover:bg-yellow-400 py-2 px-4 rounded-full text-lg"
				>About Us</a
			>
		</div>
	</header>

	<!-- About Section -->
	<section id="about" class="py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6">
				About V One
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				At V One, we pride ourselves on serving the most delicious and authentic
				cuisine from around the world. Our chefs are dedicated to creating
				memorable dining experiences for our guests.
			</p>
		</div>
	</section>

	<!-- Contact Section -->
	<section id="contact" class="bg-gray-200 py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-gray-800">
				Contact V One
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Have questions or want to make a reservation? Contact our team at the
				information below.
			</p>
			<div class="mt-8">
				<a
					href="contact-us"
					class="bg-purple-800 text-white hover:bg-green-700 py-2 px-4 rounded-full text-lg"
					>Contact Now</a
				>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="bg-gray-800 text-white text-center py-4">
		<p>&copy; 2024 V One. All rights reserved.</p>
	</footer>
</template>
