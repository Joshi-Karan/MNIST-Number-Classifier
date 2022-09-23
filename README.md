# MNIST Number Classifier
 
<h2>About Dataset:</h2>
<h4>The MNIST database of handwritten digits with 784 features, raw data available at: <a href="http://yann.lecun.com/exdb/mnist/">http://yann.lecun.com/exdb/mnist</a>. It can be split in a training set of the first 60,000 examples, and a test set of 10,000 examples</h4>
<br>
Dataset link: <a href='https://www.openml.org/search?type=data&status=active&id=554'>Click Here</a>
<hr>
<h2>Accuracy Obtained: <h2>
<h4>0.9763</h4>
<hr>
<h2>General Approach Used:</h2>
<h4>
1. The data and target value was extracted from the dictionary(The orginal data was in form of dictionary).<br>
2. Training and testing set was created by splitiing the original example.<br>
3. The training set was then augmented by appending it with the changed version of itself (The axis of images were shifted).<br>
4. The KNeighborsClassifier was used and accuracy of <b>0.9763</b> was achieved.
</h4>
