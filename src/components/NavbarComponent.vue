<template>
    <fwb-navbar class="main-nav">
        <template #logo>
            <fwb-navbar-logo alt="Flowbite logo" image-url="https://upload.wikimedia.org/wikipedia/commons/f/f1/Vue.png" link="#">
                <span class="text-[#213547]">
                    Flowbite
                </span>
            </fwb-navbar-logo>
        </template>
        <template #default="{ isShowMenu }">
            <fwb-navbar-collapse :is-show-menu="isShowMenu">
                <fwb-navbar-link is-active link="#">
                    Home
                </fwb-navbar-link>
                <fwb-navbar-link link="#">
                    Services
                </fwb-navbar-link>
                <fwb-navbar-link link="#">
                    Pricing
                </fwb-navbar-link>
                <fwb-navbar-link link="#">
                    Contact
                </fwb-navbar-link>
            </fwb-navbar-collapse>
        </template>
    </fwb-navbar>
</template>

<script setup>
import {
    FwbNavbar,
    FwbNavbarCollapse,
    FwbNavbarLink,
    FwbNavbarLogo,
} from 'flowbite-vue'
</script>

<script>
export default {
    name: 'NavbarComponent',
}
</script>

<style scoped>
    .main-nav {
        background-color: transparent !important;
    }
</style>