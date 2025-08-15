# 🎢 Disneyland Review Analysis with IBM Granite

## 📝 Project Overview
  This project aims to perform sentiment analysis on Disneyland visitor reviews using the IBM Granite model. The reviews are classified into three main categories: Positive, Neutral, and Negative. The analysis helps to understand visitors' perceptions of their Disneyland experiences, providing valuable insights to improve services and enhance the park’s appeal.

## 🔗 Raw Dataset Link

**Dataset Source:** [Disneyland Reviews on Kaggle](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews)
[Disneyland Reviews Dataset (Kaggle)](https://www.kaggle.com/datasets/erikvdven/disneyland-reviews)
  The dataset contains 1,000 analyzed reviews as a sample from a larger collection of Disneyland reviews. It covers reviews from 2009 to 2019 across three Disneyland locations such as California, Paris, and Hong Kong. Each review includes a star rating (1–5) and a written comment, with contributions from visitors around the world, including the United States, Australia, Malta, and Canada.

## 💡 Insights & Findings

  Based on the analysis of 1,000 Disneyland reviews, the overall sentiment health is very high with 74.9% positive reviews, 22.8% negative reviews, and 2.3% neutral reviews, resulting in an average satisfaction rating of 4.2/5.0. In terms of rating distribution, 52.1% of all reviews gave a perfect 5-star rating, followed by 26.8% giving 4 stars. Mid-range 3-star ratings accounted for 11.3%, while 2 stars and 1 star made up 5.5% and 4.3% respectively. This shows a clear skew towards high satisfaction, although there is still a notable portion of unhappy visitors. Branch performance analysis revealed Disneyland Hong Kong as the best-performing park with 81.0% positive reviews, followed by Disneyland California at 77.7%, and Disneyland Paris at 66.9%, indicating room for improvement in the Paris branch. Looking at visitor origins, the Top 5 most satisfied countries — Belgium, Cayman Islands, Cyprus, Egypt, and Estonia — all recorded 100% positive reviews.

  Thematic analysis of review content showed that positive reviews often mentioned keywords like "Reviewer" (927 mentions), "Disneyland" (634 mentions), "Experience" (427 mentions), "Rides" (342 mentions), and "Despite" (326 mentions). On the other hand, negative reviews commonly featured "Reviewer" (311 mentions), "Disneyland" (230 mentions), "Rides" (135 mentions), "Experience" (133 mentions), and "Expresses" (120 mentions), suggesting that even satisfied visitors still discuss common themes, but with different sentiment contexts.
  <img width="1590" height="1190" alt="image" src="https://github.com/user-attachments/assets/90cc090a-2fb1-4a0c-9fe0-cbc6a3a93366" />


## 🤖 AI Support Explanation

### 🧠 How AI Help

This project uses **IBM Granite**, a Natural Language Processing (NLP) model, to perform sentiment classification.

Steps:

**1. Data Preprocessing**

- Clean text from unnecessary symbols and characters.
- Normalize text to a consistent format.

**2. Prompt Engineering**

- Design specific prompts for IBM Granite to classify reviews into Positive, Neutral, or Negative.

**3. Model Inference**

- Use the IBM Granite API to process each review.

**4. Result Analysis**

- Collect classification results.
- Visualize sentiment distribution.
---

*This project shows how AI can help businesses understand their customers better and make smarter decisions to improve everyone's experience!*
