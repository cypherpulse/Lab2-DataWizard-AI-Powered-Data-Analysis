# DataWizard: AI-Powered Data Analysis

[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://langchain.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

## Description

This repository contains a hands-on Jupyter Notebook lab that demonstrates how to build an AI-powered data analysis assistant using LangChain's tool calling feature. The assistant enables natural language interaction for performing essential data science tasks, making data analysis accessible to non-technical users.

## Objectives

After completing this lab, you will be able to:

- Understand and explain the concept of tools in LangChain
- Create custom tools for specific data science tasks
- Build and initialize AI agents that orchestrate multiple tools
- Debug and optimize tool functionality
- Test tool implementations with various inputs and scenarios

## About the Notebook

The notebook, `LLM-Powered Data Science LCEL.ipynb`, guides you through the following:

1. **The Challenge**: Addressing the gap between non-technical users and data analysis.
2. **Tool Development**: Creating LangChain tools for tasks like:
   - Listing available datasets
   - Loading and analyzing CSV files
   - Generating dataset summaries and statistics
   - Training and evaluating machine learning models
3. **Agent Implementation**: Building an executor agent to manage multi-step workflows for data analysis.
4. **Demonstration**: Highlighting the limitations of regular conversational agents with structured data.

By the end of this lab, you'll understand how to combine language models with specialized tools to create practical applications that make data science accessible to everyone.

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Basic knowledge of Python programming
- Familiarity with AI and natural language processing concepts (helpful but not required)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/cypherpulse/AI-Math-Assistant-Tool-Calling-Langchain.git
   cd AI-Math-Assistant-Tool-Calling-Langchain
   ```

2. **Install required libraries:**
   ```bash
   pip install langchain openai jupyter
   ```

   Note: You may need an OpenAI API key for the language model integration. Set it up as per the notebook instructions.

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the notebook file: `AI-Math-Assistant Tool Calling.ipynb`

3. Follow the step-by-step instructions in the notebook to:
   - Set up the language model
   - Create custom mathematical tools
   - Build and test the AI agent
   - Experiment with different queries

## Features

- **Custom Tool Creation:** Learn to build tools for addition, subtraction, multiplication, and exponentiation
- **Agent Orchestration:** See how agents coordinate multiple tools to solve complex problems
- **Natural Language Processing:** Enable conversational math solving
- **LangChain Integration:** Utilize LangChain's powerful framework for AI agents
- **Built-in Tools Exploration:** Discover and use LangChain's pre-built tools (e.g., Wikipedia integration)
- **Interactive Learning:** Hands-on exercises with immediate feedback

## Project Structure

- `AI-Math-Assistant Tool Calling.ipynb`: Main tutorial notebook
- `README.md`: This file with project documentation

## Learning Outcomes

By the end of this lab, learners will have:
- Practical experience with LangChain tool calling
- Understanding of AI agent architecture
- Skills in creating modular, reusable tools
- Ability to debug and improve AI applications
- Knowledge of integrating LLMs with custom functionality

## Contributing

Contributions are welcome! Please feel free to:
- Report issues or bugs
- Suggest improvements
- Submit pull requests for enhancements

## License

This project is based on IBM Skills Network educational content. Please refer to the notebook for specific licensing information.

## Acknowledgments

- IBM Skills Network for the original lab content
- LangChain community for the powerful framework
- OpenAI for language model capabilities