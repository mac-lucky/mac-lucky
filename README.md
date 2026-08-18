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

<a href="https://pushward.app"><img src="https://img.shields.io/badge/pushward.app-3d59a1?style=flat-square&logo=safari&logoColor=white" alt="pushward.app" /></a>

<a href="https://github.com/mac-lucky/pushward-hass"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=pushward-hass&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="pushward-hass" /></a>
<a href="https://github.com/mac-lucky/pushward-integrations"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=pushward-integrations&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="pushward-integrations" /></a>
<a href="https://github.com/mac-lucky/pushward-grafana-plugin"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=pushward-grafana-plugin&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="pushward-grafana-plugin" /></a>
<a href="https://github.com/mac-lucky/pushward-mcp"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=pushward-mcp&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="pushward-mcp" /></a>
<a href="https://github.com/mac-lucky/pushward-unraid-plugin"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=pushward-unraid-plugin&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="pushward-unraid-plugin" /></a>

</div>

---

## 🛠️ Homelab and infrastructure

Two clusters, split on purpose. A bare-metal Talos cluster at home and a managed one in Oracle Cloud, both provisioned with OpenTofu and populated by ArgoCD from a single GitOps repo. Secrets are SOPS and age, images are multi-arch and built on tag, and a self-hosted Forgejo runs its own Actions lanes next to GitHub.

The exporters below exist because I wanted a metric nobody was publishing yet.

<div align="center">

<a href="https://github.com/mac-lucky/kubernetes-ping-exporter"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=kubernetes-ping-exporter&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="kubernetes-ping-exporter" /></a>
<a href="https://github.com/mac-lucky/plausible-exporter"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=plausible-exporter&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="plausible-exporter" /></a>
<a href="https://github.com/mac-lucky/actions-shared-workflows"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=actions-shared-workflows&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="actions-shared-workflows" /></a>
<a href="https://github.com/mac-lucky/hassio-addons"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mac-lucky&repo=hassio-addons&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="hassio-addons" /></a>

</div>

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

<img src="https://github-readme-stats.vercel.app/api?username=mac-lucky&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&rank_icon=github&cache_seconds=86400" height="180" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mac-lucky&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&hide=dockerfile,hcl,makefile&exclude_repo=Vivado-VHDL-RTC-using-I2C-Master-Slave,Arduino-RTC-with-Temperature,STM32-HC-SR04-USART-timer-pulse-width,DatabaseManager,COVID-19-daily-database-with-SQLite3,weather-station-React&cache_seconds=86400" height="180" alt="Most used languages" />

<br />

<img src="https://streak-stats.demolab.com/?user=mac-lucky&theme=tokyonight&hide_border=true&card_width=470" alt="Contribution streak" />

<br /><br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mac-lucky&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20activity" width="100%" alt="Contribution activity graph" />

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mac-lucky/mac-lucky/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mac-lucky/mac-lucky/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/mac-lucky/mac-lucky/output/github-snake.svg" width="100%" alt="Snake eating my contribution graph" />
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3d59a1,100:1a1b27&height=120&section=footer" width="100%" alt="" />

</div>
