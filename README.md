### Automated Depression Detection from Tweets: a Comparison of NLP Techniques
<b>Official implementation of the [IDAP 2024](http://idap.inonu.edu.tr/) paper.</b>

Emirhan Balcı*, Esra Saraç

## Abstract
This paper aims to classify suicidal ideation as a symptom of depression from social media posts by applying the state-of-the-art classification model BERT (Bidirectional Encoder Representations from Transformers) and three traditional machine learning algorithms for binary classification. Since depression is one of the most prevalent mental health disorders amongst psychiatric disorders, the authors intended to present an experimental analysis of the machine learning classifier results as a comparison of novel depression detection techniques. We utilized undiagnosed user posts from Twitter as our dataset and tested the fine-tuned BERT model by applying hold-out and 10-fold cross-validation techniques. Since the dataset is highly unbalanced, Support Vector Machine (SVM), Naive Bayes, and Random Forest algorithms were employed on the same dataset with and without the oversampling method SMOTE (Synthetic Minority Oversampling Technique). The results demonstrate that traditional machine learning classifiers cannot infer sentiment from data containing various linguistic cues, such as depression symptoms. On the other hand, the state-of-the-art model BERT achieves 99.29\% and 99.56\% macro and micro-F-measure values, respectively, surpassing traditional machine learning algorithms in terms of these metrics. As a robust solution to depression detection from textual data, the BERT model is more trustworthy than the traditional machine learning classifiers to detect specific cues related to depression and similar mental disorders. This study contributes to the relevant research areas of natural language processing by indicating the performance difference between the BERT model and several traditional machine learning algorithms as a generalized approach for classification tasks.

[Code](https://github.com/BashMocha/Automated-Depression-Detectiom-from-Tweets/tree/master/notebooks) | [Paper](https://github.com/BashMocha/Automated-Depression-Detectiom-from-Tweets/) | [Data](https://github.com/BashMocha/Automated-Depression-Detectiom-from-Tweets/tree/master/data)

## Updates

19/09/2024: We release the utilized dataset and the source code.

11/09/2024: The study is accpeted by IDAP'24! 🎉

15/08/2024: The paper is submitted to symposium.

## License

GNU General Public License v3.0

<hr>

Feel free to [contact](mailto:emirbalci360@gmail.com) for any questions.
