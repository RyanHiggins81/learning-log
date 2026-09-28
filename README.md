# Learning Log — Ryan Higgins

> Returning to IT and building in public, one commit at a time. Focus: **AI security & red teaming**.

I spent years in IT (desktop support, training, networking) before stepping away to work in game design. I'm now back and specialising in **AI security** — the place where penetration testing meets machine learning. This repo is my open journal: what I'm studying, what I'm building, and what I'm learning along the way.

I believe the best proof of skill is a visible trail of work. So here it is.

---

## 🎯 Goal

To become an **AI security / red team practitioner** — securing and adversarially testing AI and LLM-based systems. This log tracks the journey from foundations to portfolio.

## 📍 Current focus
- **Now:** [Linux refresh + CompTIA Security+ (Domain 1)]
- **Next:** [TryHackMe Pre Security path; first Python tool]

---

## 📜 Certifications

| Certification | Status | Date |
|---|---|---|
| Cert IV in Cyber Security (Chisholm TAFE) | In progress | [expected completion - July 2027] |
| CompTIA Security+ (SY0-701) | Planned | [target month - August - September] |
| eJPT | Planned | [target month - September - October] |


> Background: Cert III in IT (2025), plus earlier IT certifications (CompTIA, Microsoft, Cisco, Novell) now lapsed — listed here for context, not currency.
CompTIA certifications: A+; Linux+; CTT
Microsoft Certifications: MCP; MCDST; MCSA; MCT
Novell Certifications: CLA; CLP; LTS; CNI
Cisco Certifications: CCNA

---

## 🛠️ Projects
*Building these out across 2026 — watch this space.*


---

## 🔗 Find me

- **GitHub:** https://github.com/RyanHiggins81
- **Blog / write-ups:** 
- **TryHackMe:** https://tryhackme.com/p/ryan.anthony.higgins
- **HackTheBox:** https://profile.hackthebox.com/profile/019f7e4d-9dbe-727e-a4f4-fbb281423ce1


---

## 🗓️ Log

---

### [2026-07-20] — Day 1: setting up the workshop
- **Studied:** Skimmed the CompTIA SY0-701 exam objectives to see the shape of the map.
- **Built / did:** Created this repo, set up Kali + Ubuntu VMs, made TryHackMe & HackTheBox accounts.
- **Learned:** Learnt how to create and manage public git repositories.
- **Next:** Start Linux refresh (Linux Journey + OverTheWire Bandit) and Professor Messer Domain 1.

### [2026-09-28] - Local AI Assistants

A set of Python and Streamlit apps I built to keep working when I hit my Claude usage limits, and to experiment with running AI models locally.

- **Fallback Assistant (Claude API):** a lightweight chat app using Claude Haiku 4.5 through the Anthropic API, with web search, for everyday tasks, research, and brainstorming.
- **Fallback Assistant (Local):** the same app running fully offline on Ollama, GPU-accelerated on an AMD RX 6700 XT via Vulkan.
- **Local GM:** an offline game master for playtesting tabletop RPG scenarios. It indexes rulebook PDFs for rules lookups, tracks scenario state and a rolling story summary across long sessions, and rolls real dice.
- **Chatbot Framework:** a single app that runs any number of custom chatbots, each defined by a simple YAML persona file. Every bot can have its own personality, model, creativity level, and memory length, and can run locally on Ollama or through the Claude API. Bots can use tools for live web search, current weather, and dice rolls. Current bots include a roleplaying scene GM, a card game design partner, and an everyday assistant. Creating a new bot takes a few minutes, with no code changes.

Both fallback assistants share a `/log` command that saves daily entries to a synced CSV, so Claude can pick them up once my limits reset.

### Remote access

Everything runs on my home PC, but I can use any of the apps from my phone anywhere through a private Tailscale network. Nothing is exposed to the public internet, and conversations carry over seamlessly between devices. A startup script launches all the apps automatically on login.

Built with Python, Streamlit, Ollama, the Anthropic API, and Tailscale.

---

## 📚 Resources I'm using
- Linux: Linux Journey, *The Linux Command Line* (Shotts), OverTheWire Bandit
- Python: *Automate the Boring Stuff*, Exercism
- Security+: Professor Messer (SY0-701)
- Practice: TryHackMe, HackTheBox, PicoCTF

---

<sub>This is a living document — updated as I learn. Built in public on purpose.</sub>
