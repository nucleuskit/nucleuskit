<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="./assets/nucleus-hero-light.svg" />
    <source media="(prefers-color-scheme: dark)" srcset="./assets/nucleus-hero-dark.svg" />
    <img alt="Nucleuskit animated profile banner" src="./assets/nucleus-hero-dark.svg" width="100%" />
  </picture>
</div>

<div align="center">
  <a href="https://github.com/nucleuskit/nucleus">
    <img alt="Nucleus" src="https://img.shields.io/badge/%E2%86%9E%20NUCLEUS-AI--FIRST%20GO%20KERNEL-2AFADF?style=for-the-badge&labelColor=4A4A4A&color=2AFADF" />
  </a>
  <a href="https://github.com/nucleuskit/contract">
    <img alt="Contract driven" src="https://img.shields.io/badge/%E2%8E%88%20CONTRACT--DRIVEN-SERVICE%20GENERATION-F8D66D?style=for-the-badge&labelColor=4A4A4A&color=F8D66D" />
  </a>
  <a href="https://github.com/nucleuskit?tab=repositories">
    <img alt="Modules" src="https://img.shields.io/badge/%E2%97%88%20MODULES-CORE%20%7C%20HTTP%20%7C%20GRPC%20%7C%20WORKER-FF6B9A?style=for-the-badge&labelColor=4A4A4A&color=FF6B9A" />
  </a>
</div>

<div align="center">
  <a href="https://github.com/nucleuskit">
    <img alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=24&duration=2200&pause=720&color=2AFADF&center=true&vCenter=true&random=false&width=900&lines=Contracts+in,+service+systems+out;Small+kernel,+sharp+boundaries;Evolution+and+verification+for+backend+systems" />
  </a>
</div>

<br />

<div align="center">
  <img alt="Nucleuskit command switchboard" src="./assets/nucleus-switchboard-v2.svg" width="100%" />
</div>

<br />

<details open>
  <summary><b>01 / Start the kernel</b></summary>

```txt
contract -> generator -> service edge -> runtime module
```

Nucleuskit is a compact Go toolkit for building backend systems from explicit
contracts. The point is not to hide the architecture. The point is to make the
service boundary obvious, generated code predictable, and verification close to
the edge where systems actually break.

<p>
  <a href="https://github.com/nucleuskit/nucleus">
    <img alt="Open nucleus" src="https://img.shields.io/badge/Open%20nucleus-0D1117?style=flat-square&logo=github&logoColor=white" />
  </a>
  <a href="https://github.com/nucleuskit/nucleus/stargazers">
    <img alt="Star the kernel" src="https://img.shields.io/badge/Star%20the%20kernel-2AFADF?style=flat-square&logo=starship&logoColor=0D1117" />
  </a>
</p>
</details>

<details>
  <summary><b>02 / Flip the module deck</b></summary>

| Surface | Repository | Signal |
| --- | --- | --- |
| kernel | [nucleus](https://github.com/nucleuskit/nucleus) | coordinates generation, evolution, verification |
| contract | [contract](https://github.com/nucleuskit/contract) | keeps service intent explicit |
| core | [core](https://github.com/nucleuskit/core) | holds runtime primitives |
| http | [http](https://github.com/nucleuskit/http) | maps contracts to HTTP edges |
| grpc | [grpc](https://github.com/nucleuskit/grpc) | maps contracts to gRPC edges |
| worker | [worker](https://github.com/nucleuskit/worker) | runs async/background service work |

</details>

<details>
  <summary><b>03 / Inspect the design rule</b></summary>

```txt
If the contract changes, the generated surface should make the blast radius visible.
```

- Prefer explicit service boundaries over clever glue.
- Keep generated code readable enough to debug without ceremony.
- Let modules stay small, named, and replaceable.
- Put verification near the contract, not at the end of the story.

</details>
