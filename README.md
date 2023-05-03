Download Link: https://assignmentchef.com/product/solved-cs3120-hw4-classification-using-different-classification-tools
<br>
(NumPy and data visualization packages are allowed.)

(SKLearn tools and models are allowed.)

Reference: Slide8_SVM1_midterm in blackboard

Datasets:  iris.csv or MNIST.csv from blackboard

Requirement:

Select a public dataset with multiple classes. Use at least three different classifiers to classify them. Compare and discuss the classification performance of different models that you selected. Discuss what could affect the performance for different classifiers (e.g. values of hyperparameters that you used) and how they affect the performance.

<ol>

 <li><strong>Select a dataset</strong>: select one from iris.csv or MNSt.csv or</li>

</ol>

any public dataset (include your csv file in your submission if you use another dataset)




<ol start="2">

 <li><strong>Split the dataset</strong>:</li>

</ol>

Please randomly partition the data into training and testing datasets. For example, 70% for training, and 30% for testing.

<strong>If you want to better select the values of some hyperparameters, you will need to do validation</strong> (not required, but suggested). You will need to partition the data into these three splits. For example, 70% for training, 10% for validation and 20% for testing. Report your final performance only using the testing dataset<strong>. (2pts)</strong>




<ol start="3">

 <li>Select at least <strong>three different types</strong> of classifiers based on different techniques (linear SVM and nonlinear SVM belong to <strong>one type</strong>) and fit the training set to your models. You might need to convert the string label values to numbers using “LabelEncoder in sklearn”. <strong>(2pts)</strong></li>

</ol>




<ol start="4">

 <li><strong>Train your Classifiers</strong> and perform validation if needed using different hyperparameters values</li>

</ol>




<ol start="5">

 <li><strong>Evaluate</strong>: Once your classifier is trained, you should evaluate the classification performance (accuracy, precision, recall, F-measure) on the test set. These scores need to be included in your report. <strong>(5pts)</strong></li>

</ol>




<ol start="6">

 <li><strong>Repeat the training and testing for different classifiers you selected.</strong> Write down all classifiers that you selected and write down model resource for all of them in your report. If some classifier was defined by your own function, please include that function definition (code) in your report. <strong>(5pts)</strong></li>

</ol>

e.g.

import sklearn.svm as svm #model resource(see below)

from sklearn.tree import DecisionTreeClassifier #model resource(see below)

from sklearn.linear_model import LogisticRegression #model resource(see below)

model1   svm.SVC(kernel=’poly’, C=C,gamma=Gamma)

model2  LogisticRegression()

model3  DecisionTreeClassifier()




<ol start="7">

 <li><strong>Which is the best classifier and why?</strong> Answer or analysis of this question needs to be included in your report. <strong>(3pts)</strong></li>

</ol>




<ol start="8">

 <li><strong>What affect the classification performance?</strong> Answer or analysis of this question needs to be included in your report. <strong>(3pts) </strong></li>

</ol>

<em>You could try different sizes of the training/testing data, different hyperparameters’ values, Or even different datasets using different classifiers.</em>







<ol start="9">

 <li><strong>Bonus up to 5 pts.</strong> (Anything that was not listed above.)</li>

</ol>







<strong>Submission</strong>:

File 1: Report

File 2: Code (+dataset if you used another dataset that not in blackboard)




Write a report to describe /answer required questions of your design.

Upload your code with comments as a separate .py or zip file.

<strong>e.g.</strong>

<strong>File1: MidtermHW_FirstnameLastname.doc/.pdf (this is the report)</strong>

<strong>+</strong>

<strong>File2: MidtermHW_ FirstnameLastname.py (this is the code. only “.py” files accepted. </strong>

<strong>            OR</strong>

<strong>          MidtermHW_ FirstnameLastname.zip if you have multiple “.py” files or another dataset.</strong>