<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="./assets/nucleus-hero-light.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="./assets/nucleus-hero-dark.svg" />
    <img alt="Nucleuskit animated profile banner" src="./assets/nucleus-hero-dark.svg" width="100%" />
  </picture>
</div>

<div align="center">
  <a href="https://github.com/nucleuskit/nucleus">
    <img alt="Nucleus" src="https://img.shields.io/badge/Nucleus-AI--first%20Go%20kernel-2AFADF?style=for-the-badge&logo=go&logoColor=0D1117" />
  </a>
  <a href="https://github.com/nucleuskit">
    <img alt="Contract driven" src="https://img.shields.io/badge/Contract--Driven-Service%20Generation-F8D66D?style=for-the-badge&logo=githubactions&logoColor=0D1117" />
  </a>
  <a href="https://github.com/nucleuskit?tab=repositories">
    <img alt="Modules" src="https://img.shields.io/badge/Modules-core%20%7C%20http%20%7C%20grpc%20%7C%20worker-FF6B9A?style=for-the-badge&logo=gnubash&logoColor=white" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/nucleuskit">
    <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=24&duration=2400&pause=720&color=2AFADF&center=true&vCenter=true&random=false&width=900&lines=AI-first+Go+microservice+kernel;Contract-driven+service+generation;Evolution+and+verification+for+backend+systems" />
  </a>
</div>

<br />

<table>
  <tr>
    <td width="58%">
      <h3>Nucleuskit builds backend systems from contracts.</h3>
      <p>
        A compact Go toolkit for turning service contracts into generated, verifiable,
        evolvable microservice building blocks.
      </p>
      <p>
        The focus is simple: keep the service boundary explicit, make generated code
        predictable, and leave enough room for real production systems to grow.
      </p>
    </td>
    <td width="42%">
      <img alt="Nucleuskit quick stats" src="https://github-readme-stats.vercel.app/api?username=nucleuskit&show_icons=true&include_all_commits=true&rank_icon=github&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&icon_color=F8D66D&text_color=C9D1D9" />
    </td>
  </tr>
</table>

## Control Plane

<details open>
  <summary><b>System map</b></summary>

```mermaid
flowchart LR
  Contract["contract"] --> Core["core"]
  Core --> HTTP["http"]
  Core --> GRPC["grpc"]
  Core --> Worker["worker"]
  Core --> Bridge["bridge"]
  Cap["cap"] --> Core
  Nucleus["nucleus"] --> Contract
  Nucleus --> Core
  Nucleus --> HTTP
  Nucleus --> GRPC
  Nucleus --> Worker
```

</details>

<details>
  <summary><b>Module deck</b></summary>

| Module | Role | Repository |
| --- | --- | --- |
| nucleus | AI-first Go microservice kernel | [nucleuskit/nucleus](https://github.com/nucleuskit/nucleus) |
| contract | Contract model and shared surface | [nucleuskit/contract](https://github.com/nucleuskit/contract) |
| core | Service runtime primitives | [nucleuskit/core](https://github.com/nucleuskit/core) |
| http | HTTP integration module | [nucleuskit/http](https://github.com/nucleuskit/http) |
| grpc | gRPC integration module | [nucleuskit/grpc](https://github.com/nucleuskit/grpc) |
| worker | Worker execution module | [nucleuskit/worker](https://github.com/nucleuskit/worker) |
| bridge | Adapter bridge module | [nucleuskit/bridge](https://github.com/nucleuskit/bridge) |
| cap | Capability module | [nucleuskit/cap](https://github.com/nucleuskit/cap) |

</details>

<details>
  <summary><b>Operating principles</b></summary>

- Contracts before glue code.
- Generated code should be readable, replaceable, and boring in the best way.
- Runtime modules stay small enough to understand in one sitting.
- Verification belongs near the service boundary, not as an afterthought.
- AI can help generate systems, but contracts keep the system honest.

</details>

## Featured Repositories

<div align="center">
  <a href="https://github.com/nucleuskit/nucleus">
    <img height="145" alt="nucleus repo card" src="https://github-readme-stats.vercel.app/api/pin/?username=nucleuskit&repo=nucleus&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&icon_color=F8D66D&text_color=C9D1D9" />
  </a>
  <a href="https://github.com/nucleuskit/contract">
    <img height="145" alt="contract repo card" src="https://github-readme-stats.vercel.app/api/pin/?username=nucleuskit&repo=contract&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&icon_color=F8D66D&text_color=C9D1D9" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/nucleuskit/core">
    <img height="145" alt="core repo card" src="https://github-readme-stats.vercel.app/api/pin/?username=nucleuskit&repo=core&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&icon_color=F8D66D&text_color=C9D1D9" />
  </a>
  <a href="https://github.com/nucleuskit/http">
    <img height="145" alt="http repo card" src="https://github-readme-stats.vercel.app/api/pin/?username=nucleuskit&repo=http&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&icon_color=F8D66D&text_color=C9D1D9" />
  </a>
</div>

## Runtime Surface

<div align="center">
  <img alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img alt="gRPC" src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=grpc&logoColor=white" />
  <img alt="HTTP" src="https://img.shields.io/badge/HTTP-0D1117?style=flat-square&logo=fastapi&logoColor=2AFADF" />
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img alt="Contracts" src="https://img.shields.io/badge/Contracts-F8D66D?style=flat-square&logo=bookstack&logoColor=0D1117" />
  <img alt="Verification" src="https://img.shields.io/badge/Verification-FF6B9A?style=flat-square&logo=checkmarx&logoColor=white" />
</div>

<br />

<div align="center">
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nucleuskit&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=2AFADF&text_color=C9D1D9" />
  <img height="170" alt="GitHub streak" src="https://streak-stats.demolab.com?user=nucleuskit&theme=tokyonight&hide_border=true&background=0D1117&ring=2AFADF&fire=F8D66D&currStreakLabel=2AFADF" />
</div>

## Activity Stream

<div align="center">
  <img alt="GitHub trophies" src="https://github-profile-trophy.vercel.app/?username=nucleuskit&theme=onestar&no-frame=true&no-bg=true&margin-w=8&row=1&column=6" />
</div>

<div align="center">
  <img alt="GitHub activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=nucleuskit&theme=react-dark&hide_border=true&radius=8&area=true&custom_title=Nucleuskit%20Contribution%20Signal" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nucleuskit/nucleuskit/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nucleuskit/nucleuskit/output/github-snake.svg" />
    <img alt="Nucleuskit contribution snake" src="https://raw.githubusercontent.com/nucleuskit/nucleuskit/output/github-snake.svg" />
  </picture>
</div>

<div align="center">
  <img alt="Nucleuskit 3D contribution calendar" src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%" />
</div>

## Launch Links

<div align="center">
  <a href="https://github.com/nucleuskit?tab=repositories">
    <img alt="Repositories" src="https://img.shields.io/badge/Open%20Repositories-0D1117?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/nucleuskit/nucleus">
    <img alt="Explore nucleus" src="https://img.shields.io/badge/Explore%20Nucleus-2AFADF?style=for-the-badge&logo=go&logoColor=0D1117" />
  </a>
  <a href="https://github.com/nucleuskit/nucleus/stargazers">
    <img alt="Star nucleus" src="https://img.shields.io/badge/Star%20The%20Kernel-F8D66D?style=for-the-badge&logo=starship&logoColor=0D1117" />
  </a>
</div>

<br />

<div align="center">
  <img alt="Visitors" src="https://komarev.com/ghpvc/?username=nucleuskit&style=flat-square&color=2AFADF&label=profile+views" />
</div>
