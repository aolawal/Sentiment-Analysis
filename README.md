# Sentiment-Analysis

The goal of this project is to perform sentiment analysis on product reviews to evaluate customer satisfaction across three key categories: Please use the review body column.

Relevant sentences will be extracted from the review dataset that mention these aspects and classify them into sentiment using VADER.: Customer reviews often contain insights on various aspects of a product.

This project focuses on analyzing sentiments surrounding: – How well the product fits or feels when in use (headphones, earbuds, wearables, etc.). – Overall build quality, durability, and performance of the product. – Customer experiences related to product charging, battery performance, or charger issues.

Sentences containing specific keywords will be extracted and analyzed to identify sentiment patterns and areas where the product excels or needs improvement.

Project Tasks:
- Load the product review dataset.
- Filter reviews based on keywords linked to each category:

-fit, fitting, comfortable, tight, loose, wearable

-quality, durable, broken, sturdy, damage, build

-charge, charging, charged, charger, battery, power
For each category, sentences will be extracted from reviews that contain the relevant keywords.

- Ensure that partial matches (like "charging" or "charged") are captured.
- Use VADER (Valence Aware Dictionary and sEntiment Reasoner) to perform sentiment analysis on the extracted sentences.
- Classify the sentences as: (compound score > 0.05) (compound score between -0.05 and 0.05) (compound score < -0.05)
- Plot sentiment distributions for each category (Fit, Quality, Charging) using bar charts.
- Summarize the overall sentiment trends for each category and highlight areas with predominantly negative feedback.
- Extract relevant sentences based on category keywords.
- Apply VADER sentiment analysis to classify sentiment.
- Visualize sentiment distributions across categories.
- A short text summarizing the sentiment analysis results and key insights.

<img width="835" height="394" alt="image" src="https://github.com/user-attachments/assets/7846ddf0-6e5d-4f0d-b3c9-09b076973640" />

<img width="831" height="583" alt="image" src="https://github.com/user-attachments/assets/6a3ea947-da04-4ee6-9469-a269838e4634" />

<img width="811" height="356" alt="image" src="https://github.com/user-attachments/assets/dad37da3-7bbc-4a90-ab0b-dbc9023d827f" />

<img width="676" height="407" alt="image" src="https://github.com/user-attachments/assets/d6892b40-721b-4059-a8f4-285b632d96a1" />





