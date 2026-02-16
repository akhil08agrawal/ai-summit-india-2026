# India AI Impact Summit 2026 — Website Blueprint

## Overview

A single-page, no-login website for attendees of the India AI Impact Summit 2026 (Feb 16–20, Bharat Mandapam, New Delhi). The site personalizes itself based on 3 quick onboarding questions stored in a temporary browser session. All data lives on the frontend — no backend needed.

---

## Onboarding Flow (Landing Page)

The landing page IS the onboarding. Three questions, one per screen, with smooth transitions. The user can answer all three in under 30 seconds.

### Question 1 — "Who are you?"
- **Type:** Single select (pick one)
- **Options:**
  - 🚀 Startup Founder
  - 🏢 Enterprise Leader
  - ⚡ Developer / Engineer
  - 💰 Investor / VC
  - 🔬 Researcher / Academic
  - ⚖️ Policy / Government
- **Why it matters:** Drives the "Must-Visit Stalls" tab — each persona gets a completely different ranked top 10 list

### Question 2 — "What interests you most?"
- **Type:** Multi select (pick all that apply)
- **Options:**
  - 🖥️ AI Infrastructure & Compute
  - 🧠 Foundation Models & LLMs
  - 🛡️ AI Governance & Safety
  - 💡 Startups & Innovation
  - 🌍 Global Partnerships
  - 🗣️ Voice & Multilingual AI
  - 🏥 AI for Healthcare
  - 🎬 Creative AI & Media
- **Why it matters:** Tags are attached to sessions, companies, and models. Items matching the user's interests get a "✦ For You" badge and sort to the top

### Question 3 — "Which day are you visiting?"
- **Type:** Single select OR skip
- **Options:** Feb 16 (Sun) / Feb 17 (Mon) / Feb 18 (Tue) / Feb 19 (Wed) / Feb 20 (Thu) / Skip
- **Why it matters:** The Schedule tab defaults to showing the user's visit day first

