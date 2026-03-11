<template>

<section class="contact">

<h1>Contact Me</h1>

<p class="subtitle">
Feel free to reach out for collaborations, projects, or opportunities.
</p>

<div class="contact-container">

<div class="contact-card">
<h3>📧 Email</h3>
<p>kholiwemafenuka791@gmail.com</p>
</div>

<div class="contact-card">
<h3>📱 Phone</h3>
<p>+27 81 505 2488</p>
</div>

<div class="contact-card">
<h3>💼 LinkedIn</h3>
<p>linkedin.com/in/kholiwe-mafenuka</p>
</div>



</div>

</section>

</template>

<style scoped>

.contact{
padding:80px 10%;
text-align:center;
background:#f8fafc;
}

h1{
color:#1e3a8a;
margin-bottom:10px;
font-size:2.5rem;
}

.subtitle{
color:#64748b;
margin-bottom:40px;
}

.contact-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
max-width:800px;
margin:auto;
}

.contact-card{
background:white;
padding:25px;
border-radius:12px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
transition:0.3s;
}

.contact-card:hover{
transform:translateY(-6px);
border-top:4px solid #3b82f6;
}

.contact-card h3{
color:#3b82f6;
margin-bottom:10px;
}

.contact-card p{
color:#475569;
}

</style>