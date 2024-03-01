<script setup></script>

<template>
    <div class="home_container">
        <div class="image">
            <img src="../assets/images/resident.jpg" alt="House Photo">
        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
        <p>Price: <span>4.5M</span></p>
        <p>Location: <span>Kilimaini</span></p>

        <div class="link">
            <router-link :to="{ name:'details'}">Explore More</router-link>
        </div>
    </div>
</template>