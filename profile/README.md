# patimweb-agents

Plugins und Extensions für Coding-Agenten. Dasselbe Werkzeug, zwei Plattformen: einmal als
[pi](https://github.com/earendil-works/pi)-Extension in TypeScript, einmal als
[Hermes Agent](https://github.com/NousResearch/hermes-agent)-Plugin in Python.

## Portierte Werkzeuge

Wo beide Spalten gefüllt sind, ist die `pi`-Version die Referenz und die `hermes`-Version der Port
desselben Vertrags — gleiche Tools, gleiche Parameter, gleiches Konfigurationsformat.

| Domäne | pi (TypeScript, npm) | Hermes (Python) |
|---|---|---|
| SSH, SFTP, Port-Forwarding | [`pi-ssh`](https://github.com/patimweb-agents/pi-ssh) | [`hermes-ssh`](https://github.com/patimweb-agents/hermes-ssh) |
| Microsoft Teams | [`pi-teams`](https://github.com/patimweb-agents/pi-teams) | [`hermes-teams`](https://github.com/patimweb-agents/hermes-teams) |
| Outline-Wiki | [`pi-outline-wiki`](https://github.com/patimweb-agents/pi-outline-wiki) | [`hermes-outline-wiki`](https://github.com/patimweb-agents/hermes-outline-wiki) |
| Azure DevOps | [`pi-azure-devops`](https://github.com/patimweb-agents/pi-azure-devops) | [`hermes-azure-devops`](https://github.com/patimweb-agents/hermes-azure-devops) |
| ABAP-Dateisystem | [`pi-abap-fs`](https://github.com/patimweb-agents/pi-abap-fs) | [`hermes-abap-remote-fs`](https://github.com/patimweb-agents/hermes-abap-remote-fs) |
| Agent-zu-Agent-Kommunikation | [`pi-swarm`](https://github.com/patimweb-agents/pi-swarm) | — |

## Nur pi

| Plugin | Was es tut |
|---|---|
| [`pi-email`](https://github.com/patimweb-agents/pi-email) | IMAP/SMTP: lesen, suchen, senden, triagieren |
| [`pi-cron`](https://github.com/patimweb-agents/pi-cron) | geplante Prompts |
| [`pi-localsend`](https://github.com/patimweb-agents/pi-localsend) | Dateien zwischen Geräten im Netz senden |
| [`pi-mindplace`](https://github.com/patimweb-agents/pi-mindplace) | räumliches Gedächtnis der Codebase |
| [`pi-nodejs-bestpractices`](https://github.com/patimweb-agents/pi-nodejs-bestpractices) | Node.js-Skills für den Agenten |
| [`pi-cap-bestpractices`](https://github.com/patimweb-agents/pi-cap-bestpractices) | SAP-CAP-Skills für den Agenten |

## Nur Hermes

| Plugin | Was es tut |
|---|---|
| [`hermes-sapgui`](https://github.com/patimweb-agents/hermes-sapgui) | SAP GUI Scripting gegen das echte GUI-Fenster |
| [`hermes-homeassistant-pe-adapter`](https://github.com/patimweb-agents/hermes-homeassistant-pe-adapter) | Voice PE: Wake Word, Mistral Voxtral STT/TTS |
| [`hermes-mistral-voice`](https://github.com/patimweb-agents/hermes-mistral-voice) | Platzhalter, noch nicht gebaut |

## Installation

```bash
# pi
pi install npm:@patimweb/pi-ssh

# Hermes
hermes plugins install patimweb-agents/hermes-ssh
```

Alle `pi`-Pakete liegen unter dem npm-Scope [`@patimweb`](https://www.npmjs.com/org/patimweb).

## Lizenzen

MIT, sofern im jeweiligen Repository nicht anders angegeben.

---

Stand: 2026-10-30 · 20 Repositories
