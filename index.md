---
layout: default
---

<style>
  body {
    background-color: #1a1a1a;
    color: #e0e0e0;
  }
  
  .site-header {
    background-color: #2d2d2d;
    border-bottom: 2px solid #4a90e2;
  }
  
  .site-title, .site-nav .page-link {
    color: #4a90e2 !important;
  }
  
  .site-title:hover, .site-nav .page-link:hover {
    color: #7db4f0 !important;
  }
  
  h1, h2, h3, h4, h5, h6 {
    color: #4a90e2;
  }
  
  .project-section {
    margin: 3rem 0;
    padding: 2rem;
    border-radius: 8px;
  }
  
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin-top: 2rem;
  }
  
  .project-card {
    padding: 1.5rem;
    border-radius: 6px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(74, 144, 226, 0.3);
  }
  
  .project-card h3 {
    margin-top: 0;
    color: #4a90e2;
  }
  
  .project-link {
    display: inline-block;
    margin-top: 1rem;
    padding: 0.5rem 1rem;
    background-color: #4a90e2;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    transition: background-color 0.3s ease;
  }
  
  .project-link:hover {
    background-color: #7db4f0;
    color: white;
  }
  
  .intro-section {
    text-align: center;
    padding: 4rem 0;
    background: linear-gradient(135deg, #2d2d2d 0%, #1a1a1a 100%);
    margin: -2rem -2rem 3rem -2rem;
    border-radius: 0 0 15px 15px;
  }
  
  .intro-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    background: linear-gradient(45deg, #4a90e2, #7db4f0);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
  
  .intro-section p {
    font-size: 1.2rem;
    max-width: 600px;
    margin: 0 auto;
    line-height: 1.6;
  }
  
  .content-wrapper {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
  }
  
  a {
    color: #4a90e2;
  }
  
  a:hover {
    color: #7db4f0;
  }
  
  @media (max-width: 768px) {
    .intro-section h1 {
      font-size: 2rem;
    }
    
    .intro-section {
      padding: 2rem 0;
    }
    
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="content-wrapper">
  <div class="intro-section">
    <h1>dylan hudson</h1>
    <p>Data Scientist</p>
  </div>

  <div class="project-section">
    <h2>Projects</h2>

    <div class="project-grid">
      <div class="project-card">
        <h3>test</h3>
        <p>test</p>
        <a href="#" class="project-link">View</a>
      </div>
      

  </div>

  <div class="project-section">
    <h2>Connect</h2>
    <div style="text-align: left; margin-top: 2rem;">
      <a href="https://github.com/dylanhudson" class="project-link" style="margin: 0 1rem;">GitHub</a>
      <a href="mailto:dylan.hudson@gmail.com" class="project-link" style="margin: 0 1rem;">Email</a>
      <a href="#" class="project-link" style="margin: 0 1rem;">LinkedIn</a>
    </div>
  </div>
</div>
