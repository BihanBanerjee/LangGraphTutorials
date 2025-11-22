# LangGraph Tutorial

A comprehensive tutorial series for learning LangGraph, covering everything from basic workflows to advanced conditional logic and real-world applications.

## Overview

This repository contains hands-on Jupyter notebooks that demonstrate various LangGraph concepts and patterns. The tutorials progress from simple installations to complex workflows involving LLMs, prompt chaining, and conditional logic.

## Prerequisites

- Python >= 3.13
- Basic understanding of Python programming
- Familiarity with LLMs (recommended)

## Installation

This project uses `uv` for dependency management. Install dependencies:

```bash
uv sync
```

Alternatively, if you're using pip:

```bash
pip install langchain langchain-openai langgraph dotenv ipykernel
```

## Environment Setup

Create a `.env` file in the root directory with your API keys:

```env
OPENAI_API_KEY=your_openai_api_key_here
```

## Tutorial Structure

The tutorials are organized sequentially, building on concepts from previous lessons:

### 0. [Installation Test](0_test_installation.ipynb)
Verify your LangGraph installation and setup.

### 1. Basic Workflows
- [1.1 BMI Workflow](1.1_bmi_workflow.ipynb) - Create a simple BMI calculator workflow
- [1.2 BMI Workflow with Labels](1.2_bmi_workflow_with_label.ipynb) - Add labels and structure to workflows

### 2. [Simple LLM Workflow](2_simple_llm_workflow.ipynb)
Build your first workflow integrating Large Language Models.

### 3. [Prompt Chaining](3_prompt_chaining.ipynb)
Learn how to chain multiple prompts together for complex tasks.

### 4. [Prompt Chaining with Evaluation Metrics](4_prompt_chaining_evaluation_metric.ipynb)
Add evaluation metrics to measure workflow performance.

### 5. [Batsman Workflow](5_batsman_workflow_||workflow.ipynb)
Explore parallel workflow patterns.

### 6. [UPSC Essay Workflow](6_UPSC_essay_workflow.ipynb)
Build a complex essay generation workflow.

### 7. [Quadratic Equation - Conditional Workflow](7_Quadratic_Equation_Workflow_Conditional_Workflow.ipynb)
Implement conditional logic in your workflows.

### 8. [Review Reply Workflow](8_review_reply_workflow.ipynb)
Create automated review response systems.

### 9. [X Post Generator](9_X_post_generator.ipynb)
Generate social media content using LangGraph workflows.

### 10. [Basic Chatbot](10_basic_chatbot.ipynb)
Build a basic chatbot with conversational state management.

## Key Concepts Covered

- **StateGraph**: Building stateful workflow graphs
- **Node Creation**: Defining workflow nodes and their functions
- **Edge Configuration**: Connecting nodes with edges
- **Conditional Routing**: Implementing branching logic
- **Prompt Chaining**: Sequencing multiple LLM calls
- **Evaluation Metrics**: Measuring workflow performance
- **Parallel Workflows**: Running multiple paths simultaneously

## Usage

Launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Open any tutorial notebook and follow the instructions inside. Start with [0_test_installation.ipynb](0_test_installation.ipynb) to verify your setup.

## Project Structure

```
LangGraphTutorial/
├── 0_test_installation.ipynb
├── 1.1_bmi_workflow.ipynb
├── 1.2_bmi_workflow_with_label.ipynb
├── 2_simple_llm_workflow.ipynb
├── 3_prompt_chaining.ipynb
├── 4_prompt_chaining_evaluation_metric.ipynb
├── 5_batsman_workflow_||workflow.ipynb
├── 6_UPSC_essay_workflow.ipynb
├── 7_Quadratic_Equation_Workflow_Conditional_Workflow.ipynb
├── 8_review_reply_workflow.ipynb
├── 9_X_post_generator.ipynb
├── 10_basic_chatbot.ipynb
├── main.py
├── pyproject.toml
├── uv.lock
└── README.md
```

## Dependencies

- **langgraph** (>=1.0.3) - Framework for building stateful workflows
- **langchain** (>=1.0.8) - LLM application framework
- **langchain-openai** (>=1.0.3) - OpenAI integration for LangChain
- **python-dotenv** (>=0.9.9) - Environment variable management
- **ipykernel** (>=7.1.0) - Jupyter kernel

## Learning Path

1. Start with the installation test to ensure everything works
2. Follow the numbered tutorials in sequence
3. Experiment with the code examples
4. Try modifying workflows to solve your own problems

## Resources

- [LangGraph Documentation](https://python.langchain.com/docs/langgraph)
- [LangChain Documentation](https://python.langchain.com/)
- [OpenAI API Documentation](https://platform.openai.com/docs)

## License

This project is for educational purposes.

## Contributing

Feel free to open issues or submit pull requests for improvements to the tutorials.
