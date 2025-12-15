<!-- Dynamic Header with Multi-Text Typing -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&duration=3000&pause=500&color=0EA5E9&center=true&vCenter=true&width=600&lines=Ahaduzzaman+Khan;Principal+JavaScript+Developer;Founder+%40+Fluxenite;Creator+of+TBBA+CSS;Building+the+Future+of+Web+Dev;Stay+Smarter.+Build+Smarter." alt="Typing SVG" />
  </a>
</p>

<!-- Professional Summary with Animated Website Link -->
<p align="center">
  <a href="https://ahadthedev.netlify.app" target="_blank">
    <kbd>
      <b>🌐 Portfolio:</b> <span id="website-text">ahadthedev.netlify.app</span>
    </kbd>
  </a>
</p>

<h3 align="center">A disciplined software engineer specializing in scalable JavaScript architectures, open-source tooling, and developer experience.</h3>

<!-- Animated Horizontal Divider -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0EA5E9&section=header" />
</div>

<!-- Dynamic Stats with Pulsing Animation -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=transparent&title_color=0EA5E9&text_color=334155&icon_color=0EA5E9&border_color=E2E8F0&hide_border=false&include_all_commits=true&custom_title=Ahad%27s+Professional+Metrics&hide=issues" alt="GitHub Stats" height="165" />

  <!-- GitHub Trophy with Shine Effect -->
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=flat&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7&rank=SECRET,SSS,SS,S,AAA,AA,A,B,C" alt="Trophy" height="165" />
</p>

<!-- Tech Stack with Animated Icons -->
### 🛠️ **Technical Stack**

<div align="center">
  <!-- Core Tech with Hover Effects -->
  <img src="https://skillicons.dev/icons?i=js,ts,react,next,nodejs,vue,svelte,tailwind,materialui&perline=9" />

  <!-- Infra & Tools -->
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,nginx,postgres,mongodb,graphql,webpack&perline=9" />
</div>

<!-- Key Projects Section -->
### 🚀 **Core Projects**

<details>
<summary><b>Fluxenite</b> – Zero-infrastructure framework for rapid full-stack development</summary>
<br/>
• Eliminates DevOps overhead while maintaining enterprise scalability<br/>
• Status: <b>In active development</b> – seeking core contributors<br/>
</details>

<details>
<summary><b>TBBA CSS</b> – Utility-first CSS architecture system</summary>
<br/>
• Promotes design token integration and consistency<br/>
• Status: <b>Stable v1.2</b> – used in multiple production projects<br/>
</details>

<!-- Dynamic Activity Graph -->
### 📈 **Development Activity**

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github-dark&bg_color=0f172a&color=38bdf8&line=38bdf8&point=ffffff&area=true&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github&bg_color=ffffff&color=0ea5e9&line=0ea5e9&point=334155&area=true&hide_border=true" />
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github&bg_color=ffffff&color=0ea5e9&line=0ea5e9&point=334155&area=true&hide_border=true" alt="GitHub Activity Graph" />
  </picture>
</p>

<!-- Clean Contact Section -->
### 📫 **Connect**

<p align="center">
  <a href="mailto:bdgamer9191@gmail.com">
    <img src="https://img.shields.io/badge/Email-Professional_Contact-0EA5E9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="Ahaduzzamankhan">
    <img src="https://img.shields.io/badge/GitHub-Portfolio_&_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/ahaduzzamankhan">
    <img src="https://img.shields.io/badge/LinkedIn-Professional_Network-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<!-- Animation Script -->
<script>
  // Text cycling animation for website URL
  const websiteText = document.getElementById('website-text');
  const textVariations = [
    'ahadthedev.netlify.app',
    '🚀 Explore My Work',
    '💻 Developer Portfolio',
    '📂 Projects & Code'
  ];
  
  let currentIndex = 0;
  
  function cycleText() {
    currentIndex = (currentIndex + 1) % textVariations.length;
    websiteText.style.opacity = '0';
    
    setTimeout(() => {
      websiteText.textContent = textVariations[currentIndex];
      websiteText.style.opacity = '1';
    }, 300);
  }
  
  // Change text every 3 seconds
  setInterval(cycleText, 3000);
  
  // Add hover effect
  websiteText.parentElement.addEventListener('mouseenter', () => {
    clearInterval(intervalId);
    websiteText.style.color = '#0EA5E9';
    websiteText.style.textDecoration = 'underline';
  });
  
  websiteText.parentElement.addEventListener('mouseleave', () => {
    intervalId = setInterval(cycleText, 3000);
    websiteText.style.color = '';
    websiteText.style.textDecoration = '';
  });
  
  let intervalId = setInterval(cycleText, 3000);
</script>

<style>
  /* Smooth animations */
  #website-text {
    transition: all 0.3s ease;
    color: #0EA5E9;
    font-weight: 600;
  }
  
  /* Pulsing effect for stats */
  img[alt="GitHub Stats"], img[alt="Trophy"] {
    transition: transform 0.3s ease;
  }
  
  img[alt="GitHub Stats"]:hover, img[alt="Trophy"]:hover {
    transform: scale(1.02);
  }
  
  /* Skill icons animation */
  .skill-icons img {
    transition: transform 0.2s ease;
  }
  
  .skill-icons img:hover {
    transform: translateY(-3px);
  }
</style>