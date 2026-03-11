<template>

<section class="skills">

<h1>My Skills</h1>

<div class="skills-grid">

<div class="card">
<h3>Frontend</h3>
<p>HTML, CSS, JavaScript, Vue.js, React</p>
</div>

<div class="card">
<h3>Backend</h3>
<p>Java, Node.js</p>
</div>

<div class="card">
<h3>Database</h3>
<p>SQL, MySQL, Database Design</p>
</div>

<div class="card">
<h3>Tools</h3>
<p>Git, GitHub, VS Code</p>
</div>

</div>

</section>

</template>

<style scoped>

.skills{
padding:80px 10%;
text-align:center;
}

h1{
color:#3b82f6;
margin-bottom:40px;
}

.skills-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:30px;
}

.card{
background:white;
padding:30px;
border-radius:12px;
box-shadow:0 8px 20px rgba(0,0,0,0.08);
transition:0.3s;
}

.card:hover{
transform:translateY(-6px);
border-top:4px solid #3b82f6;
}

</style>