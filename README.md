# SIA — Student Insight Assistant & Premium Executive Intelligence Dashboard

## Overview
**SIA (Student Insight Assistant)** is a comprehensive two-part AI platform designed to aggregate, analyze, and visualize student interaction data. 

2. **The Intelligence Dashboard (`dashboard.html`)**: An executive-level analytics view that processes the ingested data, presenting high-level insights such as global mood, session traffic, neural completion rates, and user retention.

> **Note**: This repository contains the Frontend application. The Supabase backend and Edge Functions are currently mocked/in-progress for portfolio demonstration purposes.

---

## 📸 UI/UX Showcase

> 📎 **Please refer to the attached SIA Pitch Deck PDF for complete visual previews of the application, including the Chat UI, Executive Dashboard, and other project highlights.**

---

## Technical Stack
- **Frontend Core**: HTML5, CSS3, Vanilla JavaScript
- **Design & Styling**: Custom responsive CSS utilizing CSS Variables, Glassmorphism, and modern flexbox/grid layouts.
- **Typography & Icons**: Plus Jakarta Sans, Inter, FontAwesome
- **Data Visualization**: Chart.js
- **Backend/Integrations (Designed For)**: Supabase (PostgreSQL, Auth, Edge Functions), Google Gemini API (2.0 Flash)

## Key Features
* 🤖 **Real-time AI Processing:** Utilizes the Gemini API for intelligent, natural-language conversations.
* 📊 **Live Data Visualization:** Turns raw conversation data into actionable insights using customizable chart flows.
* 🛡️ **Secure Logging Flow:** Designed to capture conversation logs and classify user feedback or queries seamlessly into a Supabase pipeline.
* 📱 **Modern Aesthetics:** "Dark mode by default", premium spacing, and lightning-fast minimal UI designed to maximize engagement.

---

## Getting Started (Local Development)

If you would like to run this application locally, you will need to provide your own API Keys for both Gemini and Supabase. **Never commit API keys to a public repository.**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SIA.git
   ```
2. Open `index.html` in your favorite code editor.
3. Replace the placeholder for `GEMINI_KEY` on line 65 with your actual key from Google AI Studio.
4. Replace the placeholder for `SUPER_API` with your Supabase Edge Function URL.
5. Open `dashboard.html` and replace the Supabase configuration variables (URL and Anon Role Key) on Line 213.
6. Serve the files locally using an extension like VSCode Live Server (or `python -m http.server`).

*Warning: Running this application merely by opening the HTML files via `file://` might cause CORS errors with the APIs depending on your browser. A local HTTP server is recommended.*

## License & Credits
Developed as an academic portfolio project. UI/UX designed for premium executive insight tracking. 
