<template>
    <div>
      <h1>{{ greeting }}</h1>

      <button v-bind:title="buttonTitle" @click="changeGreeting">
        Click để thay đổi
      </button>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        greeting: 'Xin chào bạn!', // Lời chào mặc định
        buttonTitle: 'Nhấn để thay đổi lời chào' // Nội dung tooltip mặc định
      };
    },
    methods: {
      changeGreeting() {
        this.greeting = 'Hello, World!'; // Cập nhật lời chào
        this.buttonTitle = 'Lời chào mới đã được cập nhật'; // Cập nhật tooltip
      }
    }
  };
  </script>
  
  <style scoped>
  button {
    padding: 10px 20px;
    background-color: #42b883;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
  }
  
  button:hover {
    background-color: #38a172;
  }
  </style>
  