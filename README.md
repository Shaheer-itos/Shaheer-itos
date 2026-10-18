from pathlib import Path

content = r'''<p align="center">
  <img src="https://img.shields.io/badge/Shaheer-CS%20Student-7dd3fc?style=for-the-badge&labelColor=0b1220" alt="Shaheer — CS Student" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=3000&pause=900&color=7DD3FC&center=true&vCenter=true&width=650&lines=Computer+Science+Student;Learning+Python+and+HTML;Exploring+Data+Science+and+Cybersecurity" alt="Typing animation: CS student learning Python and HTML, exploring Data Science and Cybersecurity" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shaheer-itos&label=Profile%20views&color=7dd3fc&style=for-the-badge" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/shaheer-itos?label=Followers&style=for-the-badge" alt="GitHub followers" />
</p>

---

## 👋 Who I Am

```typescript
const shaheer = {
  title: "CS Student",
  stack: ["Python", "HTML"],
  launchedProjects: [],
  certifications: [],
  status: "Learning programming fundamentals",
  openTo: []
};
```

I’m a Computer Science student learning Python and HTML. I’ve also enrolled in courses related to Data Science and Cybersecurity and am building my technical skills step by step.

## 🛠️ Tech Stack

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=py,html&theme=light" alt="Python and HTML icons" />
</p>

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=shaheer-itos&show_icons=true&theme=nord&hide_border=true&title_color=7dd3fc&icon_color=7dd3fc" alt="GitHub stats for shaheer-itos" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shaheer-itos&layout=compact&theme=nord&hide_border=true&title_color=7dd3fc" alt="Top languages for shaheer-itos" />
</p>

## 🔥 Streak Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=shaheer-itos&theme=nord&hide_border=true&ring=7dd3fc&fire=7dd3fc&currStreakLabel=7dd3fc" alt="GitHub streak stats for shaheer-itos" />
</p>

## 🤝 Connect With Me

<p>
  <a href="https://www.linkedin.com/in/muhammad-shaheer7">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-7dd3fc?style=for-the-badge&logo=linkedin&logoColor=0b1220" alt="LinkedIn" />
  </a>
  <a href="mailto:Syedshaheerasif@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-7dd3fc?style=for-the-badge&logo=gmail&logoColor=0b1220" alt="Email" />
  </a>
  <a href="https://github.com/shaheer-itos">
    <img src="https://img.shields.io/badge/GitHub-Profile-7dd3fc?style=for-the-badge&logo=github&logoColor=0b1220" alt="GitHub" />
  </a>
</p>
'''
path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created and verified {path} ({path.stat().st_size} bytes)")
