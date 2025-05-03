<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Fernand's Profile</title>
  <style>
    h1, h3 {
      text-align: center;
      font-family: Arial, sans-serif;
    }

    #animated-text {
      transition: opacity 1s ease-in-out;
      opacity: 1;
    }

    .fade-out {
      opacity: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
    }

    table {
      margin: auto;
    }

    hr {
      margin: 2em 0;
    }

    a {
      text-decoration: none;
      color: inherit;
    }
  </style>
</head>
<body>

<h1 align="center">Hello, Wonderful World 🌎 I'm Fernand!</h1>
<h3 id="animated-text">Future CEO</h3>

<script>
  const phrases = [
    "Future CEO",
    "Cloud Chaser",
    "Content Creator",
    "Lifelong Learner from the Philippines 🇵🇭"
  ];

  const textElement = document.getElementById("animated-text");
  let index = 0;

  setInterval(() => {
    textElement.classList.add("fade-out");
    setTimeout(() => {
      index = (index + 1) % phrases.length;
      textElement.textContent = phrases[index];
      textElement.classList.remove("fade-out");
    }, 1000);
  }, 3000);
</script>

<hr>

<h3>🌟 About Me</h3>
<div align="center">
  <table>
    <tr><td>🔍</td><td><strong>Currently Exploring</strong></td><td>Google Cloud Platform</td></tr>
    <tr><td>💻</td><td><strong>Projects</strong></td><td><a href="https://youtube.com/@fernandangeloorbase">youtube.com/@fernandangeloorbase</a></td></tr>
    <tr><td>📬</td><td><strong>Let's Connect</strong></td><td>fernandangeloorbase@gmail.com</td></tr>
    <tr><td>🍃</td><td><strong>Fun Fact</strong></td><td>I Touch Grass 🌾</td></tr>
  </table>
</div>

<hr>

<h3>📱 Connect with Me</h3>
<p align="center">
  <a href="https://linkedin.com/in/fernand-angelo-orbase-026015203/" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" />
  </a>
  <a href="https://facebook.com/FERNANDonYT" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="30" width="40" />
  </a>
  <a href="https://tiktok.com/FERNANDonYT" target="_blank">
    <img src="https://cdn.worldvectorlogo.com/logos/tiktok-icon-2.svg" alt="TikTok" height="30" width="40" />
  </a>
  <a href="https://instagram.com/fernand.on.yt" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40" />
  </a>
  <a href="https://www.youtube.com/@fernandonyt" target="_blank">
    <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" height="30" width="40" />
  </a>
</p>

<hr>

<h3>🛠️ Skills & Tools</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="40" height="40"/>
  <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="Angular" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Adobe_Creative_Cloud_rainbow_icon.svg/360px-Adobe_Creative_Cloud_rainbow_icon.svg.png" alt="Adobe Creative Cloud" width="40" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/DaVinci_Resolve_17_logo.svg/98px-DaVinci_Resolve_17_logo.svg.png?20211228192035" alt="Davinci Resolve" width="40" height="40"/>
  <img src="https://res-1.cdn.office.net/files/fabric-cdn-prod_20230815.002/assets/brand-icons/product/svg/m365_48x1.svg" alt="Microsoft 365" width="40" height="40"/>
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="Google Cloud" width="40" height="40"/>
</p>

<hr>

<h3>📊 GitHub Insights</h3>
<div align="center">
  <img src="https://raw.githubusercontent.com/fernandorbase/fernand-orbase/master/profile-summary-card-output/vue/0-profile-details.svg"/>
  <img src="https://raw.githubusercontent.com/fernandorbase/fernand-orbase/master/profile-summary-card-output/vue/1-repos-per-language.svg"/>
  <img src="https://raw.githubusercontent.com/fernandorbase/fernand-orbase/master/profile-summary-card-output/vue/2-most-commit-language.svg"/>
  <img src="https://raw.githubusercontent.com/fernandorbase/fernand-orbase/master/profile-summary-card-output/vue/3-stats.svg"/>
  <img src="https://raw.githubusercontent.com/fernandorbase/fernand-orbase/master/profile-summary-card-output/vue/4-productive-time.svg"/>
</div>

<hr>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=fernandorbase&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

</body>
</html>
