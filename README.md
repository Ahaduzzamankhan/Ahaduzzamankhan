<!-- Dynamic Header with Animated Typing -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=30&duration=3000&pause=500&color=0EA5E9&center=true&vCenter=true&width=600&lines=Ahaduzzaman+Khan;Principal+JavaScript+Developer;Founder+%40+Fluxenite;Creator+of+TBBA+CSS;Building+the+Future+of+Web+Dev;Stay+Smarter.+Build+Smarter." alt="Typing SVG" />
  </a>
</p>

<!-- Professional Summary with Animated Website Link -->
<div align="center">
  <a href="https://ahadthedev.netlify.app" target="_blank">
    <kbd style="background:#0EA5E9;color:white;padding:8px 16px;border-radius:6px;font-family:monospace;cursor:pointer;transition:all 0.3s ease;">
      <b>🌐 Portfolio:</b> <span id="website-text">ahadthedev.netlify.app</span>
    </kbd>
  </a>
</div>

<h3 align="center">A disciplined software engineer specializing in scalable JavaScript architectures, open-source tooling, and developer experience.</h3>

<!-- Animated Horizontal Divider -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0EA5E9&section=header&animation=fadeIn" />
</div>

<!-- Dynamic Stats Section -->
<div align="center">
  <div style="display:inline-block;margin:10px;transition:transform 0.3s ease;">
    <img src="https://github-readme-stats.vercel.app/api?username=Ahaduzzamankhan&show_icons=true&theme=transparent&title_color=0EA5E9&text_color=334155&icon_color=0EA5E9&border_color=E2E8F0&hide_border=false&include_all_commits=true&custom_title=Ahad%27s+Professional+Metrics&hide=issues" alt="GitHub Stats" height="165" />
  </div>
  
  <div style="display:inline-block;margin:10px;transition:transform 0.3s ease;">
    <img src="https://github-profile-trophy.vercel.app/?username=Ahaduzzamankhan&theme=flat&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7&rank=SECRET,SSS,SS,S,AAA,AA,A,B,C" alt="Trophy" height="165" />
  </div>
</div>

<!-- Tech Stack Section -->
<div align="center">
  <h3>🛠️ Technical Stack</h3>
  
  <div style="margin:20px 0;">
    <img src="https://skillicons.dev/icons?i=js,ts,react,next,nodejs,vue,svelte,tailwind,materialui&perline=9" alt="Core Technologies" />
  </div>
  
  <div style="margin:20px 0;">
    <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,githubactions,nginx,postgres,mongodb,graphql,webpack&perline=9" alt="Infrastructure & Tools" />
  </div>
</div>

<!-- Key Projects Section -->
<div align="center">
  <h3>🚀 Core Projects</h3>
  
  <div style="max-width:800px;margin:0 auto;">
    <details style="background:#f8fafc;border:1px solid #e2e8f0;border-radius:8px;padding:15px;margin:10px 0;transition:all 0.3s ease;">
      <summary style="cursor:pointer;font-weight:bold;color:#0EA5E9;">Fluxenite – Zero-infrastructure framework for rapid full-stack development</summary>
      <div style="margin-top:10px;color:#475569;">
        • Eliminates DevOps overhead while maintaining enterprise scalability<br/>
        • Status: <b style="color:#10b981;">In active development</b> – seeking core contributors
      </div>
    </details>
    
    <details style="background:#f8fafc;border:1px solid #e2e8f0;border-radius:8px;padding:15px;margin:10px 0;transition:all 0.3s ease;">
      <summary style="cursor:pointer;font-weight:bold;color:#0EA5E9;">TBBA CSS – Utility-first CSS architecture system</summary>
      <div style="margin-top:10px;color:#475569;">
        • Promotes design token integration and consistency<br/>
        • Status: <b style="color:#10b981;">Stable v1.2</b> – used in multiple production projects
      </div>
    </details>
  </div>
</div>

<!-- Contact Section -->
<div align="center">
  <h3>📫 Connect</h3>
  
  <div style="margin:20px 0;">
    <a href="mailto:bdgamer9191@gmail.com" style="text-decoration:none;margin:0 10px;">
      <img src="https://img.shields.io/badge/Email-Professional_Contact-0EA5E9?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    
    <a href="https://github.com/Ahaduzzamankhan" style="text-decoration:none;margin:0 10px;">
      <img src="https://img.shields.io/badge/GitHub-Portfolio_&_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    
    <a href="https://linkedin.com/in/ahaduzzamankhan" style="text-decoration:none;margin:0 10px;">
      <img src="https://img.shields.io/badge/LinkedIn-Professional_Network-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </div>
</div>

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
  let intervalId = setInterval(cycleText, 3000);
  
  // Add hover effect to website link
  const websiteLink = websiteText.parentElement.parentElement;
  websiteLink.addEventListener('mouseenter', () => {
    clearInterval(intervalId);
    websiteText.style.color = '#ffffff';
    websiteText.style.textDecoration = 'underline';
  });
  
  websiteLink.addEventListener('mouseleave', () => {
    intervalId = setInterval(cycleText, 3000);
    websiteText.style.color = '';
    websiteText.style.textDecoration = '';
  });
  
  // Add hover effects to skill icons and project cards
  document.addEventListener('DOMContentLoaded', function() {
    // Add hover to skill icons
    const skillIcons = document.querySelectorAll('.skill-icons img');
    skillIcons.forEach(icon => {
      icon.style.transition = 'transform 0.2s ease';
      icon.addEventListener('mouseenter', () => {
        icon.style.transform = 'translateY(-3px)';
      });
      icon.addEventListener('mouseleave', () => {
        icon.style.transform = '';
      });
    });
    
    // Add hover to project cards
    const projectDetails = document.querySelectorAll('details');
    projectDetails.forEach(detail => {
      detail.addEventListener('mouseenter', () => {
        detail.style.boxShadow = '0 4px 12px rgba(14, 165, 233, 0.1)';
        detail.style.transform = 'translateY(-2px)';
      });
      detail.addEventListener('mouseleave', () => {
        detail.style.boxShadow = '';
        detail.style.transform = '';
      });
    });
    
    // Add hover to stats cards
    const statCards = document.querySelectorAll('div[style*="display:inline-block"]');
    statCards.forEach(card => {
      card.addEventListener('mouseenter', () => {
        card.style.transform = 'scale(1.02)';
      });
      card.addEventListener('mouseleave', () => {
        card.style.transform = '';
      });
    });
  });
</script>
</div>