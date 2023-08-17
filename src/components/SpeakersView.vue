<template>
  <section class="py-16">
    <div class="blur-background"></div>
    <div class="container mx-auto">
      <h2 class="text-4xl font-bold text-blue-600 mb-4 px-6">Speakers</h2>
      <p class="text-xl font-semibold text-blue-800 max-w-lg px-6">
        Learn from the experts on the cutting-edge of deception at the most sinister companies.
      </p>
      <br><br><br>
      <div class="grid grid-cols-1 gap-4 px-8">
        <div class="mt-4">
          <p class="text-blue-800 text-lg ">--> Opening Day</p>
          <p class="mt-2 text-blue-800 text-xl font-bold">April 4</p>
        </div>
        <div class="mt-4">
          <p class="text-blue-800 text-lg">--> Speakers & Workshops</p>
          <p class="mt-2 text-blue-800 text-xl font-bold">April 5</p>
        </div>
        <div class="mt-4">
          <p class="text-blue-800 text-lg">--> Interviews</p>
          <p class="mt-2 text-blue-800 text-xl font-bold">April 6</p>
        </div>
      </div>

      <br>

      <div class="grid grid-cols-3 gap-4 px-8">
        <div v-for="speaker in speakers" :key="speaker.id">
          <img :src="speaker.image" :alt="speaker.name" class="w-25 h-30 mx-auto mb-4 square-full" />
          <h3 class="text-lg font-semibold text-gray-900 mb-2">{{ speaker.name }}</h3>
          <p class="text-gray-600">{{ speaker.title }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'SpeakersView',
  data() {
    return {
      speakers: [
        {
          id: 1,
          name: 'Steven McHail',
          title: 'Designer at Globex Corporation',
          image: require('@/assets/steven.webp')
        },
        {
          id: 2,
          name: 'Jaquelin Isch',
          title: 'UX Design at InGen',
          image: require('@/assets/jaq.webp')
        },
        {
          id: 3,
          name: 'Dianne Guilianelli',
          title: 'General Manager at Initech',
          image: require('@/assets/dianne.webp')
        },
        {
          id: 4,
          name: 'Ronni Cantadore',
          title: 'Design Engineer at Weyland-Yutani',
          image: require('@/assets/ronni.webp')
        },
        {
          id: 5,
          name: 'Erhart Cockrin',
          title: 'Product Lead at Cyberdyne Systems',
          image: require('@/assets/erhart.webp')
        },
        {
          id: 6,
          name: 'Parker Johnson',
          title: 'UI Designer at MomCorp',
          image: require('@/assets/parker.webp')
        },
      ]
    };
  }
};
</script>

<style>
/* Add your styles here */
</style>
