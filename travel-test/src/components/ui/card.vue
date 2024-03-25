<template>
    <div class="card">
      <div class="aspect-card overflow-hidden rounded-lg">
        <img
          :src="imageSrc"
          :alt="altText"
          class="object-cover object-center"
          :style="{ aspectRatio: aspectRatio, objectFit: 'cover' }"
        />
      </div>
      <div class="card-content">
        <h3 class="text-xl font-bold">{{ title }}</h3>
        <p class="text-sm text-gray-500 line-clamp-3">{{ description }}</p>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      imageSrc: {
        type: String,
        required: true
      },
      altText: {
        type: String,
        default: "Card Image"
      },
      aspectRatio: {
        type: String,
        default: "500/300"
      },
      title: {
        type: String,
        required: true
      },
      description: {
        type: String,
        required: true
      }
    }
  };
  </script>
  
  <style scoped>
  .card {
    /* Add your card styles here */
  }
  
  .card-content {
    padding: 1rem;
  }
  </style>
  