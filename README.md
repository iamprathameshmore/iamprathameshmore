<style.css>
  @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;800&display=swap");

:root {
  --bg: #000000;
  --clr-1: #00c2ff;
  --clr-2: #33ff8c;
  --clr-3: #ffc640;
  --clr-4: #e54cff;

  --blur: 1rem;
  --fs: clamp(3rem, 8vw, 7rem);
  --ls: clamp(-1.75px, -0.25vw, -3.5px);
}

body {
  min-height: 100vh;
  display: grid;
  place-items: center;
  background-color: var(--bg);
  color: #fff;
  font-family: "Inter", "DM Sans", Arial, sans-serif;
}

*,
*::before,
*::after {
  font-family: inherit;
  box-sizing: border-box;
}

.content {
  text-align: center;
}

.title {
  font-size: var(--fs);
  font-weight: 800;
  letter-spacing: var(--ls);
  position: relative;
  overflow: hidden;
  background: var(--bg);
  margin: 0;
}

.subtitle {
}

.aurora {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 2;
  mix-blend-mode: darken;
  pointer-events: none;
}

.aurora__item {
  overflow: hidden;
  position: absolute;
  width: 60vw;
  height: 60vw;
  background-color: var(--clr-1);
  border-radius: 37% 29% 27% 27% / 28% 25% 41% 37%;
  filter: blur(var(--blur));
  mix-blend-mode: overlay;
}

.aurora__item:nth-of-type(1) {
  top: -50%;
  animation: aurora-border 6s ease-in-out infinite,
    aurora-1 12s ease-in-out infinite alternate;
}

.aurora__item:nth-of-type(2) {
  background-color: var(--clr-3);
  right: 0;
  top: 0;
  animation: aurora-border 6s ease-in-out infinite,
    aurora-2 12s ease-in-out infinite alternate;
}

.aurora__item:nth-of-type(3) {
  background-color: var(--clr-2);
  left: 0;
  bottom: 0;
  animation: aurora-border 6s ease-in-out infinite,
    aurora-3 8s ease-in-out infinite alternate;
}

.aurora__item:nth-of-type(4) {
  background-color: var(--clr-4);
  right: 0;
  bottom: -50%;
  animation: aurora-border 6s ease-in-out infinite,
    aurora-4 24s ease-in-out infinite alternate;
}

@keyframes aurora-1 {
  0% {
    top: 0;
    right: 0;
  }

  50% {
    top: 100%;
    right: 75%;
  }

  75% {
    top: 100%;
    right: 25%;
  }

  100% {
    top: 0;
    right: 0;
  }
}

@keyframes aurora-2 {
  0% {
    top: -50%;
    left: 0%;
  }

  60% {
    top: 100%;
    left: 75%;
  }

  85% {
    top: 100%;
    left: 25%;
  }

  100% {
    top: -50%;
    left: 0%;
  }
}

@keyframes aurora-3 {
  0% {
    bottom: 0;
    left: 0;
  }

  40% {
    bottom: 100%;
    left: 75%;
  }

  65% {
    bottom: 40%;
    left: 50%;
  }

  100% {
    bottom: 0;
    left: 0;
  }
}

@keyframes aurora-4 {
  0% {
    bottom: -50%;
    right: 0;
  }

  50% {
    bottom: 0%;
    right: 40%;
  }

  90% {
    bottom: 50%;
    right: 25%;
  }

  100% {
    bottom: -50%;
    right: 0;
  }
}

@keyframes aurora-border {
  0% {
    border-radius: 37% 29% 27% 27% / 28% 25% 41% 37%;
  }

  25% {
    border-radius: 47% 29% 39% 49% / 61% 19% 66% 26%;
  }

  50% {
    border-radius: 57% 23% 47% 72% / 63% 17% 66% 33%;
  }

  75% {
    border-radius: 28% 49% 29% 100% / 93% 20% 64% 25%;
  }

  100% {
    border-radius: 37% 29% 27% 27% / 28% 25% 41% 37%;
  }
}

</style.css>

<div class="content">
  <h1 class="title">Iamprathameshmore
    <div class="aurora">
      <div class="aurora__item"></div>
      <div class="aurora__item"></div>
      <div class="aurora__item"></div>
      <div class="aurora__item"></div>
    </div>
  </h1>
  <p class="subtitle">Made with love and only the CSS.</p>
</div>


<h1 align="left">Hello, ✌️ Iamprathameshmore</h1>

###

<p align="left">🚀 Software Engineer passionate about crafting elegant solutions to complex problems. <br>💻 Full-stack developer proficient in multiple languages and frameworks. <br>🌐 Enthusiastic about web technologies and building user-centric applications.<br>🌟 Open-source advocate, always eager to collaborate and learn from the community. <br>🎮 Gamer at heart, finding parallels between coding and gaming strategies.<br> 📚 Continuous learner, exploring new horizons in tech. Let's connect and code the future together!<br> 🌈 #CodeWizard #OpenSourceEnthusiast</p>

###

<h2 align="left">About me</h2>

###

<p align="left">✨ Creating bugs since ...<br>📚 I'm currently learning ...<br>🎯 Goals: ...<br>🎲 Fun fact: ...</p>

###

<h2 align="left">Skills and Technology</h2>

###

<h5 align="left">Skilled freelance graphic designer with over a decade of experience in the field. Dedicated to staying up-to-date on new techniques and procedures related to graphic design. Excel at web platform development, desktop publishing, computer aided design, and video creation and editing software programs. Managed multiple projects simultaneously. Excellent communicator able to work as part of a team or as the sole designer.</h5>

###

<h5 align="left">1. Programming Langueges</h5>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="40" alt="csharp logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" height="40" alt="arduino logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" height="40" alt="kotlin logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="40" alt="dart logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" height="40" alt="r logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height="40" alt="matlab logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" height="40" alt="rust logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/phpstorm/phpstorm-original.svg" height="40" alt="phpstorm logo"  />
</div>

###

<h5 align="left">2. Fream-Works</h5>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="fastapi logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/androidstudio/androidstudio-original.svg" height="40" alt="androidstudio logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="40" alt="angularjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="flask logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
</div>

###

<h5 align="left">3. DataBase</h5>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="mongodb logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="40" alt="firebase logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" height="40" alt="googlecloud logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" height="40" alt="azure logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/digitalocean/digitalocean-original.svg" height="40" alt="digitalocean logo"  />
</div>

###

<h5 align="left">4. Operating System</h5>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="linux logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" height="40" alt="windows8 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fedora/fedora-original.svg" height="40" alt="fedora logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" height="40" alt="ubuntu logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opensuse/opensuse-original.svg" height="40" alt="opensuse logo"  />
</div>

###

<img src="https://raw.githubusercontent.com/iamprathameshmore/iamprathameshmore/output/snake.svg" alt="Snake animation" />

###

<h2 align="left">Social Media Link's</h2>

###

<div align="left">
  <a href="https://www.linkedin.com/in/iamprathameshmore" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="45" height="30" alt="linkedin logo"  />
  </a>
  <a href="iamprathameshmore07@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="45" height="30" alt="gmail logo"  />
  </a>
</div>

###
