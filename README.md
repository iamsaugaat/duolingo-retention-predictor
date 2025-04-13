# 🎯 Duolingo User Retention Predictor

This project addresses a real-world challenge Duolingo faces: **predicting whether a user will return tomorrow based on today’s behavior**.

Since Duolingo’s user data isn’t public, I created a synthetic dataset based on app usage patterns and modeled the likelihood of 'next day' return.

## 📊 Features Used
- Days Active
- Average Session Length
- Language Streak Days
- Notifications Received
- Lessons Completed
- Gem Usage
- Watched Ads

## 🧠 Model Used
- **Random Forest Classifier**
- Accuracy: 66%
- Strong predictors: `days_active`, `avg_session_length`, `streak_days`

## 📌 What This Shows
This model can help platforms like Duolingo:
- Prioritize re-engagement campaigns
- Identify users at risk of churn
- Personalize nudges based on behavior patterns

## 📌 Observations
- Users with longer streaks, higher session lengths and more active days are **significantly more likely to return**.
- Passive actions like watching ads or receiving push notifications have **low correlation** with retention.
- A slight class imbalance exists — more users return than churn.

## ✅ Recommendations for Duolingo
- **Enhance streak features:** Promote and reward streaks more aggressively via UI and gamification.
- **Session depth > push volume:** Encourage deeper engagement over more notifications.
- **Target new users carefully:** Users with low `days_active` need personalized onboarding nudges.
- **A/B test gem usage:** Evaluate if gem features could boost daily return for low-engagement users.

## 📈 Results
Below are key visuals from the analysis:
<img width="957" alt="Screenshot 2025-04-13 at 4 43 23 PM" src="https://github.com/user-attachments/assets/cde304fb-49f6-4279-b900-e34e323f0bf7" />


## 🔗 Author
Saugat Pyakuryal  
[GitHub](https://github.com/iamsaugaat) | [LinkedIn](https://www.linkedin.com/in/iamsaugaat/)
