

# MaWorkflow

This project is an AI-powered solution that generates Python scripts through the collaboration of AI agents. These agents work in unison to break down tasks, write code, review and refactor, ensuring the resulting scripts are efficient, well-documented, and capable of producing real profits.

## Project Overview
![Screenshot 2024-07-01 184935](https://github.com/Noble-mungu/MaWorkflow/assets/64100418/e13438ac-59c1-45aa-8d56-caf1bda3cbe6)

The Agentic Workflow project consists of the following key components:

- `agentic.py`: The main script that orchestrates the collaboration between AI agents.
- `agent_functions.py`: Contains utility functions used by the agents during the workflow.
- `code_execution_manager.py`: Manages code execution, testing, optimization, and documentation generation.
- `browser_tools.py`: Provides tools for web browser interaction and web scraping.
- `crypto_wallet.py`: Implements a cryptocurrency wallet for handling transactions.
- `task_manager.py`: Manages and tracks tasks assigned to the agents.
- `system_messages/`: Contains system messages that guide the behavior of each agent.

## Getting Started

To run the Agentic Workflow project, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Noble-mungu/MaWorkflow.git
   ```

2. Navigate to the project directory:
   ```
   cd MaWorkflow
   ```

3. Install the required dependencies:
   ```
   pip install langchain langchain_groq spacy requests beautifulsoup4 selenium webdriver_manager pytest pylint black bitcoinlib
   ```

4. Run the `agentic.py` script:
   ```
   python agentic.py
   ```

The script will initiate the collaboration between the AI agents, and you can monitor the progress and generated code in the console output.

## AI Agents

The Agentic Workflow project involves the following AI agents:

- **Bob (Project Manager Extraordinaire)**: Leads the team, breaks down the project into manageable tasks, and assigns them to the other agents. Bob ensures the project stays on track and meets its goals.

- **Mike (AI Software Architect and Engineer)**: Responsible for code analysis, feature development, algorithm design, and code quality assurance. Mike infuses the project with cutting-edge AI capabilities.

- **Annie (Senior Agentic Workflow Developer)**: Focuses on user interface design, workflow optimization, error handling, and cross-platform compatibility. Annie creates intuitive and efficient workflows.

- **Alex (DevOps Engineer Mastermind)**: Handles environment setup, code execution, testing, deployment, and maintenance. Alex ensures the project runs smoothly and efficiently.

## JSON Tools

The agents utilize JSON tools to automate tasks, gather information, and enhance the agentic workflow solution. Some of the key JSON tools include:

- `search_google`: Searches Google for relevant information.
- `scrape_page`: Scrapes a web page for relevant information.
- `test_code`: Tests the provided code.
- `optimize_code`: Optimizes the provided code and offers suggestions.
- `generate_documentation`: Generates documentation for the provided code.
- `execute_browser_command`: Executes a browser command for web interaction.

Agents can invoke these tools using specific JSON formats within their responses.


