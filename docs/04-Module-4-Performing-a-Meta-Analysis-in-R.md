<script>
document.addEventListener("DOMContentLoaded", function() {
  var password = prompt("Enter password to view the course:");
  if (password !== "Course2025!") {
    document.body.innerHTML = "<h2>Access denied</h2>";
  }
});
</script>

# Module 4: Performing a Meta-Analysis in R 

By the end of this module, students will be able to:

•	Import, clean, and structure data for meta-analysis in R.

•	Calculate common effect size measures (e.g., mean differences, odds ratios, risk ratios) from raw data or summary statistics.

•	Conduct meta-analysis using both random and fixed effect models and interpret their results.

•	Quantify and interpret heterogeneity using statistical measures such as Cochran’s Q and I²




-
## Lecture 4.1: Cleaning, and Structuring Data for Meta-Analysis in R

Welcome! In this short lecture we’ll explain why cleaning and structuring data are essential for meta-analysis and demonstrate practical R workflows. You’ll learn to import an Excel file with readxl, remove incomplete or inconsistent rows, and handle missing values using dplyr. We’ll also convert variables—such as Intervention_Type—into appropriate types and factors so models run correctly. Proper cleaning prevents biased or misleading results by ensuring consistent formats and accurate inputs. After the lecture, download the R script and sample dataset from the course eBook to practice in RStudio.

Now Enjoy the Lecture!

<br>

**Lecture Practice Assignment** 


In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 4.1 Demonstration**, copy the code, and try running it in RStudio as you follow along step by step. 

<br>

-
## Lecture 4.2: Pooled Prevalence Estimation

Welcome to this lecture on calculating pooled prevalence in meta-analysis. Pooled prevalence is a powerful method for summarizing results across multiple studies, providing a single, overall estimate of how common a condition is across different populations or settings. In this session, we’ll cover key concepts such as prevalence, study weighting, and heterogeneity, measured by I², which tells us how consistent study results are. You’ll learn how to extract data, stabilize proportions, and implement a random-effects model in R using the meta package. By the end, you’ll understand how to interpret pooled estimates and apply your knowledge in previous lecture to assess their reliability.

Now enjoy the Lecture!

<br>

**Additional Sources** 

<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 4.2 Demonstration**, copy the code, and try running it in RStudio as you follow along step by step.

<br>

-
## Lecture 4.3 - Pre-Post_Comparison MetaAnalysis

Welcome to this lecture on analyzing continuous data in studies comparing two groups before and after an intervention. We’ll focus on understanding how interventions impact outcomes like blood pressure, weight, or knowledge scores. Using a simulated dataset, we’ll calculate the mean change in each group and combine results across studies using a random-effects meta-analysis. You’ll learn how to implement this in R with the metafor package, interpret effect sizes, assess statistical significance, and evaluate heterogeneity. Finally, you’ll have hands-on practice with the provided R code and dataset.

Now Enjoy the Lecture!


<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 4.3 Demonstration**, copy the code, and try running it in RStudio as you follow along step by step.

<br>


-
## Lecture 4.4 - Single Group Pre - Post data 

Welcome to this lecture on analyzing continuous data from a single group before and after an intervention. This design is widely used in behavioral and health sciences to measure whether an intervention produces meaningful change in outcomes such as stress levels, weight, or test scores. We’ll explore how to calculate mean differences and standardized mean change, even when only summary statistics are reported. Using R and the metafor package, we’ll simulate data, estimate effect sizes, and run a random-effects meta-analysis.

Now Enjoy the Lecture!



<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 4.4 Demonstration**, copy the code, and try running it in RStudio as you follow along step by step.

<br>



-
## Lecture 4.5 - Binary Data for a Post-Test Only Design

Welcome to this lecture on analyzing binary data in a post-test-only design. In this type of study, outcomes are measured only after the intervention, making it a common approach when baseline data are unavailable. We’ll focus on comparing two groups—such as treatment versus control—using binary outcomes like recovery (yes/no) or event occurrence. The central measure is the odds ratio (OR), which indicates how much more likely the outcome is in the treatment group compared to control. You’ll also see how pooled ORs are calculated across studies using fixed- or random-effects models, and practice applying this in R.

Now Enjoy the Lecture!

 

<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 4.5 Demonstration**, copy the code, and try running it in RStudio as you follow along step by step.



<br><br>


**Wrap-up**

In this module, you engaged in hands-on practice using R to apply key techniques in meta-analysis. Working with sample datasets, you learned how to compute pooled prevalence estimates, perform pre–post test comparisons, analyze single-group pre–post test data, and conduct binary outcome post-test meta-analyses. These practical exercises allowed you to apply statistical concepts to real-world scenarios. By completing this module, you are now better equipped to apply these methods to your own systematic review, ensuring greater rigor and reproducibility in your analysis.

<br>

**Looking ahead**

Module 5 builds upon your understanding of meta-analysis by introducing more advanced analytical techniques, including publication bias, moderator analysis, and subgroup analysis. You will explore how to identify and assess publication bias using tools such as funnel plots and statistical tests like Egger’s regression. The module also covers methods for conducting moderator and subgroup analyses to examine how study-level characteristics—such as population differences, intervention types, or methodological quality—may influence effect sizes. These approaches are essential for interpreting heterogeneity in meta-analysis and ensuring that your findings are both accurate and applicable to diverse contexts.

<br>


-
## Module 4 - Quiz 

This quiz is designed to help you review and reinforce the key concepts covered in the first module. Take your time to read each question carefully, and apply the knowledge you’ve gained from the lectures and hands-on activities. Remember, the quiz is meant to support your learning, so it’s a great way to identify areas you may want to revisit before moving on.

All the best, and enjoy testing your understanding!

[**Begin your Module 4 Quiz Now**](https://tassitano-lab.shinyapps.io/SystematicReviewQuiz/)

<br>


**Kindly click this link below to provide feedback to improve this module**

[**Click here to provide feedback**](https://surveys.illinois.edu/sec/1019362512)



Thank you for taking time to provide your feedback to improve the course. See you on the next module. 

