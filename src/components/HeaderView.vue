<template>
    <div>
      <header class="relative" >
        <div class="container mx-auto flex justify-between items-center py-9 px-4">
          <div class="flex items-center">
            <img src='../assets/logo.jpg'  class="h-10" />
            <div class="ml-2">
              <p class="text-black text-xl font-bold">DeceptiConf</p>
            </div>
          </div>
          <div class="flex items-center">
            <p class="text-blue-800 text-sm mr-4 md:mr-0 font-semibold">04-06 of April, 2022  * Los Angeles, CA</p>
        </div>
            <button class="bg-blue-500 hover:bg-blue-600 text-white py-2 px-6 rounded-full font-bold">Get Your Tickets</button>
        </div>
      </header>
      <section class="py-16 text-center">
        <div class="container mx-auto">
          <div class="blur-background"></div>
          <div class="text-white text-lg mb-8">
            <div class="mx-auto">
              <h2 class="mt-4 font-bold text-8xl text-blue-800 max-w-prose mx-auto">
                A design conference for the dark side.
              </h2>
              <p class="mt-4 font-semibold text-blue-600 text-lg max-w-prose mx-auto">
                The next generation of web users are tech-savvy and suspicious.
                They know how to use dev tools, they can detect a phishing scam from a mile away,
                and they certainly aren't accepting any checks from Western Union.
              </p>
              <p class="mt-4 font-semibold text-blue-600 text-lg max-w-prose mx-auto">
                At DeceptiConf you'll learn about the latest dark patterns being developed
                to trick even the smartest visitors, and you'll learn how to deploy them
                without ever being detected.
              </p>
            </div>
          </div>
          <br>
          <div class="grid grid-cols-4 gap-4 text-center">
            <div>
              <p class="text-blue-800 text-lg ">Speakers</p>
              <p class="mt-2 text-blue-800 text-xl font-bold">18</p>
            </div>
            <div>
              <p class="text-blue-800 text-lg">People Attending</p>
              <p class="mt-2 text-blue-800 text-xl font-bold">2,091</p>
            </div>
            <div>
              <p class="text-blue-800 text-lg">Venue</p>
              <p class="mt-2 text-blue-800 text-xl font-bold">Staples Center</p>
            </div>
            <div>
              <p class="text-blue-800 text-lg">Location</p>
              <p class="mt-2 text-blue-800 text-xl font-bold">Los Angeles</p>
            </div>
          </div>
        </div>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HeaderView'
  }
  </script>
  
  <style>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  </style>
  
  