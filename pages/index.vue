<template>
	<!-- Navigation -->
	<nav class="bg-red-800 p-4">
		<div class="container mx-auto flex justify-between items-center">
			<div class="text-white text-xl font-semibold">Yoe Yar</div>
			<ul class="flex space-x-4">
				<li>
					<a
						href="/"
						class="text-red-800 hover:text-gray-300 bg-white p-2 rounded-md"
						>Home</a
					>
				</li>
				<li>
					<a href="/more" class="text-white hover:text-gray-300">About</a>
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
			background-image: url('https://upload.wikimedia.org/wikipedia/commons/thumb/d/dc/Bagan_panorama2.jpg/2880px-Bagan_panorama2.jpg');
		"
	>
		<div class="container mx-auto text-center">
			<h1 class="text-4xl md:text-6xl lg:text-8xl font-bold leading-tight mb-4">
				Discover the Rich Heritage of Bagan, Myanmar
			</h1>
			<p class="text-lg md:text-xl lg:text-2xl mb-8">
				Explore the ancient city known for its historical temples and cultural
				significance.
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
				About Bagan, Myanmar
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Bagan, located in the Mandalay Region of Myanmar, is an ancient city
				that was the capital of the Pagan Kingdom from the 9th to 13th
				centuries. It is renowned for its vast and dense concentration of
				Buddhist temples, pagodas, and stupas. Bagan is a UNESCO World Heritage
				Site, attracting visitors from around the world to witness its
				architectural and cultural marvels. The city reached its peak during the
				11th and 13th centuries when over 10,000 temples and religious
				structures were constructed. Each temple in Bagan has a unique design
				and historical significance. Notable temples include the Ananda Temple,
				Shwezigon Pagoda, and Thatbyinnyu Temple. Bagan is not only a testament
				to the spiritual and artistic achievements of Myanmar's past but also
				offers breathtaking views of the landscape, especially during sunrise
				and sunset when hot air balloons dot the sky, creating a magical
				atmosphere. Today, Bagan stands as a symbol of Myanmar's rich cultural
				heritage, drawing history enthusiasts, photographers, and travelers
				seeking a glimpse into the country's glorious past.
			</p>
		</div>
	</section>

	<!-- Contact Section -->
	<section id="contact" class="bg-gray-200 py-16">
		<div class="container mx-auto text-center">
			<h2 class="text-3xl md:text-4xl lg:text-5xl font-bold mb-6 text-gray-800">
				Contact Us
			</h2>
			<p
				class="text-lg md:text-xl lg:text-2xl text-gray-700 leading-relaxed mx-auto max-w-2xl"
			>
				Have questions or want to learn more about Bagan Culture? Contact us
				below.
			</p>
			<div class="mt-8">
				<a
					href="#"
					class="bg-red-800 text-white hover:bg-red-700 py-2 px-4 rounded-full text-lg"
					>Contact Now</a
				>
			</div>
		</div>
	</section>

	<!-- Footer -->
	<footer class="bg-gray-800 text-white text-center py-4">
		<p>&copy; 2023 Yoe Yar. All rights reserved.</p>
	</footer>
</template>
