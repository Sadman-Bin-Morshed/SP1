# Sadman Bin Morshed — Portfolio

Personal portfolio of **Sadman Bin Morshed**, a CSE student at International Islamic University Chittagong (IIUC), built for the **CSE-2340 Software Development** course.

**Live site:** [sadmanbinmorshed.tech](https://www.sadmanbinmorshed.tech)

---

## About

A single-page portfolio that introduces Sadman, his skills, the projects he has built, and how to get in touch. It is written in plain **HTML, CSS and JavaScript**, with no frameworks or build step, and is designed to feel calm, readable and interactive, with a light cybersecurity theme throughout.

## Sections

| Section | What it shows |
|---|---|
| **Hero** | Introduction, credentials (CSE-2340 · IIUC · GH-900 GitHub Foundations) and a link to the projects |
| **Skills** | Cybersecurity, Networking, Internet of Things, Git & GitHub |
| **Projects** | CGPA-Stats (C), CircuitPal (ESP32), CSE-2340 MP2 (course portfolio) |
| **Contact** | Contact form, direct email and social links |

## Highlights

- **Cybersecurity network background:** the hero shows a live network map with nodes, data packets and "firewall" blocks, and the nodes are pulled toward the cursor like a magnet.
- **Shield grid:** a honeycomb background in the Skills section that lights up and ripples around the cursor.
- **Stage curtain:** green velvet curtains open to reveal the projects, with the phrase "Small builds, real lessons."
- **Project deck:** compact project cards that expand into full detail on hover, with a flowing card-deck switch (arrows, drag, trackpad swipe or keyboard).
- **Section entrances:** text and cards animate in when each section comes into view, and replay when you scroll back.
- **Liquid glass and frosted cards** for the intro text and contact form.
- **Responsive:** works on desktop, tablet and phone.
- **Accessible:** respects the *reduce motion* setting (animations are switched off), keeps headings readable by screen readers, and supports keyboard navigation of the project deck.

## Tech stack

- HTML5
- CSS3 (custom properties, keyframe animations, backdrop filters)
- Vanilla JavaScript (Canvas 2D, IntersectionObserver, Pointer Events)
- Hosting: Azure Static Web Apps (deployed by GitHub Actions)

## Project structure

```
SP1/
├── index.html        # Page markup and all JavaScript
├── style.css         # Styles and animations
├── images/           # Profile photo, background image and social icons
└── .github/workflows # Azure Static Web Apps deployment
```

## Run locally

No installation is needed.

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open `index.html` in a browser. Or, in VS Code, right-click it and choose **Open with Live Server**.

## Deployment

Every push to the main branch is deployed automatically to Azure Static Web Apps by the workflow in `.github/workflows/`.

## Contact

- Email: [sadmanmorshed401@gmail.com](mailto:sadmanmorshed401@gmail.com)
- GitHub: [@phonkboisad](https://github.com/phonkboisad)
- Facebook: [Sadman Morshed](https://www.facebook.com/sadman.morshed.377408)

---

© 2026 Sadman Bin Morshed. All rights reserved.
