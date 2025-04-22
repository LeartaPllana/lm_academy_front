<script setup>
import { computed } from 'vue'
const currentYear = computed(() => new Date().getFullYear())
</script>

<template>
  <!-- footer -->
  <footer>
    <div class="footer flex justify-between items-center border-t-textPrimary border-t-4 py-4">
      <nav class="flex gap-2 text-xl">
        <router-link :to="{ name: 'PrivacyPolicy' }" class="nav-link">Privacy Policy</router-link>
        <span class="border-l-2 border-black mx-2"></span>
        <router-link :to="{ name: 'TermsOfService' }" class="nav-link"
          >Terms of Service</router-link
        >
        <span class="border-l-2 border-black mx-2"></span>
        <router-link :to="{ name: 'ContactPage' }" class="nav-link">Contact</router-link>
      </nav>
      <p>Copyright &copy; {{ currentYear }}</p>
    </div>
  </footer>
  <!-- end footer -->
</template>

<style scoped></style>
