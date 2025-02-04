# Predicting Social Media Engagement: Analyzing Instagram Data from Tatte Cafe

In today's digital era, understanding what drives engagement on social media platforms like Instagram is crucial for businesses and 

influencers. In this project, we built a Social Media Engagement Predictor using data scraped from Tatte Cafe's Instagram page, leveraging

data preprocessing, sentiment analysis, and machine learning techniques.

**Step 1: Scraping and Preprocessing the Data**

We used InstaLoader to collect Instagram posts from Tatte Cafe, capturing key engagement metrics such as:

***Average Likes by Day of the Week***

<img width="804" alt="Screenshot 2025-02-03 at 10 48 06 PM" src="https://github.com/user-attachments/assets/4c132aba-0caa-4449-bf10-b366b4b7b504" />

***Average Likes by Hour***

<img width="769" alt="Screenshot 2025-02-03 at 10 49 29 PM" src="https://github.com/user-attachments/assets/eb453c5b-37e4-4ad1-bec6-30aace308bb9" />

***Top 10 Hashtags by Frequency***

<img width="844" alt="Screenshot 2025-02-03 at 10 49 49 PM" src="https://github.com/user-attachments/assets/027f1559-fe03-4d37-86b6-114d1fe2fc57" />


After cleaning the dataset, we engineered new features like hashtag count and post type (sidecar or not) to enhance predictive power.

**Step 2: Sentiment Analysis with VADER**

To assess the emotional tone of post captions, we employed VADER (Valence Aware Dictionary and sEntiment Reasoner). The sentiment scores

were classified as Positive, Negative, or Neutral, and their distribution was visualized using a bar chart.

<img width="631" alt="Screenshot 2025-02-03 at 10 56 17 PM" src="https://github.com/user-attachments/assets/196f5d57-2eca-4073-91a5-ce94d015feb1" />

**Step 3: Predicting Engagement with Machine Learning**

Using a Random Forest Regressor, we trained a model to predict the number of likes based on features such as:

✅ Posting hour

✅ Sidecar media count

✅ Comments count

✅ Hashtag count

✅ Day of the week

**Results & Insights**

The model was evaluated using Mean Squared Error (MSE) and R² Score, which indicated a strong predictive performance. These insights can help businesses optimize their social media strategy, such as:
📅 Best Days to Post – Identify high-engagement days.
⏰ Optimal Posting Time – Schedule posts when engagement is highest.
🔍 Hashtag Strategy – Utilize effective hashtags for visibility.

<img width="409" alt="Screenshot 2025-02-03 at 10 56 56 PM" src="https://github.com/user-attachments/assets/639efb39-2aab-4bf9-9db0-19ebc1c5e2b8" />

**Final Thoughts**
By combining sentiment analysis and machine learning, we successfully created a data-driven approach to predict Instagram engagement. This methodology can be expanded to other brands, influencers, and industries seeking to maximize their social media impact.

Let’s keep leveraging data to make smarter marketing decisions! 🚀
