<template>
  <section class="hero">

    <div class="hero-text">

      <h1>Hello, I'm Kholiwe 👋</h1>

      <h2>Information Systems & Software Developer</h2>

      <p>
        I build modern web applications, database systems, 
        and software solutions that solve real-world problems.
      </p>

      <div class="buttons">

        <router-link to="/projects">
          <button class="primary">View Projects</button>
        </router-link>

        <router-link to="/contact">
          <button class="secondary">Contact Me</button>
        </router-link>

        <a href="/Kholiwe_Mafenuka_CV.pdf" download>
          <button class="cv">Download CV</button>
        </a>

      </div>

      <div class="socials">

      <a href="https://github.com/kholiwe791" target="_blank">GitHub</a>

      <a href="https://www.linkedin.com/in/kholiwe-mafenuka-849177254/overlay/about-this-profile/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3B7FWAeVUnSeabBL0Kv8ONug%3D%3D" target="_blank">LinkedIn</a>

      <a href="mailto:kholiwemafenuka791@gmail.com">Email</a>

      </div>

    </div>

    <div class="hero-image">
      <img src="https://via.placeholder.com/400" alt="developer">
    </div>

  </section>
</template>

<style scoped>

.hero{
display:flex;
align-items:center;
justify-content:space-between;
padding:80px 10%;
background:linear-gradient(135deg,#f1f5f9,#e2e8f0);
min-height:80vh;
}

.hero-text{
max-width:500px;
}

h1{
font-size:48px;
color:#0f172a;
}

h2{
color:#3b82f6;
margin-top:10px;
}

p{
margin-top:15px;
color:#64748b;
line-height:1.6;
}

.buttons{
margin-top:25px;
display:flex;
gap:15px;
}

.primary{
background:#3b82f6;
color:white;
padding:12px 25px;
border:none;
border-radius:8px;
cursor:pointer;
}

.primary:hover{
background:#2563eb;
}

.secondary{
background:white;
color:#1e293b;
padding:12px 25px;
border:2px solid #3b82f6;
border-radius:8px;
cursor:pointer;
}

.secondary:hover{
background:#3b82f6;
color:white;
}

.hero-image img{
border-radius:20px;
width:350px;
box-shadow:0 10px 30px rgba(0,0,0,0.1);
}

.cv{
background:#1e293b;
color:white;
padding:12px 25px;
border:none;
border-radius:8px;
cursor:pointer;
}

.cv:hover{
background:#0f172a;
}

.socials{
margin-top:20px;
display:flex;
gap:20px;
}

.socials a{
text-decoration:none;
color:#3b82f6;
font-weight:500;
}

.socials a:hover{
text-decoration:underline;
}

</style>