# CHATGPT-Analysis
This project analyzes user reviews of the ChatGPT app to uncover patterns in user satisfaction, sentiment trends, and common complaints. It combines data cleaning, exploratory analysis, sentiment analysis, and visualization using Python.
 
 Project Structure

 📦 chatgpt-review-analysis/
├── chatgpt_reviews.csv      
├── review_analysis.ipynb     
├── sentiment_analysis.py     
├── plots/                    
└── README.md 

Features
✅ Clean and preprocess review text
📈 Analyze ratings and sentiment over time
🕒 Track user sentiment by hour of day
😠 Detect most common problems in negative reviews
🌥️ Generate word clouds for quick keyword spotting
📉 Identify time periods with low sentiment or ratings

Technologies Used
Pandas – data manipulation
Matplotlib / Seaborn – visualization
TextBlob – sentiment analysis
WordCloud – for visual keyword representation
Regex – emoji and noise removal

Key Insights
Most users rate the app 5 stars, with consistently high sentiment.
Negative reviews highlight issues like app crashes, lag, and subscription confusion.
Positive reviews are common in the evening, suggesting peak engagement times.
Text-based sentiment aligns well with star ratings.
