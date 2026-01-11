<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Andrea Vanni</title>
  <link rel="stylesheet" href="static/css/style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.css" />
</head>

<body>
  <div id="particles-js"></div>
  <script src="static/js/particles.js"></script>
  <script src="static/js/app.js"></script>
  <div id="overlay"></div>

  <article>
    <nav id="navbar">
      <div class="left">
        <a href="static/attachments/Andrea Vanni.pdf" class="btn bold" target="_blank" download>
          Download CV
        </a>
      </div>
      <i class="fa-solid fa-bars" id="linksBtn"></i>
      <div class="right">
        <a href="#about" class="link bold">About me</a>
        <a href="#skills" class="link bold">Skills</a>
        <a href="#certs" class="link bold">Certifications</a>
        <a href="#prizes" class="link bold">Prizes</a>
        <a href="#projects" class="link bold">My Projects</a>
        <a href="#contactme" class="link bold">Contact me</a>
      </div>
    </nav>
    <section id="about">
      <h1 class="sectiontitle">About me</h1>
      <img src="static/imgs/pfp.png" style="
            border-radius: 50%;
            width: 100%;
            max-height: 400px;
            max-width: 400px;
            border: 5px solid white;
          " alt />
      <p>
        Hello! I'm <b>IRVANNI</b> (online alias) and my name is <b>Andrea</b>.
        I'm an Italian enthusiast deeply passionate about computer science,
        with a strong focus on <b>backend development</b> and
        <b>cybersecurity</b>. I thrive on solving complex problems and
        continuously expanding my technical expertise. In my spare time, I
        actively participate in programming and cybersecurity competitions,
        which allow me to sharpen my skills and stay ahead in these
        ever-evolving fields.
      </p>
    </section>
    <section id="skills">
      <h1 class="sectiontitle">Skills</h1>
      <div class="skills-container">
        <div class="skills-category">
          <div class="skills-header">
            <h2 class="sectionsubtitle">Programming Languages</h2>
            <div class="skills-level-indicator">
              <span class="level-dot beginner"></span>Beginner
              <span class="level-dot intermediate"></span>Intermediate
              <span class="level-dot advanced"></span>Advanced
            </div>
          </div>
          <div class="skills-grid">
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/python.png" class="pSkill" alt="Python" />
              <span class="skill-name">Python</span>
            </div>
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/nodejs.png" class="pSkill" alt="Node.js" />
              <span class="skill-name">Node.js</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/c++.png" class="pSkill" alt="C++" />
              <span class="skill-name">C++</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/java.png" class="pSkill" alt="Java" />
              <span class="skill-name">Java</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/assembly.png" class="pSkill" alt="Assembly" />
              <span class="skill-name">Assembly</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/dart.png" class="pSkill" alt="Dart" />
              <span class="skill-name">Dart</span>
            </div>
            <div class="skill-item" data-level="beginner">
              <img src="static/imgs/c.png" class="pSkill" alt="C" />
              <span class="skill-name">C</span>
            </div>
          </div>
        </div>
        <div class="skills-category">
          <h2 class="sectionsubtitle">Web & App Development</h2>
          <div class="skills-grid">
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/html.png" class="pSkill" alt="HTML" />
              <span class="skill-name">HTML</span>
            </div>
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/css.png" class="pSkill" alt="CSS" />
              <span class="skill-name">CSS</span>
            </div>
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/javascript.png" class="pSkill" alt="JavaScript" />
              <span class="skill-name">JavaScript</span>
            </div>
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/flask.png" class="pSkill" alt="Flask" />
              <span class="skill-name">Flask</span>
            </div>
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/express-js.png" class="pSkill" alt="Express.js" />
              <span class="skill-name">Express.js</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/php.png" class="pSkill" alt="PHP" />
              <span class="skill-name">PHP</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/flutter.png" class="pSkill" alt="Flutter" />
              <span class="skill-name">Flutter</span>
            </div>
            <div class="skill-item" data-level="beginner">
              <img src="static/imgs/laravel.png" class="pSkill" alt="Laravel" />
              <span class="skill-name">Laravel</span>
            </div>
          </div>
        </div>
        <div class="skills-category">
          <h2 class="sectionsubtitle">Other Skills</h2>
          <div class="skills-grid">
            <div class="skill-item" data-level="advanced">
              <img src="static/imgs/sql.png" class="pSkill" alt="SQL" />
              <span class="skill-name">SQL</span>
            </div>
            <div class="skill-item custom-skill" data-level="advanced">
              <i class="fas fa-search pSkill"></i>
              <span class="skill-name">OSINT</span>
            </div>
            <div class="skill-item custom-skill" data-level="advanced">
              <i class="fas fa-puzzle-piece pSkill"></i>
              <span class="skill-name">Problem Solving</span>
            </div>
            <div class="skill-item custom-skill" data-level="advanced">
              <i class="fas fa-people-group pSkill"></i>
              <span class="skill-name">Team Working</span>
            </div>
            <div class="skill-item custom-skill" data-level="intermediate">
              <i class="fa-brands fa-docker pSkill"></i>
              <span class="skill-name">Docker</span>
            </div>
            <div class="skill-item custom-skill" data-level="intermediate">
              <i class="fa-brands fa-git-alt pSkill"></i>
              <span class="skill-name">Git</span>
            </div>
            <div class="skill-item" data-level="intermediate">
              <img src="static/imgs/bash.png" class="pSkill" alt="Bash" />
              <span class="skill-name">Bash</span>
            </div>
            <div class="skill-item custom-skill" data-level="intermediate">
              <i class="fas fa-shield-alt pSkill"></i>
              <span class="skill-name">Digital Forensics</span>
            </div>
            <div class="skill-item custom-skill" data-level="intermediate">
              <i class="fas fa-bug pSkill"></i>
              <span class="skill-name">Vulnerability Assessment</span>
            </div>
            <div class="skill-item custom-skill" data-level="beginner">
              <i class="fas fa-robot pSkill"></i>
              <span class="skill-name">AI</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- CERTIFICATIONS SECTION -->
    <section id="certs">
      <h1 class="sectiontitle">Certifications</h1>
      <div class="certs-container">
        <div class="certs-timeline">
          <!-- <div class="cert-item">
            <div class="cert-icon-container">
              <img src="static/imgs/iispisa.png" alt="Certification 1" class="cert-icon" />
            </div>
            <div class="cert-content">
              <h3>I.I.S. "L. da Vinci - Fascetti"</h3>
              <span class="cert-date">2026</span>
              <p>
                I graduated from the "I.I.S. L. da Vinci – Fascetti" high
                school, specializing in the computer science track. During my
                time there, I gained a solid foundation in programming,
                software development, and IT systems, which prepared me for
                further studies and a career in the tech industry. The school
                provided a challenging and enriching environment that helped
                me develop both technical and problem-solving skills.
              </p>
              <a href="static/attachments/Diploma.pdf" target="_blank" class="btn cert-btn" download>View
                Certificate</a>
            </div>
          </div> -->
          <div class="cert-item">
            <div class="cert-icon-container">
              <img src="static/imgs/icdl.png" alt="Certification 4" class="cert-icon" />
            </div>
            <div class="cert-content">
              <h3>
                ICDL Full Standard
              </h3>
              <span class="cert-date">2023</span>
              <p>
                I have achieved the International Certification of Digital
                Literacy (ICDL) Full Standard, a comprehensive certification
                that validates my proficiency across a wide range of digital
                skills. This certification covers essential areas such as
                computer essentials, online collaboration, word processing,
                spreadsheets, IT security, and more, ensuring a well-rounded
                understanding of digital tools and technologies. Earning the
                ICDL Full Standard demonstrates my ability to confidently and
                effectively navigate the digital world, making me
                well-prepared for both academic and professional challenges in
                today's technology-driven environment.
              </p>
              <a href="static/attachments/ICDL_Certificato ICDL Full Standard_2330322.pdf" target="_blank"
                class="btn cert-btn" download>View Certificate</a>
            </div>
          </div>
          <div class="cert-item">
            <div class="cert-icon-container">
              <img src="static/imgs/icdl.png" alt="Certification 3" class="cert-icon" />
            </div>
            <div class="cert-content">
              <h3>
                ICDL IT-Security
              </h3>
              <span class="cert-date">2022</span>
              <p>
                I have earned the International Certification of Digital
                Literacy (ICDL) in IT Security, which certifies my
                understanding of essential concepts and practices for
                safeguarding digital systems and data. This certification has
                equipped me with the knowledge to identify potential cyber
                threats, implement security measures, and protect sensitive
                information in both personal and professional contexts.
                Achieving this certification highlights my commitment to
                maintaining a secure digital environment and underscores my
                proficiency in managing IT security challenges effectively.
              </p>
              <a href="static/attachments/ICDL_Certificato IT Security_2330322.pdf" target="_blank" class="btn cert-btn"
                download>View Certificate</a>
            </div>
          </div>
          <div class="cert-item">
            <div class="cert-icon-container">
              <img src="static/imgs/icdl.png" alt="Certification 2" class="cert-icon" />
            </div>
            <div class="cert-content">
              <h3>ICDL Base</h3>
              <span class="cert-date">2022</span>
              <p>
                I have obtained the International Certification of Digital
                Literacy (ICDL) Base, which validates my foundational skills
                in essential digital competencies. This certification covers
                key areas such as computer essentials, online collaboration,
                word processing, and spreadsheets, demonstrating my ability to
                effectively use digital tools and technologies. Achieving this
                certification has strengthened my confidence in navigating the
                digital world and has provided me with a strong base for
                further developing my technical expertise.
              </p>
              <a href="static/attachments/ICDL_Certificato ECDL Base_2330322.pdf" target="_blank" class="btn cert-btn"
                download>View Certificate</a>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- PRIZES SECTION -->
    <section id="prizes">
      <h1 class="sectiontitle">Prizes</h1>
      <div class="prizes-container">
        <div class="prize-item highlight">
          <div class="prize-icon">
            <i class="fas fa-shield-halved"></i>
          </div>
          <div class="prize-content">
            <h3>50th Place - Olicyber - Italian Cybersecurity Olympiad</h3>
            <span class="prize-date">2025</span>
            <p>
              In 2025, I took part in the Italian Cybersecurity Olympics, ranking 50th. The final stage took place in
              Salerno and allowed me to try my hand at practical exercises in discovery and vulnerability analysis,
              strengthening my technical and strategic approach.
            </p>
            <img src="./static/imgs/olicyber2025.jpg" class="styled-image img-bordered" width="500" alt="olicyber 2023">
            <div class="prize-details">
              <span class="prize-detail"><i class="fas fa-map-marker-alt"></i>
                Salerno, Italy</span>
              <span class="prize-detail"><i class="fas fa-users"></i> 450+
                Participants</span>
            </div>
          </div>
        </div>
        <div class="prize-item highlight">
          <div class="prize-icon">
            <i class="fas fa-euro"></i>
          </div>
          <div class="prize-content">
            <h3>2nd Place - C(o)De – Challenge of Developers</h3>
            <span class="prize-date">2024</span>
            <p>
              I secured 2nd place in the C(o)De – Challenge of Developers 2024
              as part of a four-member team. Together, we demonstrated strong
              collaboration, technical expertise, and problem-solving skills,
              earning a prize of 700€ for our performance. This achievement
              highlights my ability to work effectively in a team and deliver
              results in competitive, high-pressure environments.
            </p>
            <img src="./static/imgs/codechallenge.jpg" class="styled-image img-bordered" width="300"
              alt="Code challenge RJC SOFT">
            <div class="prize-details">
              <span class="prize-detail"><i class="fas fa-map-marker-alt"></i>
                Pisa, Italy</span>
              <span class="prize-detail"><i class="fas fa-users"></i> 60+
                Participants</span>
            </div>
          </div>
        </div>
        <div class="prize-item highlight">
          <div class="prize-icon">
            <i class="fas fa-medal"></i>
          </div>
          <div class="prize-content">
            <h3>29th Place - Olicyber - Italian Cybersecurity Olympiad</h3>
            <span class="prize-date">2024</span>
            <p>
              I won a bronze medal in the Italian Cybersecurity Olympiad, a
              7-hour final competition focused on identifying
              vulnerabilities in applications and systems. This achievement
              reflects my technical skills, problem-solving
              abilities, and passion for cybersecurity, further motivating me
              to pursue a career in this field.
            </p>
            <img src="./static/imgs/olicyber2024.jpg" class="styled-image img-bordered" width="500" alt="olicyber 2024">
            <div class="prize-details">
              <span class="prize-detail"><i class="fas fa-map-marker-alt"></i>
                Turin, Italy</span>
              <span class="prize-detail"><i class="fas fa-users"></i> 450+
                Participants</span>
            </div>
          </div>
        </div>
        <div class="prize-item highlight">
          <div class="prize-icon">
            <i class="fas fa-fire"></i>
          </div>
          <div class="prize-content">
            <h3>63rd Place - Olicyber - Italian Cybersecurity Olympiad</h3>
            <span class="prize-date">2023</span>
            <p>
              I participated in the Italian Cybersecurity Olympiad 2023,
              finishing in 63rd place. Although I didn't win a medal,
              the experience of competing in this challenging event, which
              focused on identifying vulnerabilities in applications
              and systems, was incredibly valuable. It allowed me to test my
              technical skills, improve my problem-solving abilities,
              and deepen my passion for cybersecurity, further motivating me
              to grow in this field.
            </p>
            <img src="./static/imgs/olicyber2023.jpg" class="styled-image img-bordered" width="500" alt="olicyber 2023">
            <div class="prize-details">
              <span class="prize-detail"><i class="fas fa-map-marker-alt"></i>
                Turin, Italy</span>
              <span class="prize-detail"><i class="fas fa-users"></i> 550+
                Participants</span>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- PROJECTS SECTION -->
    <section id="projects">
      <h1 class="sectiontitle">My Projects</h1>
      <div class="projects-showcase">
        <div class="project-item featured">
          <div class="project-image">
            <div class="project-thumbnail">
              <img src="./static/imgs/livesecurechatservice.png" width="300" alt="">
            </div>
          </div>
          <div class="project-info">
            <div class="project-tags">
              <span class="project-tag">Python</span>
              <span class="project-tag">Flask</span>
              <span class="project-tag">WebSocket</span>
              <span class="project-tag">Tor</span>
              <span class="project-tag">Threading</span>
            </div>
            <h3>Live Secure Chat</h3>
            <p>
              This project is a Live Secure Chat, an open communication platform designed to ensure privacy and
              security. Anyone can join, with or without a password, and all exchanged information is protected through
              the use of the Tor network, which encrypts data and anonymizes connections. The goal is to provide a safe
              space for confidential conversations, where users can communicate freely without worrying about
              interception or privacy breaches. It's ideal for those seeking a secure and anonymous environment to share
              ideas, information, or simply chat with complete peace of mind.
            </p>
            <div class="project-links">
              <!-- <a href="#" class="btn">View Project</a> -->
              <a href="https://github.com/HirAvanCniK/live-secure-chat-service" target="_blank"
                class="btn btn-outline">GitHub <i class="fab fa-github"></i></a>
            </div>
          </div>
        </div>
        <div class="projects-grid">
          <div class="project-item">
            <div class="project-thumbnail">
              <i class="fas fa-robot"></i>
            </div>
            <div class="project-tags">
              <span class="project-tag">Node.js</span>
              <span class="project-tag">Discord API</span>
              <span class="project-tag">Database</span>
            </div>
            <h3>Discord Bot multi-function</h3>
            <p>
              This Discord bot, developed in Node.js using the discord.js library, is a versatile tool designed to
              enhance server experiences with a wide range of functionalities. It features organized commands including
              music playback, server moderation, entertaining interactions, educational utilities, controlled NSFW
              content, practical tools, and informational resources. Ideal for diverse communities, it combines
              entertainment, utility, and management in one comprehensive package. </p>
            <div class="project-links">
              <!-- <a href="#" class="btn">View Project</a> -->
              <a href="https://github.com/HirAvanCniK/IRVANNI-Discord-Bot" target="_blank" class="project-link"><i
                  class="fab fa-github"></i></a>
            </div>
          </div>
          <!-- <div class="project-item">
            <div class="project-thumbnail">
              <i class="fas fa-mobile-alt"></i>
            </div>
            <div class="project-tags">
              <span class="project-tag">Flutter</span>
              <span class="project-tag">Firebase</span>
            </div>
            <h3>Project Gamma</h3>
            <p>
              A mobile app for managing personal finances, developed using
              Flutter and Firebase.
            </p>
            <div class="project-links">
              <a href="#" class="btn">View Project</a>
              <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
          </div> -->
          <!-- <div class="project-item">
            <div class="project-thumbnail">
              <i class="fas fa-database"></i>
            </div>
            <div class="project-tags">
              <span class="project-tag">SQL</span>
              <span class="project-tag">Python</span>
            </div>
            <h3>Project Delta</h3>
            <p>
              A data analysis tool that processes large datasets and generates
              visual reports for business intelligence.
            </p>
            <div class="project-links">
              <a href="#" class="btn">View Project</a>
              <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
          </div> -->
        </div>
      </div>
    </section>
    <!-- CONTACTME SECTION -->
    <section id="contactme">
      <h1 class="sectiontitle">Contact Me</h1>
      <div class="contact-container">
        <div class="contact-info">
          <h2 class="sectionsubtitle">Get in Touch</h2>
          <p>
            If you have any questions, collaboration proposals, or just want
            to say hi, feel free to reach out. I'm always open to new
            opportunities and interesting conversations!
          </p>
          <div class="contact-details">
            <div class="contact-item">
              <i class="fas fa-envelope"></i>
              <a href="mailto:vanniandrea244466666@gmail.com">vanniandrea244466666@gmail.com</a>
            </div>
            <div class="contact-item">
              <i class="fas fa-map-marker-alt"></i>
              <span>Pisa, Italy</span>
            </div>
          </div>
        </div>
        <div class="social-links">
          <h2 class="sectionsubtitle">Contact me</h2>
          <div class="social-icons">
            <a href="https://github.com/HirAvanCniK" target="_blank" class="social-link">
              <i class="fab fa-github"></i>
              <span>GitHub</span>
            </a>
            <a href="https://x.com/AndreaVanni15" target="_blank" class="social-link">
              <i class="fab fa-twitter"></i>
              <span>Twitter</span>
            </a>
            <a href="https://it.linkedin.com/" target="_blank" class="social-link">
              <i class="fab fa-linkedin-in"></i>
              <span>LinkedIn</span>
            </a>
          </div>
        </div>
      </div>
    </section>
  </article>
  <footer>
    <i>&copy;
      <script>document.write(new Date().getFullYear())</script> IRVANNI. All rights reserved.
    </i>
  </footer>
  <script src="static/js/script.js"></script>
</body>

</html>
