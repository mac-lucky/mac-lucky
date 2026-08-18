<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=7AA2F7&center=true&vCenter=true&width=560&lines=Go+on+the+backend%2C+Swift+on+the+phone;Two+Kubernetes+clusters%2C+one+GitOps+repo;Prometheus+exporters+for+things+nobody+exports;Self-hosted+until+it+hurts" alt="Go on the backend, Swift on the phone" />

<a href="https://macluckylab.com"><img src="https://img.shields.io/badge/macluckylab.com-1a1b27?style=flat-square&logo=firefox&logoColor=7aa2f7" alt="Website" /></a>
<a href="https://pushward.app"><img src="https://img.shields.io/badge/pushward.app-1a1b27?style=flat-square&logo=apple&logoColor=7aa2f7" alt="PushWard" /></a>
<img src="https://img.shields.io/badge/Wroclaw,%20PL-1a1b27?style=flat-square&logo=googlemaps&logoColor=7aa2f7" alt="Wroclaw, PL" />
<img src="https://komarev.com/ghpvc/?username=mac-lucky&style=flat-square&color=3d59a1&label=views" alt="Profile views" />

<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="Argo CD" />
<img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=flat-square&logo=opentofu&logoColor=black" alt="OpenTofu" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/Home%20Assistant-18BCF2?style=flat-square&logo=homeassistant&logoColor=white" alt="Home Assistant" />
<img src="https://img.shields.io/badge/Forgejo-FB923C?style=flat-square&logo=forgejo&logoColor=white" alt="Forgejo" />

</div>

### 📱 PushWard

Push-notification platform I build end to end: iOS, watchOS and macOS clients, a Go backend on Kubernetes, and Live Activities that stay on the lock screen while a job is still running. Home Assistant, Grafana, Unraid and webhooks all feed the same activity model.

| Repo | What it does | |
|---|---|---|
| **[pushward-hass](https://github.com/mac-lucky/pushward-hass)** | HACS integration tracking Home Assistant entities as Live Activities | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-hass?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[pushward-integrations](https://github.com/mac-lucky/pushward-integrations)** | Relay plus six bridges, a seven-module Go workspace | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-integrations?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[pushward-grafana-plugin](https://github.com/mac-lucky/pushward-grafana-plugin)** | Grafana alerts into Live Activities, plus a PromQL widget engine | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-grafana-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[pushward-mcp](https://github.com/mac-lucky/pushward-mcp)** | MCP server so an agent can drive notifications and activities | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-mcp?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[pushward-unraid-plugin](https://github.com/mac-lucky/pushward-unraid-plugin)** | Forwards Unraid notifications, tracks parity, backup and mover | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-unraid-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |

### 🛠️ Homelab and infrastructure

Two clusters, split on purpose: one bare-metal Talos, one managed, both provisioned with OpenTofu and populated by ArgoCD from a single GitOps repo. SOPS and age for secrets, multi-arch images built on tag, and a self-hosted Forgejo running its own Actions lanes next to GitHub.

| Repo | What it does | |
|---|---|---|
| **[kubernetes-ping-exporter](https://github.com/mac-lucky/kubernetes-ping-exporter)** | Pod-to-pod and external ICMP latency, ships its own Helm chart | <img src="https://img.shields.io/github/stars/mac-lucky/kubernetes-ping-exporter?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[plausible-exporter](https://github.com/mac-lucky/plausible-exporter)** | Plausible Analytics into Prometheus | <img src="https://img.shields.io/github/stars/mac-lucky/plausible-exporter?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[hassio-addons](https://github.com/mac-lucky/hassio-addons)** | HA add-ons: journald shipping and a GitOps agent for /config | <img src="https://img.shields.io/github/stars/mac-lucky/hassio-addons?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[actions-shared-workflows](https://github.com/mac-lucky/actions-shared-workflows)** | Reusable CI/CD backbone every repo of mine rides on | <img src="https://img.shields.io/github/stars/mac-lucky/actions-shared-workflows?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |
| **[nvidia-gpu-exporter-unraid-plugin](https://github.com/mac-lucky/nvidia-gpu-exporter-unraid-plugin)** | Packages a GPU exporter as a one-click Unraid plugin | <img src="https://img.shields.io/github/stars/mac-lucky/nvidia-gpu-exporter-unraid-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> |

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mac-lucky&theme=tokyonight" height="140" alt="Repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=mac-lucky&theme=tokyonight&utcOffset=2" height="140" alt="Productive time" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mac-lucky&theme=tokyo-night&hide_border=true&area=true&height=250" width="100%" alt="Contribution activity graph" />

</div>
