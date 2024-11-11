---
home: no
layout: default
logo: logo.png

---


This schedule is subject to changes throughout the course at my discretion. Readings will be finalized the Friday before they are covered in class.  The textbooks references are: 
* <strong>ER:</strong> Evans, Michael J., and Jeffrey S. Rosenthal. Probability and statistics: The science of uncertainty. Macmillan, 2004.
* <strong>ISLP:</strong> James, Gareth, et al. An introduction to statistical learning: With applications in python. Springer Nature, 2023.
* <strong>ROS:</strong> Gelman, Andrew, Jennifer Hill, and Aki Vehtari. Regression and other stories. Cambridge University Press, 2021.
<!-- * <strong>ROS:</strong> Gelman, Andrew, Jennifer Hill, and Aki Vehtari. Regression and other stories. Cambridge University Press, 2021. -->

<strong> Supplementary material:</strong>  Material in <i>italics</i> is meant to reenforce your understanding of the core course material, but you will not need to know the specific definitions/theorems/examples for the exams. 

<strong> Regarding my notes:</strong> My course notes are meant as a supplement to the textbook readings and other resources. They are not a self-contained reference for the course material and will inevitably contain some mistakes. I recommend using the notes to get an idea of what concepts/examples are emphasized and then reviewing this material in the textbook. 


Please see canvas for section specific updates and assignment due dates. This schedule will be updated throughout the term. While I will attempt to stay a few weeks ahead in terms of planning the readings, readings will be finalized roughly one week before the material is covered. Class 


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 1: Discrete Probability and Monte Carlo Simulations</summary>

<h3>Topics:</h3>
<ul>
  <li>Familiarity with basic concepts in probability (events, probability distribution) (Monday)</li>
  <li>Independence and conditioning  (Wednesday)</li>
  <li><strong>Computation:</strong>  Basics of Python programming (arrays, <s>Dataframes</s> (moved to week 3), plotting), The concept of Monte Carlo simulation (Friday)</li>
</ul>

<h3>Class material</h3>
<ul>
  <!-- <li> <a href = "/course_documents/1_discrete_models/1_notes.pdf">Notes</a></li> -->
  <li> <strong>Class notes: </strong><a href = "course_documents/Math50_week1M.pdf">Monday (9/16)</a>, <a href = "course_documents/Math50-w1W.pdf">Wednesday (9/18)</a> </li>
  <li> <a href = "https://colab.research.google.com/drive/1PKX55UnkkO2qQFPdcdcg06rRYGBjXOeC?usp=sharing">Colab notebook (9/20)</a>  </li>
</ul>


<h3>Reading:</h3>
<ul>
  <li>
    <strong>ER:</strong>
    <ul>
      <li>1.1 (Intro)</li>
      <li>1.2 (Probability models)</li>
      <li><i>1.3 (Properties of probability models)</i></li>
      <li>2.1 (Random variables): Definition 2.1.1 </li>
      <li>1.5/2.8 (Conditional probability): Definition 1.5.1, Theorem 1.5.1, Theorem 1.5.2, Definitions 1.5.2 and 1.5.3 </li>
    </ul>
    <!-- <b>Note:</b> There is a lot of material in these chapters that I won't cover in detail; refer to the notes for specific definitions and Theorems. The most important concept is conditional probability (1.5). -->
  </li>
  <li>
    <strong>ISP:</strong>
    <ul>
      <li>2.3 (python tutorial) --  I use <code>np.random</code> instead of <code>np.random.default_rng</code>.  </li>
    </ul>
    <strong>Other:</strong>
    <ul>
      <li>Review the <a href="index.html">course policies</a>  and this schedule  </li>
    </ul>
  </li>
</ul>

<!-- 
<h3>Assignments due:</h3>
<ul>
  <li>Review the python tutorial from ISP</li>
</ul> -->

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 2: iid Sums, Binomial and CLT</summary>

<h3>Topics:</h3>
<ul>
  <li>Expectations and variances, conditional expectation (Monday)</li>
  <li>Binomial distribution, LLN (Monday)</li>
  <li><strong>Computation:</strong> Monte Carlo simulation, histogram, numerical illustration of CLT   (Wednesday) </li>
  <li>Continuous probability distributions and probability density , Central Limit Theorem and Normal distribution (Friday)</li>
</ul>

