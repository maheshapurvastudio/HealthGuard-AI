# 🩺 HealthGuard AI

HealthGuard AI is a modern, responsive, and multilingual medical assistant application designed to provide instant symptom analysis, offline first-aid instructions, emergency navigation, and smart health metrics tracking.

![GitHub License](https://img.shields.io/github/license/yourusername/healthguard-ai?color=blue)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38bdf8?logo=tailwind-css)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-2.5_Flash-orange?logo=google-gemini)

---
You can view the live version(without api key/ai features) here:[HealthGuard-AI](https://maheshapurvastudio.github.io/HealthGuard-AI/).
---

## ✨ Features

*   **🤖 AI Symptom Checker:** Powered by Google's **Gemini 2.5 Flash** model to parse user symptoms in multiple languages (English, Hindi, etc.) and return interactive, structured advice with safety triage.
*   **🌍 Multilingual Support:** Automatically detects the language of user input and responds fluidly in the same language.
*   **🏥 Local Expert System:** Matches common ailments (like headaches, acid reflux, and colds) instantly using a built-in offline knowledge base.
*   **🗺️ Find Nearby Care:** Instantly uses browser geolocation to find nearby hospitals and pharmacies via Google Maps.
*   **🚨 Offline First-Aid & Emergency Contacts:** Interactive first-aid guides (Choking, Severe Bleeding, Burns, Fainting) and critical Indian emergency helpline numbers.
*   **⚖️ BMI Calculator:** Quick and easy weight status calculation with localized categories.
*   **📁 Health Logs:** Locally saves a history of your symptom checks securely within the browser's `localStorage`.

---

## 🛠️ Tech Stack

*   **Frontend:** HTML5, CSS3, Tailwind CSS (via CDN)
*   **Icons:** Lucide Icons
*   **LLM Integration:** `@google/generative-ai` (Gemini-2.5-flash with JSON schema enforcement)
*   **Database/Storage:** Browser `localStorage` (Privacy-focused/Zero server-side retention)

---

## 🚀 Getting Started

### Prerequisites

To run this application locally, you will need a **Google Gemini API Key**. You can obtain one from the [Google AI Studio](https://aistudio.google.com/).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/maheshapurvastudio/HealthGuard-AI.git
   cd HealthGuard-AI
   ```
1. Add your API Key:
   Open the index.html file and locate Line 394:
   ```bash
   const API_KEY = "YOUR_GEMINI_API_KEY_HERE";
   ```
   Replace "YOUR_GEMINI_API_KEY_HERE" with your actual Gemini API key.
2. Run the App:
Since this is a client-side application, you can simply open index.html in any modern web browser to start using it immediately!

🔒 Privacy & Disclaimer
No Diagnosis: HealthGuard AI is an educational tool. It provides AI-driven suggestions and information, not formal medical diagnoses or clinical advice.

Data Security: All medical history, username data, and BMI metrics are stored strictly client-side on your browser (localStorage). No personal medical data is uploaded to external servers except for the anonymized text sent to the Gemini API for processing.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
