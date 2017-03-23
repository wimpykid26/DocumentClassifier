# DocumentClassifier
Classifies text documents using Apache Lucene 4.10

---

Trains a set of documents and then tests it on another set.
Has the ability to train in 3 different ways (LC , Lucene Standard Analyzer and ngrams analyzer)
Indexes the files specified in the path and then trains them.
Also has the ability to test the accuracy using a confusion matrix.

---

Clone the repository
1. Open it in any preferable IDE.
2. Change the path to training and test set in `DocumentClassifier.java`
3. Specify the type of Analyzer in `DocumentClassifier` method(default set to std)
4. Build and Run
