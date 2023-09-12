# Comparative-analysis-of-classifiers

<h1>Libraries :</h1>
<ol>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>Sklearn</li>
  <li>Ipython</li>
</ol>
<h2>Classification Models - </h2><h5>Logistic Regression, Decision Tree, Random Forest, KNN(K Nearest Neighbour)</h5>
<b style="font-size:'90px';">Dataset Used-</b> Voice classification<br>
<h2>Original Correlation Matrix</h2>

![corr before](https://github.com/mansiverma19/Comparative-analysis-of-classifiers/assets/83285383/227e9219-6975-4a93-bf1d-00e6daaf6104)
<p>The matrix shows that the correlation between the features.</p>
<p>Darker the shade means higher is the correlation so in order to increase the models accuracy the the features having correlation are dropped.</p>
<h2>Correlation Matrix after dropping the Features</h2>

![corr after](https://github.com/mansiverma19/Comparative-analysis-of-classifiers/assets/83285383/1fed268e-3c0d-440d-826e-f14a5670d984)

<h1>RESULTs</h1>
<h3>Logistic Regression</h3>
<pre>
  accuracy :  0.9737118822292324
  precision :  0.9625246548323472
  recall :  0.9878542510121457
  f1 score :  0.9750249750249751
</pre>
<h3>Decision Tree</h3>
<pre>
  accuracy :  0.9663512092534174
  precision :  0.9565217391304348
  recall :  0.979757085020243
  f1 score :  0.9680000000000001
</pre>
<h3>Random Forest</h3>
<pre>
  accuracy :  0.982124079915878
  precision :  0.9857433808553971
  recall :  0.979757085020243
  f1 score :  0.9827411167512691
</pre>
<h3>KNN</h3>
<pre>
  accuracy :  0.9768664563617245
  precision :  0.9777327935222672
  recall :  0.9777327935222672
  f1 score :  0.9777327935222672
</pre>
<h2>Data Visualization Dashboard</h2>
<p>The Power Bi dashboard to evaluate the models result based on the evaluation matrices .</p>
<ul>
  <li>Accuracy</li>
  <li>Precision</li>
  <li>Recall</li>
  <li>F1-Score</li>
</ul>

![Screenshot (19)](https://github.com/mansiverma19/Comparative-analysis-of-classifiers/assets/83285383/ca8af6b1-f248-4114-9aec-0d1b5f7a4080)

