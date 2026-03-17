# 🚀 DeliverShield AI  
### AI-Powered Parametric Insurance for Gig Delivery Workers

---

## 📌 Problem Statement
India’s gig delivery partners (Swiggy, Zomato, etc.) lose **20–30% of their income** due to external disruptions like heavy rain, extreme heat, pollution, and curfews.  

Currently, there is **no protection system** for their income loss.

👉 This project builds an **AI-powered parametric insurance platform** that provides **automatic payouts for lost income** using a **weekly subscription model**.

---

## 🎯 Our Solution

**DeliverShield AI** is a smart insurance platform that:
- Uses AI to **predict risks**
- Automatically **triggers claims**
- Provides **instant payouts**
- Works on a **weekly pricing model**

---

## 👤 Target Persona (Swiggy/Zomato Delivery Partner)

- Works: 8–12 hours/day  
- Earnings depend on: Orders, Peak hours, Location  
- Avg income: ₹600–₹1200/day  

### 📉 Key Problems
- 🌧️ Heavy Rain → No deliveries  
- 🌡️ Extreme Heat → Reduced work hours  
- 🌫️ Pollution → Health risk  
- 🚫 Curfews/Strikes → Zero income  

---

## 🔄 Application Workflow

1. **User Onboarding**
   - Register using mobile/email  
   - Enter city, platform, weekly income  

2. **AI Risk Profiling**
   - Analyze weather + location + history  

3. **Policy Creation**
   - Suggest weekly premium  
   - Show coverage details  

4. **Real-Time Monitoring**
   - Weather API  
   - AQI API  
   - Traffic/API disruptions  

5. **Auto Claim Trigger**
   - If threshold met → claim generated  

6. **Instant Payout**
   - UPI / Wallet transfer  

---

## 💰 Weekly Premium Model

**Formula:**
## Weekly Premium = Base Price + Risk Factor Adjustment


### Example:
| Risk Level | Premium | Coverage |
|-----------|--------|----------|
| Low       | ₹20    | ₹1000    |
| Medium    | ₹40    | ₹1500    |
| High      | ₹60    | ₹2000    |

✅ Matches gig workers’ weekly earning cycle  
✅ Dynamically updated using AI  

---

## ⚡ Parametric Triggers

### 🌧️ Weather-Based
- Rainfall > 50mm → payout  
- Temperature > 42°C → compensation  

### 🌫️ Pollution-Based
- AQI > 300 → partial payout  

### 🚫 Social Disruptions
- Curfew / strike → full payout  

### 🚦 Platform Issues
- Delivery app downtime (mock API)  

👉 Fully automated → No manual claims  

---

## 🤖 AI/ML Integration

### 1. Risk Prediction
- Inputs: Weather, location, history  
- Output: Risk score  

### 2. Dynamic Pricing
- Adjusts weekly premium  

### 3. Fraud Detection
- GPS spoof detection  
- Duplicate claims  
- Activity validation  

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)  
- Tailwind CSS  

### Backend
- Node.js + Express  

### Database
- MongoDB / MySQL  

### APIs
- OpenWeather API  
- AQI API  
- Mock Delivery APIs  

### AI/ML
- Python (Scikit-learn)  

### Payments
- Razorpay (Test Mode)  
- UPI Simulation  

---

## 📊 System Architecture
User App → Backend → AI Engine
↓
External APIs (Weather, AQI)
↓
Trigger Engine → Payment Gateway


---

## 📈 Key Features

✅ AI-based premium calculation  
✅ Real-time disruption tracking  
✅ Automated claims (zero paperwork)  
✅ Instant payouts  
✅ Fraud detection system  
✅ Weekly subscription model  

---

## 🧪 MVP Plan (Phase 1)

- Basic onboarding UI  
- Static premium model  
- 2–3 mock triggers  
- Simple dashboard  

---

## 🔮 Future Scope

- Real Swiggy/Zomato API integration  
- Advanced ML models  
- Personalized plans  
- Multi-city scaling  

---

## 🎥 Demo Plan

- User onboarding  
- Policy creation  
- Simulated rain trigger  
- Auto payout  

---

## ✅ Conclusion

DeliverShield AI provides:
- 📌 Income stability  
- ⚡ Instant automated payouts  
- 🤖 AI-driven insurance  

👉 A scalable solution designed for real-world gig workers.

---

## 📎 Repository Info

**Project Name:** deliver-shield-ai  
**Type:** Hackathon Project (Guidewire DEVTrails 2026)  

---
