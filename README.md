<div align="center">

# 🌷 Leila Ghez Torda — Career & Licensure Roadmaps 🎓✨
### *BS Psychology • Cum Laude (National University MOA)*

[![Made with Love](https://img.shields.io/badge/Made_with-Endless_Love_%26_Tulips_🌷-ec4899?style=for-the-badge)](https://github.com/vernonneilp)
[![Degree](https://img.shields.io/badge/BS_Psychology-Cum_Laude_🎓-9333ea?style=for-the-badge)](https://github.com/vernonneilp)
[![Cloud Sync](https://img.shields.io/badge/Firebase-Realtime_Cloud_Sync-10b981?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-f59e0b?style=for-the-badge)](./LICENSE)

<p align="center">
  <em>"Dedicated to my dearest Val—celebrating your Latin Honors and supporting every step toward your Civil Service Eligibility and Registered Psychometrician (RPm) license!"</em> 💖
</p>

</div>

---

## 🌸 Overview

This repository hosts two interactive, cloud-synchronized web applications crafted specifically for **Leila Ghez Torda** to track her post-graduation credentials, documentary requirements, and board exam review milestones in real time.

| Web Hub | File | Purpose & Scope |
| :--- | :--- | :--- |
| **🏛️ Civil Service Eligibility Tracker** | [`index.html`](./index.html) | Complete documentary checklist & step-by-step guide for claiming **PD 907 (Honor Graduate Eligibility)** from the Civil Service Commission (CSC). |
| **🧠 Registered Psychometrician (RPm) Hub** | [`rpm_roadmap.html`](./rpm_roadmap.html) | Full **BLEPP Board Exam** 4-subject syllabus tracker, **PRC LERIS** documentary checklist, **Tulip Pomodoro Study Timer**, and emotional support pep-talk jar. |

---

## ✨ Key Features

### 1. 🏛️ PD 907 Civil Service Honor Graduate Guide (`index.html`)
* **Interactive Documentary Checklist:** Tracks all 8 mandatory CSC requirements (`CS Form 101-HGE`, strict passport photo specifications, NU MOA Latin Honor certification, TOR, PSA Birth Certificate, and notarized `SPEL Form 1`).
* **5-Phase Filing Roadmap:** Step-by-step progress bar from securing university credentials at NU MOA to claiming the official **Certificate of Eligibility (CoE)**.
* **PD 907 FAQ & Fee Breakdown:** Quick-reference cards covering photo rules, CSC Regional Office filing, and exact evaluation/certification fees (`₱200` + `₱300`).

### 2. 🧠 Registered Psychometrician (BLEPP) Review & PRC Hub (`rpm_roadmap.html`)
* **4 BLEPP Core Subjects Tracker (450 Total Items):**
  * 📊 **Psychological Assessment (40% • 150 Items):** Psychometrics, Intelligence/Cognitive Tests, Personality Assessment, and PAPR Ethics.
  * 🧠 **Abnormal Psychology (20% • 100 Items):** DSM-5-TR diagnostic criteria, neurodevelopmental, mood, anxiety, trauma, and personality disorders.
  * 🌱 **Developmental Psychology (20% • 100 Items):** Lifespan theories (Piaget, Erikson, Vygotsky, Kohlberg, Bowlby) and developmental milestones.
  * 💼 **Industrial / Organizational Psychology (20% • 100 Items):** Job analysis, HR selection, training, performance appraisal, and organizational behavior.
* **PRC BLEPP Checklist:** Specifically tailored for Psychometrician examinees, including the **3 separate Certificates of Good Moral Character** (University, Barangay, and Church/Employer), NBI Clearance, and TOR with *"For Board Examination Purposes"* remarks.
* **🌷 Built-in Tulip Pomodoro Study Timer:** Features customizable `25m Study`, `50m Deep Study`, `5m Break`, and `15m Long Break` modes for cozy, burnout-free review sessions.
* **💌 Vernon's Study Pep-Talk Jar:** Instant mood-based encouragement buttons (*🥱 Feeling Sleepy*, *📚 Info Overload*, *🥺 Nervous*, and *🤗 Need a Hug*).

---

## ☁️ Live Cloud Synchronization Architecture

Both web applications connect to a shared **Firebase Realtime Database** (`asia-southeast1`) while keeping their data cleanly separated in dedicated nodes:

* `val_roadmap.json` $\rightarrow$ Syncs the **Civil Service (PD 907)** checklist and love notes.
* `val_rpm_roadmap.json` $\rightarrow$ Syncs the **Registered Psychometrician (BLEPP)** subject modules, PRC checklist, and study wall notes.
* **Local-First Fallback:** Every action saves instantaneously to `localStorage` first and debounces cloud `PUT` updates so the interface remains responsive offline or on mobile data.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS, FontAwesome 6 Icons
* **Typography:** `Plus Jakarta Sans` & `Dancing Script` (Google Fonts)
* **Animations:** `canvas-confetti` & CSS Keyframe Tulip/Psychology (`Ψ`) Particles
* **Database:** Google Firebase Realtime Database REST API

---

<div align="center">
  <p>Crafted with endless love, prayers, and tulips for <strong>Leila Ghez Torda, RPm</strong> 🌷💖</p>
</div>
