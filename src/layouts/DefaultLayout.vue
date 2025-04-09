<script setup>
import HeaderDefault from '@/components/default/general/HeaderDefault.vue'
import FooterDefault from '@/components/default/general/FooterDefault.vue'
</script>

<template>
  <main class="px-4">
    <!-- header -->
    <HeaderDefault />
    <!-- end header -->
    <!-- content -->
    <div class="wrapper min-h-[80vh] ">
      <router-view />
    </div>
    <!-- end content -->
    <!-- footer -->
    <FooterDefault />
    <!-- end footer -->
  </main>
</template>
