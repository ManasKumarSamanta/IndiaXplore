<div align="center">
<img src="India Map.png" alt="IndiaXplore Logo" width="100%" style="border-radius: 20px; max-height: 300px; object-fit: cover;">

<br />
<br />

<h1>🇮🇳 IndiaXplore</h1>
<p>
<b>Unifying and securing travel across Incredible India through Generative AI and zero-knowledge digital identity.</b>
</p>

<p>
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Vanilla-JS-yellow%3Fstyle%3Dfor-the-badge%26logo%3Djavascript" alt="Vanilla JS" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Tailwind_CSS-38B2AC%3Fstyle%3Dfor-the-badge%26logo%3Dtailwind-css%26logoColor%3Dwhite" alt="Tailwind CSS" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Auth0-EB5424%3Fstyle%3Dfor-the-badge%26logo%3Dauth0%26logoColor%3Dwhite" alt="Auth0" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Google_Gemini-8E75B2%3Fstyle%3Dfor-the-badge%26logo%3Dgoogle%26logoColor%3Dwhite" alt="Gemini AI" />
</p>

<h3>🚀 <a href="https://www.google.com/search?q=https://indiaxplore.netlify.app/">Experience IndiaXplore Live</a> 🚀</h3>
</div>

<hr />

🚨 The Problem

India is a premier global destination for both leisure and medical tourism. However, the ecosystem is deeply fragmented. Tourists must juggle multiple platforms for flights, hotels, and itineraries. Furthermore, physical security and verification are archaic. Travelers constantly hand over highly sensitive government IDs (Aadhar, Passports) to multiple third-party vendors and checkpoints, creating massive data privacy vulnerabilities and physical bottlenecks.

💡 The IndiaXplore Solution

IndiaXplore introduces a unified, AI-driven, and cryptographically secure travel ecosystem. We replace vulnerable physical documents with a unified QR-based Digital Travel Pass and replace fragmented travel planning with an elite AI Concierge that plans your entire trip based on strict budget constraints.

✨ Key Features

🛡️ Zero-Knowledge Digital Travel Pass: Replaces physical IDs with a dynamic, unified QR code. Compliant with the DPDP Act 2023, the platform uses the Web Crypto API (SHA-256) to hash sensitive PII (Aadhar/Passport). Plaintext IDs are never stored.

🗺️ AI Tourism Concierge: Powered by Google Gemini, the platform acts as an elite travel agent. It takes your origin, destination, and budget, and generates a mathematically realistic, highly-detailed itinerary with dynamic cost breakdowns and local cultural tips.

🏥 Medical Tourism Hub: A dedicated portal for medical travelers. It recommends top NABH/JCI accredited hospitals, builds a clinical pathway (Consultation -> Pre-Op -> Recovery), and estimates medical vs. logistical costs.

🔐 Enterprise-Grade Authentication: Integrated with the Auth0 SPA SDK for frictionless, secure, consumer-facing identity management.

🌐 Localized Experience: Built-in i18n support, offering seamless UI translations in English, Hindi, and Bengali to cater to both domestic and international tourists.

💳 End-to-End Booking Flow: Simulated checkout and payment processing flows with verified booking reference generation.

🛠️ Tech Stack & Architecture

Because we prioritized absolute speed, zero compilation overhead, and instant deployment for this prototype, IndiaXplore is built on a blazing-fast Vanilla frontend stack:

Frontend: HTML5, Vanilla JavaScript, Tailwind CSS (via CDN).

Authentication: Auth0 Single Page Application (SPA) SDK.

AI Engine: Google Gemini REST API (gemini-2.5-flash).

Cryptography: Native Web Crypto API (window.crypto.subtle).

Icons: Lucide Icons.

State Management: LocalStorage (Simulating a NoSQL Database for the Admin Console).

🚀 How to Run Locally

Since this project relies on pure frontend technologies, running it locally takes less than 5 seconds.

Clone the repository:

git clone [https://github.com/Subho4531/IndiaXplore.git](https://github.com/Subho4531/IndiaXplore.git)
cd IndiaXplore


Run the app:

Option A (VS Code): Install the Live Server extension, right-click index.html, and select "Open with Live Server".

Option B (Node.js/npx): Run npx serve . in your terminal.

Option C (Python): Run python -m http.server 8000 in your terminal.

Explore the App:

Go to http://localhost:8000/index.html

To view the secure database hashing demo, navigate to /admin-db.html and use the proxy credentials:

Email: admin@gmail.com

Password: admin123

🏆 Hackathon Tracks Targeted

Auth0 Integration: We utilized Auth0's SPA SDK to manage consumer identities without storing passwords on our servers, ensuring a secure, enterprise-level authentication flow.

Generative AI: Heavy utilization of Google Gemini to act as a dynamic data aggregator and intelligent planner, bypassing the need for expensive, high-latency travel GDS APIs.

👥 The Team (MindHack)

Manas Kumar Samanta

Arunava Das

Manjulika Bachar

Built with ❤️ at Diversion 2k26.