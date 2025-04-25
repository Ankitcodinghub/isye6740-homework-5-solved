# isye6740-homework-5-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/isye6740-100-points-solved-2/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;122076&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYE6740 Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Comparing multi-class classifiers for handwritten digits classification. (20 points)

This question is to compare different classifiers and their performance for multi-class classifications on the complete MNIST dataset at http://yann.lecun.com/exdb/mnist/. You can find the data file mnist 10digits.mat in the homework folder. The MNIST database of handwritten digits has a training set of 60,000 examples and a test set of 10,000 examples. We will compare KNN, logistic regression, SVM, kernel SVM, and neural networks.

• We suggest you to “standardize” the features before training the classifiers by dividing the values of the features by 255 (thus mapping the range of the features from [0, 255] to [0, 1]).

• For KNN and SVM, you can randomly downsample the training data to size m = 5000, to improve the computation efficiency.

Train the classifiers on the training dataset and evaluate them on the test dataset.

1. (15 points) Report confusion matrix, precision, recall, and F-1 score for each of the classifiers. For the precision, recall, and F-1 score of each classifier, we will need to report these for each of the digits. So you can create a table for this. For this question, each of the 5 classifiers, KNN, logistic regression, SVM, kernel SVM, and neural networks, accounts for 10 points.

2. (5 points) Comment on the performance of the classifier and give your explanation why some of them perform better than others.

2. SVM (25 points).

1. (5 points) Explain why can we set the margin c = 1 to derive the SVM formulation?

2. (5 points) Using Lagrangian dual formulation, show that the weight vector can be represented as

n w = Xαiyixi.

i=1

where αi ≥ 0 are the dual variables. What does this imply in terms of how to relate data to w?

3. (5 points) Explain why only the data points on the “margin” will contribute to the sum above, i.e., playing a role in defining w. Hint: use the Lagrangian multiplier derivation and KKT condition we discussed in class.

4. Simple SVM by hand.

Suppose we only have four training examples in two dimensions as shown in Fig. The positive samples at x1 = (0,0), x2 = (2,2) and negative samples at x3 = (h,1) and x4 = (0,3).

(a) (5 points) For what range of parameter h &gt; 0, the training points are still linearly separable?

(b) (5 points) Does the orientation of the maximum margin decision boundary changeas h changes, when the points are separable?

3. Neural networks and backward propagation. (15 points)

where σ(x) = 1/(1 + e−x) is the sigmoid function, zi is a two-dimensional vector such that ), and

1. (5 points) Show that the gradient is given by

,

where ui = wTzi.

2. (10 points) Also, show the gradient of ℓ(w,α,β) with respect to α and β and write down their expression.

4. Feature selection and change-point detection. (20 points)

1. (10 points) Consider the mutual information-based feature selection. Suppose we have the following table (the entries in the table indicate counts) for the spam versus and non-spam emails:

“prize” = 1 “prize” = 0

“spam” = 1 150 10

“spam” = 0 1000 15000

“hello” = 1 “hello” = 0

“spam” = 1 145 15

“spam” = 0 11000 5000

Given the two tables above, calculate the mutual information for the two keywords, “prize“ and “hello” respectively. Which keyword is more informative for deciding whether or not the email is spam?

2. (10 points) Given two distributions, f0 = N(0,1), f1 = N(0.5,1.5), derive what should be the CUSUM statistic (i.e., write down the CUSM detection statistic). Plot the CUSUM statistic for a sequence of randomly generated samples, x1,…,x100 are are i.i.d. (independent and identically distributed) according to f0 and x101,…,x200 that are i.i.d. according to f1.

5. Medical imaging reconstruction (20 points).

In this problem, you will consider an example resembles medical imaging reconstruction in MRI. We begin with a true image image of dimension 50 × 50 (i.e., there are 2500 pixels in total). Data is cs.mat; you can plot it first. This image is truly sparse, in the sense that 2084 of its pixels have a value of 0, while 416 pixels have a value of 1. You can think of this image as a toy version of an MRI image that we are interested in collecting.

Because of the nature of the machine that collects the MRI image, it takes a long time to measure each pixel value individually, but it’s faster to measure a linear combination of pixel values. We measure n = 1300 linear combinations, with the weights in the linear combination being random, in fact, independently distributed as N(0,1). Because the machine is not perfect, we don’t get to observe this directly, but we observe a noisy version. These measurements are given by the entries of the vector

y = Ax + ϵ,

where y ∈ R1300, A ∈ R1300×2500, and ϵ ∼ N(0,25 × I1300) where In denotes the identity matrix of size n × n. In this homework, you can generate the data y using this model.

Now the question is: can we model y as a linear combination of the columns of x to recover some coefficient vector that is close to the image? Roughly speaking, the answer is yes.

Key points here: although the number of measurements n = 1300 is smaller than the dimension p = 2500, the true image is sparse. Thus we can recover the sparse image using few measurements exploiting its structure. This is the idea behind the field of compressed sensing.

The image recovery can be done using lasso

.

1. (10 points) Now use lasso to recover the image and select λ using 10-fold crossvalidation. Plot the cross-validation error curves, and show the recovered image.

2. (10 points) To compare, also use ridge regression to recover the image:

.

Select λ using 10-fold cross-validation. Plot the cross-validation error curves, and show the recovered image. Which approaches give a better recovered image?
