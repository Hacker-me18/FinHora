# FinHora

> **An Open-Source AI Wealth Intelligence Platform**
>
> **Understand. Manage. Grow. — with knowledge, discipline, and time.**

FinHora is an open-source AI-powered personal wealth platform designed to help people **understand, manage, and grow their wealth over the long term**.

FinHora is not intended to be an "AI stock-picking machine". Instead, it aims to become a personal **Wealth Copilot** that brings financial knowledge, wealth management, investment research, risk analysis, and long-term planning into one intelligent system.

> **Wealth is not built by a single investment decision. It is built through knowledge, discipline, risk management, and time.**

------

## Why FinHora?

Personal finance is increasingly fragmented.

A person may have:

- Bank accounts and deposits
- Stocks and ETFs
- Mutual funds
- Bonds
- Gold
- Crypto assets
- Insurance
- Loans and credit
- Multiple financial applications
- Information scattered across news, reports, social media, and websites

The problem is often not a lack of information.

The problem is **too much information, too many products, and too little personalized understanding**.

Many people also lack the financial knowledge needed to evaluate:

- Risk and return
- Fees and hidden costs
- Diversification
- Liquidity
- Leverage
- Concentration risk
- Long-term consequences

FinHora aims to turn fragmented financial information into **understandable, actionable, and explainable wealth intelligence**.

------

## Vision

FinHora aims to become a **personal wealth intelligence layer** between people and the increasingly complex financial world.

Instead of simply asking:

> "Which stock should I buy?"

FinHora should help users answer better questions:

- What is my current financial situation?
- What are my assets, liabilities, and net worth?
- Where is my money going?
- How diversified is my portfolio?
- What risks am I actually taking?
- Do I really understand this financial product?
- What could happen to my wealth under different scenarios?
- What financial concepts should I learn next?
- How can I build a more disciplined long-term wealth plan?

The goal is not to make financial decisions **for** users.

The goal is to help users become **better financial decision makers**.

------

## Core Philosophy

### 1. Understand Before Investing

Financial products should not be treated as black boxes.

FinHora should explain:

- What a product is
- How it works
- Where potential returns come from
- What can cause losses
- What fees are involved
- What liquidity constraints exist
- What risks the user may be taking

### 2. Risk Before Return

A high return means little without understanding the risk required to obtain it.

FinHora emphasizes:

- Volatility
- Maximum drawdown
- Concentration risk
- Liquidity risk
- Leverage
- Correlation
- Counterparty risk
- Scenario analysis

### 3. Think Long Term

FinHora is built around the idea that **time and compounding matter**.

The platform should help users understand:

- Saving
- Investing
- Compound growth
- Asset allocation
- Financial goals
- Retirement planning
- Different market scenarios

### 4. Explain, Don't Blindly Recommend

FinHora prioritizes **decision support and explainability**.

Instead of:

> "Buy this asset."

A better answer is:

> "Here are the relevant facts, risks, assumptions, and possible scenarios. Given your goals and risk preferences, here is how this decision could affect your overall financial position."

### 5. Learn Continuously

Financial education should not be separated from wealth management.

A user's real financial questions should become opportunities to learn.

FinHora aims to connect:

**Financial Knowledge → Personal Context → Decision Support → Feedback → Long-term Learning**

------

# Product Concept

FinHora can be viewed as a **Personal Wealth Copilot**.

```text
                         FinHora
                            │
             ┌──────────────┼──────────────┐
             │              │              │
           Learn          Manage         Decide
             │              │              │
      Financial Knowledge  Wealth Data   Investment Analysis
      Product Education    Cash Flow     Risk Analysis
      Scam Awareness       Portfolio     Scenario Simulation
             │              │              │
             └──────────────┼──────────────┘
                            │
                            ▼
                  Personal Wealth Intelligence
```

The long-term product loop is:

```text
User Data
   ↓
Understand
   ↓
Analyze
   ↓
Explain
   ↓
Simulate
   ↓
Support Decisions
   ↓
Track Results
   ↓
Learn & Remember
   └──────────────→ User Context
```

------

# Core Capabilities

## Personal Wealth Management

