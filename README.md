# Minor-Project
This Repository contains all the files related to our Minor Project: Real Disaster Classification.
Group Members include:
Harshit Dang
Jay Kishan Singh
Pragya Anand
Tannavi Snehal

Project Details:

1)Reading of csv file of data.
    Concepts/Technologies include: Pandas.
    
2)Text cleaning/Text preprocessing.
    Concepts/Technologies include: Regular Expressions.
    NOTE: Numbers/Digits have not been replaced as of yet, but might be done in the future depending on the accuracy.
    
3)Tokenizing the data.
    Concepts/Technologies include: Natural language processing/nltk package used.
    
4)Inspection of data through visualization - Sentence length and vocabulary size.
    Concepts/Technologies include: Matplotlib.
    
5)Bag of Words approach -  A bag of words just associates an index to each word in our vocabulary, 
and embeds each sentence as a list of 0s, with a 1 at each index corresponding to a word present in the sentence.
    Concepts/Technologies include: Sklearn/countVectorizer.
 
6)Splitting of data into test and train using sklearn.

7)Compress the 14000(or so) dimensional vector into 2 dimensional vector for the purpose of visualization.
    Concepts/Technologies include: PCA/SVD, matplotlib.
    
8)Fitting a classifier to our data.
    Concepts/Technologies include: Logistic Regression (Some other classifier may be used in the future).
    
9)Using metrics to evaluate our ML model
    Concepts/Technologies include: sklearn, precision, recall, f1 score, accuracy.
    
The above steps have been completed as of yet and comprise of around 50% of the project.
A lot of optimization can be done on the code by referring to : https://blog.insightdatascience.com/how-to-solve-90-of-nlp-problems-a-step-by-step-guide-fda605278e4e
& https://github.com/hundredblocks/concrete_NLP_tutorial/blob/master/NLP_notebook.ipynb


