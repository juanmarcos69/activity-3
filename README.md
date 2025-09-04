<!--
README

HomeView.vue
------------
This is the main home view for the application.
It renders the <TheWelcome /> component inside a <main> tag.

Usage:
- This view is displayed when users visit the root route ('/').
- To customize the welcome message, edit TheWelcome.vue.

Author: [Your Name]
Date: [Today's Date]
-->

<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
