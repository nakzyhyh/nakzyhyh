<!-- Fancy Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:36BCF7,100:9B5DE5&text=Kai%20&%20Entwickler&fontSize=42&fontAlignY=40&fontColor=ffffff&desc=Code%20×%20Philosophie%20×%20Didaktik&descAlignY=58&animation=fadeIn" alt="Header Banner"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=600&lines=Software-Entwickler+%26+Systemarchitektur;Didaktik-Enthusiast;Code+for+a+better+Tomorrow" alt="Typing Animation"/>
  </a>
</p>

---
<p align="center">
  Willkommen auf meinem digitalen Campus. Hier verbinde ich Code mit Kreativität und strategischem Denken, um robuste und intelligente Lösungen zu entwickeln.
</p>

---

## Über mich

- 🚀 Aktuell baue ich ein **Skill-Portfolio** mit Fokus auf **Sicherheit, Automatisierung** und **durchdachte Software-Architekturen**.  
- 💡 Ich verbinde technische Expertise mit **Philosophie**, **Psychologie** und kreativen Hobbys wie **Klavier**, **Zeichnen** und **Lesen**.  
- ✍️ <strong>Autor</strong>: <em>Unter demselben Himmel</em> (Debütroman).

---

## 🛠 Tech Stack & Skills

<p align="center">
  <img src="https://img.shields.io/badge/Linux-Ubuntu-blue?style=for-the-badge&logo=ubuntu"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Lens%20(K8s%20IDE)-6C4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Loki-1F60C4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Alloy-444?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white"/>
  <img src="https://img.shields.io/badge/Caddy%20(Reverse%20Proxy)-2CA02C?style=for-the-badge"/>
</p>

<p align="center">
  <!-- Dev -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white"/>
</p>

---

## 🤖 AI-Enhanced Development

> Von Daten zu Entscheidungen: RAG-Pipelines, Agenten & Multimodalität – beschleunigt mit Claude Opus & OpenAI.

<p align="center">
  <!-- Modelle & Provider -->
  <img src="https://img.shields.io/badge/OpenAI%20API/CODEX-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Claude%20Opus-0A7FFF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
</p>

<p align="center">
  <!-- Serving, MLOps & Observability -->
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Loki-1F60C4?style=for-the-badge"/>
</p>


## 🔭 Traineeship Project: Kubernetes Observability E2E (2025)

**Ziel:** Ende-zu-Ende Logging für einen K8s-Cluster – **sicher**, **reproduzierbar**, **rauscharm**.  
**Ergebnis:** Pods → **Alloy (DaemonSet)** → **Loki** (DigitalOcean, hinter **Caddy/TLS + Auth**) → **Grafana** (Explore, Dashboards, Alerts).  
**Workflow:** **Lens-first** zur Verifikation (Rollouts, Events, Logs, YAML-Diffs).

### Was gelöst wurde
- 🔒 **Security by Default**: TLS/Basic-Auth via Caddy, DO-Firewall (Allowlist), sofortige PW-Änderung, persistente Volumes + Backup-Plan.  
- 🧹 **Signal statt Rauschen**: **Eigenlogs** (`monitoring` / `alloy`) werden **am Agent gedroppt** → geringere Kosten, klarere Dashboards.  
- 🧭 **Bedienbarkeit**: Queries ans **tatsächliche Label-Set** angepasst; Live-Tail; Starter-Dashboard (Log-Rate, Errors, Top-Pods).  
- 🧰 **Pro-Workflow**: Rollouts **ohne** Annotation-Hack → `kubectl rollout restart ds/alloy -n monitoring`.  
- 🧪 **Smoke-Test dokumentiert**: Eigenlogs nur als **Phase-0** zur Pipeline-Validierung, danach Apps-Sicht.



---

## 🚀 Projekte

<table>
  <tr>
    <td colspan="2">
      <h3 align="center">SkillForge: Adaptives IHK-Lern-Ökosystem</h3>
      <p align="center">
        <img src="Assets/SkillForge_Logo.png" width="400" alt="SkillForge Logo" />
      </p>
      <p align="center">
        <strong>SkillForge</strong> ist eine progressive Web-App zur gezielten Vorbereitung auf IHK-Abschlussprüfungen für Fachinformatiker.  
        Es basiert auf einem <strong>psychologisch fundierten 3-Phasen-Modell</strong> (Wissensaufnahme → Praxistransfer → Überprüfung) und bietet <strong>adaptive Lernpfade</strong>, Spaced-Repetition-Logik und realitätsnahe Szenarien (Subnetting, Nutzwertanalyse, Netzpläne).
      </p>
      <p align="center">
        <strong>Architektur:</strong> Modularer ES6-Code, UI-State-Management, vorbereitet für MongoDB/Mongoose.
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">GameGuard: Secure Your Play</h3>
      <p align="center">
        <img src="Assets/gglogo.png" width="200" alt="GameGuard Logo" />
      </p>
      <p align="center">
        Ein Desktop-Tool für eine sichere Spielumgebung: automatisierter VPN-Tunnel (WireGuard/OpenVPN), Firewall-Isolation und Kill-Switch.
      </p>
      <p align="center"><strong>Tech:</strong> Electron, Node.js, PowerShell</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">Project Lighthouse</h3>
      <p align="center">
        <img src="Assets/lighthouse.png" width="200" alt="Lighthouse Logo" />
      </p>
      <p align="center">
        Ein All-in-One-Diagnosewerkzeug mit Netzwerkbefehlen, LAN-Scanner, Live-Diagnose und geführter Fehlersuche.
      </p>
      <p align="center"><strong>Tech:</strong> Electron, Node.js, HTML, CSS</p>
    </td>
  </tr>
</table>


## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nakzyhyh/nakzyhyh/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nakzyhyh/nakzyhyh/output/snake-light.svg" />
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/nakzyhyh/nakzyhyh/output/snake-dark.svg" />
  </picture>
</p>

---

## 📫 Kontakt

<p align="center">
  <a href="DEIN_LINKEDIN_PROFIL_LINK">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge" />
  </a>
  <a href="mailto:DEINE_EMAIL@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-Mail Badge" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:9B5DE5,100:36BCF7&height=120&section=footer" alt="Footer Banner"/>
</p>
