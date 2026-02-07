# mayuriWagh2002-VishwasChain-AI-MicroLending
AI-Powered Trust Network for Rural Artisan Micro-Lending

# 🤝 VishwasChain - Trust Capital for Rural India

![VishwasChain Banner](https://img.shields.io/badge/AI-Powered%20Micro--Lending-blue?style=for-the-badge&logo=amazon-aws)
![Track](https://img.shields.io/badge/Track-Rural%20Innovation-green?style=for-the-badge)
![Hackathon](https://img.shields.io/badge/Hackathon-AI%20for%20Bharat-orange?style=for-the-badge)

## 🎯 Problem Statement

Rural artisans in India face a severe credit crisis:

- 🏦 **Banks reject them** - No credit history, no collateral
- 💰 **Moneylenders exploit them** - 60-120% annual interest rates
- 📊 **₹50,000 Crore** informal lending market in rural India
- 🎨 **Invisible Assets** - Their social capital and skills are unrecognized by formal systems

**Real Impact:** A weaver needs ₹15,000 for raw materials but pays ₹18,000-25,000 in interest to local moneylenders within 6 months.

---

## 💡 Our Solution: VishwasChain

**VishwasChain** is an AI-powered micro-lending platform that quantifies **"Trust Capital"** - the invisible social and skill-based reputation that rural artisans possess but can't prove to formal institutions.

### How It Works

```
📞 Missed Call → 🎤 Voice Testimonials → 📸 Skill Verification → 📊 Trust Score → 💳 Loan Approval
```

#### 1️⃣ Voice-Based Community Vouching
- Neighbors and customers record 15-second voice testimonials about the artisan's reliability
- **AI analyzes voice patterns** for authenticity (detects coached/fake testimonials)
- Natural language processing in **local languages** (Hindi, Marathi, Bhojpuri, etc.)

#### 2️⃣ Skill Verification via Image AI
- Artisans upload photos of their work progression
- **Computer vision assesses** skill level and consistency
- Verifies they actually produce what they claim

#### 3️⃣ Seasonal Income Prediction
- Analyzes WhatsApp/SMS transaction patterns (they already share screenshots)
- Predicts cash flow cycles (harvest seasons, festival demand)
- Recommends optimal loan repayment schedules

#### 4️⃣ Hyperlocal Economic Health Index
- Scrapes mandi prices, weather data, local news
- Adjusts risk scoring based on regional economic conditions
- Prevents over-lending during droughts/crop failures

---

## 🏗️ Technology Architecture

### AWS Services Used

| Service | Purpose |
|---------|---------|
| **Amazon Transcribe** | Voice-to-text for multilingual testimonials |
| **Amazon Comprehend** | Sentiment analysis & emotion detection |
| **Amazon Rekognition** | Image verification for craft quality assessment |
| **Amazon Bedrock** | AI models for trust scoring algorithms |
| **Amazon Connect** | Missed call-based loan application system |
| **AWS Lambda** | Serverless processing for all workflows |
| **Amazon S3** | Storage for voice recordings & images |
| **Amazon DynamoDB** | Database for user profiles & loan records |
| **Amazon SageMaker** | Custom ML models for voice authenticity |

### System Flow

```
┌─────────────┐        ┌──────────────┐       ┌─────────────┐
│   Artisan   │──────▶ │  WhatsApp/   │─────▶ │   AI        │
│ (Feature    │        │  Missed Call │       │ Processing  │
│  Phone)     │        │   System     │       │   Engine    │
└─────────────┘        └──────────────┘       └─────────────┘
                                                      │
                                                      ▼
┌─────────────┐        ┌──────────────┐       ┌─────────────┐
│   Lender    │◀────── │    Trust     │◀───── │   Database  │
│ (NRI/Urban  │        │    Score     │       │  (DynamoDB) │
│   Donor)    │        │  Calculator  │       └─────────────┘
└─────────────┘        └──────────────┘
```

---

## 🎨 Key Innovation Points

### 1. No Smartphone Required
- Works via **Missed Call + WhatsApp** (most artisans have feature phones)
- Voice-first interface for low-literacy users

### 2. Voice Emotion Analysis
- Detects authenticity of testimonials
- Multilingual support for 10+ Indian languages
- **Anti-fraud mechanism** against coached references

### 3. Federated Learning
- Privacy-preserving AI that keeps data local
- Works with poor internet connectivity
- Community data stays in the community

### 4. Cultural Context Understanding
- Recognizes seasonal work patterns (festivals, harvest)
- Understands traditional craft quality indicators
- Maps community trust networks

---

## 👥 User Personas

### 🎨 Ravi (Artisan - Borrower)
- 45 years old, pottery artisan from Maharashtra
- Needs ₹20,000 for clay and wheel repair
- Has feature phone, speaks Marathi
- Strong reputation in village but no bank account

### 🏘️ Sunita (Community Voucher)
- Regular customer who buys Ravi's pottery
- Provides voice testimonial about quality and reliability
- Uses WhatsApp to submit recording

### 💼 Priya (Lender)
- NRI in USA seeking social impact investment
- Wants to support rural artisans with fair interest rates
- Reviews artisan profiles on web dashboard

---

## 📊 Impact Metrics

| Metric | Target | Traditional System |
|--------|--------|-------------------|
| Interest Rate | **12-18%** | 60-120% |
| Loan Approval Time | **<48 hours** | 2-3 months (or rejection) |
| Default Rate | **<5%** | 15-25% |
| Voice Authenticity | **95%+ accuracy** | Manual verification |
| Languages Supported | **10+** | Usually only English/Hindi |

---

## 📁 Project Structure

```
VishwasChain-AI-MicroLending/
│
├── requirements.md          # Detailed technical requirements
├── design.md               # System architecture & design
├── README.md              # This file
└── presentation/          # Hackathon presentation (PDF)
```

---

## 🚀 Deployment Strategy

### Phase 1: Pilot (3 months)
- Launch in 5 villages in Nashik district, Maharashtra
- Target: 100 artisans
- Partner with local NGOs for onboarding

### Phase 2: Scale (6-12 months)
- Expand to 50 villages across Maharashtra
- Target: 2,000 artisans
- Integrate with existing microfinance institutions

### Phase 3: National (12-24 months)
- Multi-state expansion
- Target: 50,000+ artisans
- Partnership with government schemes (MUDRA, Stand-Up India)

---

## 💰 Business Model

### Revenue Streams
1. **Transaction Fee**: 2-3% on successful loan disbursement
2. **Platform Fee**: ₹100-200 per loan for lenders
3. **Data Insights**: Aggregated (anonymized) market intelligence to NGOs/researchers

### Sustainability
- Break-even at 5,000 active loans
- Projected ROI for lenders: 12-15% annually
- Social impact: ₹5-10 saved per ₹100 borrowed (vs moneylenders)

---

## 🏆 Competitive Advantage

| Feature | VishwasChain | Traditional Banks | Existing Microfinance |
|---------|-------------|------------------|---------------------|
| Smartphone Required | ❌ No | ✅ Yes | ⚠️ Sometimes |
| Credit History Needed | ❌ No | ✅ Yes | ⚠️ Group-based |
| Interest Rate | 12-18% | N/A (reject) | 20-35% |
| Individual Lending | ✅ Yes | ❌ No | ⚠️ Group only |
| Skill Verification | ✅ AI-powered | ❌ No | ❌ No |
| Cultural Context | ✅ Deep | ❌ No | ⚠️ Limited |

---

## 👨‍💻 Team

**Hackathon Submission for:** AI for Bharat - Track 3: Rural Innovation & Sustainable Systems

- **Team Lead:** [Your Name]
- **Technical Lead:** [Team Member Name]
- **AI/ML Specialist:** [Team Member Name]
- **Domain Expert:** [Team Member Name]

---

## 📞 Contact & Links

- **GitHub Repository:** [This repo]
- **Hackathon:** AI for Bharat by Hack2Skill
- **AWS Partner:** Innovation Partner - H2S
- **Contact:** [Your Email]

---

## 🙏 Acknowledgments

- **Inspiration:** The millions of rural artisans keeping India's traditional crafts alive
- **AWS Credits:** Thanks to Hack2Skill for AWS support
- **Mentorship:** [Any mentors/advisors]

---

## 📜 License

This project is submitted as part of the AI for Bharat Hackathon 2026.

---

<div align="center">

### 🌟 Built with ❤️ for Rural Bharat 🌟

**"Turning Social Capital into Financial Capital"**

![Made with AWS](https://img.shields.io/badge/AWS-Powered-orange?style=for-the-badge&logo=amazon-aws)
![AI for Good](https://img.shields.io/badge/AI-For%20Good-green?style=for-the-badge)

</div>
