==============================================================================
  PATRICK ANDERSON - PACOTE COMPLETO DO PROFILE README
  Tudo em um arquivo. Cada bloco abaixo vira um arquivo no repo patrickacs/patrickacs
==============================================================================

ESTRUTURA FINAL NO REPO
-----------------------
  patrickacs/
  |- README.md
  |- assets/
  |   |- hero-light.svg
  |   |- hero-dark.svg
  |   |- footer-light.svg
  |   |- footer-dark.svg
  |- .github/
      |- workflows/
          |- snake.yml

  Se a tua branch default for "master" e nao "main", troca /main/ nas URLs raw.


INDICE DE BLOCOS REMOVIVEIS (me fala os codigos e eu regero)
------------------------------------------------------------
  [B1]  Hero SVG (topo, light/dark)
  [B2]  Linha de badges: PORTFOLIO / LINKEDIN / BEHANCE / EMAIL
  [B3]  Secao 001 - INDEX (texto de apresentacao)
  [B4]  Secao 002 - DISCIPLINES (tabela das 5 areas)
  [B5]  Secao 003 - STACK (skillicons em 3 linhas)
  [B6]  Secao 004 - SELECTED WORK (3 projetos)
  [B7]  Metricas: card de stats + top languages (lado a lado)
  [B8]  Metricas: activity graph (grafico de contribuicao)
  [B9]  Metricas: snake / contribution grid
  [B10] Metricas: <details> "More numbers" (streak + trofeus)
  [B11] Secao 006 - NOW (building / learning / thinking about)
  [B12] Secao 007 - CONTACT (tabela de contatos)
  [B13] Footer SVG (marquee MAKE IT HAPPEN)

  Cada bloco esta marcado no README abaixo com um comentario  <!-- [Bn] ... -->
  Esses comentarios sao invisiveis no GitHub, pode deixar ou apagar.




==============================================================================
  ARQUIVO 1/6   ->   README.md
  cole isso no README.md da raiz do repo patrickacs/patrickacs
==============================================================================

<!--
═══════════════════════════════════════════════════════════════════════════
  PATRICK ANDERSON · github.com/patrickacs
  Assets live in /assets. If your default branch is not `main`,
  replace `/main/` in the raw URLs below.
═══════════════════════════════════════════════════════════════════════════
-->

<!-- [B1] HERO -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/hero-light.svg">
    <img alt="Patrick Anderson — Full-Stack Software Engineer" src="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/hero-light.svg" width="100%">
  </picture>
</div>

<!-- [B2] BADGES -->
<p align="center">
  <a href="https://www.patrickacs.com"><img alt="Portfolio" src="https://img.shields.io/badge/PORTFOLIO-C1440E?style=for-the-badge&logo=vercel&logoColor=FAF2E7&labelColor=C1440E"></a>
  <a href="https://www.linkedin.com/in/patrickasantos/"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-C1440E?style=for-the-badge&logo=linkedin&logoColor=FAF2E7&labelColor=C1440E"></a>
  <a href="https://www.behance.net/patrickandeson"><img alt="Behance" src="https://img.shields.io/badge/BEHANCE-C1440E?style=for-the-badge&logo=behance&logoColor=FAF2E7&labelColor=C1440E"></a>
  <a href="mailto:pandersomm@gmail.com"><img alt="Email" src="https://img.shields.io/badge/EMAIL-C1440E?style=for-the-badge&logo=maildotru&logoColor=FAF2E7&labelColor=C1440E"></a>
</p>

<br>

<!-- [B3] SECAO 001 -->
## <samp>001 &nbsp;·&nbsp; INDEX</samp>

I build products end to end — from the Kubernetes and Hyperledger Fabric infrastructure that runs them, to the interfaces people actually enjoy using.

Right now I'm a **Full-Stack Developer at BrBPO**, where I ship a multi-tenant SaaS that provisions isolated blockchain networks self-service — a setup that used to take days now takes minutes. Before that, four years across front-end architecture, design systems and crypto products.

I care about two things most engineers treat as separate concerns: **what it costs to run** and **how it feels to use**.

<samp>B.Sc. Software Engineering · University of Brasília · 2026</samp>

<br>

<!-- [B4] SECAO 002 -->
## <samp>002 &nbsp;·&nbsp; DISCIPLINES</samp>

