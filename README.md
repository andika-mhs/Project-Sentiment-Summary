# Project review sentiment classification and summarization
This project is part of the Hacktiv8 X SkillBuild capstone challenge. The goal is to clasiffy reviews based on sentiment and generate a consice summary using IBM Granite via Replicate API
# Project goals
Classify produk reviews as positive, neutral, or negative. Generate one-sentence summaries using IBM Granite LLM. Identify patterns and insights from customer reviews
# Dataset
Source : https://www.kaggle.com/datasets/mansithummar67/171k-product-review-with-sentiment-dataset. File used : sentiment.csv. Sampled 20 reviews for summarization to reduce API cost
# Tools used
Google Colab (Phyton). IBM Granite model via Replicate API. sentiment.csv for input, summarized_reviews as output
# How to run
Clone this repo. Open notebook/final_project.ipynb in Google Colab. Insert your Replicate API Token. Run all cells
# Sample output
|Sentiment: Positive|Summary:  This product is highly praised , described as "perfect"|, |Sentiment: neutral|Summary: The product, while functional, has  a few design flaws and lack s some advanced features that are present  in competitors, resulting in a  moderate rating|, |sentiment: Negative|Summary: The product is satisfactory but  lacks exceptional features to stand  out significantly|
# Limitations
Some reviews with corrupted characters produced unrelated summaries. Rate limiting from Replicate API may delay batch processing
# Conclusion
LLM models like IBM Granite are capable of condensing unstuctured product reviews into consice summaries, which can help business gan quick insight to customer satisfaction
