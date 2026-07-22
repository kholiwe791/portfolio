<template>

<section class="about">

<div class="about-container">

<div class="about-text">

<h1>About Me</h1>

<p>
Hello! I'm <b>Kholiwe Faith Mafenuka</b>, an ICT in Applications Development student
passionate about software development and technology.
</p>

<p>
I enjoy building web applications, database systems,
and software solutions that solve real-world problems.
</p>

<p>
My interests include web development, system design,
and creating user-friendly digital solutions.
</p>

</div>

<div class="about-image">
<img src="/Port1.jpeg" alt="profile">
</div>

</div>

</section>

</template>

<style scoped>

.about{
padding:80px 10%;
background:linear-gradient(135deg,#f1f5f9,#e2e8f0);
}

.about-container{
display:flex;
gap:60px;
align-items:center;
justify-content:center;
}

.about-text{
max-width:500px;
}

h1{
color:#1e3a8a;
margin-bottom:20px;
}

.about-image img{
border-radius:20px;
width:280px;
height:280px;
object-fit:cover;
display:block;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
}

</style>