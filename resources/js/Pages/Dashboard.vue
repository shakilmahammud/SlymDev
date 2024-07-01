<template>
    <div style="background: linear-gradient(45deg, #EAECF9, #FDFDFF, #EBE7F6);
">
    <Header />
    <div class="flex h-screen gap-2 ">
      <Sidebar />
      <div class="flex flex-col flex-1  bg-white shadow-lg">
        <MainContent />
      </div>
    </div>
</div>
  </template>

  <script setup>
  import Sidebar from '../components/Sidebar.vue';
  import Header from '../components/Header.vue';
  import MainContent from '../components/Content.vue';
 </script>
