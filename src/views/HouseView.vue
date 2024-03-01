<script setup>
import Navbar from '@/components/NavComponent.vue'
import Footer from '@/components/FooterComponent.vue'
import House from '@/components/HouseComponent.vue'
</script>

<template>
    <Navbar/>
     
    <section class="main_container" id="House">
        <h1 class="title">Houses</h1>

        <div class="house_container">
            <House/>
            <House/>
            <House/>
            <House/>
            <House/>
            <House/>
            <House/>
            <House/>
        </div>
    </section>

    <Footer/>

</template>