<script>
	let isOpen = false;
	let items = [
		{ id: 1, name: 'Producto 1', price: 10 },
		{ id: 2, name: 'Producto 2', price: 20 },
		{ id: 3, name: 'Producto 3', price: 30 }
	];

	function toggleCart() {
		isOpen = !isOpen;
	}

	function removeItem(id) {
		items = items.filter((item) => item.id !== id);
	}
</script>

<div class="fixed top-0 right-0 bottom-0 left-0 z-0" style="pointer-events: none;">
	<div class="fixed top-0 right-0 bottom-0 left-0 z-0 opacity-50" class:opacity-100={isOpen} />
	<div
		class="absolute top-0 right-0 bottom-0 w-64 bg-white shadow-lg transform transition-transform ease-in-out duration-300 z-10"
		class:translate-x-0={isOpen}
		class:translate-x-full={!isOpen}
	>
		<div class="px-4 py-3 border-b border-gray-200">
			<h3 class="text-lg font-bold">Carrito</h3>
		</div>
		<ul class="divide-y divide-gray-200">
			{#each items as item}
				<li class="flex justify-between items-center px-4 py-3">
					<span class="text-gray-800">{item.name}</span>
					<div class="flex items-center">
						<span class="text-gray-600">${item.price}</span>
						<button
							class="ml-2 text-red-600 hover:text-red-800"
							on:click={() => removeItem(item.id)}>Quitar</button
						>
					</div>
				</li>
			{/each}
		</ul>
		<div class="px-4 py-3 border-t border-gray-200">
			<div class="flex justify-between items-center">
				<span class="text-gray-800 font-bold">Total:</span>
				<span class="text-gray-600 font-bold"
					>${items.reduce((total, item) => total + item.price, 0)}</span
				>
			</div>
			<button
				class="mt-3 w-full bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded"
				on:click={toggleCart}>Cerrar carrito</button
			>
		</div>
	</div>
</div>
<button
	class="fixed bottom-0 right-0 mb-4 mr-4 bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-full z-20"
	on:click={toggleCart}
>
	<span class="text-xl">&#128722;</span>
</button>
