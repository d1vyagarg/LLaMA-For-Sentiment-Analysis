# LLaMA-For-Sentiment-Analysis

Sentiment analysis on financial and economic information is very important for many market decisions ranging from market insights, risk management and investment decisions.

Here , we are using LLaMA from meta to analyse the sentiment given some financial statements captured from news headlines.

First, we have used LLaMA from hugging face as it is which is trained on a very large corpse available but we see that performance is not good on this financial data.

Then we fine-tune this model based on our training data. Now model is performing really good.

To fine tune such a large model on our machine, we have used PEFT(Parameter Efficient Fine Tuning) which operates on reduced no of parameters thereby reducing 
computational and storage expenses.

