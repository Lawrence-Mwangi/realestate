<script setup>
import { ref } from 'vue';
import { useRouter } from 'vue-router';

const isResponsive = ref(false);
const router = useRouter();

const toggleMenu = () => {
  isResponsive.value = !isResponsive.value;
};

const navigate = (sectionId) => {
  if (sectionId === 'home' || sectionId === 'about' || sectionId === 'service' || sectionId === 'houses'  || sectionId ==='Contact') {
    router.push({ name: sectionId });
    isResponsive.value = false; 
  }
};

</script>


<template>
    <div class="nav_container">
        <div class="logo">
            <a href="#Home">
                <img src="../assets/images/house1.jpg" width="40px" height="40px" alt="Logo">
                <router-link :to="{ name:'home' }">LawNetEstate</router-link>
            </a>
        </div>

        <div class="nav_links"  :class="{ 'responsive': isResponsive }">
            <ul :class="{ 'show': isResponsive }">
                <li>
                    <router-link :to="{ name:'home' }"  @click="navigate('home')">Home</router-link>
                    <router-link :to="{ name:'about' }"  @click="navigate('about')">About</router-link>
                    <router-link :to="{ name:'houses' }"  @click="navigate('houses')">Houses</router-link>
                    <a href="#Service"  @click="toggleMenu">Services</a>
                    <a href="#Contact"  @click="toggleMenu">Contact</a>
                </li>
            </ul>
            
            <div class="burger"  @click="toggleMenu" :class="{ 'active': isResponsive }">
                <span></span>
                <span></span>
                <span></span>
            </div> 
        </div>
    </div>
</template>