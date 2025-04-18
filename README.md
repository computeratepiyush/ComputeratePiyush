<div align="center">

<!-- 3D Parallax Header -->
<div style="
  perspective: 1000px;
  height: 300px;
  overflow: hidden;
  position: relative;
  margin-bottom: 3rem;
">
  <div style="
    background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
    height: 400px;
    transform-style: preserve-3d;
    transform: translateZ(-50px);
    position: absolute;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-bottom: 1px solid rgba(99, 102, 241, 0.3);
  " data-parallax="true">
    <!-- Animated Typing Text with Glow -->
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=36&duration=3000&pause=1000&color=8b5cf6&center=true&vCenter=true&width=600&lines=Cyber+Guardian;Ethical+Hacker;Web+Alchemist;I'm+Piyush;Security+First" alt="Professional typing animation" style="text-shadow: 0 0 15px rgba(139, 92, 246, 0.7);"/>
    
    <!-- Floating Particles Background -->
    <div style="position: absolute; width: 100%; height: 100%; overflow: hidden; z-index: -1;">
      <div style="
        position: absolute;
        width: 5px; height: 5px;
        background: rgba(99, 102, 241, 0.5);
        border-radius: 50%;
        animation: float 15s infinite linear;
      " data-depth="0.2"></div>
      <!-- Add 10-15 more particles with different positions/sizes -->
    </div>
  </div>
</div>

<!-- Cyber Navigation Bar -->
<div style="
  display: flex;
  justify-content: center;
  gap: 15px;
  margin: 2rem 0;
  flex-wrap: wrap;
  position: sticky;
  top: 20px;
  z-index: 100;
">
  <a href="#about" class="nav-btn">About</a>
  <a href="#pentesting" class="nav-btn">Pentesting</a>
  <a href="#projects" class="nav-btn">Projects</a>
  <a href="#stats" class="nav-btn">Stats</a>
  <a href="https://bikersaccessories.com" class="nav-btn-cta">Live Work</a>
</div>

</div>

---

## 🔐 <span id="about">Cyber Profile</span>

<div style="
  background: rgba(15, 23, 42, 0.7);
  padding: 2rem;
  border-radius: 12px;
  border: 1px solid rgba(99, 102, 241, 0.3);
  margin: 3rem 0;
  backdrop-filter: blur(10px);
  transform-style: preserve-3d;
  transform: translateZ(20px);
  transition: transform 0.5s ease;
" onmouseover="this.style.transform='translateZ(30px) scale(1.02)'" 
onmouseout="this.style.transform='translateZ(20px) scale(1)'">

**"Breaking systems to build better defenses."**  

19 y/o cybersecurity specialist merging web development expertise with ethical hacking. Found and responsibly disclosed vulnerabilities in 3 e-commerce platforms (2024). Currently focused on:  
- Web application penetration testing  
- Custom security tool development  
- Bug bounty hunting  

</div>

---

## 🛡️ <span id="pentesting">Security Arsenal</span>

<!-- Animated Skill Cards -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin: 3rem 0;
">

<!-- Kali Linux Card -->
<div class="skill-card" data-tilt>
  <div class="skill-icon" style="background: linear-gradient(135deg, #557CF2, #8b5cf6);">
    <img src="https://img.icons8.com/color/48/000000/kali-linux.png" alt="Kali Linux" width="40"/>
  </div>
  <h3>Offensive Tools</h3>
  <ul>
    <li>Burp Suite Pro</li>
    <li>Metasploit Framework</li>
    <li>SQLmap</li>
  </ul>
</div>

<!-- Web Security Card -->
<div class="skill-card" data-tilt data-tilt-scale="1.05">
  <div class="skill-icon" style="background: linear-gradient(135deg, #6366F1, #EC4899);">
    <img src="https://img.icons8.com/color/48/000000/security-checked.png" alt="Web Security" width="40"/>
  </div>
  <h3>Web Security</h3>
  <ul>
    <li>OWASP Top 10</li>
    <li>XSS/CSRF Prevention</li>
    <li>JWT Exploits</li>
  </ul>
</div>

