<template>

<Navbar/>

<router-view/>

<Footer/>

</template>

<script>
import Navbar from "./components/Navbar.vue"
import Footer from "./components/Footer.vue"

export default{
components:{
Navbar,
Footer
}
}
</script>

<style>

body{
margin:0;
font-family:"Poppins", sans-serif;
background:#f1f5f9;
color:#1e293b;
}

</style>