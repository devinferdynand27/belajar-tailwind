<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar class="bg">
      <template #logo>
        <NavbarLogo image-url="https://coolbackgrounds.io/images/backgrounds/white/pure-white-background-85a2a7fd.jpg">
          PotoForlio Devin Ferdynand
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Beranda</NavbarLink>
          <NavbarLink>Tentang Saya</NavbarLink>
          <NavbarLink>Galeri</NavbarLink>
          <NavbarLink>Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
      <template #right-side>
        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Get started</button>
      </template>
    </Navbar>
</template> 