Sentiment Analysis on Amazon Food Reviews is a data-driven NLP project focused on extracting customer opinions and behavioural patterns from large-scale textual review data. The project was implemented in Python using libraries such as NLTK, Pandas, NumPy, TextBlob, Scikit-learn, Matplotlib, Seaborn, WordCloud, and Regex.

The workflow begins with data preprocessing, including text cleaning, normalization, removal of non-informative characters, and handling missing values. Using TextBlob, each review was analysed to compute sentiment polarity (positive, negative, neutral) and subjectivity, enabling differentiation between factual and opinion-based reviews. Reviews with low subjectivity were filtered out to focus on emotionally driven customer feedback.

Exploratory analysis was conducted to identify common words and sentiment-specific vocabulary, supported by frequency analysis and word clouds. Visualizations such as scatter plots and hexbin plots were used to study relationships between polarity and subjectivity.

To uncover hidden patterns in customer opinions, K-Means clustering was applied to group reviews based on sentiment characteristics. Additionally, Logistic Regression was implemented to classify sentiments, with model performance evaluated using a confusion matrix and statistical metrics.

Overall, the project combines NLP, unsupervised learning, and statistical modeling to transform unstructured text data into actionable insights for understanding customer sentiment and decision-making.

# Sentiment-analysis-on-Amazon-Food-reviews
Technologies Used: Python
Following are the Python packages which were installed using pip and used to implement the 
project: 
• NLTK 
• Pandas 
• Numpy 
• Matplotlib 
• Re
• Textblob
• Collections
• Wordcloud
• Seaborn
• String
• Sklearn
Implementation :
Sentiment analysis, Sentiment, Polarity and Subjectivity using textblob, Common Words in sentiment, Removing non-subjective reviews, K-means Clustering, Statistical analysis using sk_learn(logistic regression and confusion matrix).

Download the Dataset : https://drive.google.com/drive/folders/1d6samYZaz0aUIy4DCXKnAcWAmCrHFeY1?usp=sharing
