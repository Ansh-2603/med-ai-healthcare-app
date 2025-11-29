# Med.AI – Intelligent Healthcare Assistant

A comprehensive, modern, responsive *frontend-only* Next.js + React healthcare platform featuring AI-powered symptom analysis, voice interaction, multi-language support, role-based dashboards, and a fully interactive emergency response system.

🔗 *Live Deployment:*  
https://v0-v0medaihealthcareappmainmain-xk.vercel.app/
---

## 🚀 Features

### 🔹 Core Functionality
- *Multi-Language Support*: English, Hindi, Marathi, Tamil, Gujarati, Bengali (via i18next)
- *Voice Recognition*: Continuous listening with Web Speech API
- *Role-Based Dashboards*: Patient, Doctor & Hospital Staff
- *AI Symptom Checker*: Chat-style interface + body map + voice input
- *Emergency System*: Always-listening wake-word detector + authenticity scoring
- *Doctor Consultation*: View patients, cases, notes, and prescriptions
- *Hospital Staff Tools*: Tasks, inventory, admissions, resource management
- *No Backend Required*: Entire app runs frontend-only (sessionStorage simulation)

---

## 🔐 Authentication System
- Role-based login (Patient/Doctor/Staff)
- Clean, professional UI for login/signup
- *Demo Mode*: Click any role on landing page → instant access  
- Demo credentials (optional):  
  - Email: john.doe@example.com  
  - Password: demo123
"D:\Ansh\Downloads\WhatsApp Image 2025-11-28 at 21.42.13_07c24ff9.jpg"
---

## 🧑‍⚕ Patient Dashboard
### Symptom Checker
- Chat-like AI flow  
- Voice or typed input  
- Body map pain selector  
- Auto clarifying questions  

### AI Result Page
- Animated *triage meter (0–3 severity)*  
- Condition probability cards  
- Confidence indicators  
- “When to seek help” guidelines  
- Doctor carousel with filters  
- Escalation path visualizer  

### Emergency Page
Panic-proof UI featuring:
- Big emergency triggers (Call 108, Notify Hospital, Share Location)
- Auto-escalation countdown  
- Authenticity scoring:
  - HIGH (70%+)
  - MEDIUM (40–70%)
  - LOW (<40%)
- Real-time response timeline  
- Emergency evidence panel  

---

## 🩺 Doctor Dashboard
- Patient list with urgency indicators  
- Appointment overview  
- Case details modal  
- Add/view clinical notes & prescriptions  

---

## 🏥 Hospital Staff Dashboard
- Hospital statistics  
- Task manager with priority levels  
- Inventory tracker with low-stock alerts  
- Patient admissions & bed management  

---

## 🎙 Emergency Listening System

*Wake Words*
- English: “MedAI”, “Med AI”, “Hey MedAI”
- Hindi: “Med AI madad”, “Med AI madad karo”

*Emergency Keywords*
- “help”, “dying”, “can’t breathe”, “chest pain”, “fainting”
- Hindi: “madad”, “bachao”

*Escalation Logic*
- HIGH → instant notification  
- MEDIUM → pre-triage first  
- LOW → manual user confirmation  
- Silent escalation if user is unresponsive  

*Visual Elements*
- Always-on bottom-left listener pill  
- Audio level visualizer  
- Emergency pre-triage modal  

---

## 🧭 Routes & Pages


/                               - Landing (with emergency listener)
/login                          - Login
/signup                         - Signup
/patient/dashboard              - Patient home
/patient/symptom-input          - Symptom checker chat
/patient/ai-result              - AI analysis results
/patient/emergency              - Emergency UI
/appointments                   - Appointments
/records                        - Records viewer
/history                        - Medical history
/symptom-checker               - Dedicated symptom checker
/doctor/dashboard               - Doctor panel
/staff/dashboard                - Hospital staff panel


---

## 🛠 Technology Stack

- *Framework*: Next.js 16 (App Router)
- *Language*: TypeScript
- *Styling*: Tailwind CSS v4
- *Components*: shadcn/ui
- *Icons*: Lucide React
- *i18n*: react-i18next
- *Voice Recognition*: Web Speech API
- *State Persistence*: browser sessionStorage
- *No backend used* (safe for frontend demos)

---

## 🎨 Design System

### Colors
- Medical Blue: #0B5ED7
- Teal: #0CC7BD
- Dark Grey: #1E1E1E
- White: #FFFFFF
- Soft Grey: #F3F6FA

### Custom Animations
- animate-fade-in
- animate-slide-up
- animate-pulse-glow
- animate-shimmer
- Glassmorphism utilities (glass, glass-card)

---

## 📁 Project Structure


med-ai/
├── app/
│   ├── page.tsx
│   ├── layout.tsx
│   ├── globals.css
│   ├── providers.tsx
│   ├── patient/
│   ├── doctor/
│   ├── staff/
│   ├── appointments/
│   ├── records/
│   ├── history/
│   └── api/
├── components/
│   ├── auth/
│   ├── patient/
│   ├── doctor/
│   ├── staff/
│   ├── ui/
│   ├── emergency-listener.tsx
│   ├── emergency-pre-triage-modal.tsx
│   ├── voice-input.tsx
│   ├── body-map.tsx
│   ├── triage-meter.tsx
│   └── doctor-carousel.tsx
├── lib/
│   ├── api.ts
│   ├── auth-context.tsx
│   ├── i18n.ts
│   ├── voice-recognition.ts
│   ├── types.ts
│   └── dummy-data.ts
├── data/
├── locales/
├── public/
└── package.json


---

## 🧪 Testing Scenarios

### Emergency Flow
1. Enable listener  
2. Say “Med AI help”  
3. Pre-triage modal appears  
4. Authenticity score updates  
5. Emergency page actions  

### Symptom Flow
1. Navigate to *Symptom Input*  
2. Speak or type symptoms  
3. Select body map location  
4. AI clarifying questions  
5. View detailed result page  

### Doctor Booking
- Use doctor carousel filters  
- Tap *Book Now*

### Multi-Language
- Switch language  
- Voice recognition switches too  

---

## 🧩 Known Limitations
- Speech recognition accuracy varies by browser  
- Emergency detection is simulated  
- No real backend or data persistence  
- Intended for UI demonstration only (not real medical use)

---

## 🔮 Future Enhancements
- Real backend integration  
- Real ambulance/hospital API integration  
- WebRTC video consultations  
- Push notifications  
- Real-time doctor chat  
- React Native mobile app  
- AI model fine-tuning  
- Health tracking + vitals integration  

---

## ⚠ Safety & Disclaimer

*Med.AI is a frontend demo.*  
Emergency detection, AI analysis, triage, and medical guidance are *non-medical simulations* for educational and UI/UX demonstration use only.

## 📬 Support
- Email: support@medai.com  
- Issues: GitHub repository  

---


---      

