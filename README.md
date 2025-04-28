# YieldForge
YieldForge is an **AI-powered DeFi Yield Optimizer** built on the **Aptos blockchain**.  
It combines **smart contracts (Move language)**, **AI-based recommendation engine (Python)**, and a beautiful **React + TailwindCSS frontend** to create the next-generation DeFi experience.
---

## Project Structure
yeildForge/
├── ai-engine/          # Python AI service to recommend optimized yield strategies
├── blockchain/         # Move smart contracts deployed on Aptos blockchain
├── frontend/           # React.js frontend for users to interact with YieldForge
├── README.md
└── .gitignore

  Layer    |     Technology
Frontend   | React.js, Vite, Tailwind CSS
Blockchain | Aptos, Move Language
AI Engine  | Python (FastAPI, scikit-learn, etc.)
Hosting (future) | Vercel / AWS / Aptos Node

# Setup Instructions
1. Clone the Repository
- git clone https://github.com/003-kalki/yeildForge.git
- cd yeildForge

2. Frontend setup
- cd frontend
- npm install
- npm run dev

3.Blockchain Setup (Aptos)
Install Aptos CLI:
-> curl -sSf https://aptos.dev/cli-install | sh
  
Initialize project:
- cd blockchain
- aptos init

Compile and deploy contracts:
- aptos move compile
- aptos move publish

4. AI Engine Setup
cd ai-engine
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
- uvicorn services.api:app --reload

