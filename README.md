# cse342-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE342 Assignment 3 Solved](https://mantutor.com/product/cse342-sml-solved-3/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114081&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE342 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
1 Instructions

• You can use inbuilt libraries for Math, plotting, and handling the data (eg. NumPy, Pandas, Matplotlib).

• Usage instructions for other libraries can be found in the question.

• Only (*.py) files should be submitted for code. • Create a (*.pdf) report explaining your assumptions, approach, results, and any further detail asked in the question.

• You should be able to replicate your results during demo.

2 Question-1

Use https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz MNIST dataset for this question and select class 0, 1 and 2. Note you are not allowed to use libraries which can take data, fit the model, predict the classes and give accuracy. Perform following tasks.

• Apply PCA and reduce the dimension to p = 10. You can use the entire train set of these 3 classes to obtain PCA matrix. For the remaining parts, use the reduced dimension dataset.

• Now learn a decision tree using the train set. You need to grow a decision tree with 3 terminal nodes. This is similar to what we did in the baseball salary example. For the first split, consider all p dimensions. For each dimension, consider one split which will divide the space into two regions. Find the total Gini index. Similarly find the total Gini index for all 50 dimensions. Find the best split by searching for minimum Gini index. Suppose, you split across 10th dimension. Choose one of the splits, and repeat the steps to find best split. Once you find it, the entire p dimensional space is divided into three regions. [2]

1

• Find the class of all samples in test set of these 3 classes. For a particular test sample, check where the samples lies in the segmented space. The class for a particular sample is the class of sample which is in majority in the region to which the test sample belongs. Report accuracy and class-wise accuracy for testing dataset. [1] • Now use bagging, develop 5 different datasets from the original dataset. Learn trees for all these datasets. For test samples, use majority voting (atleast 3 trees should predict the same class) to find the class of a given sample. In case there is a tie, that is two trees predict one class and other two trees predict another class, then you can choose either of the classes.

Report the total accuracy and class-wise accuracy. [1]

2
