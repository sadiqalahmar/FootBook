# ⚽ FootBook — Football Game Booking System

> **SWE402 – Internet Programming** | University Course Project

![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Pure-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Minimal%20Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Complete-4CAF50?style=flat-square)

---

## 👤 Student Information

| Field            | Details                     |
|------------------|-----------------------------|
| **Student Name** | Sadeq Alahmer               |
| **Student ID**   | 210513525                   |
| **Instructure**  | F. Kuzey Edes Huyal         |
| **Course**       | SWE402 – Internet Programming |
| **Project**      | Football Game Booking System |
| **Repository**   | [GitHub Repository](https://github.com/sadiqalahmar/FootBook)  |

---

## 📌 Project Overview

**FootBook** is a fully responsive, browser-ready football pitch booking website built using plain **HTML5** and **CSS3** — no frameworks, no external libraries. The system allows students, players, and team organizers to browse available time slots at **Altinbas Stadium** and submit a booking request through a clean, modern web interface.

This project was developed as part of the SWE402 Internet Programming course to demonstrate core skills in:

- Semantic HTML5 document structure
- Pure CSS layout techniques (Grid, Flexbox)
- Responsive design (mobile-first breakpoints)
- Accessible UI with ARIA attributes
- CSS custom properties (design tokens)
- Minimal, purposeful JavaScript

---

## 🗂️ Project Structure

```
FootBook/
│
├── index.html          # Home page — hero, features, how-it-works, CTA
├── booking.html        # Booking page — time slots, form, confirmation
├── styles.css          # Global stylesheet (shared by both pages)
└── README.md           # Project documentation (this file)
```

### File Breakdown

| File | Purpose | Lines |
|------|---------|-------|
| `index.html` | Landing page with hero section, features grid, how-it-works steps, and call-to-action banner | ~353 |
| `booking.html` | Booking page with 6 time slot cards, full booking form, info sidebar, and confirmation section | ~827 |
| `styles.css` | Complete shared stylesheet — CSS variables, layout, components, animations, and responsive breakpoints | ~1,412 |

---

## 🌐 Pages & Features

### 🏠 Home Page (`index.html`)

- **Fixed navigation bar** with logo, nav links, and mobile hamburger menu
- **Hero section** with animated football graphic, platform stats, and dual CTA buttons
- **Features grid** — 3 cards highlighting Real-Time Slots, Instant Booking, and Team Management
- **How It Works** — 3-step visual guide with numbered step indicators and connector line
- **CTA Banner** — call-to-action strip linking to the booking page
- **Footer** with navigation links, project info, and credits

### 📅 Booking Page (`booking.html`)

- **Page hero header** with breadcrumb navigation
- **6 Time Slot Cards** (static data) showing:
  - Time and session name
  - Duration, format (5v5 / 7v7 / 11v11), field name, price
  - Availability status badge (Available / Limited / Full)
  - Spot fill meter with remaining count
- **Booking Form** with fields:
  - Full Name *(required)*
  - Email Address *(required)*
  - Preferred Date *(required, with min/max date via JS)*
  - Time Slot *(dropdown, required)*
  - Number of Players *(required, 2–22)*
  - Field Type preference *(optional)*
  - Special Requests / Notes *(optional)*
- **Info Sidebar** — Field rules, cancellation policy, contact details
- **Confirmation Section** — displays a sample booking reference after form submission

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--color-bg` | `#0a1a0f` | Page background |
| `--color-card` | `#1a3224` | Card surfaces |
| `--color-accent` | `#f0c040` | Gold highlights, buttons |
| `--color-text` | `#d4e8d8` | Body text |
| `--color-text-muted` | `#7aab85` | Labels, secondary text |
| `--color-success` | `#4caf50` | Available slot indicators |
| `--font-display` | `Bebas Neue` | Headings and titles |
| `--font-body` | `Lato` | Body and form text |

**Aesthetic direction:** Stadium Dark Luxury — deep turf green + electric gold accents, inspired by professional football venues.

---

## 📐 Responsive Breakpoints

| Breakpoint | Layout Changes |
|------------|---------------|
| **Desktop** `> 900px` | 2-column hero, 3-column features grid, 3-column slot grid, form + sidebar layout |
| **Tablet** `≤ 900px` | Single-column hero, stacked features, 2-column slot grid, stacked booking layout |
| **Mobile** `≤ 600px` | Full hamburger nav, single-column slots, single-column form rows, compact spacing |

---

## ♿ Accessibility

- Semantic HTML5 elements throughout (`<nav>`, `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`)
- ARIA roles, labels, and `aria-current` on active nav links
- `aria-required="true"` on all required form fields
- `aria-label` on icon-only buttons and nav toggles
- `aria-live="polite"` on the confirmation section
- `role="list"` and `role="listitem"` on semantic lists
- Keyboard-navigable form and navigation
- Sufficient color contrast ratios throughout

---

## 📞 Contact & Venue

| Field | Details |
|-------|---------|
| **Stadium** | Altinbas Stadium, Gate 3 |
| **Email** | sadiqalahmar20303@gmail.com |
| **Phone** | +90 536 310 13 22 |
| **Hours** | Open Daily: 6:00 AM – 10:00 PM |

---

## 🚀 How to Run

No server, no build tools, no dependencies required.

1. **Download** or clone the repository:
   ```bash
   git clone https://github.com/sadiqalahmar/FootBook.git
   ```

2. **Open the project folder:**
   ```
   FootBook/
   ├── index.html
   ├── booking.html
   ├── styles.css
   └── README.md
   ```

3. **Launch** `index.html` in any modern browser:
   - Double-click `index.html`, or
   - Right-click → *Open with* → your browser

4. **Navigate** using the navbar:
   - Click **"Book a Slot"** or **"Book Now"** to go to the booking page
   - Fill the form and submit to see the confirmation section

> ✅ Works offline. No internet connection required after fonts load from Google Fonts.

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure and semantic markup |
| CSS3 | All styling — Grid, Flexbox, custom properties, animations |
| JavaScript (Vanilla) | Mobile nav toggle + date picker min/max only |
| Google Fonts | `Bebas Neue` (display) + `Lato` (body) |

> **No frameworks. No libraries. No Bootstrap. No Tailwind. No jQuery.**

---

## 📋 Development Phases

This project was built using a structured sub-agent workflow:

| Phase | Agent | Deliverable |
|-------|-------|-------------|
| 1 | **UX Researcher** | User types, core features, booking flow |
| 2 | **UI Designer** | Color palette, typography, layout grid, design direction |
| 3 | **Frontend Developer** | Full HTML + CSS implementation across all files |
| 4 | **Code Reviewer** | Semantic structure, accessibility, best practices audit |

---

## 📄 License

This project was created for academic purposes as part of **SWE402 – Internet Programming**.  
© 2025 Sadeq Alahmer — Student ID: 210513525
