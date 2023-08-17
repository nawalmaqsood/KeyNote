<template>
    <div>
      <section class="py-16">
        <div class="blur-background"></div>
        <div class="container mx-auto">
          <div class="text-white text-lg mb-8">
            <div class="mx-auto px-6">
              <h2 class="mt-4 font-semibold text-5xl text-blue-600 max-w-prose text-left">
                Our three day schedule is jam-packed with brilliant, creative, evil geniuses.
              </h2>
              <p class="mt-4 font-bold text-blue-800 text-lg max-w-prose text-left">
                The worst people in our industry giving the best talks you've ever seen.
                Nothing will be recorded and every attendee has to sign an NDA to watch the talks.
              </p>
            </div>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-left px-6">
            <div class="mt-4">
              <p class="text-blue-800 text-lg font-bold">April 4</p>
              <p class="mt-2 text-blue-600 text-lg">The first day of the conference is focused on dark patterns for ecommerce.</p>
            </div>
            <div class="mt-4">
              <p class="text-blue-800 text-lg font-bold">April 5</p>
              <p class="mt-2 text-blue-800 text-xl">Next we spend the day talking about deceiving people with technology.</p>
            </div>
            <div class="mt-4">
              <p class="text-blue-800 text-lg font-bold">April 6</p>
              <p class="mt-2 text-blue-800 text-xl">We close out the event previewing new techniques that are still in development.</p>
            </div>
          </div>
          <br>
        </div>
      </section>
      <br><br>
      <div class="mx-auto text-center bg-white">
        <h2 class="mt-8 mb-4 font-semibold text-4xl text-blue-800 max-w-prose">
          Current sponsorships for our workshops and speakers.
        </h2>
        <div class="grid grid-cols-3 gap-1 text-center px-4 mx-auto">
          <div class="flex flex-col items-center">
            <img src='../assets/laravel.avif' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Transistor</p>
          </div>
          <div class="flex flex-col items-center">
            <img src='../assets/tuple.png' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Tuple</p>
          </div>
          <div class="flex flex-col items-center">
            <img src='../assets/static.png' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Static-Kit</p>
          </div>
          <div class="flex flex-col items-center">
            <img src='../assets/trans.png' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Laravel</p>
          </div>
          <div class="flex flex-col items-center">
            <img src='../assets/stat.png' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Statamic</p>
          </div>
          <div class="flex flex-col items-center">
            <img src='../assets/laravel.avif' class="h-16 mb-2" />
            <p class="text-gray-700 text-lg font-bold">Mirage</p>
          </div>
        </div>
      </div>
      <footer class="relative bg-white">
        <div class="container mx-auto flex justify-between items-center py-9 px-4">
          <div class="flex items-center">
            <img src='../assets/logo.jpg' class="h-10" />
            <div class="ml-2">
              <p class="text-black text-xl font-bold">DeceptiConf</p>
            </div>
          </div>
          <p class="text-gray-600 text-sm">
            Copyright © 2023 DeceptiConf, LLC. All rights reserved.
          </p>
        </div>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: 'FooterView',
  };
  </script>
  
  <style>
  /* Add your styles here */
  </style>
  