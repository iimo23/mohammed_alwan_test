<!-- src/App.vue -->
<template>
  <div>
    <login />
    <notification />
    <testimonial />
    <reports />
    
  </div>
  </template>
  
  
  <script>
  import login from './components/login.vue';
  import notification from './components/notification.vue';
  import testimonial from './components/testimonial.vue';
  import reports from './components/reports.vue';
  
  
  
  export default {
    name: 'App',
    components: {
      login,
      notification,
      testimonial,
      reports
      
    },
    methods: {
      togglePasswordVisibility() {
        this.isPasswordVisible = !this.isPasswordVisible;
      }
    }
  
  };
  
  </script>
  
  <style >
  
  </style>
  