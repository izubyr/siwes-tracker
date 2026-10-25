# SIWES Tracker 📝📍

A modern, institutional web application designed to digitize the Student Industrial Work Experience Scheme (SIWES) attendance and logbook management workflow for university students.

Traditional paper logbooks are prone to damage, loss, and delayed verification. **SIWES Tracker** addresses these challenges by introducing GPS-verified check-ins, webcam snapshot verification, and a centralized digital logbook system.

---

## ✨ Features

- **Modern SaaS Dashboard Layout:** Built with a collapsible sidebar navigation (compact icon view with hover/flyout expansion), responsive split-grid content cards, and quick summary metrics.
- **GPS-Based Check-in & Check-out:** Integrates browser Geolocation to verify that student check-ins occur at the designated industrial attachment location.
- **Selfie Verification:** Utilizes the HTML5 Canvas and `navigator.mediaDevices` camera API to capture real-time photo confirmation on arrival.
- **Digital Daily Logbook:** Dedicated interfaces for submitting daily objectives and end-of-day progress notes.
- **Historical Attendance Log:** Structured data table tracking timestamps, location verification statuses, and daily accomplishment records.
- **Client-Side Validation:** Password matching and confirmation checks implemented with vanilla JavaScript during student registration.
- **Institutional Design Identity:** Styled using an institutional palette with responsive card containers and custom CSS components.

---

## 🛠️ Tech Stack

- **Markup:** HTML5 (Semantic elements, canvas, video stream APIs)
- **Styling:** CSS3 (Flexbox, CSS Grid, custom utility classes, transitions)
- **Scripting:** Vanilla JavaScript (ES6+, MediaDevices Web API, Geolocation API)

---

## 📁 Project Structure

```text
├── index.html         # Portal landing and entry page
├── login.html         # Student authentication interface
├── register.html      # Registration form with password validation
├── dashboard.html     # Overview dashboard, profile widget, and stats
├── check-in.html      # GPS capture, webcam snapshot, and daily objective
├── check-out.html     # End-of-day summary log and check-out verification
├── attendance.html    # Historical logbook entries and attendance records
└── styles.css         # Global stylesheet, design system, and responsive layout
