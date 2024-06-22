<!-- Profile Header -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Hello%2C+I'm+FireCodeGithub;Welcome+to+my+GitHub+Profile!" />
</h1>

<!-- Introduction -->
<p align="center">
  <img src="https://avatars.githubusercontent.com/u/107129871?v=4" width="100" height="100">
</p>
<h3 align="center">Hi, I'm FireCodeGithub, a passionate developer dedicated to building impactful software solutions.</h3>

<!-- Skills Section -->
<h2 align="center">Skills</h2>
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
</p>

<!-- Profile Stats Section -->
<h2 align="center">🔥 GitHub Stats</h2>
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FireCodeGithub&show_icons=true&theme=radical" alt="GitHub Stats" />
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=FireCodeGithub&theme=radical" alt="GitHub Streak" />
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=FireCodeGithub&layout=compact&theme=radical" alt="Top Languages" />
</div>

<!-- Dark/Light Mode Toggle -->
<h2 align="center">Toggle Theme</h2>
<div align="center">
  <button id="theme-toggle" style="padding: 10px 20px; font-size: 16px; cursor: pointer; border-radius: 5px; border: none; background-color: #36BCF7; color: white; transition: background-color 0.3s, transform 0.3s;">
    Switch to Dark Mode
  </button>
</div>

<style>
  #theme-toggle:hover {
    transform: scale(1.1);
  }
</style>

<!-- Contact Section -->
<h2 align="center">Contact</h2>
<p align="center">
  <a href="mailto:firecodegithub@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<script>
  const themeToggle = document.getElementById('theme-toggle');
  let darkMode = false;

  themeToggle.addEventListener('click', () => {
    document.body.style.transition = 'background-color 0.5s, color 0.5s';
    if (!darkMode) {
      document.body.style.backgroundColor = '#333';
      document.body.style.color = '#fff';
      themeToggle.textContent = 'Switch to Light Mode';
      themeToggle.style.backgroundColor = '#444';
    } else {
      document.body.style.backgroundColor = '#fff';
      document.body.style.color = '#000';
      themeToggle.textContent = 'Switch to Dark Mode';
      themeToggle.style.backgroundColor = '#36BCF7';
    }
    darkMode = !darkMode;
  });
</script>
