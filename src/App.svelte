<script>
	export let name;
</script>

<div class="flex items-center justify-center w-full h-screen pt-4">
	<div class="max-w-sm my-2 overflow-hidden rounded shadow-lg">
		<img
			class="w-full"
			src="https://tailwindcss.com/img/card-top.jpg"
			alt="Sunset in the mountains" />
		<div class="px-6 py-4">
			<div class="mb-2 text-xl font-bold">Hello {name}!</div>
			<p class="text-base text-grey-700">
				This is a template with Svelte.js and TailwindCss
			</p>
		</div>
		<div class="px-6 pt-4 pb-2">
			<span
				class="inline-block px-3 py-1 mr-2 text-sm font-semibold text-gray-700 bg-gray-200 rounded-full">#template</span>
			<span
				class="inline-block px-3 py-1 mr-2 text-sm font-semibold text-gray-700 bg-gray-200 rounded-full">#svelte</span>
			<span
				class="inline-block px-3 py-1 text-sm font-semibold text-gray-700 bg-gray-200 rounded-full">#tailwindcss</span>
		</div>
	</div>
</div>
