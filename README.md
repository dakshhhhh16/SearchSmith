# SearchSmith
See how the world searches for your brand.

## Goal
- Make it easy for a non-technical person to understand their website’s search performance.
- Combine raw numbers + charts with AI-written explanations (brand summary, chart analysis).

## Installation
1. Clone the repository
```bash
git clone https://github.com/dakshhhhh16/SearchSmith.git
cd SearchSmith
```
2. Install the dependencies
```bash
pip install -r requirements.txt
```
3. Rename the `.env.example` file to `.env` and add your Google Gemini API key.
4. Run the app
```bash
streamlit run app.py
```

## How to Use

**Step 1: Get Your Data**
- Go to [Google Search Console](https://search.google.com/search-console)
- Select your website property
- Click **Performance** in the left sidebar
- Click **Export** (top right) → **Download Excel (.xlsx)**
- Make sure you're exporting data with **Queries**, **Pages**, and **Countries** tabs

**Step 2: Upload to SearchSmith**
- On the left sidebar, click **"Browse files"** or drag your `.xlsx` file into the upload area
- Click the **"Upload"** button

**Step 3: View Your Insights**

Once uploaded, SearchSmith will automatically generate:

1. **Brand Analysis** - AI summary of your brand based on your landing page content
2. **Global Traffic** - Total clicks, impressions, and click-through rate (CTR)
3. **Top 10 Countries** - Table showing which countries drive the most traffic
4. **Branded Traffic** - Metrics specifically for searches containing your brand name
5. **Charts with AI Analysis**:
   - **Average CTR by Position** - How your click rate varies by search ranking
   - **Click Variance** - Traffic trends over time

All sections are expandable/collapsible. The AI (powered by Gemini) provides context and explanations for each metric to help non-technical users understand their search performance.

## Features
- **Brand Analysis**: LLM-generated summary of your brand using landing page data.
- **Global Traffic**: Clicks, impressions, and CTR for your site globally.
- **Top 10 Countries**: Table of the countries that love your brand the most.
- **Branded Traffic**: Clicks, impressions, and CTR for branded queries.
- **Charts**:
    - Average CTR by position.
    - Click variance over time.

## Screenshots

![Screenshot 1](assets/img1.png)
![Screenshot 2](assets/img2.png)
