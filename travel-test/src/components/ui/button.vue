<template>
    <button :class="[variantClasses]">
      <slot></slot>
    </button>
  </template>
  
  <script>
  export default {
    props: {
      variant: {
        type: String,
        default: "primary" // Default variant if not specified
      }
    },
    computed: {
      variantClasses() {
        return {
          // Add classes based on the variant prop
          'bg-blue-500 text-white': this.variant === 'primary',
          'bg-gray-500 text-white': this.variant === 'secondary',
          // Add more variants as needed
        }
      }
    }
  }
  </script>
  