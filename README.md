<!-- 1) Replace YOUR_USERNAME with your GitHub username (Ctrl+H)
     2) Replace YOUR_TELEGRAM, YOUR_INSTAGRAM, YOUR_LINKEDIN, YOUR_EMAIL, YOUR_PORTFOLIO and the project links -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
  <img alt="Toirov Asadbek, full-stack developer from Tashkent" src="./assets/hero-light.svg" width="100%">
</picture>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=21&duration=2600&pause=900&color=3CC6C0&center=true&vCenter=true&width=700&lines=Full-stack+developer+from+Navoiy%2C+Uzbekistan;Founder+of+ICO+IT+Academy+and+MA+Studio;React+%2B+Next.js+%2B+Node.js+%2B+TypeScript;I+turn+ideas+into+shipped+products" alt="Typing intro">
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20views&color=3CC6C0&style=for-the-badge" alt="Profile views">
  <img src="https://img.shields.io/github/followers/YOUR_USERNAME?label=Followers&style=for-the-badge&color=E4AE4B&labelColor=0F1B3D" alt="Followers">
  <img src="https://img.shields.io/github/stars/YOUR_USERNAME?label=Stars&style=for-the-badge&color=3CC6C0&labelColor=0F1B3D" alt="Stars">
  <img src="https://img.shields.io/badge/Status-Building%20startups-E4AE4B?style=for-the-badge&labelColor=0F1B3D" alt="Status">
</p>

<p align="center">
  <a href="https://YOUR_PORTFOLIO"><img src="https://img.shields.io/badge/Portfolio-0F1B3D?style=for-the-badge&logo=googlechrome&logoColor=3CC6C0" alt="Portfolio"></a>
  <a href="https://t.me/YOUR_TELEGRAM"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="https://instagram.com/YOUR_INSTAGRAM"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
</p>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## ⚡ About me

```ts
import { FullStackDeveloper, Founder } from "@asadbek/core";

interface Profile {
  readonly identity: { name: string; role: string; location: string };
  readonly startups: Record<string, string>;
  readonly stack: Record<"frontend" | "backend" | "database" | "devops", string[]>;
}

export class AsadbekToirov extends FullStackDeveloper implements Founder {
  public readonly profile: Profile = {
    identity: {
      name: "Toirov Asadbek",
      role: "Full-Stack Developer & Startup Founder",
      location: "Navoiy, Uzbekistan 🇺🇿",
    },
    startups: {
      "ICO IT Academy": "IT education: from first line of code to first job",
      "MA Studio": "Websites, web apps and digital products for businesses",
    },
    stack: {
      frontend: ["React", "Next.js (App Router)", "TypeScript", "Tailwind CSS"],
      backend: ["Node.js", "Express", "NestJS", "REST APIs", "JWT Auth"],
      database: ["PostgreSQL", "MongoDB", "Prisma ORM", "Redis"],
      devops: ["Docker", "Git", "Vercel", "Linux", "CI/CD"],
    },
  };

  public currentFocus(): string[] {
    return [
      "🚀 Growing ICO IT Academy and MA Studio",
      "🧱 Designing scalable full-stack architecture",
      "🎨 Shipping fast, polished UI with dark and light themes",
    ];
  }
}
```

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,html,css,redux,nodejs,express,nestjs,postgres,mongodb,prisma,redis,docker,git,github,vercel,figma,linux,vscode&perline=11" alt="Tech stack">
</p>

<table align="center">
  <tr>
    <th>🎨 Frontend</th><th>⚙️ Backend</th><th>🗄️ Database</th><th>🐳 DevOps &amp; tools</th>
  </tr>
  <tr valign="top">
    <td>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"><br>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"><br>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8"><br>
      <img src="https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white"><br>
      <img src="https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white">
    </td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"><br>
      <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"><br>
      <img src="https://img.shields.io/badge/REST_API-0F1B3D?style=flat-square&logo=fastapi&logoColor=3CC6C0"><br>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
    </td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"><br>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
    </td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"><br>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"><br>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white">
    </td>
  </tr>
