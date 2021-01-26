edit at: https://docs.google.com/document/d/1JUEDn6mED4gadv39omlPZs4O4w1NCSRPRT3wUPNmLfg/edit

Question 1. **If the data set has a different scale, and you do not use feature scaling or mean normalization, the contour is skewed leading to slow performance of gradient descent. Why Feature Scaling for skewed contour?**

![alt text](https://github.com/xxnguyenducanh/My-questions-with-Andrew-Ng-s-ML-course-/blob/main/the%20skewed%20contour%20with%20gradient%20descent.png)
![](RackMultipart20210126-4-klhv1x_html_4374cd085306ce15.png)

[**https://stats.stackexchange.com/questions/41704/how-and-why-do-normalization-and-feature-scaling-work**](https://stats.stackexchange.com/questions/41704/how-and-why-do-normalization-and-feature-scaling-work)

[**https://stackoverflow.com/questions/26225344/why-feature-scaling-in-svm**](https://stackoverflow.com/questions/26225344/why-feature-scaling-in-svm)

Question 2. **Explain the gap between error on the training set and validation set.**

a. The hypothesis doesn&#39;t fit with data, in other words, it&#39;s a useless function, the error on the training set or validation set will be large, and there is no significant difference between them.

b. The hypothesis overfits the training data, the error on the training set will be critically low and the error on validation set will be large because the trained hypothesis generates badly on unseen data.

Question 3. **How sigma matters in the RBF kernel in SVM and why it behaves that way? (Why does Kernel make hypothesis more complex?).**

![alt text](https://github.com/xxnguyenducanh/My-questions-with-Andrew-Ng-s-ML-course-/blob/main/RBF%20kernel%20in%20SVM.png)

![](RackMultipart20210126-4-klhv1x_html_8c08d81f870776cd.png) ![](RackMultipart20210126-4-klhv1x_html_6c8bfeb847e3fca3.png) ![](RackMultipart20210126-4-klhv1x_html_c7cca350679044a9.png)

  

As we can see, for the equation of kernel function showed above: sigma plays a role to be an amplifier of the distance between x and x&#39;. If the distance between x and x&#39; is much larger than sigma, the kernel function tends to be zero. Thus, if the sigma is very small, only the x within a certain distance can affect the predicting point. In other words, smaller sigma tends to make a local classifier, larger sigma tends to make a much more general classifier.

![](RackMultipart20210126-4-klhv1x_html_31cada1ea3aa0638.png) ![](RackMultipart20210126-4-klhv1x_html_d1af0e43a1f255de.png)
![alt text](https://github.com/xxnguyenducanh/My-questions-with-Andrew-Ng-s-ML-course-/blob/main/probability%20density%20function.png)
If **Sigma Squared parameter** is larger, a larger range of _ **X = x - x&#39;** _ is reduced, because of division by this parameter, then _**k(x,x&#39;)**_ makes a range of data points which are near _ **x point** _ equal to 1 or 0. The decision boundary is a general one considering nearly all of the data points.


Note: SVM cost function

![alt text](https://github.com/xxnguyenducanh/My-questions-with-Andrew-Ng-s-ML-course-/blob/main/SVM%20cost%20function.png)

**Note:** The reason why we need ML engineer is we do not have a critically strong computing system to cover all situation, people need to fix and optimize the ML system (data processing, algorithms) to run it on a specific task with a limited computing system and dataset.**
Question 4. **What is the Gaussian Kernel?**

![](RackMultipart20210126-4-klhv1x_html_58d2b887c6b1fdfb.png)

![](RackMultipart20210126-4-klhv1x_html_58d2b887c6b1fdfb.png)

[**https://www.whydomath.org/node/wavlets/imagebasics.html#:~:text=A%20pixel%20**](https://www.whydomath.org/node/wavlets/imagebasics.html#:~:text=A%20pixel%20)

**WATCH &#39;&#39;PCA and SVD (Andrew Ng&#39;&#39; AGAIN !!**

![](RackMultipart20210126-4-klhv1x_html_bd35e24d8405f559.png)