<!-- Development Card -->
<div class="skill-card" data-tilt data-tilt-glare>
  <div class="skill-icon" style="background: linear-gradient(135deg, #10B981, #3B82F6);">
    <img src="https://img.icons8.com/color/48/000000/code.png" alt="Development" width="40"/>
  </div>
  <h3>Development</h3>
  <ul>
    <li>Python Exploits</li>
    <li>Secure Node.js</li>
    <li>Hardened WordPress</li>
  </ul>
</div>

</div>

---

## 💻 <span id="projects">Security Projects</span>

<!-- Parallax Project Gallery -->
<div class="project-gallery">

<!-- E-commerce Pentest -->
<div class="project-card" style="background-image: url('https://images.unsplash.com/photo-1556740738-b6a63e27c4df?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');">
  <div class="project-content">
    <h3>E-commerce Vulnerability Research</h3>
    <p>Discovered and reported critical payment gateway flaw in Indian e-commerce platform (2024)</p>
    <div class="project-tags">
      <span>Bug Bounty</span>
      <span>Pentesting</span>
    </div>
    <a href="#" class="project-link">Case Study (Coming Soon)</a>
  </div>
</div>

<!-- Custom Security Tool -->
<div class="project-card" style="background-image: url('https://images.unsplash.com/photo-1620712943543-bcc4688e7485?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');">
  <div class="project-content">
    <h3>Python Vulnerability Scanner</h3>
    <p>Automated tool detecting common web vulnerabilities (SQLi, XSS, exposed .git)</p>
    <div class="project-tags">
      <span>Python</span>
      <span>Security</span>
    </div>
    <a href="https://github.com/computeratepiyush" class="project-link">View on GitHub</a>
  </div>
</div>

</div>

---

## 📈 <span id="stats">Cyber Stats</span>

<!-- Animated GitHub Stats -->
<div class="stats-container">

![Pentesting Activity](https://github-readme-activity-graph.vercel.app/graph?username=computeratepiyush&theme=react-dark&hide_border=true&area=true&custom_title=Security+Research+Activity)

<div class="stats-grid">
  ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=computeratepiyush&show_icons=true&theme=radical&hide_border=true&bg_color=0f172a&title_color=8b5cf6&icon_color=6366f1&include_all_commits=true)
  
  ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=computeratepiyush&layout=compact&theme=radical&hide_border=true&bg_color=0f172a&title_color=8b5cf6)
</div>

</div>

---

## 🌐 Connect

<div class="connect-buttons">
  <a href="https://t.me/mocpiyush" class="connect-btn" style="background: #0088CC;">
    <img src="https://img.icons8.com/color/48/000000/telegram-app.png" width="24"/> Telegram
  </a>
  <a href="mailto:computeratepiyush@gmail.com" class="connect-btn" style="background: #EA4335;">
    <img src="https://img.icons8.com/color/48/000000/gmail.png" width="24"/> Email
  </a>
  <a href="https://www.linkedin.com/in/" class="connect-btn" style="background: #0A66C2;">
    <img src="https://img.icons8.com/color/48/000000/linkedin.png" width="24"/> LinkedIn
  </a>
</div>

<style>
  /* Animation Keyframes */
  @keyframes float {
    0% { transform: translateY(0) rotate(0deg); }
    100% { transform: translateY(-1000px) rotate(720deg); }
  }
  
  /* Navigation Buttons */
  .nav-btn {
    padding: 12px 24px;
    border-radius: 8px;
    background: rgba(99, 102, 241, 0.2);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255,255,255,0.1);
    color: #f8fafc;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.3s ease;
  }
  .nav-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(99, 102, 241, 0.3);
    background: rgba(99, 102, 241, 0.4);
  }
  
  /* Project Cards */
  .project-card {
    height: 300px;
    border-radius: 12px;
    position: relative;
    overflow: hidden;
    margin-bottom: 20px;
    background-size: cover;
    background-position: center;
    transition: transform 0.5s ease;
  }
  .project-card:hover {
    transform: scale(1.03);
  }
  
  /* Add more CSS for other elements */
</style>

<script>
  // Simple parallax effect
  document.querySelectorAll('[data-parallax]').forEach(el => {
    window.addEventListener('mousemove', (e) => {
      const x = (window.innerWidth - e.pageX * 0.5) / 100;
      const y = (window.innerHeight - e.pageY * 0.5) / 100;
      el.style.transform = `translateZ(-50px) translateX(${x}px) translateY(${y}px)`;
    });
  });
</script>
