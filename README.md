<div align="center">
<img src="https://i.ibb.co/qMDqqSKG/Gemini-Generated-Image-s550l2s550l2s550-1.png" alt="IndiaXplore Logo" width="100%" style="border-radius: 20px; max-height: 300px; object-fit: cover;">

<br />
<br />

<h1>🇮🇳 IndiaXplore</h1>
<p>
<b>Unifying and securing travel across Incredible India through Generative AI and zero-knowledge digital identity.</b>
</p>

<p>
<img width="48" height="48" src="https://img.icons8.com/color/48/javascript--v1.png" alt="Vanilla JS" />
<img width="48" height="48" src="https://img.icons8.com/color/48/tailwind_css.png" alt="Tailwind CSS" />
<img width="48" height="48" src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/24/external-auth0-the-solution-you-need-for-web-mobile-iot-and-internal-applications-logo-color-tal-revivo.png" alt="Auth0" />
<img width="48" height="48" src="https://img.icons8.com/skeuomorphism/32/gemini-ai.png" alt="gemini-ai"/ alt="Gemini AI" />
</p>

<h3>🚀 <a href="https://i.ibb.co/qMDqqSKG/Gemini-Generated-Image-s550l2s550l2s550-1.png">Experience IndiaXplore Live</a> 🚀</h3>
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

git clone [https://github.com/ManasKumarSamanta/IndiaXplore](https://github.com/Subho4531/IndiaXplore.git)
cd IndiaXplore


Run the app:

Option A (VS Code): Install the Live Server extension, right-click index.html, and select "Open with Live Server".

Option B (Node.js/npx): Run npx serve . in your terminal.

Option C (Python): Run python -m http.server 8000 in your terminal.

Explore the App:

Go to https://indiaxplore.netlify.app/

To view the secure database hashing demo, navigate to /admin-db and use the proxy credentials:

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