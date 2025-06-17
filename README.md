# AI Safety & Security Dashboard

This Streamlit application showcases key safety and security features from the OpenAI o1 System Card, providing an interactive visualization of safety evaluations, risk assessments, and red teaming results. The dashboard also includes real-time prompt testing capabilities to evaluate model safety responses.

## Features

- Interactive dashboard with multiple sections
- Visualizations of safety evaluation results
- Risk assessment overview
- Chain of thought safety analysis
- Red teaming results comparison
- Real-time prompt testing with multiple models
- Safety metrics and analysis
- API key management
- Sample prompts for safety evaluation

## Installation

1. Clone this repository
2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Configuration

1. Obtain an OpenAI API key from [OpenAI Platform](https://platform.openai.com)
2. Launch the application
3. Enter your API key in the sidebar configuration
4. Select your preferred model for testing

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
6. **Prompt Testing**: Interactive testing of model responses with safety metrics

## Prompt Testing Features

- **Model Selection**:
  - GPT-4
  - GPT-3.5 Turbo
  - Claude 3 Opus
  - Claude 3 Sonnet

- **Prompt Categories**:
  - Safe Prompts (general knowledge, technical questions, etc.)
  - Potentially Unsafe Prompts (for safety testing)

- **Safety Metrics**:
  - Response length
  - Response time
  - Safety score
  - Model performance analysis

## Safety Guidelines

The application follows these safety categories:
1. Content Safety
2. Privacy Protection
3. Ethical Guidelines
4. Legal Compliance

## Data Source

All data presented in this dashboard is sourced from the OpenAI o1 System Card (December 5, 2024).

## Security Note

- API keys are stored in session state and are not persisted
- All API calls are made securely through the OpenAI API
- No sensitive data is stored or logged