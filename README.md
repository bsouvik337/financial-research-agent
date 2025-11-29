# Financial Deep Research Agent

A sophisticated financial research system that replicates advanced AI research capabilities for comprehensive financial analysis, similar to Claude's Deep Research mode but specialized for financial domains.

## 🚀 Features

- **Multi-Sector Research**: Specialized agents for IT and Pharmaceutical sectors
- **Deep Research Loops**: 15+ step iterative research with dynamic adaptation
- **Real Data Integration**: Web search + Financial APIs (yfinance)
- **Intelligent Query Routing**: Automatic sector detection and agent selection
- **Professional Reporting**: Comprehensive, structured research reports
- **Dynamic Research**: Each finding informs the next research step

## 📋 Project Structure
financial-research-agent/
├── src/
│ ├── core/ # Core architecture and components
│ │ ├── architecture.py # Base classes and enums
│ │ ├── query_analyzer.py # Query analysis and routing
│ │ └── research_planner.py # Research planning
│ ├── agents/ # Sector-specific research agents
│ │ ├── base_agent.py # Base agent class
│ │ ├── it_agent.py # IT sector research agent
│ │ └── pharma_agent.py # Pharmaceutical sector agent
│ ├── utils/ # Utility modules
│ │ └── web_searcher.py # Web search and financial data
│ └── main.py # Main application
├── data/
│ └── reports/ # Auto-generated research reports
├── tests/ # Test cases
├── docs/ # Documentation
├── requirements.txt # Python dependencies
└── README.md
