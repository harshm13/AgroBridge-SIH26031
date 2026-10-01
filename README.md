# 🌾 AgroBridge

### AI-Powered Crop Quality Assessment & Smart Logistics

> **Objective Grading. Transparent Pricing. Better Realization.**

[![Smart India Hackathon](https://img.shields.io/badge/Smart%20India%20Hackathon-2026-orange?style=for-the-badge)](#-smart-india-hackathon-2026)
[![React](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black)](#-technology-stack)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#-technology-stack)
[![Python](https://img.shields.io/badge/AI%20%2F%20ML-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#-technology-stack)

AgroBridge is an AI-powered agricultural intelligence platform that brings **computer-vision crop grading, market intelligence, buyer discovery, fair-price estimation, and shared logistics** into a single farmer-focused workflow.

---

## 📚 Table of Contents

- [Overview](#-overview)
- [The Problem](#-the-problem)
- [Our Solution](#-our-solution)
- [Key Features](#-key-features)
- [Platform Modules](#️-platform-modules)
- [Target Users](#-target-users)
- [System Architecture](#️-system-architecture)
- [Technology Stack](#️-technology-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Development Roadmap](#️-development-roadmap)
- [Future Scope](#-future-scope)
- [Smart India Hackathon 2026](#-smart-india-hackathon-2026)
- [What Makes AgroBridge Different?](#-what-makes-agrobridge-different)
- [Expected Impact](#-expected-impact)
- [Vision](#-vision)
- [Team](#-team)
- [License](#-license)

---

## 📌 Overview

**AgroBridge** is designed to eliminate quality disputes by bringing **Computer Vision grading, market prices, buyer demand, and shared logistics** into one simple platform.

The platform is built around one central question:

> **How can a farmer objectively prove the grade of their crop at the farm, secure a fair price based on that grade, and efficiently pool transport to deliver it?**

AgroBridge is built for **Smart India Hackathon 2026**.

- **Problem Statement:** SIH26031
- **Theme:** Smart Automation

---

## 🚜 The Problem

Farmers often face significant financial losses at procurement centers due to a lack of standardization:

- Subjective quality assessment varies across procurement centers.
- Arbitrary downgrading by buyers can lead to severe price cuts and disputes.
- Farmers may transport crops without a guaranteed quality grade or locked-in price.
- Farmers lack simple digital tools to objectively demonstrate crop quality at the farm level.
- High transportation costs can make rejected or downgraded produce especially costly.

> **A farmer spends money transporting their crop to a market, only to have the buyer subjectively downgrade the quality and slash the price.**

---

## 💡 Our Solution

AgroBridge is designed as an **objective quality and decision engine**.

Instead of waiting until the procurement center to discover quality and pricing outcomes, AgroBridge connects the major decisions in a single workflow:

```text
🌾 Crop Photo Captured
        ↓
📷 AI Computer Vision Grading (A/B/C)
        ↓
📊 Market Intelligence for Verified Grade
        ↓
🏪 Buyer Matching
        ↓
💰 Offer Comparison
        ↓
🚚 Shared Logistics Pooling
        ↓
💳 Transaction & Payment
```

The goal is to help farmers evaluate selling opportunities using **quality, price, demand, buyer information, distance, and logistics costs together**.

---

# ⭐ Key Features

## 📷 1. Farm-Level AI Quality Grading

The core feature is designed to reduce procurement disputes.

Farmers can capture a photo of a crop sample, such as onions, using a smartphone. The AI model assesses:

- Size and uniformity
- Color parameters
- Defect and spoilage rate

The system assigns a standardized grade such as **Grade A, B, or C**, creating a digital quality signal that can be used when evaluating potential buyers.

---

## 🧠 2. AgroBridge Opportunity Engine™

The **Opportunity Engine** is the core decision-support layer of AgroBridge.

It combines multiple signals to identify promising selling opportunities.

### Signals Considered

- Current market prices
- Historical price trends
- Buyer demand
- Verified crop quality
- Buyer requirements
- Distance
- Transportation cost
- Expected realization

These signals can be converted into an **Opportunity Score**, allowing farmers to compare complex market choices more easily.

---

## 💰 3. AI Fair Price

AgroBridge aims to estimate a reasonable price range using available market information, historical trends, demand, and quality signals.

```text
Current Market Price
        +
Historical Trends
        +
Buyer Demand
        +
Verified Crop Quality
        │
        ▼
┌─────────────────────┐
│  AI Fair Price Range │
└─────────────────────┘
```

The objective is to help farmers understand how a buyer's offer compares with expected market value.

---

## 📈 4. Sell or Wait Recommendation

AgroBridge converts market signals into a simple decision-oriented recommendation.

| Recommendation | Meaning |
|---|---|
| 🟢 **SELL** | Current conditions may be favorable |
| 🟡 **WAIT** | Monitoring the market may provide a better opportunity |

The goal is to turn market intelligence into an understandable action rather than overwhelming farmers with complex charts.

---

## 🏪 5. Smart Buyer Matching

Farmers can discover relevant buyers based on:

- Crop
- Quantity
- AI-verified quality
- Location
- Buyer requirements
- Expected price

This helps connect available produce with buyers whose requirements better match the farmer's crop.

The platform is designed to facilitate **direct B2B and D2C connections**, reducing dependence on traditional intermediary chains.

---

## 🤝 6. Buyer Trust & Verification

AgroBridge is designed to provide buyer context beyond the quoted price.

Potential trust indicators include:

- Verification status
- Transaction history
- Reliability indicators
- Offer history
- Buyer requirements

This gives farmers more information when comparing potential buyers.

---

## 🧮 7. Best Net Realization

> **The highest offer is not always the most profitable option.**

For example:

| Buyer | Offer | Transport | Net Realization |
|---|---:|---:|---:|
| Buyer A | ₹2,500 | ₹400 | **₹2,100** |
| Buyer B | ₹2,350 | ₹100 | **₹2,250** |

Although Buyer A offers a higher price, Buyer B produces the higher realization after transportation costs.

### Core Metric

```text
Best Net Realization
= Expected Sale Value − Associated Costs
```

AgroBridge therefore focuses on what the farmer can **actually realize**, rather than simply displaying the highest quoted price.

---

## 🚚 8. Smart Logistics

Transportation can be a major barrier to direct selling for smallholders.

AgroBridge aims to connect selling opportunities with:

- Distance
- Estimated transportation cost
- Suitable transport options
- Shared transportation opportunities
- Delivery planning

### Shared Transportation

AgroBridge can support pooling partial truckloads among nearby farmers so multiple farmers can collectively fulfill larger direct-buyer requirements.

This allows farmers to evaluate the **complete economics of a sale**, including logistics.

---

## 🗺️ 9. Market Intelligence

AgroBridge brings important agricultural market information into one place.

Potential insights include:

- Market prices
- Price trends
- Buyer demand
- Arrival volumes
- Nearby markets
- Crop-specific opportunities

---

## 💬 10. AI Selling Copilot

The AI assistant is designed as a **contextual agricultural selling companion**, rather than a generic chatbot.

### Example Questions

```text
"What is the best market for my Grade A onions?"

"Should I sell today?"

"Which buyer gives me the best realization?"

"Why is this offer better?"

"What should I do next?"
```

The Copilot can guide farmers toward relevant AgroBridge features and help them understand available selling options.

---

# 🖥️ Platform Modules

| Module | Purpose |
|---|---|
| 🏠 Dashboard | Overview of crops, markets, and opportunities |
| 🌾 My Crops | Manage crops and available produce |
| 📊 Market Intelligence | Explore prices and market trends |
| 🧠 Opportunity Engine | Identify promising selling opportunities |
| 🏪 Marketplace | Discover buyers and offers |
| 👤 Buyer Profiles | View buyer information and trust indicators |
| 🔬 Quality Check | Capture and evaluate crop quality via AI |
| 🚚 Logistics | Explore transportation opportunities |
| 💳 Transactions | Track sales and payments |
| 💬 AI Copilot | Get contextual assistance |
| 🆘 Support | Access help and grievance assistance |
| 👨‍🌾 Profile | Manage farmer information |

---

# 🎯 Target Users

### 👨‍🌾 Farmers

Discover objective grades, markets, buyers, and selling opportunities.

### 🏢 Farmer Producer Organizations — FPOs

Aggregate produce and improve collective market access.

### 🏪 Buyers

Discover relevant, quality-verified agricultural produce from farmers and FPOs.

### 🚚 Logistics Providers

Connect transportation with agricultural selling opportunities.

### 🏛️ Agricultural Ecosystem

Improve transparency, connectivity, and market efficiency.

---

# 🏗️ System Architecture

```text
                         ┌─────────────────┐
                         │     FARMER      │
                         └────────┬────────┘
                                  │
                                  ▼
                    ┌─────────────────────────┐
                    │    AgroBridge Frontend  │
                    │       React + Vite      │
                    └────────────┬────────────┘
                                 │
                              REST API
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │      AgroBridge API     │
                    │         FastAPI         │
                    ├─────────────────────────┤
                    │ Authentication           │
                    │ AI Quality Grading (CNN)│
                    │ AI Predictions           │
                    │ Buyer Matching           │
                    │ Transactions             │
                    └────────────┬────────────┘
                                 │
                 ┌───────────────┼───────────────┐
                 ▼               ▼               ▼
          ┌─────────────┐ ┌─────────────┐ ┌─────────────┐
          │  Database   │ │   AI / ML   │ │ Market Data │
          └─────────────┘ └─────────────┘ └─────────────┘
```

---

# 🛠️ Technology Stack

## Frontend

- **React**
- **Vite**
- **Tailwind CSS**
- **Framer Motion**
- **Lucide React**
- **Recharts**
- **React Router**
- **Axios**

## Backend

- **Python**
- **FastAPI**
- **REST APIs**

## AI / ML

- **Python**
- **Computer Vision (CNN)** for quality grading
- **XGBoost / Random Forest** for machine-learning workflows
- Market prediction and opportunity scoring
- AI-assisted recommendations using **Llama-3**

## Database

- **SQLite** for development
- Designed with future scalability in mind

---

# 📁 Project Structure

```text
AgroBridge/
│
├── backend/
│   ├── api/
│   │   ├── chatbot.py
│   │   ├── predictions.py
│   │   ├── grading.py
│   │   └── pooling.py
│   │
│   ├── db/
│   │   ├── database.py
│   │   └── models.py
│   │
│   ├── ml/
│   │   ├── predict.py
│   │   └── train.py
│   │
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── data/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   ├── index.css
│   │   └── main.jsx
│   │
│   ├── package.json
│   ├── tailwind.config.js
│   └── vite.config.js
│
├── .gitignore
├── README.md
└── package-lock.json
```

---

# 🚀 Getting Started

## Prerequisites

Make sure the following are installed:

- **Node.js 18+**
- **npm**
- **Python 3.10+**
- **Git**

## 1. Clone the Repository

```bash
git clone https://github.com/harshm13/AgroBridge-SIH26031.git
cd AgroBridge-SIH26031
```

## 2. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The frontend normally runs at:

```text
http://localhost:5173
```

## 3. Backend Setup

From the project root:

```bash
cd backend
python -m venv venv
```

### Linux / macOS

```bash
source venv/bin/activate
```

### Windows PowerShell

```powershell
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the API:

```bash
uvicorn main:app --reload
```

The backend normally runs at:

```text
http://localhost:8000
```

---

# 🔐 Environment Variables

Create a local environment file:

```text
backend/.env
```

Keep secrets and API keys out of Git.

> ⚠️ **Never commit `.env` files, passwords, tokens, or API keys to GitHub.**

Use `.env.example` as the template whenever available.

---

# 🗺️ Development Roadmap

```text
Phase 1
Frontend Foundation & Computer Vision Prototype
        │
        ▼
Phase 2
Market Intelligence
        │
        ▼
Phase 3
Opportunity Engine
        │
        ▼
Phase 4
Buyer Matching
        │
        ▼
Phase 5
Smart Logistics & Pooling
        │
        ▼
Phase 6
AI Selling Copilot
        │
        ▼
Phase 7
Transactions & Trust
        │
        ▼
Phase 8
FPO & Multilingual Expansion
```

---

# 🌱 Future Scope

## 📱 Farmer-First Mobile Experience

A lightweight experience optimized for smartphones and rural connectivity.

## 🌐 Multilingual Support

Planned support for:

- Marathi
- Hindi
- English
- Additional regional languages

## 📶 Low-Connectivity Experience

Important market and opportunity information should remain accessible even with limited connectivity.

## 👥 FPO Aggregation

Enable FPOs to aggregate produce from multiple farmers and explore collective selling opportunities.

## 🔔 Smart Alerts

Notifications for:

- Price changes
- New buyer opportunities
- Demand changes
- Recommended selling windows
- Offer updates

## 📍 Opportunity Map

A geographical view of:

- Markets
- Buyers
- Demand
- Logistics opportunities

## 📊 Farmer Impact Analytics

Potential impact indicators include:

- Improved realization
- Transportation savings
- Successful transactions
- Buyer reliability
- Market reach

---

# 🏆 Smart India Hackathon 2026

- **Problem Statement:** SIH26031
- **Theme:** Smart Automation
- **Focus:** Quality assessment and grading of onions are often subjective and vary across procurement centers, resulting in disputes.

AgroBridge is built around a simple principle:

> **To eliminate disputes and protect farmer earnings, quality assessment must be objective, digital, and conducted at the farm level before logistics are engaged.**

---

# 💡 What Makes AgroBridge Different?

Traditional market platforms may answer:

> **"What is today's market price?"**

AgroBridge aims to answer:

> **"Considering price, demand, quality, buyer reliability, distance, and logistics, what is my best selling opportunity?"**

### 🔄 The Key Shift

```text
TRADITIONAL CHAIN

Farmer Transport
      ↓
Subjective Grading at Mandi
      ↓
Arbitrary Price Cuts & Disputes
      ↓
Fragmented Farmer Realization


AGROBRIDGE

Farm-Level AI Photo Capture
      ↓
Objective Grade (A/B/C)
      ↓
Shared Transport Pooling
      ↓
Direct Sale
      ↓
Better Net Realization
```

AgroBridge focuses on the decision that matters most:

> **How can a farmer make the best possible selling decision with the information available?**

---

# 🌍 Expected Impact

AgroBridge aims to contribute toward:

- Better price discovery
- Improved farmer realization
- More transparent buyer relationships
- Lower transaction and logistics costs
- Better market connectivity
- Stronger FPO participation
- More informed selling decisions
- Reduced dependence on fragmented market information

---

# 🔭 Vision

We envision an agricultural ecosystem where farmers can make selling decisions using **transparent, understandable, and actionable information**.

> **Every farmer should know the value of their produce, understand their options, and have the information needed to choose the best selling opportunity.**

---

# 👨‍💻 Team

## Team TerminalStack 🇮🇳

Built with ❤️ for **Smart India Hackathon 2026**.

---

# 📜 License

This project is developed for **educational, research, and hackathon purposes**.

---

<div align="center">

### 🌾 AgroBridge

**Right Market • Right Buyer • Right Time • Better Realization**

**Built for Smart India Hackathon 2026 🇮🇳**

</div>
