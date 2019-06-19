# KNN-on-DonorChoose-dataset

In this project I have applied `KNN algorithm` on DonorChoose dataset to predict whether a given project will be approved funding or not.<br>

I have created 4 dataset. Each dataset contains text features encoded with different encoding techniques.<br>
**Set1** | Text features encoded with simple `Bag of words` vectorizer.<br>
**Set2** | Text Features encoded with `TFIDF` vectorizer.<br>
**Set3** | Text features encoded with `Avarage Word2Vec` vectorizer.<br>
**Set4** | Text features encoded with `TFIDF Word2Vec` vectorizer.<br>

Then KNN is applied on all 4 datasets.<br>

<b> Conclusion after applying KNN to all datasets </b><br>

`KNN` is not able to distinguish between true positive and true negative. All the datapoints are predicted as Positive. 

##### Credits : www.AppliedAICourse.com
