<template>
  
    <div class="arrow-button">
      👇🏾Order yours Now 
      <a href="https://www.amazon.com" target="_blank" class="arrow-link">
        <div class="arrow-icon"></div>
      </a>
    </div>
  </template>
  <script>
  export default {
    name: 'ArrowComponent',
    props: {},
    components: {
      
    },
  };

 </script>
  
  <style scoped>
  .arrow-button {
    position: fixed;
    bottom: 20px;
    right: 20px;
  }
  
  .arrow-link {
    display: block;
    width: 50px;
    height: 50px;
    background-color: #3498db; /* Set your desired button color */
    border-radius: 50%;
    overflow: hidden;
    position: relative;
    animation: breathingAnimation 2s infinite alternate; /* Adjust animation duration as needed */
    transition: background-color 0.3s ease; /* Smooth color change on hover */
  }
  
  .arrow-link:hover {
    background-color: #2980b9; /* Change the color on hover */
  }
  
  .arrow-icon {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border: solid #fff;
    border-width: 0 3px 3px 0;
    display: inline-block;
    padding: 5px;
    transition: transform 0.3s ease; /* Smooth transform on hover */
  }
  
  .arrow-link:hover .arrow-icon {
    transform: translate(-50%, -50%) rotate(-45deg);
  }
  
  @keyframes breathingAnimation {
    0% {
      transform: scale(1);
    }
    100% {
      transform: scale(1.5);
    }
  }
  </style>
  