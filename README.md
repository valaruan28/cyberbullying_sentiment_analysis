# 🚨 Cyberbullying Sentiment Analysis using LLM (Granite-3B)

## 📌 Project Overview

This project aims to explore, analyze, and extract insights from a cyberbullying dataset using a combination of Exploratory Data Analysis (EDA) and Large Language Model (LLM)-based sentiment and content interpretation. The primary goal is to understand the patterns, emotional tone, and potential harm present in tweets labeled with different cyberbullying types.

The project uses IBM's `granite-3.3-8b-instruct` model hosted on Replicate for intelligent text analysis and sentiment-based insights, going beyond traditional statistical methods.

---

## 📂 Raw Dataset

- Dataset: Annotated tweet samples labeled with 6 cyberbullying categories.
- Columns:
  - `tweet_text`: The tweet content.
  - `cyberbullying_type`: One of the following labels:
    - `not_cyberbullying`
    - `gender`
    - `religion`
    - `age`
    - `ethnicity`
    - `other_cyberbullying`

🔗 Dataset: https://drive.google.com/file/d/1_-G53_wKswJ4IxsHnnneH8IK_l3GLRnN/view?usp=drive_link

---

## 📊 Insight & Findings

1. **Distribution of Bullying Types**:
   - Most common types: Religion, Age, and Gender-based bullying.
   - Least represented: Other cyberbullying.

2. **Emotional Tone**:
   - Ethnicity and religion categories contained the most aggressive and emotionally harmful language.
   - Gender-related tweets often used sarcasm or objectification.

3. **Linguistic Patterns**:
   - Age bullying often used infantilizing or dismissive tones.
   - Ethnicity bullying included direct slurs and dehumanizing metaphors.
   - Notable presence of veiled insults and coded language, particularly in gender and religion categories.

4. **Societal Implications**:
   - Tweets reflect underlying societal biases, discrimination, and normalization of certain stereotypes.
   - Suggests the need for stronger content moderation and public awareness.

---

## 🤖 AI Support Explanation

This project utilizes the [`ibm-granite/granite-3.3-8b-instruct`](https://replicate.com/ibm-granite/granite-3.3-8b-instruct) LLM hosted on Replicate to derive deep, contextual insights from the tweet texts.

LLM capabilities include:
- Classifying sentiment (Positive, Negative, Neutral).
- Summarizing patterns in hate speech and harassment.
- Highlighting implicit bullying, sarcasm, and coded language.
- Explaining emotional tone and psychological risk.

Prompt engineering was used to generate structured questions for the model, and the model outputs were integrated back into the analysis workflow.

---

## 🛠️ Technologies Used

- Python (Pandas, Seaborn, Matplotlib)
- Replicate API
- IBM Granite 3.3B Instruct LLM
- Jupyter Notebook / Google Colab

