<p align="left">Hi there, I'm Diya👋<br><br>I'm a creative problem-solver with a passion for **design, development, and all things tech**</p>


###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" height="40" alt="figma logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="40" alt="c logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="cplusplus logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" height="40" alt="canva logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="django logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>

###

<div align="left">
  <a href="https://www.linkedin.com/in/diya-sharma-84a5872b9/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"  />
  </a>
  <a href="discordapp.com/users/734287479372382222" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="52" height="40" alt="discord logo"  />
  </a>
</div>

###

<div align="center">
  <img height="200" src="https://media1.tenor.com/m/A5RWQDxbE-cAAAAd/kenma.gif"  />
</div>

###

<div align="center">
  <img src="https://profile-counter.glitch.me/dizzcreet/count.svg?"  />
</div>
<div align="center">
  <canvas id="pacmanCanvas" width="600" height="100"></canvas>
</div>

<script>
  const contributions = [0, 0, 0, 0, 5, 2]; // Replace with real data
  const canvas = document.getElementById('pacmanCanvas');
  const ctx = canvas.getContext('2d');

  function draw() {
    // Draw dots
    contributions.forEach((count, i) => {
      for (let j = 0; j < count; j++) {
        ctx.beginPath();
        ctx.arc(50 + i * 100, 30 + j * 15, 5, 0, Math.PI * 2);
        ctx.fillStyle = '#26a641'; // GitHub green
        ctx.fill();
      }
    });

    // Draw Pacman
    ctx.beginPath();
    ctx.arc(50 + (contributions.length - 1) * 100, 50, 20, 0.2, 1.8 * Math.PI);
    ctx.lineTo(50 + (contributions.length - 1) * 100, 50);
    ctx.fillStyle = '#ffdf00';
    ctx.fill();
  }
  draw();
</script>

###

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dizzcreet/dizzcreet/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dizzcreet/dizzcreet/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/dizzcreet/dizzcreet/output/pacman-contribution-graph.svg">
</picture>

###
