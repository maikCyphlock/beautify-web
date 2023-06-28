<nav class="bg-gray-900">
	<div class="mx-auto px-4 sm:px-6 lg:px-8">
		<div class="flex items-center justify-between h-16">
			<div class="flex items-center">
				<a href="/" class="text-white font-bold text-xl">Logo</a>
				<div class="hidden sm:block sm:ml-6">
					<div class="flex">
						<a
							href="/"
							class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-gray-700"
							>Inicio</a
						>
						<a
							href="/about"
							class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-gray-700"
							>Acerca de</a
						>
						<a
							href="/contactme"
							class="px-3 py-2 rounded-md text-sm font-medium text-white hover:bg-gray-700"
							>Contacto</a
						>
					</div>
				</div>
			</div>

			<div class="flex justify-center px-5 py-2 rounded-sm text-gray-600 bg-white">
				<input
					type="search"
					name="search"
					placeholder="Buscar"
					class="text-sm focus:outline-none"
				/>
				<button type="submit" class="">
					<svg
						xmlns="http://www.w3.org/2000/svg"
						fill="none"
						viewBox="0 0 24 24"
						stroke-width="1.5"
						stroke="currentColor"
						class="w-6 h-6"
					>
						<path
							stroke-linecap="round"
							stroke-linejoin="round"
							d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"
						/>
					</svg>
				</button>
			</div>
		</div>
	</div>

	<!-- Menú móvil: se muestra al hacer clic en el botón de hamburguesa -->
	<div class="hidden sm:hidden">
		<div class="px-2 pt-2 pb-3 space-y-1">
			<a
				href="#"
				class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700"
				>Inicio</a
			>
			<a
				href="#"
				class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700"
				>Acerca de</a
			>
			<a
				href="#"
				class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-gray-700"
				>Contacto</a
			>
		</div>
	</div>
</nav>
