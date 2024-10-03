<template>
  <NavbarComponent />
  <section class="w-full h-[18.75rem]">
    <div class="w-full h-full content-center">
      <SearchComponent />
    </div>
  </section>
</template>

<script setup>
import { FwbDropdown, FwbListGroup, FwbListGroupItem } from 'flowbite-vue'
import NavbarComponent from './components/NavbarComponent.vue'
import SearchComponent from './components/SearchComponent.vue'
</script>