Build a structured view of a user's financial life:

- Assets
- Liabilities
- Net worth
- Income
- Expenses
- Cash flow
- Financial goals
- Portfolio allocation

```text
Net Worth
├── Cash
├── Investments
│   ├── Stocks
│   ├── Funds / ETFs
│   ├── Bonds
│   ├── Gold
│   └── Crypto
├── Other Assets
└── Liabilities
    ├── Loans
    └── Credit
```

## Portfolio Intelligence

Go beyond simple profit and loss analysis.

Potential capabilities include:

- Asset allocation
- Concentration analysis
- Volatility
- Maximum drawdown
- Correlation
- Risk exposure
- Liquidity analysis
- Performance attribution
- Diversification analysis
- Rebalancing analysis

The objective is to help users understand:

> **"What risks am I actually taking?"**

## Financial Research Agent

FinHora can use specialized agents and tools to research financial information from sources such as:

- Market data
- Company financials
- Fund information
- Economic indicators
- Financial news
- Regulatory documents
- Public reports
- Financial literature

The system should distinguish between:

**Facts → Analysis → Assumptions → Conclusions**

rather than presenting generated text as unquestionable truth.

## Risk Analysis Agent

A dedicated risk layer can evaluate:

```text
Portfolio
   ↓
Exposure
   ↓
Volatility
   ↓
Correlation
   ↓
Concentration
   ↓
Liquidity
   ↓
Stress Scenarios
   ↓
Risk Assessment
```

Users may eventually be able to ask:

> "What happens to my portfolio if the stock market falls 20%?"

or:

> "How vulnerable is my wealth if I lose my income for six months?"

## Financial Education Agent

FinHora should help users progressively build financial knowledge through real questions and personalized learning.

Potential topics include:

- Money and inflation
- Interest rates
- Bonds
- Stocks
- Funds and ETFs
- Portfolio theory
- Diversification
- Risk and return
- Valuation
- Compound interest
- Asset allocation
- Retirement planning
- Crypto assets
- Financial scams

Instead of only answering a question, FinHora can explain the underlying concepts and connect them to the user's situation.

## Financial Product & Scam Analysis

Users may eventually provide information about a financial product, advertisement, investment proposal, or suspicious claim.

FinHora can help identify potential warning signs such as:

- Unusually high promised returns
- Lack of transparency
- Hidden fees
- Liquidity restrictions
- Excessive leverage
- Unclear counterparties
- Misleading marketing language
- Inconsistent risk/return claims

The purpose is **risk awareness and education**, not automatic legal or regulatory judgment.

## Wealth Scenario Simulator

Long-term wealth management requires thinking about uncertainty.

FinHora can eventually provide scenario analysis such as:

```text
                    Current Wealth
                          │
             ┌────────────┼────────────┐
             ↓            ↓            ↓
         Bull Case     Base Case     Bear Case
             │            │            │
             └────────────┼────────────┘
                          ↓
                   Future Wealth
```

Potential scenarios include:

- Different investment returns
- Inflation
- Market crashes
- Income changes
- Savings changes
- Retirement timing
- Asset allocation changes

The purpose is not to predict the future. It is to help users understand **how assumptions affect possible outcomes**.

------

# Agent Architecture

FinHora is intended to evolve from a simple assistant into a coordinated financial intelligence system.

```text
                         User
                          │
                          ▼
                 ┌─────────────────┐
                 │ Wealth Agent    │
                 └────────┬────────┘
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼
   Wealth Planner   Investment Analyst   Education Agent
        │                 │                 │
        └─────────────────┼─────────────────┘
                          │
                 ┌────────▼────────┐
                 │   Risk Agent    │
                 └────────┬────────┘
                          │
                 ┌────────▼────────┐
                 │ Research / Tool │
                 │     Layer       │
                 └────────┬────────┘
                          │
        ┌─────────────────┼─────────────────┐
        ▼                 ▼                 ▼
   Market Data       Financial Data      Web / News
                          │
                          ▼
                 Knowledge & Memory
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
          RAG        User Context    Portfolio Data
```

The architecture will evolve with the product. FinHora favors **clear boundaries, explainable workflows, and practical engineering over unnecessary agent complexity**.

