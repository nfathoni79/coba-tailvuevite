<template>
  <div class="bg-gradient-to-br from-teal-500 to-blue-500">
    <div class="px-4 max-w-4xl mx-auto min-h-screen flex flex-col sm:px-8">
      <div class="sm:flex-1">
        <header class="py-4 sm:py-6 md:py-10">
          <a class="text-3xl font-bold" href="#">
            Logo
          </a>
        </header>

        <div class="flex flex-col justify-between text-rose-100 space-y-8 md:flex-row md:items-center md:space-x-8 md:space-y-0">
          <div class="space-y-6 md:space-y-8">
            <p class="text-xl">My name is Agus</p>
            <p class="font-medium text-3xl">
              I work at
              <a class="bg-rose-800 text-yellow-200 px-2 inline-block transform -rotate-1 hover:rotate-0" href="#">Something Labs</a>,
              where I create learning materials and look after the community.
            </p>
          </div>

          <div class="flex-shrink-0">
            <img class="w-40 transform -rotate-12 hover:rotate-0 transition md:w-52" src="https://simonswiss.com/img/new-avatar.png" alt="avatar">
          </div>
        </div>

        <div class="mt-8 sm:mt-16">
          <nav>
            <a class="px-2 mr-4 mt-4 bg-white inline-block text-2xl font-semibold text-rose-900 transform rotate-3 shadow-md hover:rotate-0 sm:mr-12 sm:text-xl sm:mt-0" href="#">Articles</a>
            <a class="px-2 mr-4 mt-4 bg-white inline-block text-2xl font-semibold text-rose-900 transform -rotate-3 shadow-md hover:rotate-0 sm:mr-12 sm:text-xl sm:mt-0" href="#">Talks</a>
          </nav>
        </div>

      </div>
      <footer class="py-8 text-white text-lg">
        <div class="">
          <p class="leading-9">
            Built with
            <a class="leading-6 px-2 pt-1 bg-white bg-opacity-25 transform -rotate-3 inline-block hover:rotate-0" href="#">Tailwind CSS</a>
          </p>
        </div>
      </footer>
    </div>
  </div>
</template>
