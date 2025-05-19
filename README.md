# Public Sentiment Analysis on Rwanda's Distance-Based Fare Pricing

## 🚀 Project Overview
This project analyzes public sentiment on Rwanda's newly introduced distance-based fare pricing model for public transport. By examining social media comments, I extracted key themes and categorized user feedback into positive, negative, and neutral sentiments.

## 📂 Project Structure
- `Executive_Summary.md` — Detailed executive summary with insights and recommendations  
- `Dataset` — Raw and processed data used for the analysis  
- `Python Scripts` — Python scripts for data preprocessing, sentiment analysis, and visualization  
- `Results` — Outputs including word clouds, sentiment scores, and dashboard  
- `PowerBI_Dashboard.pbix` — Interactive Power BI dashboard visualizing the results  

## 📝 Key Insights
- Majority of users expressed positive sentiments regarding fair pricing and service improvements.  
- Negative comments focused on technical issues, overcrowding, and regional disparities.  
- Neutral comments included inquiries and clarifications about system functionality.  

## 🚀 Models Used
- **TextBlob:** Rule-based sentiment analysis  
- **VADER (from NLTK):** Fine-tuned for social media text  
- **Theme Clustering:** Identified key discussion themes via text clustering  

## 🧪 Methodology & Challenges
- Initially attempted to use X API to fetch tweets directly but exceeded the free plan limit (100 tweets/month) very early.  
- Scraped blogs and news but found limited public interaction on this topic.  
- Final dataset consists of 128 unique replies to two posts (in Kinyarwanda and English) by RURA from early December 2024 announcing the pilot pricing scheme.  
- Power BI requires a premium subscription to share dashboards publicly; thus, only a PDF version of the dashboard is provided alongside the Power BI project file.  

## 💡 How to Use
1. Clone the repository:
    ```bash
    git clone [repository_link]
    ```
2. Set up your Python environment:
    ```bash
    pip install -r requirements.txt
    ```
3. Download or Run scripts in the `rwanda_ict_chamber_hackathon` folder for data preprocessing, sentiment analysis, and theme clustering.  
4. Explore the Power BI dashboard or the provided PDF for interactive insights.  

## ⚡ Results Visualization
- Interactive Power BI dashboard showing sentiment distribution, theme clusters, and trends.  
- Word cloud highlighting key themes in user comments.  

## 📌 Contributions
- Please open issues for bugs or improvement suggestions.  
- Contributions are welcome! Fork and submit pull requests.  

## ⚖️ License
This project is licensed under the MIT License.
