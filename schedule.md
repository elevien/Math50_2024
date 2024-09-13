---
home: no
layout: default
logo: logo.png

---


This schedule is subject to changes throughout the course at my discretion. Readings will be finalized the Friday before they are covered in class.  The textbooks references are: 
* <strong>ER:</strong> Evans, Michael J., and Jeffrey S. Rosenthal. Probability and statistics: The science of uncertainty. Macmillan, 2004.
* <strong>ISLP:</strong> James, Gareth, et al. An introduction to statistical learning: With applications in python. Springer Nature, 2023.
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
  <li><strong>Computation:</strong>  Basics of Python programming (arrays, Dataframes, plotting), The concept of Monte Carlo simulation (Friday)</li>
</ul>

<h3>Class material</h3>
<ul>
  <!-- <li> <a href = "/course_documents/1_discrete_models/1_notes.pdf">Notes</a></li> -->
  <li> Class notes </li>
  <li> Colab notebook </li>
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
  <li> <a href = "/course_documents/2_iidsums_continuous/2_notes.pdf">Notes</a></li>
  <li> <a href = "/course_documents/2_iidsums_continuous/2_notes.pdf">Colab notebook</a></li>
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
    <li><i>4.2.1/4.4.1 (Law of large numbers/Central Limit Theorem):</i> You will not need to know the more technical definitions in the textbook, only the intuitive definitions in the book.  </li>
  </ul>
  </li>
</ul>


<h3>Assignments due:</h3>
<ul>
  <li>HW1</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 3: Linear Regression Basics (Single Predictor)</summary>

<h3>Topics:</h3>
<ul>
  <li>Properties of Normal random variables (Monday)</li>
  <li>Single-predictor regression as conditional model (Monday)</li>
  <li>Correlation coefficients, R-squared, autogregressive models (Wednesday)</li>
  <li>Least squares (Wednesday)</li>
  <li><strong>Computation:</strong> Simulating regression models and working with tabular data (Friday)</li>
</ul>

<h3>Class material</h3>
<ul>
  <li> <a href = "">Notes</a></li>
  <li> <a href = "">Colab notebook</a></li>
</ul>

<h3>Reading:</h3>
<ul>
<li> <strong>ER:</strong>
  <ul>
    <li>4.2.1/4.4.1 (Properties of Normal distribution) </li>
    <li>10.1 (related variables): Example 10.1.1 </li>
    <li>10.3.2 (Simple lineage regression model) </li>
  </ul>
  </li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW2</li>
  <li>HW1 Self-evaluation</li>
</ul>

</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 4: Statistical Inference</summary>

<h3>Topics:</h3>
<ul>
  <li>Properties of Estimators (Monday) </li>
  <li>Confidence intervals (Monday) </li>
  <li>Hypothesis testing (Wednesday)</li>
  <li><strong>Computation:</strong> Hands on examples in <code>statsmodels</code> (Friday)</li>
</ul>

<h3>Reading:</h3>
<ul>
<li> <strong>ER:</strong>
  <ul>
    <li>4.2.1/4.4.1 (Properties of Normal distribution) </li>
    <li>10.1 (related variables): Example 10.1.1 </li>
    <li>10.3.2 (Simple lineage regression model) </li>
  </ul>
  </li>
<li> <strong>ISP:</strong>
  <ul>
    <li>3.1 (Linear regression): Note the difference between how linear regression is presented here vs. in <strong>ER:</strong>.   </li>
  </ul>
  </li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW3</li>
  <li>HW2 Self-evaluation</li>
</ul>

</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 5: Multiple Predictors <strong>MIDTERM (Oct 14) </strong></summary>

<h3>Topics:</h3>
<ul>
  <li>Collinearity </li>
  <li>Interpretation of regression coefficients</li>
  <li><strong>Computation:</strong> Performing multivariate regression in <code>statsmodels</code> and data visualization (Wednesday)</li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>Midterm</li>
  <li>HW4</li>
  <li>No self-eval for HW3 due to midterm</li>
</ul>

</details>


<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 6: Interactions and other features </summary>

<h3>Topics:</h3>
<ul>
  <li>Adding interactions to regression models (Monday) </li>
  <li>Nonlinear models, the concept of feature space  (Wednesday)</li>
  <li>Model selection, cross validation (Wednesday)</li>
  <li><strong>EXAM</strong> (Friday) </li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW5</li>
  <li>HW4 Self-evaluation</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 7: Logistic Regression</summary>

<h3>Topics:</h3>
<ul>
  <li>Logistic function (Modany) </li>
  <li>Logistic regression vs. binning (Monday)</li>
  <li>Categorical regression (Wednesday)</li>
  <li>Fitting logistic models in <code>statsmodels</code></li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW6</li>
  <li>HW5 Self-evaluation</li>
</ul>

</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 8: Overfitting and Regularization</summary>

<h3>Topics:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW7</li>
  <li>HW6 Self-evaluation</li>
</ul>
</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary>Week 9: Bayesian Inference and MCMC</summary>

<h3>Topics:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Reading:</h3>
<ul>
  <li>[TBD]</li>
</ul>

<h3>Assignments due:</h3>
<ul>
  <li>HW8</li>
  <li>HW7 Self-evaluation</li>
</ul>
</details>

<!-- ################################################################################################################ -->
<!-- ################################################################################################################ -->
<details>
<summary> Review and <strong> FINAL EXAM (Date TBD) </strong> </summary>



<h3>Review:</h3>
<ul>
  <li>[TBD]/li>
</ul>


</details>

