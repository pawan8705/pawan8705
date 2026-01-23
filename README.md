<!-- 🌈 Dynamic Gradient Header -->
<div align="center">
  <div style="position: relative;">
    <!-- Animated Background -->
    <div style="
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 300px;
      background: linear-gradient(45deg, #3b82f6, #8b5cf6, #ec4899, #f59e0b);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      border-radius: 20px;
      opacity: 0.1;
      z-index: 1;
    "></div>
    
    <!-- Content -->
    <div style="position: relative; z-index: 2; padding: 40px 20px;">
      <!-- Profile Image with Animation -->
      <div style="
        width: 150px;
        height: 150px;
        margin: 0 auto 20px;
        border-radius: 50%;
        background: linear-gradient(45deg, #3b82f6, #8b5cf6);
        padding: 5px;
        animation: pulse 2s infinite;
        box-shadow: 0 10px 30px rgba(59, 130, 246, 0.3);
      ">
        <img src="https://avatars.githubusercontent.com/u/132332955?v=4" 
             width="140" 
             height="140" 
             style="border-radius: 50%; border: 4px solid white;"
             alt="Pawan Tripathi"
             onerror="this.src='https://api.dicebear.com/7.x/avataaars/svg?seed=pawan8705'"/>
      </div>
      
      <!-- Animated Name -->
      <h1 style="
        font-size: 3rem;
        background: linear-gradient(45deg, #3b82f6, #8b5cf6, #ec4899);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        margin-bottom: 10px;
        animation: textGlow 3s ease-in-out infinite alternate;
      ">
        Pawan Tripathi
      </h1>
      
      <!-- Floating Tags -->
      <div style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin: 20px 0;">
        <span style="
          background: rgba(59, 130, 246, 0.1);
          padding: 8px 16px;
          border-radius: 50px;
          border: 2px solid #3b82f6;
          animation: float 6s ease-in-out infinite;
        ">🚀 Frontend Developer</span>
        
        <span style="
          background: rgba(139, 92, 246, 0.1);
          padding: 8px 16px;
          border-radius: 50px;
          border: 2px solid #8b5cf6;
          animation: float 6s ease-in-out infinite 0.5s;
        ">🎨 UI/UX Enthusiast</span>
        
        <span style="
          background: rgba(236, 72, 153, 0.1);
          padding: 8px 16px;
          border-radius: 50px;
          border: 2px solid #ec4899;
          animation: float 6s ease-in-out infinite 1s;
        ">🤖 AI Explorer</span>
      </div>
      
      <!-- Live Stats -->
      <div style="
        display: flex;
        justify-content: center;
        gap: 30px;
        margin-top: 30px;
        flex-wrap: wrap;
      ">
        <div style="text-align: center;">
          <div style="
            font-size: 2rem;
            font-weight: bold;
            color: #3b82f6;
            animation: countUp 2s ease-out;
          " id="repoCount">Loading...</div>
          <div style="color: #6b7280;">Repositories</div>
        </div>
        
        <div style="text-align: center;">
          <div style="
            font-size: 2rem;
            font-weight: bold;
            color: #8b5cf6;
            animation: countUp 2s ease-out 0.5s;
          " id="projectCount">Loading...</div>
          <div style="color: #6b7280;">Projects</div>
        </div>
        
        <div style="text-align: center;">
          <div style="
            font-size: 2rem;
            font-weight: bold;
            color: #ec4899;
            animation: countUp 2s ease-out 1s;
          " id="techCount">Loading...</div>
          <div style="color: #6b7280;">Technologies</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ✨ Typewriter Effect -->
<div align="center" style="margin: 40px 0;">
  <div style="
    background: linear-gradient(135deg, #0f172a, #1e293b);
    padding: 30px;
    border-radius: 20px;
    border: 1px solid rgba(59, 130, 246, 0.2);
    max-width: 800px;
    margin: 0 auto;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
  ">
    <div id="typewriter" style="
      font-size: 1.5rem;
      color: #f1f5f9;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
    "></div>
  </div>
</div>

<!-- 🎯 Quick Links -->
<div align="center" style="margin: 40px 0;">
  <a href="https://pawan-tripathi-portfolio.vercel.app" target="_blank" style="
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    color: white;
    padding: 12px 24px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    margin: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
    animation: pulseCTA 2s infinite;
  " onmouseover="this.style.transform='translateY(-5px)';this.style.boxShadow='0 10px 20px rgba(59, 130, 246, 0.4)'" 
     onmouseout="this.style.transform='translateY(0)';this.style.boxShadow='none'">
    🌐 View Portfolio
  </a>
  
  <a href="https://calendly.com/your-link" target="_blank" style="
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: linear-gradient(45deg, #ec4899, #f59e0b);
    color: white;
    padding: 12px 24px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    margin: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
  " onmouseover="this.style.transform='translateY(-5px)';this.style.boxShadow='0 10px 20px rgba(236, 72, 153, 0.4)'" 
     onmouseout="this.style.transform='translateY(0)';this.style.boxShadow='none'">
    📅 Schedule Chat
  </a>
  
  <a href="mailto:your.email@example.com" style="
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background: linear-gradient(45deg, #10b981, #3b82f6);
    color: white;
    padding: 12px 24px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    margin: 10px;
    transition: transform 0.3s, box-shadow 0.3s;
  " onmouseover="this.style.transform='translateY(-5px)';this.style.boxShadow='0 10px 20px rgba(16, 185, 129, 0.4)'" 
     onmouseout="this.style.transform='translateY(0)';this.style.boxShadow='none'">
    ✉️ Contact Me
  </a>
</div>

<!-- 🛠️ Tech Stack Carousel -->
<div align="center" style="margin: 60px 0;">
  <h2 style="
    font-size: 2rem;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 40px;
  ">
    🚀 Tech Stack
  </h2>
  
  <div style="
    display: flex;
    overflow: hidden;
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
    padding: 20px 0;
  ">
    <!-- First Row -->
    <div style="
      display: flex;
      animation: scrollLeft 30s linear infinite;
      gap: 30px;
      padding: 20px;
    ">
      <!-- Tech Cards -->
      <div class="tech-card" style="
        background: linear-gradient(135deg, rgba(59, 130, 246, 0.1), rgba(59, 130, 246, 0.05));
        border: 2px solid #3b82f6;
        border-radius: 20px;
        padding: 20px;
        width: 120px;
        height: 120px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        transition: all 0.3s;
        animation: float 3s ease-in-out infinite;
      " onmouseover="this.style.transform='translateY(-10px) scale(1.05)';this.style.boxShadow='0 20px 40px rgba(59, 130, 246, 0.3)'" 
         onmouseout="this.style.transform='translateY(0) scale(1)';this.style.boxShadow='none'">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" height="50" />
        <div style="margin-top: 10px; font-weight: bold; color: #3b82f6;">React</div>
      </div>
      
      <div class="tech-card" style="
        background: linear-gradient(135deg, rgba(139, 92, 246, 0.1), rgba(139, 92, 246, 0.05));
        border: 2px solid #8b5cf6;
        border-radius: 20px;
        padding: 20px;
        width: 120px;
        height: 120px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        transition: all 0.3s;
        animation: float 3s ease-in-out infinite 0.2s;
      " onmouseover="this.style.transform='translateY(-10px) scale(1.05)';this.style.boxShadow='0 20px 40px rgba(139, 92, 246, 0.3)'" 
         onmouseout="this.style.transform='translateY(0) scale(1)';this.style.boxShadow='none'">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="50" height="50" />
        <div style="margin-top: 10px; font-weight: bold; color: #8b5cf6;">TypeScript</div>
      </div>
      
      <!-- Add more tech cards similarly -->
    </div>
  </div>
</div>

<!-- 📊 GitHub Stats with 3D Effect -->
<div align="center" style="margin: 60px 0;">
  <h2 style="
    font-size: 2rem;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 40px;
  ">
    📈 GitHub Analytics
  </h2>
  
  <div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  ">
    <!-- Stats Card 1 -->
    <div style="
      background: linear-gradient(135deg, #0f172a, #1e293b);
      border-radius: 20px;
      padding: 30px;
      border: 1px solid rgba(59, 130, 246, 0.2);
      transform-style: preserve-3d;
      perspective: 1000px;
      transition: transform 0.5s;
    " onmouseover="this.style.transform='rotateY(5deg) rotateX(5deg)'" 
       onmouseout="this.style.transform='rotateY(0) rotateX(0)'">
      <img src="https://github-readme-stats.vercel.app/api?username=pawan8705&show_icons=true&theme=radical&count_private=true&hide_border=true&bg_color=0d1117&title_color=3b82f6&icon_color=3b82f6&text_color=ffffff" 
           alt="GitHub Stats"
           style="width: 100%; border-radius: 10px;" />
    </div>
    
    <!-- Stats Card 2 -->
    <div style="
      background: linear-gradient(135deg, #0f172a, #1e293b);
      border-radius: 20px;
      padding: 30px;
      border: 1px solid rgba(139, 92, 246, 0.2);
      transform-style: preserve-3d;
      perspective: 1000px;
      transition: transform 0.5s;
    " onmouseover="this.style.transform='rotateY(-5deg) rotateX(5deg)'" 
       onmouseout="this.style.transform='rotateY(0) rotateX(0)'">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=pawan8705&theme=radical&hide_border=true&background=0d1117&stroke=3b82f6&ring=3b82f6&fire=3b82f6&currStreakLabel=3b82f6" 
           alt="GitHub Streak"
           style="width: 100%; border-radius: 10px;" />
    </div>
  </div>
</div>

<!-- 🌟 Featured Projects Gallery -->
<div align="center" style="margin: 60px 0;">
  <h2 style="
    font-size: 2rem;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 40px;
  ">
    🚀 Featured Projects
  </h2>
  
  <div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 30px;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  ">
    
    <!-- Project Card 1 -->
    <div class="project-card" style="
      background: linear-gradient(135deg, rgba(59, 130, 246, 0.1), rgba(59, 130, 246, 0.05));
      border-radius: 20px;
      padding: 30px;
      border: 2px solid #3b82f6;
      position: relative;
      overflow: hidden;
      transition: all 0.5s;
      cursor: pointer;
    " onmouseover="this.style.transform='translateY(-10px)';this.style.boxShadow='0 30px 60px rgba(59, 130, 246, 0.3)';" 
       onmouseout="this.style.transform='translateY(0)';this.style.boxShadow='none';">
      <div style="
        position: absolute;
        top: -50px;
        right: -50px;
        width: 100px;
        height: 100px;
        background: linear-gradient(45deg, #3b82f6, #8b5cf6);
        border-radius: 50%;
        opacity: 0.1;
      "></div>
      
      <h3 style="color: #3b82f6; margin-bottom: 15px; font-size: 1.5rem;">NeoElectronix</h3>
      <p style="color: #94a3b8; margin-bottom: 20px;">Modern E-commerce platform for electronics with real-time inventory and payment integration.</p>
      
      <div style="display: flex; gap: 10px; margin-bottom: 20px;">
        <span style="background: rgba(59, 130, 246, 0.2); padding: 5px 10px; border-radius: 15px; font-size: 0.9rem; color: #3b82f6;">React</span>
        <span style="background: rgba(139, 92, 246, 0.2); padding: 5px 10px; border-radius: 15px; font-size: 0.9rem; color: #8b5cf6;">Firebase</span>
        <span style="background: rgba(236, 72, 153, 0.2); padding: 5px 10px; border-radius: 15px; font-size: 0.9rem; color: #ec4899;">Tailwind</span>
      </div>
      
      <div style="display: flex; gap: 15px;">
        <a href="https://github.com/pawan8705/NeoElectonix" target="_blank" style="
          display: inline-flex;
          align-items: center;
          gap: 8px;
          background: #3b82f6;
          color: white;
          padding: 8px 16px;
          border-radius: 25px;
          text-decoration: none;
          font-size: 0.9rem;
          transition: all 0.3s;
        " onmouseover="this.style.transform='scale(1.1)';this.style.boxShadow='0 5px 15px rgba(59, 130, 246, 0.4)'" 
           onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'">
          <span>👨‍💻 Code</span>
        </a>
        
        <a href="https://neo-electonix-l5ub.vercel.app/" target="_blank" style="
          display: inline-flex;
          align-items: center;
          gap: 8px;
          background: #8b5cf6;
          color: white;
          padding: 8px 16px;
          border-radius: 25px;
          text-decoration: none;
          font-size: 0.9rem;
          transition: all 0.3s;
        " onmouseover="this.style.transform='scale(1.1)';this.style.boxShadow='0 5px 15px rgba(139, 92, 246, 0.4)'" 
           onmouseout="this.style.transform='scale(1)';this.style.boxShadow='none'">
          <span>🌐 Live</span>
        </a>
      </div>
    </div>
    
    <!-- Add more project cards similarly -->
    
  </div>
</div>

<!-- 🎮 Interactive Skills Progress -->
<div align="center" style="margin: 60px 0;">
  <h2 style="
    font-size: 2rem;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 40px;
  ">
    📊 Skills Proficiency
  </h2>
  
  <div style="
    background: linear-gradient(135deg, #0f172a, #1e293b);
    border-radius: 20px;
    padding: 40px;
    max-width: 800px;
    margin: 0 auto;
    border: 1px solid rgba(59, 130, 246, 0.2);
  ">
    <!-- Skill Bar 1 -->
    <div style="margin-bottom: 25px;">
      <div style="display: flex; justify-content: space-between; margin-bottom: 8px;">
        <span style="color: #f1f5f9; font-weight: 500;">React & TypeScript</span>
        <span style="color: #3b82f6; font-weight: bold;" id="reactPercent">90%</span>
      </div>
      <div style="
        height: 10px;
        background: rgba(59, 130, 246, 0.1);
        border-radius: 5px;
        overflow: hidden;
      ">
        <div id="reactBar" style="
          height: 100%;
          width: 0%;
          background: linear-gradient(90deg, #3b82f6, #8b5cf6);
          border-radius: 5px;
          animation: fillBar 2s ease-out forwards;
        "></div>
      </div>
    </div>
    
    <!-- Add more skill bars similarly -->
    
  </div>
</div>

<!-- 🌐 Social Connections -->
<div align="center" style="margin: 60px 0;">
  <h2 style="
    font-size: 2rem;
    background: linear-gradient(45deg, #3b82f6, #8b5cf6);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-bottom: 40px;
  ">
    🤝 Let's Connect
  </h2>
  
  <div style="
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
  ">
    <!-- Social Button 1 -->
    <a href="https://linkedin.com/in/pawantripathi" target="_blank" style="
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 60px;
      height: 60px;
      background: linear-gradient(135deg, #0a66c2, #004182);
      border-radius: 50%;
      color: white;
      font-size: 1.5rem;
      text-decoration: none;
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
    " onmouseover="
      this.style.transform='translateY(-10px) scale(1.1)';
      this.style.boxShadow='0 15px 30px rgba(10, 102, 194, 0.4)';
    " onmouseout="
      this.style.transform='translateY(0) scale(1)';
      this.style.boxShadow='none';
    ">
      <span>in</span>
      <div style="
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: rgba(255, 255, 255, 0.2);
        transform: translateY(100%);
        transition: transform 0.3s;
      "></div>
    </a>
    
    <!-- Add more social buttons similarly -->
    
  </div>
</div>

<!-- ✨ Magic Footer -->
<div align="center" style="
  margin-top: 80px;
  padding: 40px 20px;
  background: linear-gradient(135deg, #0f172a, #1e293b);
  border-radius: 30px 30px 0 0;
  position: relative;
">
  <!-- Animated Particles -->
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    overflow: hidden;
    pointer-events: none;
  ">
    <div style="
      position: absolute;
      width: 4px;
      height: 4px;
      background: #3b82f6;
      border-radius: 50%;
      animation: particleFloat 20s linear infinite;
      left: 10%;
    "></div>
    <!-- Add more particles -->
  </div>
  
  <div style="position: relative; z-index: 1;">
    <div style="
      font-size: 1.8rem;
      background: linear-gradient(45deg, #3b82f6, #8b5cf6, #ec4899);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 20px;
      font-weight: bold;
    ">
      Thanks for visiting! 🚀
    </div>
    
    <p style="color: #94a3b8; max-width: 600px; margin: 0 auto 30px;">
      "The beautiful thing about learning is that no one can take it away from you."
      <br/>
      <span style="color: #3b82f6; font-style: italic;">- B.B. King</span>
    </p>
    
    <!-- Visitor Counter -->
    <div style="
      background: rgba(59, 130, 246, 0.1);
      padding: 15px 30px;
      border-radius: 50px;
      display: inline-flex;
      align-items: center;
      gap: 10px;
      border: 2px solid rgba(59, 130, 246, 0.3);
    ">
      <span style="color: #3b82f6;">👁️ Visitors:</span>
      <span style="color: #f1f5f9; font-weight: bold; font-size: 1.2rem;" id="visitorCount">0000</span>
    </div>
    
    <!-- Back to Top -->
    <a href="#" style="
      display: inline-block;
      margin-top: 30px;
      color: #94a3b8;
      text-decoration: none;
      transition: color 0.3s;
    " onmouseover="this.style.color='#3b82f6'">
      ↑ Back to Top
    </a>
  </div>
</div>

<!-- 🎵 Animation CSS -->
<style>
  /* Keyframe Animations */
  @keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
  }
  
  @keyframes textGlow {
    0% { text-shadow: 0 0 20px rgba(59, 130, 246, 0.5); }
    100% { text-shadow: 0 0 30px rgba(139, 92, 246, 0.7), 0 0 40px rgba(139, 92, 246, 0.4); }
  }
  
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }
  
  @keyframes countUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  
  @keyframes scrollLeft {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  
  @keyframes fillBar {
    to { width: var(--target-width); }
  }
  
  @keyframes pulseCTA {
    0%, 100% { transform: scale(1); box-shadow: 0 5px 15px rgba(59, 130, 246, 0.4); }
    50% { transform: scale(1.05); box-shadow: 0 10px 25px rgba(59, 130, 246, 0.6); }
  }
  
  @keyframes particleFloat {
    0% { transform: translateY(100vh) rotate(0deg); opacity: 1; }
    100% { transform: translateY(-100px) rotate(360deg); opacity: 0; }
  }
  
  /* Smooth Scrolling */
  html {
    scroll-behavior: smooth;
  }
  
  /* Hover Effects */
  .tech-card:hover {
    transform: translateY(-10px) scale(1.05);
  }
  
  .project-card:hover::before {
    opacity: 1;
  }
  
  /* Responsive Design */
  @media (max-width: 768px) {
    h1 { font-size: 2rem !important; }
    .tech-card { width: 100px !important; height: 100px !important; }
    .project-card { min-width: 100% !important; }
  }
</style>

<!-- 📱 JavaScript for Interactive Elements -->
<script>
  // Typewriter Effect
  const texts = [
    "Building modern web experiences with React & TypeScript...",
    "Exploring AI-powered development workflows...",
    "Creating beautiful, responsive user interfaces...",
    "Passionate about clean code and best practices...",
    "Open to collaborations and exciting projects!"
  ];
  
  let textIndex = 0;
  let charIndex = 0;
  let isDeleting = false;
  
  function typeWriter() {
    const currentText = texts[textIndex];
    const typewriter = document.getElementById('typewriter');
    
    if (isDeleting) {
      typewriter.textContent = currentText.substring(0, charIndex - 1);
      charIndex--;
    } else {
      typewriter.textContent = currentText.substring(0, charIndex + 1);
      charIndex++;
    }
    
    if (!isDeleting && charIndex === currentText.length) {
      setTimeout(() => isDeleting = true, 2000);
    } else if (isDeleting && charIndex === 0) {
      isDeleting = false;
      textIndex = (textIndex + 1) % texts.length;
    }
    
    setTimeout(typeWriter, isDeleting ? 50 : 100);
  }
  
  // Initialize when page loads
  document.addEventListener('DOMContentLoaded', () => {
    typeWriter();
    
    // Animate skill bars
    const skills = {
      react: 90,
      typescript: 85,
      tailwind: 80,
      nodejs: 70,
      ai: 75
    };
    
    Object.keys(skills).forEach((skill, index) => {
      setTimeout(() => {
        const bar = document.getElementById(`${skill}Bar`);
        const percent = document.getElementById(`${skill}Percent`);
        if (bar && percent) {
          bar.style.setProperty('--target-width', `${skills[skill]}%`);
          bar.style.width = `${skills[skill]}%`;
          percent.textContent = `${skills[skill]}%`;
        }
      }, index * 300);
    });
    
    // Update counters
    const counters = {
      repoCount: 25,
      projectCount: 15,
      techCount: 20
    };
    
    Object.keys(counters).forEach((counter, index) => {
      const element = document.getElementById(counter);
      if (element) {
        let count = 0;
        const target = counters[counter];
        const increment = target / 50;
        
        const updateCounter = () => {
          if (count < target) {
            count += increment;
            element.textContent = Math.ceil(count);
            setTimeout(updateCounter, 30);
          } else {
            element.textContent = target;
          }
        };
        
        setTimeout(updateCounter, index * 500);
      }
    });
    
    // Visitor counter (simulated)
    const visitorElement = document.getElementById('visitorCount');
    if (visitorElement) {
      const baseCount = 1234;
      const randomIncrement = Math.floor(Math.random() * 50);
      visitorElement.textContent = (baseCount + randomIncrement).toString().padStart(4, '0');
    }
    
    // Parallax effect on scroll
    window.addEventListener('scroll', () => {
      const scrolled = window.pageYOffset;
      const rate = scrolled * -0.5;
      const banner = document.querySelector('[style*="gradientBG"]');
      if (banner) {
        banner.style.transform = `translate3d(0px, ${rate * 0.5}px, 0px)`;
      }
    });
    
    // Interactive particle system
    function createParticles() {
      const footer = document.querySelector('[style*="particleFloat"]');
      if (!footer) return;
      
      for (let i = 0; i < 15; i++) {
        const particle = document.createElement('div');
        particle.style.cssText = `
          position: absolute;
          width: ${Math.random() * 6 + 2}px;
          height: ${Math.random() * 6 + 2}px;
          background: ${['#3b82f6', '#8b5cf6', '#ec4899'][Math.floor(Math.random() * 3)]};
          border-radius: 50%;
          animation: particleFloat ${Math.random() * 20 + 15}s linear infinite;
          left: ${Math.random() * 100}%;
          animation-delay: ${Math.random() * 5}s;
        `;
        footer.parentElement.appendChild(particle);
      }
    }
    
    createParticles();
  });
  
  // Mouse move effect for tech cards
  document.addEventListener('mousemove', (e) => {
    const cards = document.querySelectorAll('.tech-card');
    cards.forEach(card => {
      const rect = card.getBoundingClientRect();
      const x = e.clientX - rect.left;
      const y = e.clientY - rect.top;
      
      const centerX = rect.width / 2;
      const centerY = rect.height / 2;
      
      const rotateY = (x - centerX) / 25;
      const rotateX = (centerY - y) / 25;
      
      if (card.matches(':hover')) {
        card.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) translateY(-10px) scale(1.05)`;
      }
    });
  });
</script>

<!-- 📝 Custom Badges (Optional) -->
<div align="center" style="margin-top: 30px;">
  <img src="https://img.shields.io/badge/Status-Available%20for%20Work-10b981?style=for-the-badge&logo=linkedin" alt="Status" />
  <img src="https://img.shields.io/badge/Open%20Source-Contributor-3b82f6?style=for-the-badge&logo=github" alt="Open Source" />
  <img src="https://img.shields.io/badge/React-Expert-61dafb?style=for-the-badge&logo=react" alt="React Expert" />
  <img src="https://img.shields.io/badge/AI-Enthusiast-ec4899?style=for-the-badge&logo=openai" alt="AI Enthusiast" />
</div>
