<template>
  <section class="projects">
    <h1>My Projects</h1>

    <div class="projects-grid">

      <div class="project-card">
        <h3>Student Digital Card System</h3>
        <p>A web application that allows students to apply for and manage digital ID cards with secure validation.</p>
      </div>

      <div class="project-card">
        <h3>Payroll Application</h3>
        <p>A Java-based system designed to manage employee records, salaries, and payroll processing.</p>
      </div>

      <div class="project-card">
        <h3>Nanny Service System</h3>
        <p>A booking and management platform for nanny services, allowing clients to request and schedule childcare assistance.</p>
      </div>

      <div class="project-card">
        <h3>SQL Database System</h3>
        <p>An advanced database project using SQL with triggers, procedures, functions, and data management features.</p>
      </div>

      <div class="project-card">
        <h3>Global Grapes Market Project</h3>
        <p>A strategic export plan focused on supplying premium grapes to international markets with sustainable farming and logistics planning.</p>
      </div>

      <div class="project-card">
        <h3>Car Accessories Online Store</h3>
        <p>An e-commerce concept for selling car accessories online, focusing on product management and customer purchasing experience.</p>
      </div>

      <div class="project-card">
        <h3>E.M.E.L.D.T Counselling App</h3>
        <p>A counselling platform that provides users with different mental health sessions at various prices to make support more accessible.</p>
      </div>

    </div>
  </section>
</template>

<style scoped>
.projects {
  padding: 80px 10%;
  text-align: center;
  background: #f8fafc;
  font-family: 'Poppins', sans-serif;
}

h1 {
  color: #1e3a8a; /* darker blue for better contrast */
  margin-bottom: 50px;
  font-size: 2.8rem;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 30px;
}

.project-card {
  background: #ffffff;
  padding: 30px 20px;
  border-radius: 16px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
  transition: all 0.3s ease;
  cursor: pointer;
  text-align: left;
}

.project-card h3 {
  color: #1e40af;
  margin-bottom: 15px;
  font-size: 1.4rem;
}

.project-card p {
  color: #475569;
  line-height: 1.6;
}

.project-card:hover {
  transform: translateY(-8px) scale(1.02);
  border-top: 4px solid #3b82f6;
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.12);
}

@media (max-width: 600px) {
  h1 {
    font-size: 2rem;
  }

  .project-card {
    padding: 20px;
  }
}
</style>