</table>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## 🚀 Startups & featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 ICO IT Academy</h3>
      <p>An IT academy that teaches programming through real projects, from the first line of code to a deployed full-stack app and the first job.</p>
      <img src="https://img.shields.io/badge/Founder-E4AE4B?style=flat-square&labelColor=0F1B3D">
      <img src="https://img.shields.io/badge/Education-3CC6C0?style=flat-square"><br><br>
      <a href="https://YOUR_ICO_LINK"><img src="https://img.shields.io/badge/Visit_website-0F1B3D?style=for-the-badge&logo=googlechrome&logoColor=3CC6C0"></a>
    </td>
    <td width="50%" valign="top">
      <h3>🎨 MA Studio</h3>
      <p>A digital studio that designs and builds websites, web apps and brands for businesses, from idea to launch.</p>
      <img src="https://img.shields.io/badge/Founder-E4AE4B?style=flat-square&labelColor=0F1B3D">
      <img src="https://img.shields.io/badge/Web_studio-3CC6C0?style=flat-square"><br><br>
      <a href="https://YOUR_MA_LINK"><img src="https://img.shields.io/badge/Visit_website-0F1B3D?style=for-the-badge&logo=googlechrome&logoColor=3CC6C0"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Personal portfolio</h3>
      <p>My portfolio with projects, skills and contact form. Built with Next.js and Tailwind CSS.</p>
      <a href="https://YOUR_PORTFOLIO"><img src="https://img.shields.io/badge/Live_demo-3CC6C0?style=for-the-badge&labelColor=0F1B3D"></a>
      <a href="https://github.com/YOUR_USERNAME/YOUR_PORTFOLIO_REPO"><img src="https://img.shields.io/badge/Source_code-E4AE4B?style=for-the-badge&labelColor=0F1B3D"></a>
    </td>
    <td width="50%" valign="top">
      <h3>📦 More projects</h3>
      <p>Client sites from MA Studio, learning platforms for ICO IT Academy and experiments.</p>
      <a href="https://github.com/YOUR_USERNAME?tab=repositories"><img src="https://img.shields.io/badge/Explore_repos-0F1B3D?style=for-the-badge&logo=github&logoColor=white"></a>
    </td>
  </tr>
</table>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## 🏆 GitHub trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=7" alt="GitHub trophies">
</p>

## 📊 GitHub stats

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub stats" height="170">
  <img src="./profile/top-langs.svg" alt="Top languages" height="170">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&background=0F1B3D&ring=E4AE4B&fire=E4AE4B&currStreakLabel=3CC6C0" alt="GitHub streak">
</p>

## 📈 Contribution activity

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&bg_color=0F1B3D&color=AFC0DD&line=3CC6C0&point=E4AE4B&area=true&area_color=3CC6C0&hide_border=true&radius=12" alt="Activity graph" width="100%">

<img src="./profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution graph" width="100%">

## 🐍 Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile/snake-dark.svg">
  <img alt="Snake eating my contributions" src="./profile/snake.svg" width="100%">
</picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## 💼 Experience

**🚀 Founder & Full-Stack Developer, ICO IT Academy**  
*Navoiy, Uzbekistan · Present*
- Building the academy's product and learning platform end to end.
- Designing courses around real projects so students finish with a portfolio.

**🎨 Founder & Full-Stack Developer, MA Studio**  
*Navoiy, Uzbekistan · Present*
- Delivering websites and web apps for businesses with React, Next.js and Node.js.
- Owning the full cycle: design, frontend, backend, database and deployment.

<details>
<summary><b>⚙️ My workspace (click to expand)</b></summary>
<br>

| | |
|---|---|
| 💻 OS | Windows / Linux |
| 🧑‍💻 Editor | VS Code |
| 🎨 Theme | One Dark Pro |
| 🔤 Font | JetBrains Mono |
| 🌐 Browser | Chrome |
| 🎨 Design | Figma |

</details>

<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/divider-dark.svg"><img alt="" src="./assets/divider-light.svg" width="100%"></picture>

## 🤝 Let's connect

<p align="center">Open to collaborations, freelance projects and startup ideas. Write me on Telegram 👇</p>

<p align="center">
  <a href="https://t.me/YOUR_TELEGRAM"><img src="https://img.shields.io/badge/Write_on_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://img.shields.io/badge/Send_an_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/footer-dark.svg">
  <img alt="Thanks for stopping by" src="./assets/footer-light.svg" width="100%">
</picture>
