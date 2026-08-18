<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:3d59a1&height=180&section=header&text=maclucky&fontColor=c0caf5&fontSize=70&fontAlignY=32" width="100%" alt="maclucky" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=7AA2F7&center=true&vCenter=true&width=560&lines=Go+on+the+backend%2C+Swift+on+the+phone;Two+Kubernetes+clusters%2C+one+GitOps+repo;Prometheus+exporters+for+things+nobody+exports;Self-hosted+until+it+hurts" alt="Go on the backend, Swift on the phone" />

<br />

<a href="https://macluckylab.com"><img src="https://img.shields.io/badge/macluckylab.com-1a1b27?style=for-the-badge&logo=firefox&logoColor=7aa2f7" alt="Website" /></a>
<a href="https://pushward.app"><img src="https://img.shields.io/badge/PushWard-1a1b27?style=for-the-badge&logo=apple&logoColor=7aa2f7" alt="PushWard" /></a>
<img src="https://img.shields.io/badge/Wroclaw,%20PL-1a1b27?style=for-the-badge&logo=googlemaps&logoColor=7aa2f7" alt="Wroclaw, PL" />
<img src="https://komarev.com/ghpvc/?username=mac-lucky&style=for-the-badge&color=3d59a1&label=VIEWS" alt="Profile views" />

</div>

---

## 📱 PushWard

A push-notification platform I build end to end. Native clients on iOS, watchOS and macOS, a Go backend on Kubernetes, and Live Activities that keep a job, a build or a sensor on your lock screen while it is still running rather than pinging you once and disappearing.

The interesting part is everything feeding it. Home Assistant entities, Grafana alerts, Unraid array events and webhook sources all land in the same activity model, so one glance covers the house, the cluster and CI.

<div align="center">
<a href="https://pushward.app"><img src="https://img.shields.io/badge/pushward.app-3d59a1?style=for-the-badge&logo=safari&logoColor=white" alt="pushward.app" /></a>
</div>

| Repo | What it does | |
|---|---|---|
| **[pushward-hass](https://github.com/mac-lucky/pushward-hass)** | HACS integration that tracks Home Assistant entities as Live Activities | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-hass?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" /> |
| **[pushward-integrations](https://github.com/mac-lucky/pushward-integrations)** | Relay plus six bridges, a seven-module Go workspace | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-integrations?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| **[pushward-grafana-plugin](https://github.com/mac-lucky/pushward-grafana-plugin)** | Turns Grafana alerts into Live Activities, plus a PromQL widget engine | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-grafana-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go%20+%20React-00ADD8?style=flat-square&logo=grafana&logoColor=white" alt="Go and React" /> |
| **[pushward-mcp](https://github.com/mac-lucky/pushward-mcp)** | MCP server so an agent can drive notifications and activities | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-mcp?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| **[pushward-unraid-plugin](https://github.com/mac-lucky/pushward-unraid-plugin)** | Forwards Unraid notifications and tracks parity, backup and mover | <img src="https://img.shields.io/github/stars/mac-lucky/pushward-unraid-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/PHP%20+%20Bash-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP and Bash" /> |

---

## 🛠️ Homelab and infrastructure

Two clusters, split on purpose. A bare-metal Talos cluster and a managed one, both provisioned with OpenTofu and populated by ArgoCD from a single GitOps repo. Secrets are SOPS and age, images are multi-arch and built on tag, and a self-hosted Forgejo runs its own Actions lanes next to GitHub.

The exporters below exist because I wanted a metric nobody was publishing yet.

| Repo | What it does | |
|---|---|---|
| **[kubernetes-ping-exporter](https://github.com/mac-lucky/kubernetes-ping-exporter)** | Pod-to-pod and external ICMP latency, ships its own Helm chart | <img src="https://img.shields.io/github/stars/mac-lucky/kubernetes-ping-exporter?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| **[plausible-exporter](https://github.com/mac-lucky/plausible-exporter)** | Plausible Analytics into Prometheus | <img src="https://img.shields.io/github/stars/mac-lucky/plausible-exporter?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| **[hassio-addons](https://github.com/mac-lucky/hassio-addons)** | Home Assistant add-ons: journald shipping and a GitOps agent for /config | <img src="https://img.shields.io/github/stars/mac-lucky/hassio-addons?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| **[actions-shared-workflows](https://github.com/mac-lucky/actions-shared-workflows)** | Reusable CI/CD backbone every repo of mine rides on | <img src="https://img.shields.io/github/stars/mac-lucky/actions-shared-workflows?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" /> |
| **[nvidia-gpu-exporter-unraid-plugin](https://github.com/mac-lucky/nvidia-gpu-exporter-unraid-plugin)** | Packages a GPU exporter as a one-click Unraid plugin | <img src="https://img.shields.io/github/stars/mac-lucky/nvidia-gpu-exporter-unraid-plugin?style=flat-square&color=3d59a1&labelColor=1a1b27&logo=github&logoColor=7aa2f7" alt="stars" /> <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Shell" /> |

---

## 🧰 Tools of the trade

<div align="center">

<img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte" />

<br />

<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
<img src="https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" />
<img src="https://img.shields.io/badge/OpenTofu-FFDA18?style=for-the-badge&logo=opentofu&logoColor=black" alt="OpenTofu" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white" alt="Traefik" />

<br />

<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Home%20Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white" alt="Home Assistant" />
<img src="https://img.shields.io/badge/Forgejo-FB923C?style=for-the-badge&logo=forgejo&logoColor=white" alt="Forgejo" />

</div>

---

## 📊 By the numbers

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mac-lucky&theme=tokyonight" width="100%" alt="Profile summary" />

<br />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mac-lucky&theme=tokyonight" height="200" alt="Repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mac-lucky&theme=tokyonight" height="200" alt="Most committed language" />

<br />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=mac-lucky&theme=tokyonight" height="200" alt="Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=mac-lucky&theme=tokyonight&utcOffset=2" height="200" alt="Productive time" />

<br />

<img src="https://streak-stats.demolab.com/?user=mac-lucky&theme=tokyonight&hide_border=true&card_width=470" alt="Contribution streak" />

<br /><br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mac-lucky&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20activity" width="100%" alt="Contribution activity graph" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d59a1,100:1a1b27&height=120&section=footer" width="100%" alt="" />

</div>
