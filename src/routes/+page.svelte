<script>
	import ProductShowCase from './productShowCase.svelte';
	import ProductCategory from './ProductCategory.svelte';
	import Footer from './Footer.svelte';
	import AddCart from './AddCart.svelte';
</script>

<div
	class="bg-cover bg-center"
	style="background-image: url(https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb&dl=element5-digital-ceWgSMd8rvQ-unsplash.jpg&w=1920);"
>
	<div class="bg-gray-900 bg-opacity-75 h-screen flex flex-col justify-center items-center">
		<h1 class="text-5xl md:text-6xl text-white font-bold text-center mb-4">
			Bienvenido a nuestra boutique
		</h1>
		<p class="text-2xl md:text-3xl text-gray-300 text-center mb-8">
			Descubre nuestra selección de ropa y accesorios de moda
		</p>
		<a href="/checkout" class="bg-white hover:bg-gray-100 text-gray-800 font-bold py-4 px-8 rounded"
			>Comprar ahora</a
		>
	</div>
</div>

<ProductShowCase />
<ProductCategory />
<Footer />
<AddCart />
