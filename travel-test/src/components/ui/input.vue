<template>
    <input
      v-bind="$attrs"
      v-on="$listeners"
      :type="type"
      :placeholder="placeholder"
      class="w-full px-3 py-2 border border-gray-300 rounded-md shadow-sm focus:outline-none focus:border-blue-500 focus:ring focus:ring-blue-500 focus:ring-opacity-50"
    />
  </template>
  
  <script>
  export default {
    props: {
      type: {
        type: String,
        default: "text" // Default input type if not specified
      },
      placeholder: {
        type: String,
        default: ""
      }
    }
  }
  </script>
  