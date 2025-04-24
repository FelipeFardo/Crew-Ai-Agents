
# 📈 Crew-AI: Stock Recommendation System with Multi-Agent Architecture

This project leverages the [CrewAI](https://github.com/crewAIInc/crewAI) framework to orchestrate multiple autonomous AI agents specialized in financial analysis. Each agent has a distinct role in the stock recommendation pipeline, working collaboratively to generate detailed market insights.

## 🚀 Features

- **Stock Analysis**: In-depth evaluation of publicly traded companies.
- **Investment Recommendations**: Suggestions based on financial data and market trends.
- **Multi-Agent Architecture**: Implementation of agents like Financial Analyst, Researcher, and Technical Analyst.
- **Integration with Financial APIs**: Real-time data acquisition for informed decision-making.

## 🧠 System Architecture

The system includes several specialized agents:

1. **Data Collector**: Gathers financial information from external sources.
2. **Fundamental Analyst**: Assesses company fundamentals.
3. **Technical Analyst**: Analyzes market charts and trends.
4. **Report Generator**: Compiles all analyses into an actionable report.

## ⚙️ How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/FelipeFardo/Crew-Ai-Stock-Recommendation-Multi-Agents.git
   cd Crew-Ai-Stock-Recommendation-Multi-Agents
   ```

2. **Install dependencies**:

   Use `pipenv` to install dependencies listed in `Pipfile`

3. **Set up environment variables**:

   Create a `.env` file and include required API keys (OpenAI).

4. **Run the notebook**:

   Open `my-first-crew.ipynb` in Jupyter and follow the instructions to start the analysis.

## 📁 Project Structure

- `my-first-crew.ipynb`: Main notebook with agent definitions and execution flow.
- `Pipfile` / `Pipfile.lock`: Project dependencies.
- `Stocks/`: Directory for stock-related data or scripts.

## 📄 License

This project is licensed under the [MIT License](LICENSE).