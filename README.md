# Project review sentiment classification and summarization
This project is part of the Hacktiv8 X SkillBuild capstone challenge. The goal is to clasiffy reviews based on sentiment and generate a consice summary using IBM Granite via Replicate API
# Project goals
Classify produk reviews as positive, neutral, or negative. Generate one-sentence summaries using IBM Granite LLM. Identify patterns and insights from customer reviews
# Dataset
Source : https://www.kaggle.com/datasets/mansithummar67/171k-product-review-with-sentiment-dataset. File used : Equal.csv. Sampled 20 reviews for summarization to reduce API cost
# Tools used
Google Colab (Phyton). pandas, replicate, time. IBM Granite model via Replicate API. Equal.csv for input, summarized_reviews.csv as output
# How to run
Clone this repo. Open notebook/final_project.ipynb in Google Colab. Insert your Replicate API Token. Run all cells
# Sample output
[60299] Sentiment: negative
|Original Review: Very poor...|
|Summary: The product review indicates an extremely negative opinion, with the user expressing extreme dissatisfaction.|,
[28847] Sentiment: neutral
|Original Review: worth the money...|
|Summary: The product offers good value for its price, making it a worthwhile investment.|
# Limitations
Some reviews with corrupted characters produced unrelated summaries. Rate limiting from Replicate API may delay batch processing
# Conclusion
LLM models like IBM Granite are capable of condensing unstuctured product reviews into consice summaries, which can help business gan quick insight to customer satisfaction
