<script setup>
import Navbar from '@/components/NavComponent.vue'
import Hero from '@/views/HeroView.vue'
import Service from '@/views/ServiceView.vue'
import Footer from '@/components/FooterComponent.vue'
import Contact from '@/views/ContactView.vue'
</script>

<template>
    <Navbar/>

    <section class="hero" id="Hero">
        <Hero/>
    </section>

    <section class="main_container" id="Service">
        <Service/>
    </section>
    
    <section class="main_container" id="Contact">
        <Contact/>
    </section>

        <Footer/>
</template>
