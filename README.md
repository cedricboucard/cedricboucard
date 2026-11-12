# Cédric Boucard — Support IT & Cybersécurité

**Technicien support N1/N2 · orientation SOC Analyst · Toulouse**

Deux ans de support applicatif en production, un poste Linux au quotidien et des outils Python qui mêlent supervision système, IA locale et sécurité. J'apprends en construisant, avec un parti pris : **IA 100 % locale** (Ollama + Piper TTS), sans dépendance au cloud.

---

## 🛠️ Projets

### 📞 [helpdesk-simulator](https://github.com/cedricboucard/helpdesk-simulator)
Simulateur vocal d'appels support N1/N2 en ligne de commande, directement inspiré de mon expérience terrain.
- Utilisateurs simulés par **Llama 3.2 (Ollama)**, doublés en temps réel par **Piper TTS**
- Scénarios progressifs : mot de passe, imprimante, lecteur réseau, SQL Server, ERP verrouillé, mode chaos
- Travaille le diagnostic méthodique (modèle OSI, services, droits) et les soft skills (stress, reformulation, pas de jargon)
- `Python` `Ollama` `Piper TTS` `CLI`

### 🛡️ [sentinelle-watchdog](https://github.com/cedricboucard/sentinelle-watchdog)
Agent de monitoring Linux + Docker avec diagnostic de cause racine par IA locale.
- Surveille CPU, RAM, disque et état des conteneurs
- Envoie les logs pertinents à **Ollama (Llama 3.2)** et produit un rapport vocal via **Piper TTS**
- Notification Discord, anti-spam par cooldown, prêt pour systemd, 100 % hors-ligne
- `Python` `Docker` `Ollama` `Piper TTS` `systemd`

### 🗣️ [pc-agents](https://github.com/cedricboucard/pc-agents)
Système multi-agents qui donne une personnalité au CPU, au GPU et à la RAM.
- Télémétrie en temps réel (charge, température, fréquence) via `psutil` et `pynvml`
- Dialogues générés par un LLM local (Ollama), affichés dans le terminal avec un code couleur ANSI par composant
- Mode chat interactif pour interroger directement chaque composant
- `Python` `Ollama` `psutil` `pynvml` · Licence MIT

### Autres réalisations
| Projet | Description |
|---|---|
| [SIEM Severity Legend](https://cedricboucard.github.io/SIEM-Severity-Legend/) | Référentiel visuel des niveaux de sévérité des incidents SOC |
| Console-SOC | Maquette de dashboard SOC en HTML/CSS pur |

---

## 🔐 Cybersécurité

- **TryHackMe** — top 5 % mondial (`CedriCode`), Pre-Security et Cyber Security 101 terminés
- **Divulgation responsable** — CVE-2026-22778 (vLLM, CVSS 9.8) ; signalement d'une injection de prompt sur Gemini
- **Outils pratiqués** — Wireshark, Nmap, Hydra, Metasploit, SQLMap, Burp Suite, Snort, Volatility 3, FlareVM, REMnux
- **Lab** — Kali + Metasploitable2 pour l'exploitation et l'analyse en environnement isolé

---

## 💼 Expérience

**Chargé d'assistance applicative — Berger-Levrault** · 2 ans
Support utilisateurs N1/N2 sur des logiciels métier : diagnostic, qualification et suivi des incidents, prise en main à distance, escalade vers les équipes techniques.
`Salesforce` `GLPI` `Jira` `Prise en main à distance`

**Formation** — BTS SNIR (Systèmes Numériques, option Informatique et Réseaux)

---

## 🧰 Compétences

| Domaine | Outils et notions |
|---|---|
| Support & méthodes | Diagnostic N1/N2, ITIL (entonnoir, clôture), gestion d'utilisateurs, documentation |
| Systèmes & réseau | Linux (Ubuntu au quotidien), Windows, modèle OSI, services, permissions, SMB, DHCP |
| Développement | Python (CLI, automatisation, API Docker), SQL, Bash, HTML/CSS, bases React |
| Homelab | VirtualBox, Docker, labs de pentest |
| IA locale | Ollama (Llama 3.2), Piper TTS |
| ITSM | GLPI, Jira, Salesforce |

---

## 🎯 Objectifs

- [ ] **LFCA** (Linux Foundation Certified IT Associate) — en préparation via Coursera
- [ ] **TryHackMe SOC Level 1**
- [ ] **CompTIA Security+**

---

## 📫 Contact

[![TryHackMe](https://img.shields.io/badge/TryHackMe-CedriCode-red?style=flat&logo=tryhackme)](https://tryhackme.com/p/CedriCode)
[![GitHub](https://img.shields.io/badge/GitHub-cedricboucard-181717?style=flat&logo=github)](https://github.com/cedricboucard)

Je recherche un poste **Support N1/N2 ou SOC Analyst à Toulouse**. N'hésitez pas à parcourir mes dépôts ou à me contacter.
