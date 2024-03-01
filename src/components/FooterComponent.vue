<script setup></script>

<template>
    <div class="footer_container">

        <div class="footer_content">
            <div class="logo">
                <img src="../assets/images/house.jpg" width="50px" height="50px" alt="Logo Image">
            </div>
            <h2>LawNetEstate Property Ltd</h2>
            <p>Uzuri Plaza, second floor, room 232</p>
            <p>Kiambu town, Kenya</p>
        </div>
        <div class="footer_links">
            <h4>Links</h4>
            <router-link :to="{ name:'home' }">Home</router-link>
            <router-link :to="{ name:'about' }">About</router-link>
            <router-link :to="{ name:'houses' }">Houses</router-link>
            <a href="#Service">Services</a>
            <a href="#Contact">Contact</a>
        </div>
        <div class="social_media">
            <h4>Social Media</h4>
            <div class="icon_container">
                <div class="icons">
                    <a href="https://github.com/lawrencemwangi" target="_blank">
                        <img src="../assets/images/facebook.png" alt="Facebook icon">
                    </a>
                </div>
                <div class="icons">
                    <a href="https://www.instagram.com/lawrenzo.mwangi" target="_blank">
                        <img src="../assets/images/instagram.png" alt="Instagram icon">
                    </a>               
                </div>
                <div class="icons">
                    <a href="#" target="_blank">
                        <img src="../assets/images/twitter.png" alt="Twitter icon">
                    </a>
                </div>
                <div class="icons">
                    <a href="https://wa.me/254799509242?text='Hello Developer Lawrence'" target="_blank">
                        <img src="../assets/images/whatsapp.png" alt="Facebook icon">
                    </a>
                </div>
            </div>
        </div>
    </div>
    <hr>
    <div class="footer_copyrigth">
        <p>&copy; 2024 | LawNetEstate Property Ltd | All Rights Reserved</p>
    </div>
</template>