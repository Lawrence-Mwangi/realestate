<script setup></script>


<template>
    <div class="nav_container">
        <div class="logo">
            <a href="#Home">
                <img src="../assets/images/house1.jpg" width="40px" height="40px" alt="Logo">
                <h2>LawNetEstate</h2>
            </a>
        </div>

        <div class="nav_links">
            <li>
                <router-link :to="{ name:'home' }">Home</router-link>
                <router-link :to="{ name:'about' }">About</router-link>
                <router-link :to="{ name:'houses' }">Houses</router-link>
                <a href="#Service">Services</a>
                <a href="#Contact">Contact</a>
            </li>
            
            <div class="burger">
                <span></span>
                <span></span>
                <span></span>
            </div> 
        </div>
    </div>
</template>