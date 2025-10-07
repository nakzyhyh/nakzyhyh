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

## 🛠 Tech Stack & Skills (Originale Icons)

<!-- Dev / Core -->
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/powershell/powershell-plain.svg" height="40" alt="PowerShell"/>
</p>

<!-- DevOps / Platforms -->
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="40" alt="Kubernetes"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/helm/helm-original.svg" height="40" alt="Helm"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="Linux"/>
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/digitalocean.svg" height="40" alt="DigitalOcean"/>
  <img src="https://cdn.simpleicons.org/caddy/2CA02C" height="40" alt="Caddy"/>
</p>

<!-- Observability -->
<p align="center">
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/grafana.svg" height="40" alt="Grafana"/>
  <img src="https://raw.githubusercontent.com/gilbarbara/logos/master/logos/prometheus.svg" height="40" alt="Prometheus"/>
  <img src="https://cdn.simpleicons.org/grafana/1F60C4" height="40" alt="Loki"/>
  <img src="https://cdn.simpleicons.org/grafana/444" height="40" alt="Alloy"/>
  <img src="https://cdn.simpleicons.org/lens/5B9BD5" height="40" alt="Lens"/>
</p>

<!-- AI / Data -->
<p align="center">
  <img src="https://cdn.simpleicons.org/fastapi/009688" height="40" alt="FastAPI"/>
  <img src="https://cdn.simpleicons.org/pytorch/EE4C2C" height="40" alt="PyTorch"/>
  <img src="https://cdn.simpleicons.org/scikitlearn/F7931E" height="40" alt="scikit-learn"/>
  <img src="https://cdn.simpleicons.org/openai/412991" height="40" alt="OpenAI"/>
  <img src="https://cdn.simpleicons.org/anthropic/0A7FFF" height="40" alt="Anthropic"/>
  <img src="https://cdn.simpleicons.org/leaflet/199900" height="40" alt="Leaflet"/>
</p>

---

## 🤖 AI-Enhanced Development

> Von Daten zu Entscheidungen: RAG-Pipelines, Agenten & Multimodalität – mit OpenAI & Claude orchestriert.

---

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

### MYCora (kompakt, mit AI-Tech)
Kern-Use-Case: **Pilzfunde dokumentieren**, filtern & **KI‑Vorschlag** zur Bestimmung.  
**Frontend:** Journal/Karten, Overlay mit Chips & Galerie, Leaflet-Karte, Import/Export (JSON).  
**Bekannte Limits:** **localStorage‑Quota** (`mycora_autobak_v2`), Mini‑Map‑Feed fixen, SW nur UI‑offline.

<details>
  <summary><b>AI‑Funktionen & Technik</b> (präzise, kompakt)</summary>

  <b>Funktionen</b>  
  • <b>KI trainieren aus Journal</b> → lernt ein erklärbares <i>Merkmals-/Artenmodell</i> aus gelabelten Einträgen (Bilder + Artname).  
  • <b>KI‑Vorschlag</b> → Bild hochladen, Top‑k‑Scores mit Konfidenzen.

  <b>Pipeline</b>  
  1) <i>Embedding</i>: MobileNet v3 Large (TorchVision), Kopf entfernt → Feature‑Vektor  \n
  2) <i>Classifier</i>: Logistic Regression (One‑vs‑Rest), scikit‑learn (optional Kalibrierung)

  <b>Preprocessing</b>  
  Resize 224×224 • CenterCrop • Normalize (ImageNet µ/σ) • optionale Augmentation

  <b>Serving</b>  
  FastAPI/Uvicorn • Endpunkte: <code>GET /health</code>, <code>POST /traits/train</code>, <code>POST /traits/predict</code> • Modell unter <code>MODEL_DIR/trait_model.pkl</code>, Warm‑Reload

  <b>Qualität & Betrieb</b>  
  Top‑k=5 • Score‑Threshold (z. B. ≥0.55) → „unsicher“ • Infer ≈ 50–150 ms/CPU (CX22) • Bilder nur für Embedding/Infer • Backups/Modelle auf Storage‑Box (SSHFS)
</details>

---

### SkillForge: Adaptives IHK-Lern-Ökosystem
PWA zur IHK-Vorbereitung (FISI). **3-Phasen-Modell** (Wissensaufnahme → Praxistransfer → Überprüfung), **Spaced Repetition**, realitätsnahe Szenarien (Subnetting, Nutzwertanalyse, Netzpläne).  
**Architektur:** Modularer ES6-Code, UI-State-Management, vorbereitet für MongoDB/Mongoose.

---

### GameGuard: Secure Your Play
Desktop-Tool für eine sichere Spielumgebung: automatisierter VPN-Tunnel (WireGuard/OpenVPN), Firewall-Isolation & Kill-Switch.  
**Tech:** Electron, Node.js, PowerShell.

---

### Project Lighthouse
All-in-One-Diagnose: Netzwerkbefehle, LAN-Scanner, Live-Diagnose & geführte Fehlersuche.  
**Tech:** Electron, Node.js, HTML, CSS.

---

### Weitere Lösungen (kurz)
- **n8n Workflow-Templates** (Shopify, Content-Automation), Dockerized, self-hosted.  
- **Observability-Blueprint** (Loki/Grafana/Alloy) – TLS, Auth, DO-Firewall.  
- **PowerShell-Skripte** (Windows-Deployment, Netzwerk-Checks, Backup/Sync).  
- **Portfolio-PWA** (HTML/CSS/JS) mit Offline-Cache & modularen Komponenten.

---

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
  <a href="https://n8nk-ai.de">
    <img src="https://cdn.simpleicons.org/vercel/000000" height="22" alt="Vercel"/> n8nk-ai.de
  </a>
  &nbsp;•&nbsp;
  <a href="https://github.com/nakzyhyh">
    <img src="https://cdn.simpleicons.org/github/ffffff" height="22" alt="GitHub"/> @nakzyhyh
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:9B5DE5,100:36BCF7&height=120&section=footer" alt="Footer Banner"/>
</p>
