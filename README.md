# Deep-Learning-Language-Detection
Deep learning language classification using RNN

You will train a recurrent neural network that takes a code snippet andpredicts which programming language it is written in.

The dataset contains 11103 snippets for train and 2995 snippets for testfrom 6 programming languages: C++, C#, Python, JavaScript, HTML and SQL.
Each programming language is almost equally represented in the dataset.
Each snippet is found in a separate file in the train-data-split and test-data-split folders.
The train/test labels are stored as a dictionary in the code-train-gt.json and code-test-gt.json files, using the filename as identifier.
The dataset is a subset of the dataset used in the [Deep Learning Language Detection](https://github.com/aliostad/deep-learning-lang-detection), where each snippet is cut in chunks of length 1000.
