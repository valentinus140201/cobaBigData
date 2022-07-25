<template>
  <div class="relative">
    <img src="https://images.pexels.com/photos/3747463/pexels-photo-3747463.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260" class="absolute inset-0 object-cover w-full h-full" alt="" />
    <div class="relative bg-gray-900 bg-opacity-75">
      <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
        <div class="flex flex-col items-center justify-between xl:flex-row">
          <div class="w-full max-w-xl mb-12 xl:mb-0 xl:pr-16 xl:w-7/12">
            <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-white sm:text-4xl sm:leading-none">
              The quick, brown fox <br class="hidden md:block" />
              jumps over a <span class="text-teal-accent-400">lazy dog</span>
            </h2>
            <p class="max-w-xl mb-4 text-base text-gray-400 md:text-lg">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudan, totam rem aperiam, eaque ipsa quae.
            </p>
            <a href="#" aria-label="" class="inline-flex items-center font-semibold tracking-wider transition-colors duration-200 text-teal-accent-400 hover:text-teal-accent-700">
              Learn more
              <svg class="inline-block w-3 ml-2" fill="currentColor" viewBox="0 0 12 12">
                <path d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"></path>
              </svg>
            </a>
          </div>
          <div class="w-full max-w-xl xl:px-8 xl:w-5/12">
            <div class="bg-black rounded shadow-2xl p-7 sm:p-10">
              <h3 class="mb-4 text-xl font-bold sm:text-center sm:mb-6 sm:text-4xl text-white">
                Sign up for free
              </h3>
              <form>
                <div class="mb-1 sm:mb-2">
                  <input
                    placeholder="Email"
                    required=""
                    type="text"
                    class="flex-grow w-full h-12 px-4 mb-2 transition duration-200 bg-black border border-gray-300 rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
                    id="email"
                    name="email"
                  />
                </div>
                <div class="mb-1 sm:mb-2">
                  <input
                    placeholder="Username (6+ characters)"
                    required=""
                    type="text"
                    class="flex-grow w-full h-12 px-4 mb-2 transition duration-200 bg-black border border-white rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
                    id="userName"
                    name="userName"
                  />
                </div>
                <div class="mb-1 sm:mb-2">
                  <input
                    placeholder="Password (6+ characters)"
                    required=""
                    type="password"
                    class="flex-grow w-full h-12 px-4 mb-2 transition duration-200 bg-black border border-white rounded shadow-sm appearance-none focus:border-deep-purple-accent-400 focus:outline-none focus:shadow-outline"
                    id="password"
                    name="password"
                  />
                </div>
                <div class="mt-4 mb-2 sm:mb-4 grid grid-cols-2">
                  <button
                    type="submit"
                    class="padding-button-signup px-12 h-12 font-bold tracking-wide text-gray-300 bg-gray-600 transition duration-200 rounded shadow-md focus:shadow-outline focus:outline-none">
                    Sign Up
                  </button>
                    <div class="self-center">
                        Or
                        <router-link to="/signin" class="py-3 pr-4 pl-2 rounded dark:text-orange-400 hover:underline">Log in</router-link>
                    </div>
                </div>
                <p class="text-xs text-gray-600 sm:text-sm">
                  We respect your privacy. Unsubscribe at any time.
                </p>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>