<script setup>
  import { defineProps } from 'vue';

  defineProps({
    Title: {
      type: String,
      default: 'Become a Vue Dev'
    },
    Subtitle: {
      type: String,
      default: 'Find the Vue job that fits your skills and needs'
    }
  });
</script>

<template>
  <section class="bg-green-600 py-16 mb-4">
      <div
        class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col items-center"
      >
        <div class="text-center">
          <h1
            class="text-4xl font-extrabold text-white sm:text-5xl md:text-6xl"
          >
            {{ Title }}
          </h1>
          <p class="my-4 text-xl text-white">
            {{ Subtitle }}
          </p>
        </div>
      </div>
    </section>
</template>