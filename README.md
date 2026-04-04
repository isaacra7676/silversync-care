# silversync-care

> **Live demo →** `https://<wannabedataanalyst96>.github.io/silversync-care`
# 💊 SilverSync Care

A mobile-responsive medication tracker designed for elderly users — built with accessibility at its core. Large fonts, high-contrast UI, big touch targets, and a caregiver nudge feature.

> Built as a PM portfolio project to demonstrate product thinking around the elderly healthcare space.

---

## 🌐 Live Demo

**[Open SilverSync Care →](https://your-username.github.io/silversync-care/)**

> Replace the link above with your actual GitHub Pages URL after deployment.

---

## 📸 Features

| Feature | Description |
|---|---|
| 📅 Weekly dashboard | Mon–Sun view showing all medications per day |
| ✅ Taken / Pending toggle | One-tap status update per day |
| ➕ Add medication | Name, time, frequency, and custom days |
| 🗑️ Delete medication | Remove meds instantly from the manage list |
| 🔁 Frequency badges | Daily, Alternate day, and Weekly once labels |
| 🔔 Nudge button | Send a gentle reminder to a caregiver's device |
| 📱 Mobile responsive | Works on all screen sizes |
| ♿ Accessibility-first | Extra-large fonts, high contrast, big buttons |

---

## 🚀 Getting Started

No build tools, no dependencies, no installation required.

### Option 1 — Open locally

```bash
git clone https://github.com/your-username/silversync-care.git
cd silversync-care
open index.html
```

### Option 2 — Deploy to GitHub Pages (free hosting)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your app will be live at `https://your-username.github.io/silversync-care/`

---

## 🗂️ Project Structure

```
silversync-care/
├── index.html       # Entire app — HTML, CSS, and JS in one file
└── README.md        # This file
```

No frameworks. No bundlers. Pure HTML, CSS, and vanilla JavaScript.

---

## 🎨 Design Decisions

**Why single-file?**
Zero setup friction. An elderly user's caregiver can open the file directly in any browser without installing anything.

**Why high contrast black on white?**
WCAG AA compliance and legibility for users with reduced vision — a common condition in the 65+ age group.

**Why big buttons?**
Motor control declines with age. Touch targets are sized for users with shaky hands (minimum 44px height on all interactive elements).

**Why a Nudge feature?**
Medication non-adherence in elderly patients is often solved not by reminders to the patient, but by caregiver involvement. The nudge creates a accountability loop without being intrusive.

---

## 💡 PM Context

This project was built as part of a product design exercise answering:

> *"Design a product to help elderly people manage their medications."*

**User:** Independent elderly adults, 65+, living alone or with occasional caregiver support.

**Core pain points identified:**
- Forgetting to take medications or taking them twice
- Complex schedules (daily vs. alternate day vs. weekly)
- Caregiver anxiety about adherence with no visibility

**North star metric:** Daily dose adherence rate (% of scheduled doses marked Taken per week)

**Trade-offs made:**
- Chose a web app over a native app — lower barrier to entry, no app store required
- Chose manual tracking over smart pill box integration — faster to ship, works on any device
- Kept the UI to a single screen — reduced cognitive load for elderly users

---

## 🔭 Roadmap (future ideas)

- [ ] SMS/WhatsApp caregiver alerts when a dose is missed
- [ ] Persistent storage using localStorage or a backend
- [ ] Medication refill reminders
- [ ] Export weekly adherence report as PDF
- [ ] Multi-patient support for professional caregivers

---

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Vanilla JavaScript (no frameworks)
- [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) via Google Fonts

---

## 📄 License

MIT — free to use, modify, and distribute.

---

*Made with care for the people who built everything before us.
