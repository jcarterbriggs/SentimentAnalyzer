<a id="top"></a>

# Reddit Analyzer for McAfee Posts

This Jupyter notebook implements a **Reddit analyzer** focused on posts about **McAfee antivirus software**. It utilizes several APIs and libraries including:

- <span style="color:blue">**PRAW**</span> - Reddit API wrapper 
- <span style="color:blue">**OpenAI**</span> - GPT-3 API
- <span style="color:blue">**TextBlob**</span> - Text processing/NLP
- <span style="color:blue">**SpaCy**</span> - Advanced NLP 

## Key Steps

- Search Reddit for posts containing keywords like **"McAfee"** [Link](#get-training-data)

- Use **OpenAI's GPT-3** to <span style="color:green">**classify posts**</span> as relevant or not to McAfee antivirus

- <span style="color:green">**Save**</span> classified posts to a CSV file

- **Analyze** top subreddits where McAfee is discussed 

- Retrieve posts and <span style="color:green">**analyze sentiment**</span> over time using TextBlob

- <span style="color:green">**Train**</span> a SpaCy text classification model on the classified post data

- <span style="color:green">**Evaluate**</span> model accuracy on a validation set

- Improve model by <span style="color:green">**merging**</span> additional labeled data

- Experiment with <span style="color:green">**fine-tuning BERT**</span> in TensorFlow for the text classification task

- Use the final model to classify new Reddit posts and <span style="color:green">**plot sentiment trends**</span> over time


## Key Takeaways

The notebook demonstrates an **end-to-end pipeline** for:

- Gathering social media data
- Training a classifier using ML 
- Generating insights around product sentiment

Key techniques used include:

- Transfer learning 
- Data labeling
- Model evaluation
- Time series visualization
