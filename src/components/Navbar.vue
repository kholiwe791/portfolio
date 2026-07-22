<template>

<nav class="nav">

<h2 class="logo">&lt;Code by Kholiwe/&gt;</h2>

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

body{
padding-top:80px;
}

.nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#1e293b;
color:white;

position:fixed;
top:0;
left:0;
width:100%;
z-index:1000;
box-sizing:border-box;
}

:deep(.router-link-exact-active){
color:#3b82f6;
border-bottom:2px solid #3b82f6;
padding-bottom:4px;
}

.logo{
color:#3b82f6;
font-family: 'JetBrains Mono', monospace;
font-size: 1.2rem;
font-weight: 600;
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