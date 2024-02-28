**Natural Language Processing (NLP) for Sentiment Analysis**
>During political seasons, social media platforms become platforms for various public narratives. These narratives can range from positive to negative sentiments. To effectively gauge public sentiment towards specific posts, we have developed a Natural Language Processing (NLP) model. This model aims to analyze user sentiments based on their social media posts.

**Dataset Overview** 
>We have utilized the Twitter sentiment dataset from the 2017 Jakarta Gubernatorial Election. This dataset is available on [GitHub](https://rizalespe.github.io/Dataset-Sentimen-Analisis-Bahasa-Indonesia/). It provides a balanced distribution of tweets for each candidate and an equal distribution of positive and negative sentiments.


**Model Architecture**  
The NLP model is implemented using the Sequential API with two approaches:

- NLP Model with a Single Layer
- NLP Model with Multiple Layers
The model with the superior performance will be selected for deployment.

**Training and Evaluation**
The model's performance is evaluated based on metrics such as accuracy, loss, precision, recall, and F1 score. We utilize classification reports and visualization techniques like heatmaps to assess the model's predictive capabilities.

**Conclusion**
The NLP model demonstrates varying degrees of success in predicting sentiments. While some models exhibit underfitting or overfitting tendencies, others achieve satisfactory performance levels. Further model improvements can be achieved through parameter tuning, adjusting hidden layers, and expanding the dataset. Despite its limitations, the model serves as a valuable tool for sentiment analysis, especially concerning the 2017 Jakarta Gubernatorial Election tweets. However, it's important to note that the model's predictions may be influenced by the nature and scope of the dataset.


**Hugging Face Deployment Sentiment Analysis**: https://huggingface.co/spaces/batraccoon/Indonesian-Sentiment-Analysis-App

