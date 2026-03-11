<template>

<nav class="nav">

<h2 class="logo">Kholiwe</h2>

<ul>

<li><router-link to="/">Home</router-link></li>
<li><router-link to="/about">About</router-link></li>
<li><router-link to="/skills">Skills</router-link></li>
<li><router-link to="/projects">Projects</router-link></li>
<li><router-link to="/contact">Contact</router-link></li>

</ul>

</nav>

</template>

<style scoped>

.nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#1e293b;
color:white;
}

.logo{
color:#3b82f6;
}

ul{
display:flex;
gap:25px;
list-style:none;
}

a{
text-decoration:none;
color:white;
font-weight:500;
}

a:hover{
color:#3b82f6;
}

</style>