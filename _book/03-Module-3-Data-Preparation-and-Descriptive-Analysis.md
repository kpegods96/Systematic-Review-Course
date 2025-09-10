<script>
document.addEventListener("DOMContentLoaded", function() {
  var password = prompt("Enter password to view the course:");
  if (password !== "Course2025!") {
    document.body.innerHTML = "<h2>Access denied</h2>";
  }
});
</script>

# Module 3: Data Preparation and Descriptive Analysis 

<br>

Welcome to this module on data extraction and descriptive analysis in systematic reviews. In this session, you will learn how to move from raw study information to structured, analyzable datasets. We’ll practice identifying essential study characteristics, outcome measures, and effect sizes, and then converting them into formats suitable for statistical analysis. You will also gain skills in handling missing data, detecting errors and inconsistencies, and reducing potential bias. Finally, we’ll explore descriptive statistics and visualizations—such as summary tables, histograms, and boxplots—to identify data patterns and sources of variability. These skills will prepare you for effect size calculation and further analyses.

<br>


-
## Lesson 3.1 - Handling Missing Data 

Hello and welcome! In this lecture, we’ll explore how to handle missing or incomplete data in systematic reviews—a common challenge that, if left unaddressed, can introduce bias and weaken conclusions. Our goal is to equip you with practical strategies to manage missing data effectively. You’ll learn about the risks of incomplete data, as well as techniques like mean imputation, last observation carried forward, and multiple imputation—essential tools for every evidence reviewer. We’ll also emphasize the importance of first contacting study authors to obtain missing information before applying these methods. Let’s dive in and build confidence in handling missing data.

Now enjoy the lecture 

<video width="700" height="500" controls>
  <source src="http://publish.illinois.edu/tassitanolab-training/files/2025/08/Lecture-3.1.mp4">
  Your browser does not support the video tag.
</video>

<br><br>


**Additional Sources:**

