<div class="container mx-auto px-4">
	<div class="max-w-md mx-auto py-8">
		<h2 class="text-3xl font-extrabold text-gray-900 mb-6 text-center">Checkout</h2>
		<form>
			<div class="grid grid-cols-2 gap-4 mb-4">
				<div>
					<label for="first_name" class="block text-sm font-medium text-gray-700 mb-1">Nombre</label
					>
					<input
						type="text"
						name="first_name"
						id="first_name"
						autocomplete="given-name"
						class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
					/>
				</div>
				<div>
					<label for="last_name" class="block text-sm font-medium text-gray-700 mb-1"
						>Apellido</label
					>
					<input
						type="text"
						name="last_name"
						id="last_name"
						autocomplete="family-name"
						class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
					/>
				</div>
			</div>
			<div class="mb-4">
				<label for="email" class="block text-sm font-medium text-gray-700 mb-1"
					>Correo electrónico</label
				>
				<input
					type="email"
					name="email"
					id="email"
					autocomplete="email"
					class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
				/>
			</div>
			<div class="mb-4">
				<label for="country" class="block text-sm font-medium text-gray-700 mb-1"
					>País / Región</label
				>
				<input
					type="text"
					name="country"
					id="country"
					autocomplete="country"
					class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
				/>
			</div>
			<div class="grid grid-cols-2 gap-4 mb-4">
				<div>
					<label for="city" class="block text-sm font-medium text-gray-700 mb-1">Ciudad</label>
					<input
						type="text"
						name="city"
						id="city"
						autocomplete="city"
						class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
					/>
				</div>
				<div>
					<label for="postal_code" class="block text-sm font-medium text-gray-700 mb-1"
						>Código postal</label
					>
					<input
						type="text"
						name="postal_code"
						id="postal_code"
						autocomplete="postal-code"
						class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
					/>
				</div>
			</div>
			<div class="mb-4">
				<label for="address" class="block text-sm font-medium text-gray-700 mb-1">Dirección</label>
				<textarea
					id="address"
					name="address"
					rows="4"
					class="w-full p-2 border border-gray-300 rounded-md shadow-sm bg-white focus:outline-none focus:ring-blue-500 focus:border-blue-500"
				/>
			</div>
			<div class="text-center">
				<button
					type="submit"
					class="inline-block bg-purple-500 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-full focus:outline-none focus:shadow-outline-purple"
				>
					Comprar
				</button>
			</div>
		</form>
	</div>
</div>
