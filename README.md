# Welcome to My GitHub Profile

<style>
  body {
    font-family: Arial, sans-serif;
    color: #333;
    line-height: 1.6;
  }
  .container {
    text-align: center;
    padding: 50px;
  }
  .header {
    background-color: #4CAF50;
    color: white;
    padding: 20px;
  }
  .intro {
    font-size: 18px;
    margin: 20px 0;
  }
  .projects {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
  }
  .project {
    border: 1px solid #ddd;
    border-radius: 5px;
    margin: 10px;
    padding: 20px;
    width: 30%;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s;
  }
  .project:hover {
    transform: scale(1.05);
  }
  .project img {
    max-width: 100%;
    border-radius: 5px;
  }
  .project-title {
    font-size: 20px;
    margin: 10px 0;
  }
  .project-description {
    font-size: 14px;
    color: #555;
  }
</style>

<div class="container">
  <div class="header">
    <h1>Welcome to My GitHub Profile</h1>
  </div>
  <p class="intro">Hello! I'm a passionate developer interested in creating web applications, learning new technologies, and collaborating on exciting projects. Here are some of my recent works:</p>
  <div class="projects">
    <div class="project">
      <img src="https://via.placeholder.com/300" alt="Project 1">
      <div class="project-title">Project One</div>
      <div class="project-description">This is a description of Project One. It's an awesome project that showcases my skills in HTML, CSS, and JavaScript.</div>
    </div>
    <div class="project">
      <img src="https://via.placeholder.com/300" alt="Project 2">
      <div class="project-title">Project Two</div>
      <div class="project-description">This is a description of Project Two. It highlights my experience with backend development and database management.</div>
    </div>
    <div class="project">
      <img src="https://via.placeholder.com/300" alt="Project 3">
      <div class="project-title">Project Three</div>
      <div class="project-description">This is a description of Project Three. It's a mobile application that I've built using React Native.</div>
    </div>
  </div>
</div>

<script>
  document.querySelector('.header').addEventListener('mouseover', function() {
    this.style.backgroundColor = '#45a049';
  });
  document.querySelector('.header').addEventListener('mouseout', function() {
    this.style.backgroundColor = '#4CAF50';
  });
</script>
