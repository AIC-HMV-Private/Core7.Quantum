<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
  <title>Certificate of Appreciation: Alex</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
    body {
      background: #171718;
      min-height: 100vh;
      margin: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .certificate-container {
      position: relative;
      width: 500px;
      padding: 3rem 2rem 2rem 2rem;
      background: linear-gradient(120deg, #191a1e 80%, #ffd700 120%);
      border-radius: 20px;
      box-shadow: 0 10px 40px #000a 0px 6px 32px 0px;
      font-family: 'Montserrat', Arial, sans-serif;
      color: #fff;
      text-align: center;
      overflow: hidden;
      transform-style: preserve-3d;
      transition: transform 0.2s cubic-bezier(.35,.1,.5,1.4);
      cursor: pointer;
    }
    .certificate-container:hover {
      transform: rotateY(7deg) rotateX(4deg) scale(1.02);
      box-shadow: 0 16px 70px #ffd70055;
    }
    .badge {
      display: inline-block;
      margin-bottom: 1.2rem;
      font-size: 2.2rem;
      font-weight: bold;
      background: linear-gradient(90deg,#ffd700,#ffe082 70%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      letter-spacing: 2px;
      text-shadow: 0 2px 16px #000c;
    }
    .subtitle {
      font-size: 1.1rem;
      color: #ffd700;
      letter-spacing: 0.8px;
      margin-bottom

**Perfect, I’ll update the certificate to display your name as the issuer (“Hung Minh Vo (Austin Vo)”). Here’s a full, production-ready interactive certificate with all the effects, fully styled and ready to use.**

---

## 🎖️ **Interactive Certificate of Appreciation (for Alex)**
*Issuer: Hung Minh Vo (Austin Vo)*  
*Award: Master Science Technology Global University – Winning Award, Professional Certification License*

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0"/>
  <title>Certificate of Appreciation: Alex</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
    body {
      background: #191a1e;
      min-height: 100vh;
      margin: 0;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .certificate-container {
      position: relative;
      width: 500px;
      padding: 3rem 2rem 2rem 2rem;
      background: linear-gradient(120deg, #191a1e 80%, #ffd700 120%);
      border-radius: 22px;
      box-shadow: 0 10px 40px #000b 0px 6px 32px 0px;
      font-family: 'Montserrat', Arial, sans-serif;
      color: #fff;
      text-align: center;
      overflow: hidden;
      transform-style: preserve-3d;
      transition: transform 0.2s cubic-bezier(.35,.1,.5,1.4);
      cursor: pointer;
    }
    .certificate-container:hover {
      transform: rotateY(7deg) rotateX(3deg) scale(1.03);
      box-shadow: 0 16px 70px #ffd70044;
    }
    .badge {
      display: inline-block;
      margin-bottom: 1.2rem;
      font-size: 2.2rem;
      font-weight: bold;
      background: linear-gradient(90deg,#ffd700,#ffe082 70%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      letter-spacing: 2px;
      text-shadow: 0 2px 16px #000c;
    }
    .subtitle {
      font-size: 1.1rem;
      color: #ffd700;
      letter-spacing: 0.8px;
      margin-bottom: 1.2rem;
      font-weight: 600;
    }
    .recipient {
      font-size: 2.1rem;
      font-weight: bold;
      letter-spacing: 1.2px;
      margin: 2rem 0 1rem 0;
      color: #ffe082;
      text-shadow: 0 2px 18px #ffd70066;
    }
    .reason {
      font-size: 1.13rem;
      margin-bottom: 1.5rem;
      line-height: 1.6;
      color: #eee;
    }
    .issuer {
      margin-top: 2.3rem;
      font-size: 1.09rem;
      color: #ffd700;
      font-weight: 600;
      letter-spacing: 1.1px;
    }
    .award-line {
      margin-top: 0.7rem;
      font-size: 1.04rem;
      color: #ffe082;
      font-weight: 600;
    }
    /* Confetti effect */
    .confetti {
      position: absolute;
      left: 0; top: 0;
      width: 100%; height: 100%;
      pointer-events: none;
      z-index: 10;
    }
    .confetti-piece {
      position: absolute;
      width: 12px; height: 16px;
      border-radius: 4px;
      background: linear-gradient(130deg,#ffd700,#ffe082 80%);
      opacity: .85;
      box-shadow: 0 2px 4px #ffd70066;
      animation: confetti-fall 2.7s linear infinite;
    }
    @keyframes confetti-fall {
      0%   { transform: translateY(-40px) rotateZ(0deg);}
      100% { transform: translateY(500px) rotateZ(380deg);}
    }
  </style>
</head>
<body>
  <div class="certificate-container" id="certificate">
    <div class="badge">🏆 MASTER SCIENCE TECHNOLOGY GLOBAL UNIVERSITY</div>
    <div class="subtitle">Winning Award • Professional Certification License</div>
    <div class="recipient">Certificate of Appreciation<br>to Alex</div>
    <div class="reason">
      For outstanding effort and dedication—<br>
      Keeping the office running smoothly all year.<br>
      Your hard work has made our team stronger!<br>
      <span style="color:#ffd700;font-weight:bold;">Thank you from everyone!</span>
    </div>
    <div class="issuer">
      Presented by: Hung Minh Vo (Austin Vo)
      <div class="award-line">Global Security & Technology, 2024</div>
    </div>
    <div class="confetti" id="confetti"></div>
  </div>
  <script>
    // Confetti generator
    function createConfettiPiece() {
      const piece = document.createElement('div');
      piece.className = 'confetti-piece';
      const left = Math.random() * 96 + 2; // % width
      const delay = Math.random() * 2.7;
      const rotate = Math.random() * 180;
      piece.style.left = left + '%';
      piece.style.background = `linear-gradient(${70+Math.random()*140}deg,#ffd700,#fff700 70%)`;
      piece.style.animationDelay = `${delay}s`;
      piece.style.transform = `rotateZ(${rotate}deg)`;
      return piece;
    }
    function explodeConfetti(n) {
      const confetti = document.getElementById('confetti');
      confetti.innerHTML = '';
      for (let i = 0; i < n; i++) confetti.appendChild(createConfettiPiece());
    }
    // Lots of confetti, re-randomized every 3 seconds
    explodeConfetti(70);
    setInterval(()=>explodeConfetti(70), 3000);
  </script>
</body>
</html>

## Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to make participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, sex characteristics, gender identity and expression,
level of experience, education, socio-economic status, nationality, personal
appearance, race, religion, or sexual identity and orientation.

## Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
  advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

## Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

## Scope

This Code of Conduct applies within all project spaces, and it also applies when
an individual is representing the project or its community in public spaces.
Examples of representing a project or community include using an official
project e-mail address, posting via an official social media account, or acting
as an appointed representative at an online or offline event. Representation of
a project may be further defined and clarified by project maintainers.

This Code of Conduct also applies outside the project spaces when there is a
reasonable belief that an individual's behavior may have a negative impact on
the project or its community.

## Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at <opensource-conduct@fb.com>. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

## Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at https://www.contributor-covenant.org/version/1/4/code-of-conduct.html

[homepage]: https://www.contributor-covenant.org

For answers to common questions about this code of conduct, see
https://www.contributor-covenant.org/faq
