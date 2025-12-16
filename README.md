<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Md Firoj Hasan - Full Stack Developer</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    
    body {
      background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 100%);
      color: #e0e0e0;
      line-height: 1.6;
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }
    
    h1 {
      color: #00d9ff;
      margin: 30px 0;
      font-size: 2.8rem;
      text-shadow: 0 0 10px rgba(0, 217, 255, 0.3);
    }
    
    h2, h3, h4 {
      color: #4fc3f7;
      margin: 25px 0 15px 0;
      padding-bottom: 8px;
      border-bottom: 2px solid #2d3748;
    }
    
    section {
      background: rgba(30, 30, 46, 0.7);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 25px;
      margin: 25px 0;
      border: 1px solid #374151;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    
    section:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 40px rgba(0, 0, 0, 0.4);
    }
    
    img[align="right"] {
      border-radius: 15px;
      border: 3px solid #00d9ff;
      box-shadow: 0 0 20px rgba(0, 217, 255, 0.4);
      margin: 20px;
    }
    
    p {
      font-size: 1.1rem;
      margin: 15px 0;
      color: #b0b0b0;
    }
    
    strong {
      color: #00d9ff;
      font-weight: 600;
    }
    
    ul {
      list-style-type: none;
      padding-left: 20px;
    }
    
    li {
      margin: 12px 0;
      padding-left: 25px;
      position: relative;
      color: #d1d5db;
    }
    
    li:before {
      content: '🚀';
      position: absolute;
      left: 0;
      color: #00d9ff;
    }
    
    a {
      color: #60a5fa;
      text-decoration: none;
      transition: color 0.3s ease, text-shadow 0.3s ease;
      font-weight: 500;
    }
    
    a:hover {
      color: #00d9ff;
      text-decoration: underline;
      text-shadow: 0 0 8px rgba(0, 217, 255, 0.5);
    }
    
    .icons {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin: 20px 0;
      align-items: center;
    }
    
    .icons a {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 45px;
      height: 45px;
      background: rgba(55, 65, 81, 0.5);
      border-radius: 10px;
      transition: all 0.3s ease;
      border: 1px solid transparent;
    }
    
    .icons a:hover {
      background: rgba(0, 217, 255, 0.2);
      border-color: #00d9ff;
      transform: translateY(-3px) scale(1.1);
      box-shadow: 0 5px 15px rgba(0, 217, 255, 0.3);
    }
    
    .icons img {
      filter: brightness(0.9);
      transition: filter 0.3s ease;
    }
    
    .icons a:hover img {
      filter: brightness(1.2);
    }
    
    .tech-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    
    .tech-category {
      background: rgba(40, 40, 60, 0.7);
      padding: 20px;
      border-radius: 10px;
      border-left: 4px solid #00d9ff;
    }
    
    @media (max-width: 768px) {
      body {
        padding: 15px;
      }
      
      h1 {
        font-size: 2rem;
      }
      
      img[align="right"] {
        width: 100%;
        margin: 20px 0;
        float: none;
      }
      
      .icons {
        justify-content: center;
      }
    }
  </style>
