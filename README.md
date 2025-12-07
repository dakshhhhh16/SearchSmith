# SearchSmith
See how the world searches for your brand.

## Goal
- Make it easy for a non-technical person to understand their website’s search performance.
- Combine raw numbers + charts with AI-written explanations (brand summary, chart analysis).

## Installation
1. Clone the repository
```bash
git clone https://github.com/suryanshgupta9933/unilytics.git
cd unilytics
```
2. Install the dependencies
```bash
pip install -r requirements.txt
```
3. Rename the `.env.example` file to `.env` and add your OpenAI API key.
4. Run the app
```bash
streamlit run app.py
```

## Features
- **Brand Analysis**: LLM-generated summary of your brand using landing page data.
- **Global Traffic**: Clicks, impressions, and CTR for your site globally.
- **Top 10 Countries**: Table of the countries that love your brand the most.
- **Branded Traffic**: Clicks, impressions, and CTR for branded queries.
- **Charts**:
    - Average CTR by position.
    - Click variance over time.

## Screenshots
