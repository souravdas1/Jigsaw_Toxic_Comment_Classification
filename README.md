# Jigsaw_Toxic_Comment_Classification



**1. Introduction**

Previous toxicity models built by the Conversation AI team, a research initiative founded by Jigsaw and Google (both part of Alphabet), incorrectly learned to associate the names of frequently attacked identities with toxicity. These models predicted high toxicity for those comments containing words like gay, lesbian, black, white, etc, even when the comments were not actually toxic (e.g. I am a gay black man).


**2. Business Problem**

To build a model that recognizes toxicity and minimizes this type of unintended bias with respect to mentions of identities. The model should be interpretable and no strict latency requirements.


**3. Machine Learning Problem**

To build a model that will classify the comments based on toxicity levels, i.e. if target > 0.5, the comment is toxic (label = 1), otherwise non-toxic (label = 0).


**4. Source of Data**

Dataset for this study is downloaded from [Kaggle](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification)