------

# Technology Direction

FinHora is also an exploration of modern AI Agent engineering applied to personal finance.

Potential technologies include:

- Python
- FastAPI
- LangGraph
- Large Language Models
- Tool Calling
- MCP
- RAG
- Vector Databases
- Knowledge Graphs
- Financial Data APIs
- Structured Outputs
- Agent Memory
- Evaluation
- Observability
- Guardrails
- Docker

Technology choices are not permanently fixed. The project will prioritize **simple, maintainable, testable, and explainable engineering**.

------

# Open Source & Business Model

FinHora is designed with an **Open Core** philosophy.

The long-term concept is:

```text
                 FinHora
                    │
       ┌────────────┴────────────┐
       │                         │
 Open Source Core          FinHora Cloud
       │                         │
       ├── Agent Framework       ├── Free
       ├── Core Engine           ├── Plus
       ├── Basic Analytics       ├── Pro
       ├── Knowledge / RAG       ├── Premium
       └── Self-hosting          └── Enterprise
```

The open-source project can provide:

- Core agent architecture
- Core wealth intelligence components
- Self-hosting capabilities
- Developer tooling
- Community extensions

A future commercial platform may provide:

- Managed cloud service
- Advanced AI capabilities
- Premium financial data
- Advanced research
- Long-term portfolio monitoring
- Family wealth management
- Developer APIs
- Enterprise deployments
- Advanced integrations

The goal is to keep the core technology open while building sustainable services around the platform.

------

# Roadmap

FinHora is a long-term project. The roadmap will evolve with real user feedback.

### Phase 0 — Foundation

- [x] Project created
- [x] Product vision defined
- [ ] Repository architecture
- [ ] Core domain model
- [ ] Initial technical architecture

### Phase 1 — MVP

- [ ] Personal wealth profile
- [ ] Asset / liability management
- [ ] Net worth tracking
- [ ] Basic portfolio analysis
- [ ] Financial knowledge assistant
- [ ] Basic AI Agent workflow

### Phase 2 — Intelligence

- [ ] Portfolio risk analysis
- [ ] Financial research agent
- [ ] Financial product analysis
- [ ] Scenario simulation
- [ ] User memory and personalization
- [ ] RAG knowledge system

### Phase 3 — Platform

- [ ] Market and financial data integrations
- [ ] Multi-agent orchestration
- [ ] Advanced portfolio intelligence
- [ ] Continuous wealth monitoring
- [ ] Evaluation and observability
- [ ] Web application

### Phase 4 — Ecosystem

- [ ] Self-hosted deployment
- [ ] FinHora Cloud
- [ ] API platform
- [ ] Community extensions
- [ ] Premium capabilities
- [ ] Enterprise integrations

------

# Project Status

🚧 **Early-stage / Active Development**

FinHora is currently a product and engineering exploration. Many capabilities described above are part of the long-term vision and are not yet implemented.

The repository will evolve incrementally from a small, usable core toward a broader personal wealth intelligence platform.

------

# Contributing

FinHora is intended to grow as an open-source project.

Contributions, ideas, discussions, and feedback are welcome as the project develops.

Areas that may benefit from future contributions include:

- Agent engineering
- Financial data integration
- Financial knowledge systems
- Portfolio analytics
- Risk modeling
- UI / UX
- Evaluation
- Documentation
- Testing

Contribution guidelines will be added as the project matures.

------

# Disclaimer

FinHora is an open-source software project intended for **education, research, financial awareness, and decision support**.

It does not constitute financial, investment, tax, accounting, or legal advice. Information generated by AI systems may be incomplete, inaccurate, outdated, or based on incorrect assumptions.

Users are responsible for independently verifying information and making their own financial decisions.

Any future deployment involving regulated financial services, personalized investment advice, financial product distribution, or automated trading must comply with applicable laws and regulations in the relevant jurisdiction.

------

# License

Licensed under the **Apache License 2.0**.

See [LICENSE](LICENSE) for details.

------

<div align="center">

**FinHora**

*Understand your wealth. Manage your risk. Grow with time.*

</div>
