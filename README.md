# Classification Task on AutoImmune Data Set and Measuring their Accuracy
<br>
<br>
The goal of this project is to implement two different classifiaction Algorithm on the given dataset named autoimmune.txt. Here we have implement two approaches Cross Fold Validation and ROC Curve Construction to compare the performance of the two different classifier

Following are the basic steps -
1. <b>Data Preparation</b> - As each sample data is distributed over single column we need to transpose the data and then normalise all the attribute values so that they will come in the same scale
2. <b>Selection of Algorithm</b> - Here we have seleceted K-Nearest Neighbour and Support Vector Machine algorithm for our classification task.
3. <b>Perform 10-fold cross-validation</b> - Perorm 10 Fold Cross Validation to get the individual accuracy and compare their performance
4. <b>Split Train Test Data </b> - Split the data into Train Test and train the model with the train data and further test it with Test Data
5. <b>Construct ROC Curve</b> to compare their performance
