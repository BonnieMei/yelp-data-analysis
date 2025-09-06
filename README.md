# Yelp Data Analysis Project

Based on the Yelp open datasets, this project uses SQL + Python for data cleaning, statistical analysis, and visualization.
The goal is to explore business ratings, user behaviors, review sentiments, and user network patterns within the Yelp community.

## Tech Stack

- MySQL (SQL-based data cleaning and statistical queries)
- Python (pandas, seaborn, matplotlib, folium, textblob, networkx)

## Project Files

- SQL Report: [yelp_data_analysis.pdf](./yelp_data_analysis.pdf)
- Python Notebook: [yelp_report.ipynb](./yelp_report.ipynb)
  - [Open in Google Colab](https://colab.research.google.com/github/xxbuxx/yelp-data-analysis/blob/main/yelp_report.ipynb)
- Tableau Dashboard: [View Here](https://public.tableau.com/views/Yelp_business_analysis/Dashboard1?:language=zh-CN&:sid=&:redirect=auth&publish=yes&showOnboarding=true&:display_count=n&:origin=viz_share_link)
  
## Key Insights
- **User Behavior**
  - Most users wrote ≤2 reviews, while *Elite* users contributed disproportionately more.  
  - Longer reviews are more likely to be marked as *useful*.  

- **Business Analysis**
  - Most businesses fall in the 3.5–4.0 star range.  
  - 5-star businesses are abundant but may reflect platform promotion bias.  
  - Las Vegas & Phoenix dominate review counts, making them Yelp’s core markets.  

- **Review Sentiment**
  - Overall reviews skew positive, especially among Elite users.  
  - Negative reviews tend to receive more *useful* votes (people find complaints more informative).  
  - Positive reviews feature words like *great, love, good*; negative ones highlight *bad, horrible, worst*.  

- **User Network**
  - Yelp’s user-friend network is sparse, but a small set of core users (influencers) drive engagement.  

## How to Run Locally
1. Clone this repo:
   ```bash
   git clone https://github.com/xxbuxx/yelp-data-analysis.git
2. Install dependencies:
   ```bash
   pip install pandas seaborn matplotlib folium textblob wordcloud networkx python-louvain
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook yelp_report.ipynb