</head>
<body>

  <h1 align="center">👋 Hello, I'm Md Firoj Hasan</h1>
  <h3 align="center">Full Stack Web Developer | MERN Stack & Laravel Expert</h3>

  <img align="right" width="400" loading="lazy" src="https://img.freepik.com/free-vector/coding-round-composition_1284-40752.jpg" alt="Developer working on code">

  <section>
    <h2>✨ About Me</h2>
    <p>
      I'm <strong>Md Firoj Hasan</strong>, a passionate <strong>Full Stack Web Developer</strong> from Dhaka, Bangladesh. 
      I specialize in building modern, efficient, and scalable web applications using cutting-edge technologies.
    </p>
    <p>
      My expertise includes the <strong>MERN Stack</strong> (MongoDB, Express.js, React, Node.js), <strong>PHP + Laravel</strong>, 
      and <strong>Next.js</strong> for server-side rendering and production-ready applications.
    </p>
    <p>
      I'm a self-motivated, detail-oriented developer who constantly learns new technologies to stay ahead. 
      I enjoy solving real-world problems and building solutions that make a meaningful impact.
    </p>
  </section>

  <section>
    <h2>📂 Projects & Links</h2>
    <ul>
      <li>💻 Skilled in building <strong>MERN</strong>, <strong>Laravel</strong>, and <strong>Next.js</strong> based full-stack projects</li>
      <li>🎨 Portfolio: <a href="https://grand-starlight-c8411f.netlify.app/" target="_blank">Live Portfolio Website</a></li>
      <li>📧 Email: <strong>mdfirojhasan.info@gmail.com</strong></li>
      <li>📄 Resume: <a href="https://drive.google.com/file/d/1-EjH4BZpbEYbi49DMe7vowt1wp5ctv9l/view?usp=sharing" target="_blank">View/Download Resume</a></li>
      <li>🔗 LinkedIn: <a href="https://www.linkedin.com/in/md-firoj-hasan/" target="_blank">Professional Profile</a></li>
      <li>⚡ Fun Fact: <strong>I believe clean code is an art form! 🎨</strong></li>
    </ul>
  </section>

  <section>
    <h3>🤝 Connect With Me</h3>
    <div class="icons">
      <a href="https://www.linkedin.com/in/md-firoj-hasan/" target="_blank" title="LinkedIn">
        <img src="https://img.icons8.com/color/48/000000/linkedin.png" width="30" alt="LinkedIn"/>
      </a>
      <a href="https://github.com/firoj10" target="_blank" title="GitHub">
        <img src="https://img.icons8.com/ios-glyphs/30/FFFFFF/github.png" width="30" alt="GitHub"/>
      </a>
      <a href="mailto:mdfirojhasan.info@gmail.com" target="_blank" title="Email">
        <img src="https://img.icons8.com/color/48/000000/gmail-new.png" width="30" alt="Email"/>
      </a>
      <a href="https://www.facebook.com/mdfirojhasann" target="_blank" title="Facebook">
        <img src="https://img.icons8.com/color/48/000000/facebook.png" width="30" alt="Facebook"/>
      </a>
    </div>
  </section>

  <section>
    <h2>🚀 Tech Stack</h2>
    <div class="tech-grid">
      <div class="tech-category">
        <h4>Frontend Development</h4>
        <div class="icons">
          <a href="https://reactjs.org/" target="_blank" title="React">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="30" alt="React"/>
          </a>
          <a href="https://nextjs.org/" target="_blank" title="Next.js">
            <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" width="30" alt="Next.js"/>
          </a>
          <a href="https://tailwindcss.com/" target="_blank" title="Tailwind CSS">
            <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="30" alt="Tailwind"/>
          </a>
          <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" title="JavaScript">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="30" alt="JavaScript"/>
          </a>
          <a href="https://getbootstrap.com/" target="_blank" title="Bootstrap">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" width="30" alt="Bootstrap"/>
          </a>
        </div>
      </div>

      <div class="tech-category">
        <h4>Backend Development</h4>
        <div class="icons">
          <a href="https://nodejs.org/" target="_blank" title="Node.js">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="30" alt="Node.js"/>
          </a>
          <a href="https://expressjs.com/" target="_blank" title="Express.js">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" width="30" alt="Express.js"/>
          </a>
          <a href="https://www.mongodb.com/" target="_blank" title="MongoDB">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" width="30" alt="MongoDB"/>
          </a>
          <a href="https://www.php.net/" target="_blank" title="PHP">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" width="30" alt="PHP"/>
          </a>
          <a href="https://laravel.com/" target="_blank" title="Laravel">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original-wordmark.svg" width="30" alt="Laravel"/>
          </a>
        </div>
      </div>
    </div>

    <h4>Additional Tools & Libraries</h4>
    <div class="icons">
      <a href="https://redux.js.org/" target="_blank" title="Redux">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" width="25" alt="Redux"/>
      </a>
      <a href="https://axios-http.com/" target="_blank" title="Axios">
        <img src="https://axios-http.com/assets/logo.svg" width="25" alt="Axios"/>
      </a>
      <a href="https://www.postman.com/" target="_blank" title="Postman">
        <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" width="25" alt="Postman"/>
      </a>
      <a href="https://www.figma.com/" target="_blank" title="Figma">
        <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="25" alt="Figma"/>
      </a>
      <a href="https://git-scm.com/" target="_blank" title="Git">
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="25" alt="Git"/>
      </a>
      <a href="https://vercel.com/" target="_blank" title="Vercel">
        <img src="https://www.vectorlogo.zone/logos/vercel/vercel-icon.svg" width="25" alt="Vercel"/>
      </a>
      <a href="https://vitejs.dev/" target="_blank" title="Vite">
        <img src="https://vitejs.dev/logo.svg" width="25" alt="Vite"/>
      </a>
    </div>
  </section>

  <script>
    // Add smooth scrolling
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
          target.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
          });
        }
      });
    });

    // Add animation to icons on page load
    document.addEventListener('DOMContentLoaded', () => {
      const icons = document.querySelectorAll('.icons a');
      icons.forEach((icon, index) => {
        setTimeout(() => {
          icon.style.opacity = '0';
          icon.style.transform = 'translateY(20px)';
          icon.offsetHeight; // Trigger reflow
          icon.style.transition = 'all 0.5s ease';
          icon.style.opacity = '1';
          icon.style.transform = 'translateY(0)';
        }, index * 100);
      });
    });
  </script>

</body>
</html>
