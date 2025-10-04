# 🎓 Ethesis - MD Thesis Analysis Dashboard

A professional Gradio-based dashboard for comprehensive MD thesis analysis using AI-powered expert evaluation and strategic insights.

## Features

- **Expert Panel Evaluation**: Three specialized evaluators with distinct perspectives
  - **Dr. Sarah Williams** (Medical College Professor) - Educational focus
  - **Dr. Michael Chen** (Renowned Researcher) - Scientific rigor focus  
  - **Dr. Jennifer Martinez** (Industry Professional) - Practical application focus
- **Chief Guide Strategic Analysis**: Meta-analysis of expert feedback with actionable insights
- **Professional Dashboard Interface**: Modern, tabular presentation with clean formatting
- **AI-Powered Analysis**: Uses advanced AI for comprehensive evaluation
- **Strategic Recommendations**: Immediate priorities and medium-term development plans
- **Defense Preparation Strategy**: Readiness assessment and preparation areas

## Expert Evaluation Criteria

The system evaluates theses on these 10 criteria:

1. **Originality and Contribution**
2. **Research Question and Objectives**
3. **Literature Review**
4. **Methodology and Study Design**
5. **Results and Data Analysis**
6. **Discussion and Interpretation**
7. **Ethical and Regulatory Compliance**
8. **Structure, Organization, and Presentation**
9. **Writing Quality and Scholarly Tone**
10. **Overall Impact and Defense Readiness**

## Analysis Output

The dashboard provides:

- **Expert Consensus Analysis**: Points of agreement and disagreement
- **Strategic Recommendations**: Prioritized action items with timelines
- **Defense Preparation**: Readiness assessment and key preparation areas
- **Quality Metrics**: Comprehensive scoring and assessment tables
- **Technical Insights**: Specific recommendations based on expert feedback

## Setup

1. **Activate the virtual environment:**
   ```bash
   source /home/psingh/medgemma/medgemma_env/bin/activate
   ```

2. **Install dependencies:**
   ```bash
   cd /home/psingh/medgemma/Ethesis
   pip install -r requirements.txt
   ```

3. **Set up OpenAI API key:**
   Create a `.env` file in the project root with your API key:
   ```bash
   echo 'OPENAI_API_KEY=your-api-key-here' > .env
   ```

## Usage

1. **Run the application:**
   ```bash
   python src/app.py
   ```

2. **Access the dashboard:**
   - Open your browser and go to `http://localhost:7860`
   - Click "Generate Strategic Analysis" to get comprehensive evaluation
   - View the professional dashboard with expert analysis and strategic insights

## Dashboard Features

- **Expert Panel Overview**: See all three evaluators and their focus areas
- **One-Click Analysis**: Generate complete evaluation with single button click
- **Professional Formatting**: Clean, tabular presentation of results
- **Strategic Insights**: Actionable recommendations with priorities and timelines
- **Defense Readiness**: Comprehensive preparation strategy and assessment

## Requirements

- Python 3.8+
- OpenAI API key
- Internet connection for AI model access

## Project Structure

```
Ethesis/
├── src/
│   └── app.py          # Main Gradio dashboard application
├── requirements.txt    # Python dependencies
├── setup.sh           # Setup script
├── .env               # Environment variables (API key)
└── README.md          # This file
```

## Technical Details

- **Framework**: Gradio 4.0+ with custom CSS styling
- **AI Integration**: Advanced AI models for comprehensive analysis
- **Interface**: Professional dashboard with gradient styling and card-based layout
- **Output Format**: Structured analysis with tables and clear section separation
- **Configuration**: Environment-based API key management via `.env` file