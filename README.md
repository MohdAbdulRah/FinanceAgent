# 💰 AI Financial Coach

AI Financial Coach is a personalized financial advisor powered by
Google's ADK (Agent Development Kit) framework.\
The application provides intelligent financial analysis and actionable
recommendations based on user inputs such as income, expenses, debts,
and financial goals.

------------------------------------------------------------------------

## 🚀 Features

### 🧠 Multi-Agent Financial Analysis System

The application uses a multi-agent architecture where each agent handles
a specific financial responsibility:

#### 📊 Budget Analysis Agent

-   Analyzes spending patterns
-   Identifies unnecessary expenses
-   Recommends budget optimizations

#### 💸 Savings Strategy Agent

-   Creates personalized savings plans
-   Suggests emergency fund strategies
-   Recommends goal-based savings allocation
-   Tracks savings milestones

#### 🏦 Debt Reduction Agent

-   Develops optimized debt payoff strategies
-   Compares Avalanche and Snowball methods
-   Calculates payoff timelines
-   Estimates interest savings

------------------------------------------------------------------------

## 📂 Expense Analysis

-   CSV file upload support
-   Manual expense entry option
-   Tracks:
    -   Date
    -   Category
    -   Amount
-   Automated expense categorization
-   Spending pattern detection
-   Visual breakdown of expenses

------------------------------------------------------------------------

## 💰 Savings Recommendations

-   Emergency fund sizing
-   Custom savings allocation across multiple goals
-   Practical automation techniques
-   Progress tracking and milestone recommendations

------------------------------------------------------------------------

## 🏦 Debt Management

-   Multiple debt handling
-   Interest rate optimization
-   Avalanche vs Snowball comparison
-   Visual payoff timelines
-   Actionable reduction strategies

------------------------------------------------------------------------

## 📈 Interactive Visualizations

-   Pie charts for expense breakdown
-   Bar charts for income vs expenses
-   Debt comparison graphs
-   Progress tracking metrics

------------------------------------------------------------------------

# 🛠️ How to Run the Application

## 1️⃣ Get Gemini API Key

Get a free Gemini API Key from Google AI Studio:

https://aistudio.google.com/apikey

Create a `.env` file in the project root and add:

    GOOGLE_API_KEY=your_api_key_here

------------------------------------------------------------------------

## 2️⃣ Clone the Repository

``` bash
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd awesome-llm-apps/advanced_ai_agents/multi_agent_apps/ai_financial_coach_agent/
```

------------------------------------------------------------------------

## 3️⃣ Install Dependencies

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## 4️⃣ Run the Application

``` bash
streamlit run ai_financial_coach_agent.py
```

------------------------------------------------------------------------

# 📄 CSV File Format

  -----------------------------------------------------------------------
  Column                         Description
  ------------------------------ ----------------------------------------
  Date                           Transaction date in YYYY-MM-DD format

  Category                       Expense category

  Amount                         Transaction amount (supports currency
                                 symbols and comma formatting)
  -----------------------------------------------------------------------

## 📌 Example CSV

``` csv
Date,Category,Amount
2024-01-01,Housing,1200.00
2024-01-02,Food,150.50
2024-01-03,Transportation,45.00
```

------------------------------------------------------------------------

# 🧩 Tech Stack

-   Python
-   Streamlit
-   Google ADK (Agent Development Kit)
-   Gemini API
-   Pandas
-   Data Visualization Libraries

------------------------------------------------------------------------

# 📜 License

This project is for educational and demonstration purposes.

------------------------------------------------------------------------

⭐ If you found this project helpful, consider giving it a star!
