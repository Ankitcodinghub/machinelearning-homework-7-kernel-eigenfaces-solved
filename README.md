# machinelearning-homework-7-kernel-eigenfaces-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Homework 7-Kernel Eigenfaces Solved](https://www.ankitcodinghub.com/product/machinelearning-homework-7-kernel-eigenfaces-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92060&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Homework 7-Kernel Eigenfaces Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
I. Kernel Eigenfaces

In this section, you are going to do face recognition using eigenface and fisherface.

Reference: https://www.csie.ntu.edu.tw/~mhyang/papers/fg02.pdf

● Data

o The Yale Face Database.zip contains 165 images of 15 subjects

(subject01, subject02, etc.). There are 11 images per subject, one for each of the following facial expressions or configurations: center-light, w/glasses, happy, left-light, w/no glasses, normal, right-light, sad, sleepy, surprised, and wink.

o Thesedataareseparatedintotrainingdataset(135images)andtesting dataset(30 images). You can resize the images for easier implementation.

● What you are going to do

o Part1:UsePCAandLDAtoshowthefirst25eigenfacesandfisherfaces,

and randomly pick 10 images to show their reconstruction. (please refer

to the lecture slides).

o Part2:UsePCAandLDAtodofacerecognition,andcomputethe

performance. You should use k nearest neighbor to classify which subject

the testing image belongs to.

o Part3:UsekernelPCAandkernelLDAtodofacerecognition,and

compute the performance. (You can choose whatever kernel you want, but you should try different kernels in your implementation.) Then compare the difference between simple LDA/PCA and kernel LDA/PCA, and the difference between different kernels.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
II. t-SNE

Here are nice implementations of t-SNE in different programming languages:

https://lvdmaaten.github.io/tsne/

● Data &amp; reference code o Download link:

https://lvdmaaten.github.io/tsne/code/tsne_python.zip,

o mnist2500_X.txt:contains2500featurevectorswithlength784,for

describing 2500 mnist images.

o mnist2500_labels.txt:providescorrespondinglabels o tsne.py: reference code

● What you are going to do

o Part1: Try to modify the code a little bit and make it back to symmetric

SNE. You need to first understand how to implement t-SNE and find out the specific code piece to modify. You have to explain the difference between symmetric SNE and t-SNE in the report (e.g. point out the crowded problem of symmetric SNE).

o Part2: Visualize the embedding of both t-SNE and symmetric SNE. Details of the visualization:

▪ Project all your data onto 2D space and mark the data points into different colors respectively. The color of the data points depends on the label.

▪ Use videos or GIF images to show the optimize procedure. o Part3: Visualize the distribution of pairwise similarities in both high-

dimensional space and low-dimensional space, based on both t-SNE and

symmetric SNE.

o Part4:Trytoplaywithdifferentperplexityvalues.Observethechangein

visualization and explain it in the report.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
III. Report

<ul>
<li>● &nbsp;Submit a report in pdf format. The report should be written in English.</li>
<li>● &nbsp;Report format:</li>
</ul>
○ a. code with detailed explanations (40%)

<ul>
<li>Paste the screenshot of your functions with comments and
explain your code. For example, explain the process to clustering

and show different kernels, etc.
</li>
<li>Note that if you don’t explain your code clearly, you cannot get any points in section b and c either.</li>
</ul>
● Kernel Eigenfaces ○ Part1 (10%)

○ Part2 (5%)

○ Part3 (10%) ● t-SNE

○ Part1 (10%) ○ Part2 (2%) ○ Part3 (2%) ○ Part4 (1%)

○ b. experiments settings and results (35%) &amp; discussion (15%) ■ Show everything we asked you to show

● Kernel Eigenfaces ○ Part1 (5%) ○ Part2 (5%)

○ Part3 (5%) &amp; (5%) ● t-SNE

○ Part1 (5%) &amp; (5%) ○ Part2 (5%)

○ Part3 (5%)

○ Part4 (5%) &amp; (5%)

○ c. observations and discussion (10%)

■ Anything you want to discuss, such as the meaning of eigenfaces

or trying different dimension reduction methods, comparing the advantages and disadvantages of them.

</div>
</div>
</div>
