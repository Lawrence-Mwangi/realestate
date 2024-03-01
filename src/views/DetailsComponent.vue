<script setup>
import Navbar from '@/components/NavComponent.vue'
import Footer from'@/components/FooterComponent.vue'
</script>

<template>
    <Navbar/>

    <section class="main_container" id="details">
        <h1 class="title">House Details</h1>
        <div class="details_container">
            <h3>Spacious Five Bedroom House</h3>
            <div class="house_images">
                <div class="details_image">
                    <img src="../assets/images/house.jpg" alt="House Image">
                </div>
                <p>The house is located in Kilimani 5 minutes off the main road, it's a 5 bedroom house with
                    following:-
                </p>
                <ul >
                    <li>Solar water heater system with Ample storage Tank</li>
                    <li>Large capacity standby generator</li>
                    <li>Fitted kiteen</li>
                    <li>Two parking slot per unit</li>
                    <li>All bedroom are En suite</li>
                    <li>Provisioon of internet and connectivity</li>
                    <li>CCTV suurvillance system</li>
                    <li>Spcious children playing area</li>
                    <li>Landspace Garderns</li>
                    <li>Swimming pool</li>
                    <li>Secure Access contorl System</li>
                </ul>
            </div>
            <div class="buttons">
                <div class="btn">
                    <button type="submit">Inquiries</button>
                </div>
                <div class="btn">
                    <button type="submit">Buy Now</button>
                </div>
            </div>
        </div>
    </section>
    <Footer/>
</template>