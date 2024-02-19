# Keyword Classifier

## 💬 About:
- This is a project I did to use machine learning to build a keyword classifier as part of an SEO workflow. It should be noted that I did this a couple of years ago before ChatGPT was released and it uses a more 'traditional' machine learning approach. This would be a lot easier to achive out-of-the-box using an LLM.

## 💾 Files in this repo are:
- **keyword_classifier.ipynb** - this is the notebook that contains the code for the data cleaning. processing and model creation. There is also extensive documentation on what I did too.
-  **keyword_categories.csv** - this is the data used for model training and consists of 10,000 keywords across 25 categories.
-  **gbdt_colab.sav** - this file contains the parameters of a saved model. I cheated a little bit as I used a Gradient Boosted Decision Tree model out-of-box as I knew it would give good perdormance for this type of data. In reality I would experiment with different types of models to see whivh gives the best performamce and optimise accordingly.
  
## ⚡ Next Steps:
- Reimplement the project using Lazy Predict to see if a Gradient Boosted Descision Tree really give the best performance. It would also be good to implement this project using an LLM to see if it can be improved..
