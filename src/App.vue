<template>
  <div class="navbar" style="background: blueviolet;">
    <NavbarComponent></NavbarComponent>
  </div>
  <div class="header">
    <HeaderComponet></HeaderComponet>
  </div>
  <div class="main">
    <MainComponentVue></MainComponentVue>
  </div>

  <div class="produk">
    <ProdukComponent></ProdukComponent>
  </div>

  <div class="container mx-auto px-4">
    <hr />
  </div>

  <div class="team">
    <br />
    <br />
    <TeamComponent></TeamComponent>
  </div>

  <div class="kontak">
    <br />
    <br />
    <KontakComponent></KontakComponent>
  </div>
  <div class="footer">
    <br />
    <br />
    <FooterComponent></FooterComponent>
  </div>
</template>
<script>
import NavbarComponent from './components/NavbarComponent.vue'
import HeaderComponet from './components/HeaderComponent.vue'
import MainComponentVue from './components/MainComponent.vue'
import TeamComponent from './components/TeamComponent.vue'
import KontakComponent from './components/KontakComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import ProdukComponent from './components/ProdukComponent.vue'
export default {
  components: {
    NavbarComponent,
    HeaderComponet,
    MainComponentVue,
    TeamComponent,
    KontakComponent,
    FooterComponent,
    ProdukComponent,
  },
}
</script>
