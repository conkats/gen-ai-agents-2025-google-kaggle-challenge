# gen-ai-agents-2025-google-kaggle-challenge
---

## 📘 Overview
- Repository of my participation to the 5-Day Gen and AI Agents Intensive course 2025 by **Google × Kaggle | November 10–14, 2025** and taggling the capstone project. The course covers fundamental concepts, architectures, tools, and best software engineering practices for GenAI, building, evaluating, scaling and working with AI agents using **Google’s Gemini API** and modern multi-agent frameworks.

### 🎯 Course Goals
- Learn to build **practical AI agents**
- Explore **multi-agent architectures** and tool integration
- Master **evaluation and scaling** techniques
- Develop a **capstone project** showcasing agent capabilities

---
###  Local development setup:
#### Clone this repository
git clone https://github.com/yourusername/ai-agents-intensive-2025-google-challenge.git
cd ai-agents-intensive-2025-google-challenge
   ```bash
   git add .
   git commit -m "Add Day N notes and notebook"
   git push
```
🔐 Security & API Keys

⚠️ Never commit API keys or secrets to this repository.

Store your GOOGLE_API_KEY securely as a Kaggle Secret and read through the relevant docs
(Kaggle → Settings → Secrets → Add Secret)

Use local environment variables for development (.env files are in .gitignore)

See resources/kaggle_links.md for detailed setup instructions

📁 Repository Structure
```ai-agents-intensive-2025/
│
├── README.md                      # This file
├── LICENSE                        # MIT License
├── .gitignore                     # Excludes secrets, cache, etc.
│
├── resources/
│   └── kaggle_links.md            #  All course URLs, Kaggle setup & API guide
│
├── day1_intro_to_agents/          # Day 1 Kaggle notebook
│   ├── day-1b-agent-architectures
│   └── day-1a-from-prompt-to-action.ipynb         
│
├── day2_agent_architecture/       # Day 2 Kaggle notebook
│   ├── day-2a-agent-tools.ipynb   
│   └── day-2b-agent-tools-best-practices.ipynb
│
├── day3_tools_and_memory/        # Day 3 Kaggle notebook
│   ├── day-3a-agent-memory.ipynb   
│   └── day-3b-agent-sessions.ipynb
│ 
├── day4_evaluation_and_scaling/   # Day 4 Kaggle notebook
│   ├── day-4a-agent-observability.ipynb
│   └── day-4b-agent-evaluation.ipynb
│
└── day5_production/                 # Day 5 production
    ├── day-5a-agent2agent-communication.ipynb
    └── day-5b-agent-deployment.ipynb
└── capstone-project/                    
    └── tripmindai.ipynb.ipynb        #final submitted capstone project for TripMindAI
```

## Capstone-Project:
### The Problem:
Modern travel planning is overwhelming. A simple trip requires juggling a dozen browser tabs—flights, hotels, and activities—often leading to decision fatigue and disjointed itineraries.

### The Solution: ***TripMindAI**
Is not just another booking site; it is an intelligent agentic system that acts as your personal travel architect. Built on a robust multi-agent architecture, TripMind decomposes the complex problem of travel planning into specialised tasks handled by distinct AI agents.

🎯 TripMindAI's Objective: Ease the process and save time before finalising bookings.

Streamline pre‑booking research so users can quickly compare and select flights and hotels.
Support both exploratory trip planning and more structured business travel needs.
🌟 What the project covers - Key Features

✅ Multi-agent system architecture:

 - Search for flights based on destination, origin and dates given
 - Search for hotels based on destination
 - Parallel agent system framework to search for hotels and flights - happens simultaneously
 - Loop refinement agent to refine the output from the agent and not relying on one-shot response: Flight Assistant, hotel finder → Orchestraror-LLM
 - Sequential Agent to manage and coordinate the agents workflow
 - Powered Coordinator/Manager: Root agent orchestrates the entire process → Final Suggestion
✅ Tools:

- Custom-Function (Save information,  Retrieve information)
- MCP tool
✅ Sessions & Memory:

- Memory and Database storage for using session and states
- Hold the memory of the proposed suggestion and trip of the user, needed if changing plans, add database using sqlite (long-term memory with databases)


🧠 Acknowledgements

This repository follows the structure and learning flow of the Google × Kaggle 5-Day AI Agents Intensive 5 day course (2025 ).

