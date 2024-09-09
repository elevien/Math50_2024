---
home: yes
layout: default
logo: logo.png

---


<details open><summary>About the course</summary>
<p><strong>Instructor:</strong> Ethan Levien</p>
<p><strong>Prerequisites:</strong> There are many other paths to prepare you for this course. The important thing is that you have some exposure to probability theory and are comfortable coding.</p>

<p><strong>Course objectives:</strong> This is an introductory/intermediate statistics class with an emphasis on using simulation to explore statistical models. You will learn how to build, fit, and make predictions with regression models. Such models form the basis of many widely used data analysis techniques, including machine learning algorithms. This is an applied course, and we won’t spend much time deriving equations or proving theorems (at least compared to MATH 40 and 70). Instead, we will learn by playing around with real and simulated data. We will challenge the underlying assumptions of a method and see when things “break”. The goal is to help you develop an intuition about statistical inference, which can be generalized to real-world settings where theorems and analytical formulas are not applicable.

See <a href="schedule.html">weekly schedule</a> for detials. 

</p>






<p><strong>Note on coding:</strong> All coding for the course will be done in Python. Some advantages of Python (over R) are that: (1) We can easily run everything directly in the browser using Google <a href="https://colab.research.google.com/">Colab Notebooks</a>, so there is no need to download anything on your machine. (2) Python is widely used in data science and machine learning, both in academia and in industry. (3) While some very basic things are more difficult to implement, I think you’ll find it’s easier to generalize to more advanced methods. (4) I know Python and I’ve basically never coded in R.</p>

<p><strong>My availability:</strong> I will hold office hours in person:</p>
<ul>
    <li>Thursday 8:30am-10:00am AND 12:00pm - 1:30pm</li>
</ul>
<p>I will generally be available to answer questions on Slack (<span class="important">please use Slack over email for course-related matters</span>) throughout the week. I will occasionally answer questions on the weekend, but there is no guarantee.</p>
</details>

<details>
<summary>Course policies</summary>


<p><strong>Attendance:</strong> The course meets twice a week and attendance is mandatory.</p>

<p><span class="important"><strong>Exams:</strong> There will be an (in-class) midterm quiz and a final. I will provide more details in class.</span></p>

<p><strong>Exercises:</strong> Your homework is to submit solutions to a set of exercises. You will submit your solutions to Canvas (approximately) every week before I release the solutions. Then, the following week you will self-evaluate (i.e., grade) your solutions and submit the evaluation. You should use the following point scale, which I will elaborate on in class.</p>
<ul>
    <li>0 - No work was done, or barely any effort was made.</li>
    <li>1 - You put down partial work, but didn't put much effort in and didn't reach out if you needed help.</li>
    <li>2 - You put in effort, but didn't get the problem exactly correct. You reached out at least once if you needed help.</li>
    <li>3 - You got the problem correct, or made a very significant effort, including attending office hours and asking questions on Slack if needed.</li>
</ul>
<p>The number of points you get for each self-evaluation is the score you’ve given yourself plus an additional point for providing an explanation of what you did wrong. The graders will review your self-evaluations.</p>

<strong>Guidelines for turning in exercises:</strong>
<ul>
    <li>They should be turned in in PDF form on Canvas. You can produce this PDF directly from your Colab notebook by saving it as a PDF or by copying screenshots of your code into a word document and exporting it as a PDF. There are many other ways as well.</li>
    <li>All code and figures should be in the PDF.</li>
    <li>Exercises should be in order and clearly labeled.</li>
</ul>


<p><strong>Final grades:</strong> See Canvas for details on how your final grade will be computed.</p>

<p><strong>Use of Large Language Models (LLM) such as ChatGPT:</strong> I STRONGLY encourage you to use LLM to assist with exercises and the final project. However, it is important that you use it in a way that supports learning the material and not as a crutch. Therefore, usage of ChatGPT and other AI programs is subject to the following guidelines.</p>

<ol>
    <li>You can use LLM to help write code, proofread your writing, and answer conceptual questions.</li>
    <li>In some instances, I may specifically ask you to use ChatGPT. In this case, the above constraints may not apply.</li>
    <li>You may NOT use it to produce entire written answers.</li>
    <li>You may not copy and paste the exercises into ChatGPT prompts. In fact, I have tested many of the problems and found this will give nonsensical or incorrect answers (some exceptions are inevitable, of course).</li>
    <li>If you use LLM to answer a homework question, you must include an explanation of how you used it. You do not need to share the entire chat transcript, but you should summarize the arc of the conversation and key prompts you used in a sentence or two.</li>
    <li>You may only use LLM programs which are publicly available or accessible to ALL Dartmouth students free of charge.</li>
</ol>

<p>Here are some examples of <span style="color: blue;"><strong>acceptable</strong></span> LLM usage:</p>
<ul>
    <li>"How do I reformat a pandas DataFrame so that the columns and rows are switched?"</li>
    <li>"Given numpy arrays <code>x</code>, <code>y</code>, and <code>z</code>, how do I make a scatter plot where <code>x</code> and <code>y</code> are the coordinates and <code>z</code> is the color of the point?"</li>
    <li>"In class, my professor said [insert something I said]. I'm having trouble understanding this statement, can you help me?"</li>
    <li>"Proofread this paragraph from my project proposal [insert text from project proposal]."</li>
    <li>"When I run this code [insert your code], I get the following error [insert error], can you help me debug it?"</li>
</ul>

<p><span class="important">[Note: I reserve the right to change the guidelines above at any point during the term.]</span></p>

</details>

<details>
<summary>Resources</summary>



<p> <strong> Textbooks: </strong> The course is based on two textbooks: </p>
<ul>
    <li><a href="https://hastie.su.domains/ISLP/ISLP_website.pdf">Introduction to Statistical Learning (Python version)</a>: This is a textbook on statistics and machine learning which covers regression. It is helpful to get a different perspective. The approach I take is much more probabilistic. In particular, I prefer to make it more explicit how the models are grounded in underlying probability distributions.</li>
    <li><a href="https://www.utstat.toronto.edu/mikevans/jeffrosenthal/">Probability and Statistics -- The Science of Uncertainty (Second Edition)</a>: This is a textbook on probability theory which is far more technical than the level of this course, however, it contains many useful examples and exercises which are appropriate for Math 50.</li>
</ul>

<p><strong>Software:</strong> All coding will be done using Python in <a href="https://colab.research.google.com/">Colab Notebooks</a>. Within Python, there are a number of packages we will use throughout the course, including:</p>
<ul>
    <li><a href="https://numpy.org/">numpy</a> for working with arrays, linear algebra, and generating random numbers.</li>
    <li><a href="https://pandas.pydata.org/">pandas</a> for working with tabular data sets.</li>
    <li><a href="https://www.statsmodels.org/stable/index.html">statsmodels</a> for classical statistics.</li>
</ul>
</details>

<details>
<summary>Accessibility Needs</summary>

<p>Students with disabilities who may need disability-related academic adjustments and services for this course are encouraged to see me privately as early in the term as possible. Students requiring disability-related academic adjustments and services must consult the Student Accessibility Services office (Carson Hall, Suite 125, 646-9900). Once SAS has authorized services, students must show the originally signed SAS Services and Consent Form and/or a letter on SAS letterhead to me. As a first step, if students have questions about whether they qualify to receive academic adjustments and services, they should contact the SAS office. All inquiries and discussions will remain confidential.</p>
</details>
