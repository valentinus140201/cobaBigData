<script>

import FormHub from '@/components/FormHub.vue'

export default {
  name: 'NavBar',
  components: {
    FormHub
  }
}
</script>

<template>
	<header class="p-4 dark:text-gray-100">
		<div class="flex justify-between h-16 mx-auto" bis_skin_checked="1">
			<a rel="noopener noreferrer" href="#" aria-label="Back to homepage" class="flex items-center p-2">
                <FormHub/>
            </a>
			<ul class="items-stretch hidden space-x-3 lg:flex">
				<li class="flex">
					<router-link to="/" rel="noopener noreferrer" class="flex items-center px-4 -mb-1 border-b-2 dark:border-transparent">Home</router-link>
				</li>
				<li class="flex">
					<router-link to="/about" rel="noopener noreferrer" class="flex items-center px-4 -mb-1 border-b-2 dark:border-transparent">About</router-link>
				</li>
			</ul>
			<div class="items-center flex-shrink-0 hidden lg:flex" bis_skin_checked="1">
				<button class="self-center py-3 pr-4 rounded dark:text-gray-500">Sign in</button>
				<button class="self-center py-3 pr-4 rounded dark:text-gray-500">Sign up</button>
			</div>
			<button class="p-4 lg:hidden">
				<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="w-6 h-6 dark:text-gray-100">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
				</svg>
			</button>
		</div>
	</header>
</template>

<style>
    header{
        background-color: #1b1b1b;
    }
</style>