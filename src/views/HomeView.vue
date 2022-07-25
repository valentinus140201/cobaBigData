<template>
  <div class="relative bg-deep-purple-accent-400">
    <div class="absolute inset-x-0 bottom-0">
      <svg viewBox="0 0 224 12" fill="currentColor" class="w-full -mb-1 text-white" preserveAspectRatio="none">
        <path d="M0,0 C48.8902582,6.27314026 86.2235915,9.40971039 112,9.40971039 C137.776408,9.40971039 175.109742,6.27314026 224,0 L224,12.0441132 L0,12.0441132 L0,0 Z"></path>
      </svg>
    </div>
    <div class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20">
      <div class="relative max-w-2xl sm:mx-auto sm:max-w-xl md:max-w-2xl sm:text-center">
        <h2 class="mb-6 font-sans text-3xl font-bold tracking-tight text-white sm:text-4xl sm:leading-none">
          The quick, brown fox<br class="hidden md:block" />
          jumps over a
          <span class="relative inline-block px-2">
            <span class="relative beda-warna">lazy dog</span>
          </span>
        </h2>
        <p class="mb-6 text-base text-indigo-100 md:text-lg">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae. explicabo. Sed ut perspiciatis unde omnis.
        </p>
        <form class="flex flex-col items-center w-full mb-4 md:flex-row md:px-16">
          <input placeholder="Kode Soal" required="" type="text" class="flex-grow w-full h-12 px-4 mb-3 text-black transition duration-200 border-2 border-transparent rounded appearance-none md:mr-2 md:mb-0 bg-deep-purple-900 focus:border-teal-accent-700 focus:outline-none focus:shadow-outline"/>
          <a href="#" class="beda-warna inline-flex items-center justify-center w-full h-12 px-6 font-semibold tracking-wide transition duration-200 rounded shadow-md md:w-auto hover:text-orange-400 bg-gray-700 hover:bg-gray-400 focus:shadow-outline focus:outline-none"> Confirm </a>
        </form>
        <p class="max-w-md mb-10 text-xs tracking-wide text-indigo-100 sm:text-sm sm:mx-auto md:mb-16">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque.
        </p>
      </div>
    </div>
  </div>
</template>

<style>
    body{
        background-color: black;
    }

    .beda-warna{
        color:#FF9900;
    }
</style>