[Potential impact of missing outcome data on treatment effects in systematic reviews: imputation study](http://publish.illinois.edu/tassitanolab-training/files/2025/09/Kahale_2020_Potential-impact-of-missing-outcome-data-on-treatment-effects-in-systematic-reviews.pdf)


<br>

**Lecture Practice Assignment:**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 3.1 Demonstration: Handling Missing Data**, copy the code, and try running it in RStudio as you follow along step by step.

<br><br>


-
## Lesson 3.2 - Exploring Heterogeneity in Systematic Review Data

Welcome to today’s lecture on interpreting heterogeneity in meta-analysis. When we combine results from multiple studies, we rarely find identical outcomes. Instead, differences often emerge due to variations in study design, populations, or interventions. This variability, known as heterogeneity, is a critical concept to understand because it influences how much confidence we can place in pooled results. In this session, we’ll explore statistical tools such as Cochran’s Q, its p-value, and the I² statistic, as well as visual tools like the forest plot. These methods together provide a clearer picture of study consistency and overall evidence strength.

Now enjoy the lecture


<video width="700" height="500" controls>
  <source src="http://publish.illinois.edu/tassitanolab-training/files/2025/08/Lecture-3.2.mp4">
  Your browser does not support the video tag.
</video>
 

<br><br>



**Additional Sources:**

[Heterogeneity in meta-analyses: an unavoidable challenge worth exploring]( http://publish.illinois.edu/tassitanolab-training/files/2025/09/Choi_2025_Heterogeneity-in-meta-analyses-an-unavoidable-challenge-worth-exploring.pdf)


<br>


**Lecture Practice Assignment:**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 3.2 Demonstration: Exploring Heterogeneity in Systematic Review Data**, copy the code, and try running it in RStudio as you follow along step by step..


<br><br>


<br><br>

-
## Lecture 3.3 -  Effect size in Meta - Analysis 

Welcome! In this short lecture, we’ll dive into the concept of effect size, a cornerstone of meta-analysis. Effect size helps us move beyond statistical significance by showing the magnitude and practical importance of an intervention’s impact across studies. Unlike p-values, it provides a standardized measure that makes results comparable, even when different scales are used. We’ll explore common metrics such as Cohen’s d, Hedges’ g, odds ratios, and correlations, highlighting when and how to use them. By the end, you’ll understand why effect sizes are essential for interpreting and synthesizing research findings meaningfully.

Now enjoy the lecture 

<video width="700" height="500" controls>
  <source src="http://publish.illinois.edu/tassitanolab-training/files/2025/08/Lecture-3.3.mp4">
  Your browser does not support the video tag.
</video>

<br><br>


**Additional Sources:**


[Practical Meta Analysis Effect Size Calculator](https://www.campbellcollaboration.org/calculator/#)


<br>


**Lecture Practice Assignment:**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 3.3 Demonstration: Effect size in Meta - Analysis **, copy the code, and try running it in RStudio as you follow along step by step.

<br><br>


-
## Lecture 3.4 - Fixed and Random Effect Models 

Welcome! In this lecture, we’ll explore two fundamental statistical models in meta-analysis: the fixed effect model and the random effects model. Understanding these models is crucial because they shape how we interpret pooled results across studies. While the fixed effect model assumes all studies estimate the same underlying effect, the random effects model accounts for variability between studies, offering more generalizable conclusions. We’ll look at the assumptions behind each, when they should be applied, and examples of their use in real research. By the end, you’ll be equipped to choose the most appropriate model for your analyses.

Now enjoy the lecture 

<video width="700" height="500" controls>
  <source src="http://publish.illinois.edu/tassitanolab-training/files/2025/08/Lecture-3.4.mp4">
  Your browser does not support the video tag.
</video>


<br><br>


**Additional Sources:**


[Fixed-Effect vs Random-Effects Models for Meta-Analysis: 3 Points to Consider]( http://publish.illinois.edu/tassitanolab-training/files/2025/09/Dettori_2022_Fixed-Effect-vs-Random-Effects-Models-for-meta-analysis.pdf)

<br>


**Lecture Practice Assignment:**

Click the link below to view the questions and instructions for Assignment 4 in Module 3. Make sure to read through everything carefully before you get started!

[***Begin Module 3 – Assignment 4***](http://publish.illinois.edu/tassitanolab-training/files/2025/09/Module-3-–-Lecture-3.4-assignment.pdf)

<br><br>


**Wrap-up**

In this module, you gained hands-on experience in extracting meta-data from selected studies, a critical step in preparing for meta-analysis. You also practiced how to calculate effect sizes using R code, deepening your understanding of how study outcomes are quantitatively synthesized. Additionally, the module explored the underlying assumptions and appropriate applications of both fixed-effect and random-effects models, helping you develop the skills to select the most suitable model based on study characteristics and the presence of heterogeneity.

<br>


**Looking ahead**

In the next module, you will engage in more hands-on practice using R to strengthen your practical skills in meta-analysis. With the aid of sample datasets, you will learn how to compute pooled prevalence estimates, perform pre–post test comparisons, analyze single-group pre–post test data, and conduct binary outcome post-test meta-analyses. These exercises are designed to help you apply key statistical techniques to real-world scenarios. By the end of the module, you will be equipped to confidently apply these methods to your own systematic review, enhancing both the rigor and reproducibility of your analysis.

<br>


-
## Module 3 - Quiz 

This quiz is designed to help you review and reinforce the key concepts covered in the first module. Take your time to read each question carefully, and apply the knowledge you’ve gained from the lectures and hands-on activities. Remember, the quiz is meant to support your learning, so it’s a great way to identify areas you may want to revisit before moving on.

All the best, and enjoy testing your understanding!

[**Begin your Module 3 Quiz Now**](https://tassitano-lab.shinyapps.io/SystematicReviewQuiz/)

<br>


**Kindly click this link below to provide feedback to improve this module**

[**Click here to provide feedback**](https://surveys.illinois.edu/sec/1705982931)



Thank you for taking time to provide your feedback to improve the course. See you on the next module. 
