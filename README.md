from pathlib import Path

content = """<details open>
<summary><h2>Hi! 👋</h2></summary>

### Hi there,

I'm a developer who enjoys building apps, experimenting with software, and turning ideas into real projects.

Most of my work is focused on **Android development, emulation, game development, web systems, and UI/UX**. I like improving performance, polishing interfaces, and keeping projects simple, clean, and useful.

Some of the projects I've worked on include **Retra**, Unity applications, Godot game prototypes, Firebase-based systems, and web projects.

- ⚡ Fun fact: I can spend way too long polishing a UI until it feels just right.

</details>

<details open>
<summary><h2>🛠️ Tech & Tools</h2></summary>

### ⚙️ Tech Stack

| Category | Technologies |
| --- | --- |
| **Mobile** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) |
| **Game Dev** | ![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white) ![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat&logo=godot-engine&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white) |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) |
| **Backend / DB** | ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat&logo=firebase&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white) |
| **Creative** | ![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat&logo=blender&logoColor=white) ![Aseprite](https://img.shields.io/badge/Aseprite-7D929E?style=flat&logo=aseprite&logoColor=white) |
| **OS / CLI** | ![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat&logo=windows11&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white) |

</details>

<details open>
<summary><h2>🚀 Featured Projects</h2></summary>

### 🎮 Retra

A mobile-focused GBA emulator project built around a clean interface, fast-forward controls, smooth gameplay presentation, and ongoing performance improvements.

### 🔬 ForenSim AI

A forensic simulation and educational application concept focused on interactive investigation workflows, AR features, Firebase integration, and role-based access.

### 🌱 Game Development

I also experiment with **Unity** and **Godot**, including top-down RPG systems, pixel-art characters, animation workflows, inventory systems, and gameplay prototypes.

</details>

<details open>
<summary><h2>📊 GitHub Stats</h2></summary>

> Replace `YOUR_GITHUB_USERNAME` below with your actual GitHub username.

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=github_dark&hide_border=true" alt="Top languages" />
</p>

</details>

## Contact 📬

You can reach me through:

[![GitHub](https://img.shields.io/badge/GitHub-YOUR_USERNAME-181717?style=flat&logo=github)](https://github.com/YOUR_GITHUB_USERNAME)
[![Email](https://img.shields.io/badge/Email-YOUR_EMAIL-D14836?style=flat&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

---

## 💗 Support

If you like my projects, you can support my work here:

[![GitHub Sponsor](https://img.shields.io/badge/GitHub-Sponsor-EA4AAA?style=flat&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/YOUR_GITHUB_USERNAME)
[![PayPal](https://img.shields.io/badge/PayPal-Support-00457C?style=flat&logo=paypal&logoColor=white)](YOUR_PAYPAL_LINK)
"""

path = Path("/mnt/data/README_profile_style.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
