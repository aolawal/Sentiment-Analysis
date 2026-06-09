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

<img width="789" height="604" alt="image" src="https://github.com/user-attachments/assets/0eab1215-4d11-4f97-86b3-82180a28f2e3" />

<img width="715" height="550" alt="image" src="https://github.com/user-attachments/assets/ba634578-220b-484b-8f9f-f722094e3bb0" />

<img width="826" height="394" alt="image" src="https://github.com/user-attachments/assets/5564c1f2-89d9-4fec-9248-4342bffe7982" />

<img width="785" height="435" alt="image" src="https://github.com/user-attachments/assets/98ec2f98-fbde-4dd2-b4f7-d6ba08542a9f" />

<img width="905" height="572" alt="image" src="https://github.com/user-attachments/assets/07bd55b8-5ac1-43fa-a226-ed0583aa750a" />

<img width="896" height="143" alt="image" src="https://github.com/user-attachments/assets/02dad6d9-bc28-4959-aff2-3ee185c326f1" />

<img width="920" height="539" alt="image" src="https://github.com/user-attachments/assets/3db71af6-9f00-49a4-90c3-297303ca95b0" />

<img width="905" height="435" alt="image" src="https://github.com/user-attachments/assets/c6990223-7277-4e3e-b019-35466f48326f" />

<img width="854" height="524" alt="image" src="https://github.com/user-attachments/assets/7e312ea8-d7b0-4f9b-908a-3cd2a3ec7905" />

<img width="727" height="614" alt="image" src="https://github.com/user-attachments/assets/fff678ac-63ab-40c1-a3d7-e798f9a0cb4a" />

<img width="794" height="338" alt="image" src="https://github.com/user-attachments/assets/069bb898-ab76-433e-b91c-6e801bbe131e" />

<img width="913" height="352" alt="image" src="https://github.com/user-attachments/assets/ca72f2a6-738b-4cd4-b96d-6af6d161eaa2" />

<img width="758" height="392" alt="image" src="https://github.com/user-attachments/assets/901b7631-c30d-43a2-89cb-aed465ad42f0" />

<img width="925" height="232" alt="image" src="https://github.com/user-attachments/assets/eebe4287-86c2-466e-bf40-c0ded6664d7a" />

<img width="735" height="380" alt="image" src="https://github.com/user-attachments/assets/2074c05f-b3fc-4a94-aed8-11e520709f4b" />

<img width="815" height="385" alt="image" src="https://github.com/user-attachments/assets/88693d24-4f00-4749-a622-9bb0ac3d91ec" />

<img width="766" height="359" alt="image" src="https://github.com/user-attachments/assets/41ca8bfb-fdc4-4daf-ab95-d2994802f31c" />

<img width="939" height="604" alt="image" src="https://github.com/user-attachments/assets/4868bb49-77e3-4989-8702-fd5948fb1d9c" />

<img width="897" height="434" alt="image" src="https://github.com/user-attachments/assets/e6cf157e-5e7a-42ae-8cfe-c626ed330cb9" />

<img width="936" height="566" alt="image" src="https://github.com/user-attachments/assets/d350c0cb-3a32-4460-a551-655580a4564b" />

<img width="902" height="601" alt="image" src="https://github.com/user-attachments/assets/0cc01794-7afa-407b-8fc8-e7a60be3cd99" />

<img width="962" height="460" alt="image" src="https://github.com/user-attachments/assets/4629f6c8-fded-431a-b3a0-fe5f63c78775" />

# Key Insights
- 3 out of the top 5 products with highest positive review ratio had below 100 reviews, while Sennheiser and PTron had 1,879 and 168 reviews. Overall all the company products had an appreciable positive review but they need to work more on customer complaints for the two JBL products.(as displayed above)
- About 70% of the company's total reviews are positive which is a good one but invariably it makes our data distribution bias (Overall Sentiment Distribution chart)
- Overall across all product lines , the company receive more positive reviews on Build Quality aspect, while the least positive reviews come from Fit/feel aspect. While they need to work more on addressing the Fit?feel challenges, they can consiolidate on the positive goodwillof Build Quality aspect. (See Postive Sentiment Distribution chart for detailed analysis)
- Fit/Feel had the highest Postive to Negative Review ratio (See Sentiment Count per Aspect chart)
- The company product review show that it received over 40% 5-star review out of its total rating (Review Star Disribution chart)





