### After Onboarding
- Preferences are saved in session (no login, no cookies banner needed — it's ephemeral)
- User lands on the personalized dashboard
- A small ⚙️ button lets them re-do the onboarding at any time

---

## Dashboard — 9 Tabs

### Tab 1: ◉ Overview
The homepage after onboarding. Shows the big picture at a glance.

**Content blocks:**
1. **Headline Stats Banner** — 6 cards in a grid:
   - 20+ Heads of State
   - 250K+ Expected Visitors
   - 3,250+ Speakers
   - 700+ Sessions
   - 600+ Startups
   - $68B+ Investment Committed

2. **Keynote Speakers** — Card grid showing 8 headliners:
   - PM Modi, Sam Altman, Sundar Pichai, Dario Amodei, Demis Hassabis, Emmanuel Macron, Brad Smith, Michael Kremer
   - Each card: name, role, day, and one-line topic summary

3. **7 Governance Sutras** — Numbered list:
   - Trust is the Foundation / People First / Innovation over Restraint / Fairness & Equity / Accountability / Understandable by Design / Safety, Resilience & Sustainability

4. **Key Takeaways** — 5 highlight cards:
   - India's $100B+ AI infrastructure play
   - Voice-first multilingual AI as the next frontier
   - India is #2 market for OpenAI and Anthropic
   - India's 7-sutra "innovation over restraint" governance
   - Feb 19 is THE day for all major sessions

### Tab 2: 📅 Schedule
Day-by-day event schedule with 40+ sessions.

**Interaction:**
- 5 day-selector tabs at the top (defaults to user's chosen visit day)
- Each session card shows: time, session name, venue, speakers (if known), and interest tags
- Sessions matching user's interest selections get a "✦ For You" badge and sort higher
- Highlighted sessions (keynotes, plenaries) get a saffron left border

**Data per day:**
- Day 1 (Feb 16): 5 sessions — Inauguration, AI for Road Safety, Challenge Finals Day 1, PM Modi Expo Launch, Kathavatar Films
- Day 2 (Feb 17): 6 sessions — J-PAL with Nobel Laureate, MDB Financing, Health Systems, AI Compendium, YUVAi Hackathon, Challenge Awards
- Day 3 (Feb 18): 6 sessions — SDGs reshaping, AI Governance Co-Chairs, Research Symposium, Data for Development, AI by HER Hackathon, Lenovo LEAP
- Day 4 (Feb 19): 7 sessions — Opening Ceremony, Leaders' Plenary, CEO Roundtable, Tech CEO Headliners, Macron Keynote, Shekhar Kapur Masterclass, Adobe Future of Film
- Day 5 (Feb 20): 6 sessions — AI for Agriculture, Democratizing Compute, Food Systems, Reimagining Education, Leaders' Declaration, GPAI Council

### Tab 3: 📍 Must-Visit Stalls
Personalized top 10 recommendations that change completely based on persona.

**6 different lists (10 stalls each):**
- **Startup Founder:** Startup Pavilion → Challenge Finale → Sarvam AI → French Pavilion → WAVES Corner → Compute Portal → Jio Pavilion → Investor Panel → Neysa/Blackstone → AI by HER
- **Enterprise Leader:** EY Scout Robot → AMD-TCS Helios → KPMG → French Enterprise Zone → Jio Pavilion → Adobe → Cisco → AI Compendium → Qualcomm → Innovation Chakra
- **Developer:** BharatGen/IIT Bombay → Sarvam AI → Compute Portal → AI Immersive Theatre → WAVES Corner → Fujitsu Japan → Woman Hackathon → Lenovo LEAP → Yesgnome/Sketly → Democratizing Resources
- **Investor:** Startup Pavilion → Challenge Finale → Gaming Showcase → Gold Rush Panel → Sarvam AI → WAVES Corner → AI by HER → French Pavilion → KPMG Hub → Innovation Chakra
- **Researcher:** BharatGen/IIT Bombay → J-PAL Social Good → AI Compendium → Science Chakra → Fractal Analytics → AIRAWAT → World Bank → UN ODET → Fujitsu → Gnani AI
- **Policy:** Governance Sessions → Safe AI Chakra → UN ODET → CPRG Dialogues → Ministry Pavilions → Country Pavilions → Bihar Pavilion → World Bank/ADB → Safety Institute → Legal Framework

Each stall shows: rank number, name, and a one-line "why visit" explanation.

### Tab 4: 🏢 Companies
All major companies at the summit.

**Filter bar:** All / Global Tech / Indian Enterprise

**22 company cards total:**
- Global (12): OpenAI, Google/Alphabet, Anthropic, Microsoft, AMD, Qualcomm, Fujitsu, Adobe, Cisco, Scale AI, Mistral AI, NVIDIA (via Yotta)
- Indian (10): Reliance/Jio, TCS, Infosys, Wipro, Tech Mahindra, HCLTech, Yotta, Neysa, KPMG, EY

Each card: company name, key person at summit, showcase description, interest tags. Cards matching user interests get highlighted.

### Tab 5: 🧠 AI Models
All 12 IndiaAI Mission indigenous foundation model developers.

**12 model cards:**
- Sarvam AI (120B), BharatGen/IIT Bombay (17B MoE), Fractal Analytics (Reasoning), Tech Mahindra (Indic), Avataar.ai (Avatars), Gnani AI (Voice), Krutrim/Ola (12B), Soket AI Labs (120B), Gan AI (Video), GenLoop (Indic LLM), ZenteiQ (8B Engineering), Shodh AI (7B Materials)

Each card: developer name, model name, parameter count, focus area, funding info. Sorted by relevance to user's interests.

### Tab 6: 💰 Deals & Investments
All major financial announcements.

**10 deal cards:**
- Big Tech Combined $68B+ / Blackstone-Neysa $1.2B / IndiaAI Mission ~$1.2B / State VC Fund $1.1B / Semiconductors $18B / Microsoft ₹1.5L Cr / Amazon ₹2.9L Cr / Google ₹1.25L Cr / AMD-TCS Helios / C2i $15M

**Challenge Finalists section:**
- 9 named finalists from 3 challenges (AI for ALL, AI by HER, YUVAi)
- Includes international teams: MalariaX (Thailand), Gooey AI (USA), Happykids AI (Luxembourg)

### Tab 7: 🌍 Country Pavilions
13 nation pavilions.

**Pavilion cards:** France (Hall 14, 436 sq.m, 29 companies — detailed), Japan (Fujitsu), UK (David Lammy delegation), Australia, Germany, Italy, Russia, Netherlands, Switzerland, Serbia, Estonia, Tajikistan, Africa (multi-nation)

Each card: flag emoji, country name, hall location (if known), number of companies, key highlight.

### Tab 8: 🗺️ Venue & Navigation
Physical layout and logistics.

**Hall Layout** — 7 hall cards:
- Hall 1 (EY, Booth 1.7) / Hall 2 (Unknown) / Hall 3 (Synopsys, 3F.16) / Hall 4 (HCLTech, 4.5) / Hall 5 (Bihar, Stalls 8 & 12) / Hall 6 (Unknown) / Hall 14 (France, 14.5E)

**Entry Gates** — 3 gate cards:
- Gate 4: 7:30 AM – 2 PM (car/shuttle)
- Gate 7: After 2 PM only (walk-in)
- Gate 10: Full day, Metro Blue Line — recommended ⭐

**Other Venues:**
- Sushma Swaraj Bhawan (startups/students)
- Ambedkar Bhavan (policy/governance)
- India Habitat Centre (education)
- UN House (ODET side events)

### Tab 9: ⚡ Survival Tips
Practical advice + interactive checklist.

**8 tip cards:**
- Arrive before 9 AM / Carry cash / Download offline / Expect VIP disruptions / Gate 10 Metro / Use golf carts / Bring water & snacks / Plan your route

**Interactive Checklist** (checkboxes, state persists in session):
- Download summit app / Carry cash / Portable charger / Water bottle + snacks / Comfortable shoes / Offline materials / Business cards / Plan route by chakra zones

---

## Personalization Logic (How preferences affect the experience)

| User Selection | What Changes |
|---|---|
| **Persona** (Q1) | Must-Visit Stalls tab shows a completely different ranked list of 10 stalls |
| **Interests** (Q2) | Sessions, companies, and models matching selected interests get "✦ For You" badges and sort to top |
| **Visit Day** (Q3) | Schedule tab defaults to showing that day; if skipped, defaults to Day 4 (the biggest day) |

---

## Design Direction

- **Theme:** Dark mode with India flag accent colors (saffron #FF9933, white, green #138808)
- **Typography:** Serif display font for headings, clean sans-serif for body
- **Atmosphere:** Floating gradient orbs on onboarding, subtle grain texture overlay, smooth fade/slide animations
- **Layout:** Single-page app with tab navigation, responsive across mobile and desktop
- **No login, no backend, no cookies** — pure frontend with session state

---

## Data Sources

All data compiled from 50+ sources including:
- PIB (Government Press Information Bureau)
- CNBC, TechCrunch, Bloomberg, Business Standard, BusinessToday
- Company newsrooms (AMD, Blackstone, EY, HCLTech, Atos, Fujitsu)
- World Bank, UN ODET, J-PAL, OECD
- Official summit website (impact.indiaai.gov.in)

Last updated: February 17, 2026. Summit runs through February 20.
