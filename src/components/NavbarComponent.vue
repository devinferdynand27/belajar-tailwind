<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
  <Navbar class="bg">
    <template #logo>
      <NavbarLogo
        image-url="https://coolbackgrounds.io/images/backgrounds/white/pure-white-background-85a2a7fd.jpg"
      >
        Devin Ferdynand
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
      <button
        style="background: #bf00ff;"
        type="button"
        class="text-white bg-puply-700 hover:bg-puply-800 focus:ring-4 focus:outline-none focus:ring-puply-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-puply-600 dark:hover:bg-puply-700 dark:focus:ring-puply-800"
      >
        Profil saya
      </button>
    </template>
  </Navbar>
</template>
