<template>
  <div class="home">
    <header-shayna />
    <hero-shayna />
    <woman-shayna />
    <insta-shayna />
    <logo-shayna />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomanShayna from '@/components/WomanShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import LogoShayna from '@/components/Logo.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    LogoShayna,
    Footer
  }
}
</script>
