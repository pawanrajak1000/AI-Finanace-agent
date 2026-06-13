# AI-Finanace-agent
AI_FINANCIAL_AGENT
💰 AI Financial Coach with Google ADK & Gemini
An end-to-end AI-powered personal finance advisor built using Streamlit, Google Agent Development Kit (ADK), and Gemini LLM.
The system analyzes income, expenses, savings, and debts to deliver personalized financial insights through multiple specialized AI agents.

🚀 Key Features
🤖 Multi-Agent AI Architecture
Budget Analysis Agent

Categorizes expenses
Identifies overspending patterns
Provides actionable cost-cutting recommendations
Savings Strategy Agent

Calculates emergency fund (6 months of expenses)
Recommends savings allocation
Suggests automation techniques for consistent saving
Debt Reduction Agent

Generates optimized payoff strategies
Compares Avalanche vs Snowball methods
Estimates interest savings and payoff duration
📊 Data Input Options
Upload CSV transaction files
Manual expense entry by category
Debt entry with interest rate & minimum payments
📈 Interactive Visualizations
Expense breakdown (Pie Charts)
Income vs Expense comparison
Debt distribution and payoff comparison
Savings progress indicators
🧠 AI Capabilities
Structured JSON outputs using Pydantic schemas
Prompt-engineered financial reasoning
Reliable response parsing & fallback logic
Explainable AI recommendations
🛠 Tech Stack
Frontend / UI: Streamlit
AI / LLM: Google Gemini, Google ADK (Agent Development Kit)
Backend: Python, AsyncIO
Data Processing: Pandas, NumPy
Validation: Pydantic
Visualization: Plotly, Plotly Express
Security: dotenv, environment-based API keys
📂 CSV Format (Required)
Column	Description
Date	YYYY-MM-DD
Category	Expense category
Amount	Numeric value
▶️ Run Locally
pip install -r requirements.txt
streamlit run app.py
