🚀 Expense Tracking System

📌 Overview:

This project was built as part of my broader journey toward designing AI-ready, scalable systems.
Instead of treating Python as just a new language, the focus here was to apply backend design principles in a lightweight, fast-moving environment, using modern Python frameworks to prototype an end-to-end system.
The application enables users to track, manage, and analyze expenses through a simple UI backed by a structured API layer.


🏗️ Architecture:

Frontend: Streamlit
Backend: FastAPI
Data Validation: Pydantic
Flow:
Streamlit UI → FastAPI APIs → Data Processing Layer
Key design considerations:
Clear separation between UI and API layers
API-first design for extensibility
Strong data contracts using Pydantic
Lightweight architecture optimized for rapid iteration

⚙️ Key Features:

Add, update, and delete expenses
Categorize and track spending
API-driven backend for flexibility
Simple and interactive UI for quick usage

🧠 Key Learnings:

This project was less about the feature set and more about strengthening core engineering capabilities in a Python ecosystem:
Designing clean and maintainable APIs using FastAPI
Enforcing data integrity and validation using Pydantic
Building end-to-end systems with clear separation of concerns
Rapid prototyping using lightweight frameworks
Adapting backend engineering principles to Python-based stacks

🔍 Why This Matters:

As systems evolve toward AI-driven architectures, engineers need to move beyond conceptual understanding and get hands-on with the underlying stack.
This project represents a step in that direction—bridging traditional backend expertise with modern Python-based ecosystems used in AI applications.

▶️ Getting Started
# Clone the repository
git clone https://github.com/pmanicka/Expense-Tracking-System.git

# Navigate to project folder
cd Expense-Tracking-System

# Install dependencies
pip install -r requirements.txt

# Run FastAPI backend
uvicorn main:app --reload

# Run Streamlit frontend
streamlit run app.py
📈 Next Steps
Integrate database persistence (PostgreSQL / NoSQL)
Add authentication & user-specific data handling
Introduce analytics/insights layer
Extend toward AI-based expense categorization & recommendations
🤝 Connect
If you're exploring similar transitions into AI or building lightweight systems for rapid experimentation, happy to connect and exchange ideas.
