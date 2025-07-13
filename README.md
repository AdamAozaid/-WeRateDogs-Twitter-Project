# 🐶 WeRateDogs Twitter Data Analysis with Python

This is a full end-to-end data analysis project exploring the popular [WeRateDogs](https://twitter.com/dog_rates) Twitter account. I scraped and analyzed real Twitter data to discover trends in dog ratings, breed popularity, and user engagement.

---

## 📌 Objective

To collect, clean, analyze, and visualize data from the WeRateDogs Twitter account and uncover insights into:
- Dog breed popularity
- Rating trends over time
- Correlation between ratings and retweets/favorites
- Tweet characteristics that drive engagement

---

## 🗃️ Dataset Overview

This project uses **three datasets**, but **I scraped one of them** using Twitter API v2.

1. **twitter_archive_enhanced.csv**  
   - Contains 2356 tweets from @dog_rates, including text, timestamp, dog name, and rating.

2. **image_predictions.csv**  
   - Contains the output from a neural network predicting dog breeds from attached images.

3. **tweet_json.txt** *(scraped by me)*  
   - Contains additional tweet data including retweet count, favorite count, and engagement metadata. Scraped using Tweepy and Twitter API.

---

## 🧹 Data Wrangling

The data cleaning process involved:
- Merging datasets into a **master dataframe**
- Fixing inconsistent dog names (e.g. “a”, “the”)
- Standardizing rating formats
- Removing retweets and replies
- Extracting useful variables (like timestamp, source, breed, etc.)

---

## 📊 Key Findings

- **Golden Retrievers** were the most commonly rated breed.
- Most dogs receive a rating **greater than 10/10** – because they’re good dogs.
- Tweets with **higher ratings** tended to get more favorites and retweets.
- The most engaging tweets had **funny captions**, **good lighting in images**, or featured **puppies**.

---

## 📈 Visualizations

I used **Matplotlib**, **Seaborn**, and **Plotly** to visualize:
- Rating distributions
- Top breeds by frequency
- Favorite count vs rating
- Timeline of tweet activity

---

## 📦 Tools & Technologies

- `Python`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`, `Plotly`
- `Tweepy` for scraping
- `Jupyter Notebook`

---

## 🚀 Highlights

✅ Hands-on data scraping with Twitter API  
✅ Full cleaning & tidying workflow  
✅ Insightful visual storytelling  
✅ Portfolio-quality project with real-world data  

---

## 📁 Repository Structure

🐕 WeRateDogs Twitter Project/
│
├── DataSets/
│ ├── twitter_archive_enhanced.csv
│ ├── image_predictions.csv
│ └── tweet_json.txt
│
├── Notebook/
│ └── WeRateDogs Twitter Project.ipynb
│
├── Reports/
│ └── Summary Report.html
│
└── README.md