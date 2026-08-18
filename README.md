# Hi there! 👋 I'm Ahmad Olaitan Adam
### @Robotlee10 | Aspiring Engineer & Developer

> "Everything will be ok in the end. If it isn't ok, it isn't the end." 🌟

---


## 🚀 About Me
I am a passionate aspiring engineer and developer focused on building clean web applications, mastering core programming principles, and exploring new backend technologies.

*   🔭 **Current Focus:** Sharpening my Python and building clean, dependency-light web layouts.
*   🌱 **Learning Journey:** Actively learning Python and sharpening my frontend JavaScript skills.
*   👯 **Collaboration:** Open to collaborating on lightweight open-source projects or front-end web tools.
*   🌍 **Location:** Nigeria (UTC +01:00)

---

# robotlee.xyz — Personal Website

[![Live Site](https://img.shields.io/badge/live-robotlee.xyz-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://robotlee.xyz)
[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Capacitor](https://img.shields.io/badge/capacitor-%23119EFF.svg?style=for-the-badge&logo=capacitor&logoColor=white)](#)

The source code for **robotlee.xyz**, the personal website and portfolio of **Ahmad Olaitan Adam** ([@Robotlee10](https://github.com/Robotlee10)) — an aspiring Mechatronics Engineer and developer. The site is built with plain HTML, CSS, and JavaScript, deployed as a static site on Vercel, installable as a Progressive Web App (PWA), and wrapped as a native Android app using Capacitor.

**🔗 Live site:** [robotlee.xyz](https://robotlee.xyz)

---

## ✨ About

This repository powers a personal portfolio site showcasing projects, skills, and areas of interest across web development, electronics/repair work, automotive, CAD, and general learning notes. It's built to be lightweight, fast, and dependency-free on the front end — no frameworks required — while still supporting an installable app experience on both desktop (PWA) and Android (Capacitor).

## 🚀 Features

- **Static, framework-free front end** — plain HTML/CSS/JS pages for speed and simplicity
- **Multi-page site** — Home, About, Services, Contact, and topic-specific sections
- **Progressive Web App (PWA)** — installable, with a web manifest and service worker for offline support
- **Native Android app** — packaged via [Capacitor](https://capacitorjs.com/)
- **Custom 404 page**
- **CI/CD via GitHub Actions** for automated workflows
- **Deployed on Vercel** with a custom `vercel.json` configuration

## 📁 Project Structure

```
My-website-robotlee.xyz-/
├── .github/workflows/     # GitHub Actions CI/CD workflows
├── android/                # Capacitor-generated native Android project
├── auto/                   # Automotive-related content/section
├── cad/                    # CAD-related content/section
├── contact/                 # Contact page assets
├── learn/                   # Learning notes / resources section
├── portfolio/               # Portfolio / projects section
├── repair/                  # Repair-related content/section
├── tools/                   # Tools section
├── web/                     # Web development section
├── 404.html                 # Custom 404 error page
├── Ex.html                  # Example/experimental page
├── about.html                # About page
├── index.html                # Homepage
├── services.html             # Services page
├── capacitor.config.json     # Capacitor (mobile app) configuration
├── manifest.json              # PWA web app manifest
├── sw.js                       # Service worker (offline/PWA support)
├── package.json                 # Node/Capacitor project metadata & dependencies
├── vercel.json                   # Vercel deployment configuration
└── .gitignore
```

## 🛠️ Tech Stack

| Layer              | Technology                                      |
|--------------------|--------------------------------------------------|
| Front end          | HTML5, CSS3, JavaScript                          |
| PWA                | Web App Manifest, Service Worker                 |
| Mobile app         | [Capacitor](https://capacitorjs.com/) (Android)  |
| Hosting/Deployment | [Vercel](https://vercel.com)                     |
| CI/CD              | GitHub Actions                                   |

## 💻 Getting Started (Local Development)

Since this is a static site, you can run it locally with any simple HTTP server.

```bash
# Clone the repository
git clone https://github.com/Robotlee10/My-website-robotlee.xyz-.git
cd My-website-robotlee.xyz-

# Serve the site locally (choose one)
npx serve .
# or
python3 -m http.server 8000
```

Then open `http://localhost:8000` (or the port shown) in your browser.

## 📱 Building the Android App

The Android app is generated and managed with Capacitor.

```bash
# Install dependencies
npm install

# Sync web assets into the native Android project
npx cap sync android

# Open the project in Android Studio to build/run
npx cap open android
```

## ☁️ Deployment

The site is deployed on **Vercel** and configured via `vercel.json`. Pushing to the main branch triggers a new deployment automatically. GitHub Actions workflows in `.github/workflows/` handle additional automation.

## 🤝 Connect

- ✉️ **Email:** youngengineer1010@gmail.com
- 💼 **LinkedIn:** [Ahmad Olaitan Adam](https://www.linkedin.com/in/robotlee10)
- 🐦 **X/Twitter:** [@robotlee_10](https://x.com/robotlee_10)
- 🌐 **Website:** [robotlee.xyz](https://robotlee.xyz)

## 📄 License

No license has been specified for this repository. All rights reserved by the author unless stated otherwise.

---

*Keep building, keep learning, and trust the process. 🚀*




