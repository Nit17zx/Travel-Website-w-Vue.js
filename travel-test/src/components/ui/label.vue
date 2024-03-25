<template>
    <label :for="htmlFor" class="text-sm">
      <slot></slot>
    </label>
  </template>
  
  <script>
  export default {
    props: {
      htmlFor: {
        type: String,
        required: true
      }
    }
  }
  </script>
  