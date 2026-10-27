# Sacrifice of Praise (SoP) 2.0 — Official Event Website

[![Firebase Hosting](https://img.shields.io/badge/Hosted%20On-Firebase%20Hosting-FFA611?logo=firebase&logoColor=white)](https://sacrifice-of-praise.web.app)
[![Live Site](https://img.shields.io/badge/Live%20Website-sacrifice--of--praise.web.app-brightgreen)](https://sacrifice-of-praise.web.app)

A live, high-performance, single-file vanilla web application for **Sacrifice of Praise (SoP) 2.0**, modeled after the minimalist benchmark [Harvest of Praise](https://harvestofpraise.netlify.app/).

---

## 🌐 Live Website

- **Primary URL:** [https://sacrifice-of-praise.web.app](https://sacrifice-of-praise.web.app)
- **Firebase Domain:** [https://sacrifice-of-praise.firebaseapp.com](https://sacrifice-of-praise.firebaseapp.com)

---

## 🌟 Event Overview

- **Event Name:** Sacrifice of Praise (SoP) 2.0
- **Theme:** Pure Worship. True Sacrifice
- **Scripture:** *Hebrews 13:15* — *"Through Jesus, therefore, let us continually offer to God a sacrifice of praise—the fruit of lips that openly profess his name."*
- **Nature:** Live a cappella worship concert (void of instruments, rich in harmony, truth, and spiritual depth)
- **Date:** **Saturday, December 12, 2026**
- **Time:** **10:00 AM – 2:00 PM (GMT/WAT)** (Gates open at 9:00 AM)
- **Venue:** **Lawn Tennis Courts, Federal College of Education (Technical) [FCE(T)], Akoka, Lagos, Nigeria**
- **Expected Attendance:** 1,000+
- **Admission:** Free (Registration required)

---

## ✨ Key Features

1. **Top-Right Quick Actions:**
   - **Photo Gallery Button:** Pulsing indicator that smoothly scrolls to the auto-scrolling photo marquee.
   - **Register Now Button:** High-contrast gold call-to-action that scrolls down to the on-page registration.
2. **Hero & Real-Time Countdown:**
   - Real-time days, hours, minutes, and seconds countdown to Saturday, Dec 12, 2026 10:00 AM.
   - 1-click **Add to Calendar** (Google Calendar + Apple / Outlook `.ics` download).
3. **The Movement & Programme (Charter Extract):**
   - Spiritual description, vision, mission, and event parameters extracted from the official proposal.
4. **Animated Picture Gallery:**
   - Dual-track continuous horizontal marquee auto-scrolling in opposite directions with pause-on-hover.
   - View mode toggle between **Animated Scroll** and **Grid View**.
   - Fullscreen **Lightbox** with keyboard navigation (`Esc`, `←`, `→`).
5. **Seamless Google Form Registration:**
   - Submits directly to the official Google Form in the background with zero CORS errors.
   - Triggers celebratory confetti upon submission.
   - Generates a personalized digital event admission pass with guest details.
   - Fallback direct external link to the Google Form.
6. **Footer & Partnership:**
   - Leadership contacts for Kingsley Bassey (Convener) & Ajetunmobi Oluwayinka (Strategist).
   - Unobtrusive sponsor badge: *"proudly supported by house603 digital solutions"* with official logo.

---

## ✏️ How to Edit on the Fly (Zero Build Step)

Because this project is built in pure **Vanilla HTML5 + CSS + JavaScript** (with Tailwind CSS and Lucide icons loaded via CDN), there are **no build tools, no Node.js compilers, and no complex dependencies**:

1. Click on [`index.html`](./index.html) right here on GitHub.
2. Click the **pencil icon** ("Edit this file") in the top right.
3. Edit any text, dates, venue, or links directly in your browser.
4. Click **Commit changes**.
5. To deploy changes to Firebase, run:
   ```bash
   firebase deploy --only hosting
   ```

---

## 📁 Repository Structure

```text
Sacrifice-of-Praise/
├── index.html            # Complete, self-contained landing page
├── firebase.json         # Firebase Hosting configuration (hosts root '.')
├── .firebaserc           # Firebase project alias ('sacrifice-of-praise')
├── house603-logo.png     # Official house603 logo
├── flyer.webp            # Web-optimized event flyer
├── flyer.jpg             # High-res fallback flyer
├── header-image.webp     # Header graphic
├── gallery/              # 8 event gallery photos (WebP + JPG fallback + Full-res)
│   ├── 1.webp, 1.jpg, 1-full.webp
│   └── ... up to 8
└── README.md
```