|  |  |  |
| :--- | :--- | :--- |
| <samp>**001**</samp> | **FRONT-END ENGINEERING** | Accessible, high-performance interfaces in React, Next.js and TypeScript — design systems and real-time features that scale. |
| <samp>**002**</samp> | **UI / UX ENGINEERING** | Engineering driven by user journeys, not just mockups — from flow to pixel, motion included. |
| <samp>**003**</samp> | **BACK-END &amp; APIS** | Services in NestJS and Node.js — REST, JWT/RBAC auth, queues and clean integrations. |
| <samp>**004**</samp> | **CLOUD &amp; DEVOPS** | Shipping and running software on Kubernetes — CI/CD, infrastructure as code, reliability. |
| <samp>**005**</samp> | **BLOCKCHAIN** | Permissioned networks on Hyperledger Fabric v2 — chaincode lifecycle and on-chain asset tokenization. |

<br>

<!-- [B5] SECAO 003 -->
## <samp>003 &nbsp;·&nbsp; STACK</samp>

|  |  |
| :--- | :--- |
| <samp>**FRONT**</samp> | <img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind,threejs,figma&theme=light" height="42"> |
| <samp>**BACK**</samp> | <img src="https://skillicons.dev/icons?i=nestjs,nodejs,postgres,redis,prisma,python&theme=light" height="42"> |
| <samp>**INFRA**</samp> | <img src="https://skillicons.dev/icons?i=kubernetes,docker,nginx,ansible,githubactions,gcp&theme=light" height="42"> |

<samp>Also: Hyperledger Fabric v2 · Helm · CloudNativePG · GSAP · Framer Motion</samp>

<br>

<!-- [B6] SECAO 004 -->
## <samp>004 &nbsp;·&nbsp; SELECTED WORK</samp>