<h3>Class material</h3>
<ul>
 <li><strong>Class notes: </strong>
 <ul>
 <li><a href = "course_documents/Math50-w2M_DRAFT.pdf">Monday (9/23) DRAFT</a></li> 
 <li><a href = "course_documents/Math50-w2M_CLASS.pdf">Monday (9/23) Class</a></li>
<li><a href = "course_documents/Math50-w2F_DRAFT.pdf">Friday (9/27) DRAFT</a></li>
  </ul></li>

 <li><strong>Code: </strong>
 <ul>
  <li> <a href = "https://colab.research.google.com/drive/1WdyY-RixRxbewVAsfGGNoIB4UQlfsxMS?usp=drive_link">Colab notebook (9/25)</a></li>
</ul></li>
</ul>



<h3>Reading:</h3>
<ul>
<li> <strong>ER:</strong>
  <ul>
    <li>3.1 and 3.2 (Expectations) </li>
    <li>3.5 (conditional expectation)</li>
    <li>3.3 (Variance and covariance)</li>
    <li><i>2.3 (Discrete distributions) </i></li>
    <li>2.4 (Continuous)</li>
    <li><i>4.2.1/4.4.1 (Law of large numbers/Central Limit Theorem):</i> You will not need to know the more technical definitions in the textbook, only the intuition behind these results. The CLT theorem video referenced below is extremely helpful for this.   </li>
  </ul>
  </li>
</ul>

  <li><strong>Addition resources</strong> (from 3Blue1Brown):
  <ul>
  <li><a href = "https://www.youtube.com/watch?v=U_85TaXbeIo">Simple proof of Bayes' Theorem</a> </li>
  <li><a href = "https://www.youtube.com/watch?v=8idr1WZ1A7Q">Binomial distribution</a> </li>
  <li><a href = "https://www.youtube.com/watch?v=zeJD6dqJ5lo">Central Limit Theorem</a> </li>
  </ul>
  </li>


<h3>Assignments due:</h3>
<ul>
  <li><a href = "course_documents/Math50_hw1.pdf">HW1</a> </li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 3: Working with Normal RVs, Least squares LR </summary>

<h3>Topics:</h3>
<ul>
  <li>Properties of Normal random variables (Monday)</li>
  <li>Single-predictor regression as conditional model (Monday)</li>
  <li>Correlation coefficients, R-squared, <s>regression to the mean</s> (Wednesday)</li>
  <li>Least squares (Wednesday)</li>
  <li><strong>Computation:</strong> Simulating regression models and working with tabular data (Dataframes) (Friday)</li>
</ul>

<h3>Class material</h3>
<ul>
  <li> <strong>Class notes:</strong>
    <ul>
    <li><a href = "course_documents/Math50_w3-OLD-2023.pdf">Class notes from 2023</a> </li>
    <li><a href = "course_documents/Math50-w3M_DRAFT.pdf">Monday (9/30) DRAFT </a> </li>
    <li><a href = "course_documents/Math50-w3MW.pdf">Monday (9/30) CLASS </a> </li>
    </ul>
    </li>
  <li><strong>Code:</strong>
  <ul>
   <li><a href ="https://colab.research.google.com/drive/1nkuxp_giX9P7L-EP4dnwn_xS8r7rckSv?usp=sharing">Colab notebook (10/7)</a></li>
   </ul>
   </li>
</ul>

<h3>Reading:</h3>
<ul>
<li> <strong>ER:</strong>
  <ul>
    <li>4.6 (Properties of Normal distribution) </li>
    <li>Definition 3.3.3 covariance </li>
    <li>10.1 (related variables): Example 10.1.1 </li>
    <li>10.3.2 (Simple lineage regression model): Example 10.3.3. Use slightly different notation (e.g. instead of b I write a hat over the regression coefficient to indicate its estimate). You can skip Theorem 10.3.2, 10.3.3 and 10.3.4 for now.  </li>
  </ul>
  </li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li><a href = "course_documents/Math50_hw2.pdf">HW2</a> </li>
  <li>HW1 Self-evaluation</li>
</ul>

</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 4: Other aspects of single predictor LR  </summary>

<h3>Topics:</h3>
<ul>
  <li> <strong>Computation:</strong> Finish regression examples in python, coefficient of determination </li> 
  <li> More on coefficient of determination, estimators, standard error (Wednesday/Friday)</li>
  <li> <strong>Computation:</strong> regression with <code>statsmodels</code>, visualizing confidence intervals in regression (Friday) </li>
