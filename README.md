# Janaza.ma - Funeral Announcements Platform

A community-driven, charitable platform managed by the **Mishkat Al-Khair Association**, designed to facilitate sharing funeral announcements, timings, and encouraging prayers and continuous charity (Sadaqah Jariyah) for the deceased.

## Features

* **Instant Publishing:** Visitors can post funeral announcements directly without admin bottlenecks.
* **Smart Duplicate Prevention:** Built-in logic to prevent duplicate posts based on the mosque, timing, and gender.
* **Auto-Expiration:** Announcements are automatically hidden from the feed 6 hours after the prayer time.
* **Dark Mode:** Elegant, eye-friendly dark theme tailored with the association's visual identity.
* **Maps Integration:** Easily link or generate Google Maps directions to the exact mosque or cemetery.
* **Sadaqah Jariyah:** A dedicated section supporting the association's charitable activities (Well drilling, medical aid, etc.) with easy RIB copying and WhatsApp donation receipt integration.
* **Quran Player:** Integrated audio player for continuous Quranic recitation.

## Tech Stack

* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript.
* **Backend/Database:** Firebase (Firestore) - Real-time Database.
* **Typography:** Google Fonts (Cairo & Tajawal).

## Local Setup & Deployment

Since this is a lightweight Single Page Application (SPA), the setup is straightforward:

### Local Development
1. Clone this repository to your local machine.
2. Open the `index.html` file in any modern web browser.
3. *Note:* To use your own database, update the `firebaseConfig` object inside the `index.html` `<script>` tag.

### Deployment (Production)
This project is fully ready to be deployed on platforms like **Vercel** or **Netlify**:
1. Connect your GitHub repository to Vercel/Netlify.
2. Deploy the main branch (no build commands are required).

---
*Developed as a Sadaqah Jariyah (Continuous Charity) for the sake of Allah.*
