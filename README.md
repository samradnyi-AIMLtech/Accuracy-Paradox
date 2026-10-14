## Why a 99% Score Can Be a Total Lie (The Accuracy Paradox)

Imagine you build a system to catch credit card fraud. Out of 1,000 transactions, 990 are totally normal and only 10 are actual fraud. 

If your program gets lazy and just labels **every single transaction as normal**, what score does it get? A staggering **99% Accuracy**! 

Sounds like an amazing result, right? Except for one massive problem: **it caught zero fraud cases.** 

This project is a quick, hands-on Python demonstration showing why standard "accuracy" can completely trick you on uneven datasets, and how other metrics reveal the real truth.

## 🔍 What This Project Shows

* **The Illusion:** A model looks incredible on paper with a 99% score because it guesses the safe, everyday stuff right.
* **The Reality:** When you look closer using a **Confusion Matrix**, you realize it completely failed to find any of the rare, important events you built it for.
* **The Fix:** How to use better tools like Precision, Recall, and F1-Score so you never get fooled by a misleading score again.

## 💡 Breaking Down the Metrices

| Metric | What it actually means | When to care about it |
| :--- | :--- | :--- |
| **Accuracy** | *Out of everything, how many total guesses did we get right?* | Great for balanced data, but dangerous when one group is tiny. |
| **Precision** | *When our model cries "Fraud!", is it actually fraud?* | Use this when false alarms are expensive or annoying. |
| **Recall** | *Out of all the real fraud out there, how much did we actually catch?* | Use this when missing the target is dangerous (like medical tests or security). |
| **F1-Score** | *The ultimate reality check score.* | Combines precision and recall to tell you if the model is genuinely useful. |