|  |  |  |
| :--- | :--- | :--- |
| <samp>**001**</samp> | **Blockchain-as-a-Service Platform** <br> <samp>BrBPO · 2025 →</samp> | Self-service provisioning of isolated Hyperledger Fabric networks behind a 5-step wizard. An 11-step NestJS pipeline orchestrates Ansible against the Kubernetes API, with SSE log streaming and namespace-per-organization isolation. <br> <samp>`NestJS` `Kubernetes` `Fabric v2` `Ansible` `Helm`</samp> |
| <samp>**002**</samp> | **Design System &amp; Component Library** <br> <samp>BrBPO · 2023–2025</samp> | Became the org-wide standard: +20% engagement, 40% faster feature delivery, 25% shorter code-review cycles across a 3,000-person org. <br> <samp>`React` `TypeScript` `Next.js` `a11y`</samp> |
| <samp>**003**</samp> | **[patrickacs.com](https://www.patrickacs.com)** <br> <samp>Personal · 2024 →</samp> | Portfolio built as a performance exercise — WebGL, scroll-driven motion and i18n without giving up Lighthouse scores. <br> <samp>`Next.js` `GSAP` `Three.js`</samp> |

<samp>→ Full case studies at **[patrickacs.com/work](https://www.patrickacs.com/work)**</samp>

<br>

## <samp>005 &nbsp;·&nbsp; METRICS</samp>

<!-- [B7] STATS + TOP LANGS -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=patrickacs&show_icons=true&count_private=true&border_radius=0&hide_title=true&card_width=450&bg_color=0D0C0B&text_color=8C8378&icon_color=FF6A3D&border_color=2E2924&ring_color=FF6A3D&cache_seconds=86400">
    <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=patrickacs&show_icons=true&count_private=true&border_radius=0&hide_title=true&card_width=450&bg_color=FAF2E7&text_color=44403C&icon_color=C1440E&border_color=DCCEB8&ring_color=C1440E&cache_seconds=86400">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=patrickacs&layout=compact&langs_count=8&hide=html,css,scss&border_radius=0&card_width=330&title_color=F5EDE1&bg_color=0D0C0B&text_color=8C8378&border_color=2E2924&cache_seconds=86400">
    <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=patrickacs&layout=compact&langs_count=8&hide=html,css,scss&border_radius=0&card_width=330&title_color=14110E&bg_color=FAF2E7&text_color=44403C&border_color=DCCEB8&cache_seconds=86400">
  </picture>
</div>

<!-- [B8] ACTIVITY GRAPH -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=patrickacs&custom_title=Contribution%20Activity&hide_border=true&radius=0&area=true&bg_color=0D0C0B&color=F5EDE1&title_color=F5EDE1&line=FF6A3D&point=F5EDE1&area_color=FF6A3D">
    <img width="100%" alt="Contribution activity" src="https://github-readme-activity-graph.vercel.app/graph?username=patrickacs&custom_title=Contribution%20Activity&hide_border=true&radius=0&area=true&bg_color=FAF2E7&color=14110E&title_color=14110E&line=C1440E&point=14110E&area_color=C1440E">
  </picture>
</div>

<!-- [B9] SNAKE -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/patrickacs/patrickacs/output/github-contribution-grid-snake-dark.svg">
    <img width="100%" alt="Contribution grid" src="https://raw.githubusercontent.com/patrickacs/patrickacs/output/github-contribution-grid-snake.svg">
  </picture>
</div>

<!-- [B10] MORE NUMBERS -->
<details>
<summary><samp><b>&nbsp;More numbers&nbsp;</b></samp></summary>
<br>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=patrickacs&border_radius=0&date_format=M%20j%5B%2C%20Y%5D&background=0D0C0B&border=2E2924&stroke=2E2924&ring=FF6A3D&fire=FF6A3D&currStreakNum=F5EDE1&currStreakLabel=FF6A3D&sideNums=F5EDE1&sideLabels=8C8378&dates=6B6259">
    <img width="70%" alt="Contribution streak" src="https://streak-stats.demolab.com?user=patrickacs&border_radius=0&date_format=M%20j%5B%2C%20Y%5D&background=FAF2E7&border=DCCEB8&stroke=DCCEB8&ring=C1440E&fire=C1440E&currStreakNum=14110E&currStreakLabel=C1440E&sideNums=14110E&sideLabels=57534E&dates=A8A29E">
  </picture>
  <br><br>
  <img width="100%" alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=patrickacs&theme=flat&no-frame=true&no-bg=true&margin-w=8&row=1&column=7">
</div>
</details>

<br>

<!-- [B11] SECAO 006 -->
## <samp>006 &nbsp;·&nbsp; NOW</samp>

|  |  |
| :--- | :--- |
| <samp>**BUILDING**</samp> | Multi-tenant blockchain provisioning at scale — and the developer experience around it |
| <samp>**LEARNING**</samp> | WebGL &amp; shader work, platform engineering patterns |
| <samp>**THINKING ABOUT**</samp> | Where infrastructure cost and interface quality are actually the same decision |

<br>

<!-- [B12] SECAO 007 -->
## <samp>007 &nbsp;·&nbsp; CONTACT</samp>

Open to full-stack and platform roles, remote or Brasília-based. The fastest way to reach me is email — I answer everything.

|  |  |
| :--- | :--- |
| <samp>**EMAIL**</samp> | [pandersomm@gmail.com](mailto:pandersomm@gmail.com) |
| <samp>**LINKEDIN**</samp> | [/in/patrickasantos](https://www.linkedin.com/in/patrickasantos/) |
| <samp>**PORTFOLIO**</samp> | [patrickacs.com](https://www.patrickacs.com) |
| <samp>**BEHANCE**</samp> | [/patrickandeson](https://www.behance.net/patrickandeson) |

<br>

<!-- [B13] FOOTER -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/footer-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/footer-light.svg">
    <img alt="Make it happen — patrickacs.com" src="https://raw.githubusercontent.com/patrickacs/patrickacs/main/assets/footer-light.svg" width="100%">
  </picture>
</div>


==============================================================================
  ARQUIVO 2/6   ->   assets/hero-light.svg
==============================================================================

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 420" width="1200" height="420" role="img" aria-label="Patrick Anderson - Full-Stack Software Engineer">
<title>Patrick Anderson - Full-Stack Software Engineer</title>
<style><![CDATA[
  .s{font-family:'Helvetica Neue',Helvetica,Arial,sans-serif}
  .m{font-family:ui-monospace,'SF Mono',SFMono-Regular,Menlo,Consolas,'Liberation Mono',monospace}
  .lbl{font-size:12px;letter-spacing:2.4px;fill:#7A6F62}
  .lbl-i{font-size:12px;letter-spacing:2.4px;fill:#14110E}
  .idx{font-size:12px;letter-spacing:1.6px;fill:#C1440E}
  .disc{font-size:12.5px;letter-spacing:1.8px;fill:#14110E}
  .name{font-size:104px;font-weight:700;letter-spacing:-3px;fill:#14110E}
  .rule{stroke:#DCCEB8;stroke-width:1}
  .grid{stroke:#14110E;stroke-width:1;opacity:.05}

  .draw{stroke-dasharray:1200;stroke-dashoffset:1200;animation:draw 1.4s cubic-bezier(.16,1,.3,1) forwards}
  @keyframes draw{to{stroke-dashoffset:0}}

  .up{opacity:0;animation:up .9s cubic-bezier(.16,1,.3,1) forwards}
  .d1{animation-delay:.10s}.d2{animation-delay:.22s}.d3{animation-delay:.40s}
  .d4{animation-delay:.48s}.d5{animation-delay:.56s}.d6{animation-delay:.64s}
  .d7{animation-delay:.72s}.d8{animation-delay:.80s}.d9{animation-delay:.90s}
  @keyframes up{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:translateY(0)}}

  .dot{fill:#C1440E;animation:pulse 2.4s ease-in-out infinite}
  @keyframes pulse{0%,100%{opacity:1}50%{opacity:.25}}

  .w{font-size:12.5px;letter-spacing:2.4px;font-weight:700;fill:#C1440E;opacity:0}
  .w1{animation:cyc 12s steps(1,end) infinite}
  .w2{animation:cyc 12s steps(1,end) infinite -3s}
  .w3{animation:cyc 12s steps(1,end) infinite -6s}
  .w4{animation:cyc 12s steps(1,end) infinite -9s}
  @keyframes cyc{0%{opacity:1}25%{opacity:0}100%{opacity:0}}
]]></style>

  <rect width="1200" height="420" fill="#FAF2E7"/>

  <!-- structural grid -->
  <g class="grid">
    <line x1="60" y1="0" x2="60" y2="420"/>
    <line x1="730" y1="0" x2="730" y2="420"/>
    <line x1="1140" y1="0" x2="1140" y2="420"/>
  </g>

  <!-- top meta -->
  <g class="m up d1">
    <text class="lbl-i" x="60" y="58">FULL-STACK SOFTWARE ENGINEER</text>
    <text class="lbl" x="1122" y="58" text-anchor="end">AVAILABLE FOR WORK</text>
    <circle class="dot" cx="1136" cy="54" r="4"/>
  </g>

  <line class="rule draw" x1="60" y1="86" x2="1140" y2="86"/>

  <!-- wordmark -->
  <g class="s">
    <text class="name up d2" x="56" y="226">PATRICK</text>
    <text class="name up d3" x="56" y="326">ANDERSON</text>
  </g>

  <!-- disciplines -->
  <g class="m">
    <g class="up d4"><text class="idx" x="762" y="140">001</text><text class="disc" x="812" y="140">FRONT-END</text></g>
    <g class="up d5"><text class="idx" x="762" y="176">002</text><text class="disc" x="812" y="176">UI / UX</text></g>
    <g class="up d6"><text class="idx" x="762" y="212">003</text><text class="disc" x="812" y="212">BACK-END &amp; APIS</text></g>
    <g class="up d7"><text class="idx" x="762" y="248">004</text><text class="disc" x="812" y="248">CLOUD &amp; DEVOPS</text></g>
    <g class="up d8"><text class="idx" x="762" y="284">005</text><text class="disc" x="812" y="284">BLOCKCHAIN</text></g>
    <text class="lbl up d9" x="762" y="330">BRASILIA, BR</text>
    <text class="lbl up d9" x="762" y="348">15.7975&#176;S  47.8919&#176;W</text>
  </g>

  <line class="rule draw" x1="60" y1="360" x2="1140" y2="360"/>

  <!-- footline -->
  <g class="m up d9">
    <text class="lbl" x="60" y="396">SOFTWARE BUILT TO BE</text>
    <text class="w w1" x="310" y="396">FAST</text>
    <text class="w w2" x="310" y="396">ACCESSIBLE</text>
    <text class="w w3" x="310" y="396">SCALABLE</text>
    <text class="w w4" x="310" y="396">LOVED</text>
    <text class="lbl-i" x="1140" y="396" text-anchor="end">PATRICKACS.COM</text>
  </g>
</svg>


==============================================================================
  ARQUIVO 3/6   ->   assets/hero-dark.svg
==============================================================================

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 420" width="1200" height="420" role="img" aria-label="Patrick Anderson - Full-Stack Software Engineer">
<title>Patrick Anderson - Full-Stack Software Engineer</title>
<style><![CDATA[
  .s{font-family:'Helvetica Neue',Helvetica,Arial,sans-serif}
  .m{font-family:ui-monospace,'SF Mono',SFMono-Regular,Menlo,Consolas,'Liberation Mono',monospace}
  .lbl{font-size:12px;letter-spacing:2.4px;fill:#8C8378}
  .lbl-i{font-size:12px;letter-spacing:2.4px;fill:#F5EDE1}
  .idx{font-size:12px;letter-spacing:1.6px;fill:#FF6A3D}
  .disc{font-size:12.5px;letter-spacing:1.8px;fill:#F5EDE1}
  .name{font-size:104px;font-weight:700;letter-spacing:-3px;fill:#F5EDE1}
  .rule{stroke:#2E2924;stroke-width:1}
  .grid{stroke:#F5EDE1;stroke-width:1;opacity:.05}

  .draw{stroke-dasharray:1200;stroke-dashoffset:1200;animation:draw 1.4s cubic-bezier(.16,1,.3,1) forwards}
  @keyframes draw{to{stroke-dashoffset:0}}

  .up{opacity:0;animation:up .9s cubic-bezier(.16,1,.3,1) forwards}
  .d1{animation-delay:.10s}.d2{animation-delay:.22s}.d3{animation-delay:.40s}
  .d4{animation-delay:.48s}.d5{animation-delay:.56s}.d6{animation-delay:.64s}
  .d7{animation-delay:.72s}.d8{animation-delay:.80s}.d9{animation-delay:.90s}
  @keyframes up{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:translateY(0)}}

  .dot{fill:#FF6A3D;animation:pulse 2.4s ease-in-out infinite}
  @keyframes pulse{0%,100%{opacity:1}50%{opacity:.25}}

  .w{font-size:12.5px;letter-spacing:2.4px;font-weight:700;fill:#FF6A3D;opacity:0}
  .w1{animation:cyc 12s steps(1,end) infinite}
  .w2{animation:cyc 12s steps(1,end) infinite -3s}
  .w3{animation:cyc 12s steps(1,end) infinite -6s}
  .w4{animation:cyc 12s steps(1,end) infinite -9s}
  @keyframes cyc{0%{opacity:1}25%{opacity:0}100%{opacity:0}}
]]></style>

  <rect width="1200" height="420" fill="#0D0C0B"/>

  <!-- structural grid -->
  <g class="grid">
    <line x1="60" y1="0" x2="60" y2="420"/>
    <line x1="730" y1="0" x2="730" y2="420"/>
    <line x1="1140" y1="0" x2="1140" y2="420"/>
  </g>

  <!-- top meta -->
  <g class="m up d1">
    <text class="lbl-i" x="60" y="58">FULL-STACK SOFTWARE ENGINEER</text>
    <text class="lbl" x="1122" y="58" text-anchor="end">AVAILABLE FOR WORK</text>
    <circle class="dot" cx="1136" cy="54" r="4"/>
  </g>

  <line class="rule draw" x1="60" y1="86" x2="1140" y2="86"/>

  <!-- wordmark -->
  <g class="s">
    <text class="name up d2" x="56" y="226">PATRICK</text>
    <text class="name up d3" x="56" y="326">ANDERSON</text>
  </g>

  <!-- disciplines -->
  <g class="m">
    <g class="up d4"><text class="idx" x="762" y="140">001</text><text class="disc" x="812" y="140">FRONT-END</text></g>
    <g class="up d5"><text class="idx" x="762" y="176">002</text><text class="disc" x="812" y="176">UI / UX</text></g>
    <g class="up d6"><text class="idx" x="762" y="212">003</text><text class="disc" x="812" y="212">BACK-END &amp; APIS</text></g>
    <g class="up d7"><text class="idx" x="762" y="248">004</text><text class="disc" x="812" y="248">CLOUD &amp; DEVOPS</text></g>
    <g class="up d8"><text class="idx" x="762" y="284">005</text><text class="disc" x="812" y="284">BLOCKCHAIN</text></g>
    <text class="lbl up d9" x="762" y="330">BRASILIA, BR</text>
    <text class="lbl up d9" x="762" y="348">15.7975&#176;S  47.8919&#176;W</text>
  </g>

  <line class="rule draw" x1="60" y1="360" x2="1140" y2="360"/>

  <!-- footline -->
  <g class="m up d9">
    <text class="lbl" x="60" y="396">SOFTWARE BUILT TO BE</text>
    <text class="w w1" x="310" y="396">FAST</text>
    <text class="w w2" x="310" y="396">ACCESSIBLE</text>
    <text class="w w3" x="310" y="396">SCALABLE</text>
    <text class="w w4" x="310" y="396">LOVED</text>
    <text class="lbl-i" x="1140" y="396" text-anchor="end">PATRICKACS.COM</text>
  </g>
</svg>


==============================================================================
  ARQUIVO 4/6   ->   assets/footer-light.svg
==============================================================================

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" width="1200" height="120" role="img" aria-label="Make it happen - patrickacs.com">
<title>Make it happen</title>
<style><![CDATA[
  .m{font-family:ui-monospace,'SF Mono',SFMono-Regular,Menlo,Consolas,'Liberation Mono',monospace}
  .lbl{font-size:12px;letter-spacing:2.4px;fill:#7A6F62}
  .mq{font-size:26px;font-weight:700;letter-spacing:3px;fill:#14110E}
  .mqa{font-size:26px;font-weight:700;letter-spacing:3px;fill:#C1440E}
  .rule{stroke:#DCCEB8;stroke-width:1}
  .track{animation:slide 22s linear infinite}
  @keyframes slide{from{transform:translateX(0)}to{transform:translateX(-800px)}}
]]></style>

  <rect width="1200" height="120" fill="#FAF2E7"/>
  <line class="rule" x1="0" y1="0.5" x2="1200" y2="0.5"/>

  <clipPath id="cp"><rect x="0" y="14" width="1200" height="56"/></clipPath>
  <g clip-path="url(#cp)">
    <g class="track m">
      <text class="mq" x="0" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="800" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="1600" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="2400" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
    </g>
  </g>

  <line class="rule" x1="60" y1="84" x2="1140" y2="84"/>
  <g class="m">
    <text class="lbl" x="60" y="108">&#169; PATRICK ANDERSON</text>
    <text class="lbl" x="600" y="108" text-anchor="middle">BRASILIA &#8212; BRAZIL</text>
    <text class="lbl" x="1140" y="108" text-anchor="end">PATRICKACS.COM</text>
  </g>
</svg>


==============================================================================
  ARQUIVO 5/6   ->   assets/footer-dark.svg
==============================================================================

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" width="1200" height="120" role="img" aria-label="Make it happen - patrickacs.com">
<title>Make it happen</title>
<style><![CDATA[
  .m{font-family:ui-monospace,'SF Mono',SFMono-Regular,Menlo,Consolas,'Liberation Mono',monospace}
  .lbl{font-size:12px;letter-spacing:2.4px;fill:#8C8378}
  .mq{font-size:26px;font-weight:700;letter-spacing:3px;fill:#F5EDE1}
  .mqa{font-size:26px;font-weight:700;letter-spacing:3px;fill:#FF6A3D}
  .rule{stroke:#2E2924;stroke-width:1}
  .track{animation:slide 22s linear infinite}
  @keyframes slide{from{transform:translateX(0)}to{transform:translateX(-800px)}}
]]></style>

  <rect width="1200" height="120" fill="#0D0C0B"/>
  <line class="rule" x1="0" y1="0.5" x2="1200" y2="0.5"/>

  <clipPath id="cp"><rect x="0" y="14" width="1200" height="56"/></clipPath>
  <g clip-path="url(#cp)">
    <g class="track m">
      <text class="mq" x="0" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="800" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="1600" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
      <text class="mq" x="2400" y="56">MAKE IT HAPPEN <tspan class="mqa">&#8212;</tspan> LET&#8217;S BUILD SOMETHING <tspan class="mqa">&#8212;</tspan> </text>
    </g>
  </g>

  <line class="rule" x1="60" y1="84" x2="1140" y2="84"/>
  <g class="m">
    <text class="lbl" x="60" y="108">&#169; PATRICK ANDERSON</text>
    <text class="lbl" x="600" y="108" text-anchor="middle">BRASILIA &#8212; BRAZIL</text>
    <text class="lbl" x="1140" y="108" text-anchor="end">PATRICKACS.COM</text>
  </g>
</svg>


==============================================================================
  ARQUIVO 6/6   ->   .github/workflows/snake.yml
  opcional - so repinta o snake nas cores do README
==============================================================================

name: contribution grid

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches: [main]

jobs:
  build:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - name: Generate snake
        uses: Platane/snk@v3
        id: snake
        with:
          github_user_name: ${{ github.repository_owner }}
          # Filenames match the ones already referenced in README.md.
          # If the custom colours ever error out, just drop the &color_snake=... part.
          outputs: |
            dist/github-contribution-grid-snake.svg?palette=github-light&color_snake=%23C1440E
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark&color_snake=%23FF6A3D

      - name: Publish to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


==============================================================================
  FIM
==============================================================================