</ul>

<h3>Reading:</h3>
<ul>
<li><strong>ROS</strong>
  <ul>
  <li>Chapter 4: Read the entire chapter (it's not too technical), but 4.2 and 4.4 are especially important. </li>
  </ul>
</li>
<li> <strong>ER (OPTIONAL): These are optional if you would prefer a more technical treatment. </strong>
  <ul>
    <li>6.1 and 6.3</li>
  </ul>
  </li>
<li> <strong>ISP  (OPTIONAL): This is helpful if you would like additional examples in Python.</strong>
  <ul>
    <li>3.1 (Linear regression)  </li>
  </ul>
  </li>
</ul>

<h3>Class material</h3>
<ul>
  <li> <strong>Class notes:</strong>
    <ul>
    <li><a href = "course_documents/Math50_w4-OLD-2023.pdf">Class notes from 2023</a> </li>
    <li><a href = "course_documents/Math50-w4MW_DRAFT.pdf">Monday and Wednesday (10/7,10/9) DRAFT </a> </li>
    </ul>
    </li>
  <li><strong>Code:</strong>
  <ul>
   <li><a href ="https://colab.research.google.com/drive/1nkuxp_giX9P7L-EP4dnwn_xS8r7rckSv?usp=sharing">Colab notebook (10/7 notebook from week 3)</a></li>
   <li><a href ="https://colab.research.google.com/drive/11CTz-uyCJZMn6fMNaDKSZkH_YtlGVeBW?usp=sharing">Colab notebook (10/11) </a></li>
   </ul>
   </li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW3 Due date pushed to Week 5</li>
  <li>HW2 Self-evaluation</li>
</ul>

</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 5: Hypothesis testing for LR <strong>MIDTERM (Oct 16) </strong></summary>

<h3>Topics:</h3>
<ul>
  <li>Midterm review (Monday)</li>
  <li>Introduction to regression with multiple predictors (Friday)</li>
  <li><strong>Computation:</strong> $p$-values, Performing multivariate regression in <code>statsmodels</code> and data visualization (Friday)</li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>No new reading</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>Midterm</li>
  <li><a href = "course_documents/Math50_hw3.pdf">HW3</a> </li>
</ul>


</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 6: Multiple predictor LR I </summary>

<h3>Topics:</h3>
<ul>
  <li> No class monday</li>
  <li> Effects of adding predictors to regression models (Wednesday)</li>
  <li> Interpreting regression coefficients and model building considerations (Wednesday) </li>
  <li> <strong>Computation:</strong>  Examples in python (Wednesday) </li>
</ul>

<h3>Reading:</h3>
<ul>
<li><strong>ROS:</strong>
  <ul>
  <li>Ch. 10: Ignore the r code and skip 10.5,10.8 and 10.9  </li>
  </ul>
</li>
<li> <strong>ISP  (OPTIONAL): This is helpful if you would like additional examples in Python beyond my notebooks.</strong>
  <ul>
    <li>3.1 (Linear regression)  </li>
  </ul>
  </li>
</ul>

<h3>Class material</h3>
<ul>
  <li> <strong>Class notes:</strong>
    <ul>
    <li><a href = "course_documents/Math50-w6.pdf">My notes</a> </li>
    <li><a href ="https://colab.research.google.com/drive/1f7o12K0n7lEhE-SXrlDG8x6QOh4rqrDt?usp=sharing">Colab notebook (10/25) </a></li>
    </ul>
    </li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>No HW due</li>
  <li>HW3 Self-evaluation</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 7: Multiple predictor LR II </summary>

<h3>Topics:</h3>
<ul>

  <li> Simpsons paradox (Monday) </li>
  <li> Catagorical predictors/dummy variables (Monday/Wednesday) </li>
  <li> Interactions (Wednesday) </li>
  <li> <strong>Computation:</strong> Hands on examples in statsmodels </li>
</ul>

<h3>Reading/notes:</h3>
<ul>
  <li><a href = "course_documents/Math50-w7.pdf">My typed notes</a> </li>
  <li><a href = "course_documents/Math50-w7M-Lecture.pdf">Monday (10/28) CLASS</a> </li>
  <li><a href = "course_documents/Math50-w7W-Lecture.pdf">Wednesday (10/30) CLASS</a> </li>
  <li> <strong>ISP:</strong> Sections 3.3.1 and 3.3.2 </li>
  <li><strong><a href = "https://users.aalto.fi/~ave/ROS.pdf">Regression and Other stories </a></strong>
  <ul>
  <li>Section 12.1 and 12.2 (linear transformations of predictors)   </li>
  <li>Section 11.3 (residual plots)</li>
  </ul>
</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li><a href = "course_documents/Math50_hw4.pdf">HW4 (deadline extended -- see canvas)</a></li>
  <li>No Self-evaluation due</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 8: Model assessment and nonlinear models </summary>

<h3>Topics:</h3>
<ul>
    <li> Bias variance tradeoff, overfitting, double descent (Monday)</li>
    <li> Cross validation (Monday) </li>
    <li> Regularization (Wednesday/Friday) </li>
    <li> Laplace rule of succession </li>
</ul>

<h3>Reading/notes:</h3>
<ul>
  <li> <a href="course_documents/Math50-w8.pdf">My typed notes from 2023 (DRAFT -- covers cross validation, overfitting, Fourier series)</a> Colab notebook is linked within. </li>
  <li> <a href="course_documents/Math50-w8M_CLASS.pdf">Monday (11/4) CLASS</a> </li>
  <li> <a href="course_documents/Math50-w8W_CLASS.pdf">Wednesday/Friday (11/6 and 11/8) CLASS</a> (I ended class on Friday with some examples of regularization) </li>
  <li> <strong>ISLP:</strong> Sections 2.1 and 2.2 (overfitting and bias variance tradeoff) </li>
  <li> <strong>ISLP:</strong> Section 6.2 (regularization) </li>
  <li> <s><strong>ISLP:</strong> Sections 4.1, 4.2, 4.3 (logistic regression)</s> </li>
  <li> <strong>ISLP:</strong> There is a section on cross validation but it might be a bit confusing since we didn't cover logistic regression </li>
  <li> <strong><a href="https://users.aalto.fi/~ave/ROS.pdf">Regression and Other Stories</a></strong>: Section 11.8 (optional additional explanation of CV) </li>
</ul>

<h3>Additional resources</h3>
<ul>
  <li><a href="https://mlu-explain.github.io/double-descent/">Double descent</a></li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW4 Self-evaluation</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 9/10: Fourier models, Bayesian Inference, other topics</summary>

<h3>Topics:</h3>
<ul>
  <li>Fourier models/time series data (Monday) </li>
  <li>Priors (Wednesday)</li>
  <li>Laplace rule of succesion from Bayesian perspective (Wednesday)</li>
  <li>Relationship between bayesian linear regression and regularization</li>
  <li>The kernel trick, other topics? </li>
</ul>

<h3>Reading/notes:</h3>
<ul>
  <li> <strong>ER:</strong>
  <ul>
    <li>7.1 (Priors and posterior) -- Focus on example 7.1.1 and try following/reproducing the calculations with alpha=beta=1 (so the beta distribution, which we haven't discussed, becomes a uniform distribution which you are very familiar with).   </li>
    <li>10.3.3  (Bayesian linear regression) -- Optional</li>
  </ul>
  </li>
  <li> <strong> ISLP:</strong> Section 6.2, subsection titled "Bayesian Interpretation of Ridge Regression and the Lasso"</li>
</ul>

<h3>Additional resources</h3>
<ul>
  <li><a href= "https://www.quantstart.com/articles/Bayesian-Inference-of-a-Binomial-Proportion-The-Analytical-Approach/"> Bayesian inference for bernoulli trials </a></li>
  <li><a href="https://www.youtube.com/watch?v=HZGCoVF3YvM">Bayesian inference  (from 3Blue1Brown, there are many other great videos on youtube)</a></li>
  <li><a href="https://www.youtube.com/watch?v=r6sGWTCMz2k">Fourier series (from 3Blue1Brown), just for fun</a></li>
  <li><a href="https://mlu-explain.github.io/double-descent/">Double descent</a></li>
</ul>


<h3>Assignments due:</h3>
<ul>
  <li><a href = "course_documents/Math50_hw5.pdf">HW5 due last day of class</a></li>
</ul>


</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary> Review and <a href = "https://www.dartmouth.edu/reg/calendar/exams/exams24-25.html"><strong> FINAL EXAM</strong>  </a>  </summary>



<h3>Review:</h3>
<ul>
  <li>[TBD]</li>
</ul>


</details>

