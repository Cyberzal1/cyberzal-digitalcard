# 🛡️ Cyberzal — Digital Business Card

> A cyberpunk-terminal-themed interactive digital business card for **Cyberzal (Sopfian Ismail)** — Cyber Security Ops / Cloud Support & DevOps professional.

**Live:** [cyberzal-digitalcard.netlify.app](https://cyberzal-digitalcard.netlify.app/)

---

## About

This is a personal digital business card — a single-page, always-on identity hub that replaces the paper name card with something that actually fits a security professional's brand: dark terminal aesthetics, a scanning-line animation, a live `STATUS: ONLINE` indicator, and a QR code for instant sharing at meetups, career fairs, or client meetings.

Instead of handing someone a piece of cardboard that gets lost in a wallet, this card is a link (or a QR scan) away — always up to date, always reachable, and it doubles as a quick portfolio snapshot: who I am, what I focus on, and where to find my resume and profiles.

## Why a "business" digital card?

- **One link, always current** — update the source once, redeploy, and every card I've ever shared reflects the change. No reprinting, no outdated titles.
- **Instant credibility snapshot** — a recruiter, mentor, or client sees role, education, and focus area in seconds, styled to match the "cyber security" identity rather than a generic template.
- **Frictionless sharing** — the built-in QR code means a card can be shared in person in under 3 seconds, no typing a name into LinkedIn search.
- **Direct access to the resume** — a one-click **Download Resume** button serves the PDF straight from the card, so a first conversation can turn into a follow-up email with an attachment already in hand.
- **A small, self-contained proof of technical craft** — even a "business card" is built and shipped like a product: React + Vite, deployed via Netlify, versioned on GitHub.

## What's on the card

| Section | Content |
|---|---|
| **Identity** | Name (Cyberzal aka Sopfian Ismail), role tag `CYBER SECURITY OPS`, sub-tag `Cloud Support & DevOps` |
| **Bio** | Leveraging experience from RAiD to solve complex security challenges, focusing towards **Penetration Testing** and **Red Team** work |
| **Education** | MBA Cyber Security — Xaltius Academy |
| **Focus** | Penetration Testing |
| **Actions** | Download Resume (`Sopfian_CV.pdf`), Show QR Code (scan to share), links to [LinkedIn](https://www.linkedin.com/in/cyberzal/) and [GitHub](https://github.com/Cyberzal1/) |
| **Status** | Live "STATUS: ONLINE" indicator |

## Tech Stack

- **React** — UI and component structure
- **Vite** — build tooling and dev server
- **Netlify** — hosting and continuous deployment
- **CSS (Tailwind-style utility classes)** — dark/cyan cyberpunk terminal theme, scan-line and glow animations

## Project Structure

```
cyberzal-digitalcard/
├── assets/              # compiled CSS/JS build output
├── index.html           # entry point
├── Sopfian_CV.pdf        # downloadable resume
├── vite.svg
└── README.md
```

## Running Locally

```bash
git clone https://github.com/Cyberzal1/cyberzal-digitalcard.git
cd cyberzal-digitalcard
npm install
npm run dev
```

## Deployment

The `main` branch auto-deploys to Netlify on every push.

---

*Built by [Cyberzal](https://github.com/Cyberzal1) — MBA (Cyber Security) student, cybersecurity practitioner, and builder of practical security tooling.*
