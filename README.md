# YieldForge
YieldForge is an **AI-powered DeFi Yield Optimizer** built on the **Aptos blockchain**.  
It combines **smart contracts (Move language)**, **AI-based recommendation engine (Python)**, and a beautiful **React + TailwindCSS frontend** to create the next-generation DeFi experience.
---

# Tech Stack
1. Frontend	- React.js, Vite, Tailwind CSS
2. Blockchain	- Aptos, Move Language
3. AI Engine	- Python (FastAPI, scikit-learn, etc.)
4. Hosting (future)	- Vercel / AWS / Aptos Node

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

