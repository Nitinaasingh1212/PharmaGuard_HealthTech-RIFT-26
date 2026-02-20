# PharmaGuard: Pharmacogenomic Risk Prediction 🛡️💊

PharmaGuard is a state-of-the-art AI-powered platform designed to predict medication risks based on a patient's genetic profile (VCF files). It helps doctors and patients identify potential adverse drug reactions, dosage adjustments, and alternative therapies using advanced genomic analysis and Google's Gemini AI.

## 🚀 Key Features

- **VCF File Analysis:** Processes genetic variation data to identify critical biomarkers.
- **AI-Powered Insights:** Uses Gemini 1.5 Flash to provide clinical explanations and CPIC-aligned recommendations.
- **Drug-Drug & Drug-Lifestyle Interactions:** Factors in phenoconversion (smoking, grapefruit, etc.) for more accurate risk assessment.
- **Premium UI/UX:** A stunning, responsive dashboard built with React, Tailwind CSS, and Lucide icons.
- **Evidence-Based:** Links results to CPIC guidelines and PubMed references.

## 🛠️ Tech Stack

- **Frontend:** React 19, Vite, TypeScript
- **Styling:** Tailwind CSS (Premium Dark/Light Mode)
- **AI Engine:** Google Gemini AI (@google/genai)
- **Icons:** Lucide React
- **Deployment:** Vercel

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Nitinaasingh1212/PharmaGuard_HealthTech-RIFT-26.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env.local` file and add your Gemini API Key:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

## 🌐 Deployment

This project is optimized for deployment on **Vercel**. Ensure you add the `GEMINI_API_KEY` in the Vercel Environment Variables dashboard.

## 📄 License

This project is for informational purposes only. Consult a medical professional for clinical decisions.

---
Built for **RIFT 2026 Hackathon** 🚀
