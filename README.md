# AI Safety & Security Dashboard

This Streamlit application showcases key safety and security features from the OpenAI o1 System Card, providing an interactive visualization of safety evaluations, risk assessments, and red teaming results.

## Features

- Interactive dashboard with multiple sections
- Visualizations of safety evaluation results
- Risk assessment overview
- Chain of thought safety analysis
- Red teaming results comparison

## Installation

1. Clone this repository
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Running the App

To run the application, execute:
```bash
streamlit run Home.py
```

The app will open in your default web browser at `http://localhost:8501`.

## Sections

1. **Overview**: General information about the o1 model and its safety features
2. **Safety Evaluations**: Results from various safety tests and evaluations
3. **Preparedness Framework**: Risk assessment across different categories
4. **Chain of Thought Safety**: Analysis of model reasoning and potential deception
5. **Red Teaming Results**: Comparison with GPT-4o and key observations

## Data Source

All data presented in this dashboard is sourced from the OpenAI o1 System Card (December 5, 2024).