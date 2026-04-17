🐾 StreetPaws India
> \*\*AI-powered street dog population mapping for humane, data-driven Animal Birth Control (ABC) programmes across India.\*\*
![License: MIT](./LICENSE)
[![Status: Prototype](https://img.shields.io/badge/Status-Prototype-orange.svg)]()
[![Made for India](https://img.shields.io/badge/Made%20for-India-blue.svg)]()
![Open to Contributors](./CONTRIBUTING.md)
---
The Problem
India has an estimated 20 million stray dogs — yet only 15–20% receive treatment annually. ABC programmes frequently fail not because of lack of effort, but because they operate without reliable population data. No one knows:
Where dogs are concentrated
Which dogs have already been sterilised
Whether sterilised dogs are being returned to their original locations (critical for welfare)
Whether coverage is improving or declining over time
The result: wasted resources, duplicated surgeries, welfare risks, and no way to prove impact to municipalities or courts.
---
The Solution
StreetPaws India is a crowdsourced, AI-powered platform that gives NGOs, municipalities, and Animal Welfare Boards a real-time population map — for the first time.
How it works
```
Resident spots a dog → Photos it via mobile app → GPS location auto-tagged
        ↓
AI pipeline: Quality check → Dog detection → Individual fingerprint extraction
        ↓
Matching engine: Is this dog already in the system? Same dog, different location?
        ↓
NGO Dashboard: Real-time map · Coverage heatmap · Sterilisation tracking · Reports
```
Core Features
Feature	Description
📸 Crowdsourced sighting reports	Any resident can submit a photo — no login required
🔍 AI re-identification	Matches individual dogs across multiple sightings using visual fingerprinting
🗺️ Real-time population map	GPS-clustered heatmap of dog density by ward/zone
✅ Sterilisation tracking	Tracks which dogs are neutered, vaccinated, ear-notched
📍 Location-return enforcement	Ensures post-surgery dogs are returned to their exact territory
📊 ABC coverage reports	Ward-by-ward progress reports formatted for municipality/AWBI submission
🧑‍⚕️ NGO operations dashboard	Capture planning, surgery scheduling, field team coordination
🔄 Human review queue	Borderline AI matches reviewed by trained volunteers before confirmation
---
Why Now
The Supreme Court of India (August 2025) directed municipalities nationwide to create feeding zones, helplines, and measurable ABC coverage — with a push toward a uniform pan-India policy
Municipalities are now legally obligated to show coverage numbers — and they have no tool to measure them
The ABC Rules 2023 and Animal Welfare Board of India require structured data that this system is designed to produce
Lucknow's ABC programme — the most successful in India — achieved 84.3% sterilisation coverage through organised, data-driven operations. This system gives every other city the same operational intelligence Lucknow built manually.
---
Current Status
Phase	Status	Description
Phase 0	✅ Complete	Technical blueprint + interactive prototype
Phase 1	🔄 In Progress	Pilot build — one ward in Chennai
Phase 2	📅 Planned	Municipality partnership + live deployment
Phase 3	📅 Planned	State-level expansion
👉 View the live interactive prototype — open in any browser to see the full NGO dashboard, dog profiles, AI review queue, and mobile app simulation.
---
Tech Stack (Planned)
Layer	Technology
Mobile App	React Native (iOS + Android)
AI Pipeline	Python · PyTorch · MegaDescriptor / re-ID models
Backend API	FastAPI
Database	PostgreSQL + PostGIS
Dashboard	React + Leaflet.js
Infrastructure	Docker · Railway / Render (Phase 1 free tier)
---
Project Structure
```
streetpaws-india/
├── README.md               ← You are here
├── LICENSE                 ← MIT License
├── CONTRIBUTING.md         ← How to join the project
├── docs/
│   └── blueprint.docx      ← Full technical specification (12 sections)
├── demo/
│   └── index.html          ← Interactive prototype (open in browser)
└── .github/
    └── ISSUE\_TEMPLATE.md   ← Bug report / feature request template
```
As the build progresses, `backend/`, `mobile/`, and `dashboard/` folders will be added here.
---
Get Involved
This is an open-source civic project — built to eventually become a government/NGO tool for animal welfare in India. We welcome:
🧑‍💻 Developers — React Native, Python/FastAPI, ML/computer vision
🐕 Animal welfare volunteers — Dog photo labelling for AI training data
🏙️ NGO and municipal partners — Pilot zone testing in Chennai
💰 Grant writers / funders — CSR, animal welfare foundations, govt schemes
See CONTRIBUTING.md to get started.
---
Contact & Partnerships
If you are an NGO, municipal officer, or developer interested in partnering on the pilot:
📧 Open a GitHub Issue tagged `partnership`
🏙️ Priority pilot city: Chennai, Tamil Nadu
🤝 First target partner: Blue Cross of India, Chennai
---
License
MIT License — free for NGOs, municipalities, and government bodies to use, adapt, and deploy.
---
StreetPaws India is built on the belief that every stray dog deserves a safe life — and that the fastest path to that is giving the people trying to help them better tools.
