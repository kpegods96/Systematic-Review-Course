<script>
document.addEventListener("DOMContentLoaded", function() {
  var password = prompt("Enter password to view the course:");
  if (password !== "Course2025!") {
    document.body.innerHTML = "<h2>Access denied</h2>";
  }
});
</script>


# Module 5: Assessing Bias and Heterogeneity

By the end of this module, students will be able to:

•	Utilize funnel plots and Egger’s test to detect potential publication bias.

•	Investigate sources of heterogeneity by conducting subgroup.

•	Apply meta-regression techniques to explore potential moderators of heterogeneity.


-
## Lecture 5.1 - Publication Bias 

Welcome! In today’s session, we will explore publication bias, a critical issue that can undermine the validity of systematic reviews and meta-analyses. Publication bias arises when studies reporting significant or positive findings are more likely to be published, while those with non-significant or negative results remain hidden. This selective visibility distorts the evidence base, leading to exaggerated estimates of effectiveness and potentially misleading conclusions. By understanding how publication bias occurs, recognizing its impact, and learning the methods used to detect and adjust for it, we can ensure that meta-analyses provide a more accurate and balanced reflection of reality.

Now Enjoy the Lecture!


<br>

**Additional Sources** 

<br>


-
## Lecture 5.2 - Funnel Plot in R

Welcome! In this lecture, we’ll focus on the funnel plot, a fundamental tool in meta-analysis for detecting publication bias and assessing the reliability of evidence. Funnel plots provide a simple yet powerful way to visualize whether all relevant studies—both large and small—are represented fairly in the data. When the plot is symmetrical, it suggests minimal bias, but asymmetry may indicate missing studies or selective reporting. Understanding how to construct and interpret funnel plots is essential for maintaining transparency and ensuring valid conclusions in systematic reviews. By the end, you’ll know why and how funnel plots strengthen evidence synthesis.

Now Enjoy the Lecture!


<br>

**Additional Sources** 

<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 5.2 Demonstration: Funnel Plot in R**, copy the code, and try running it in RStudio as you follow along step by step.

<br>


-
## Lecture 5.3 - Egger's Test in R

Welcome! In this session, we’ll examine Egger’s test, an important statistical method for detecting publication bias in meta-analyses. While funnel plots offer a visual way to identify potential bias, Egger’s test provides a more objective and quantitative approach. It assesses whether the funnel plot is symmetrical—an indicator that study results are being fairly represented. When asymmetry is present, it may suggest that smaller studies with null or negative findings are missing from the published literature. By learning how Egger’s test works and why it matters, you’ll gain a deeper understanding of how to strengthen the validity of meta-analysis.

Now Enjoy the Lecture!


<br>

**Additional Sources** 

<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 5.3 Demonstration: Egger's Test in R**, copy the code, and try running it in RStudio as you follow along step by step.


<br>



-
## Lecture 5.4 - Bibliometric Analysis Using Biblioshiny

Have you ever wondered how research trends are mapped across thousands of studies? Welcome! In this video, we’ll explore Bibliometric Analysis, a quantitative method used to study patterns within academic literature. Bibliometrics helps researchers examine citation counts, influential authors, keyword trends, and collaboration networks, offering powerful insights into how knowledge develops and spreads across disciplines. Coined by Alan Pritchard in 1969, bibliometrics has become central to research evaluation and science mapping. By revealing who publishes, what topics dominate, and how ideas connect, bibliometric analysis strengthens systematic reviews and guides future research, collaboration, and academic strategy.

Now Enjoy the Lecture!

<br>

**Additional Sources** 

<br>

**Lecture Practice Assignment**



<br>


-
## Lecture 5.5: Moderation - Subgroup Analysis 

Welcome! In this video, we’ll explore moderation and subgroup analysis in meta-analysis—two approaches that help explain variation in study results. Meta-analysis often reveals heterogeneity, meaning that effect sizes differ across studies. Moderation analysis investigates whether certain study characteristics, such as population type, setting, or methodology, account for these differences. Subgroup analysis, a specific form of moderation, focuses on categorical factors—for example, comparing treatment effects across genders or income levels. These methods are essential for understanding why outcomes may vary, refining interpretations, and guiding more tailored conclusions, provided they are applied carefully and supported by strong theoretical rationale.

Now Enjoy the Lecture!



<br>

**Additional Sources** 

<br>

**Lecture Practice Assignment**

In this practice assignment, start by clicking on this [**link**](https://kpegods96.github.io/demo/). Once there, head over to **Lecture 5.5 Demonstration: Moderation - Subgroup Analysis**, copy the code, and try running it in RStudio as you follow along step by step.


<br><br>

**Wrap-up**

In this module, you explored advanced techniques in meta-analysis, with a focus on publication bias, moderator analysis, and subgroup analysis. You learned how to detect publication bias using funnel plots and assess it statistically with Egger’s regression test, enhancing your ability to evaluate the credibility of meta-analytic findings. Through guided exercises using a sample dataset in R, you gained practical experience in applying these techniques. You also conducted moderator and subgroup analyses to explore how different study-level factors—such as population characteristics or intervention types—can influence effect sizes and contribute to heterogeneity. With these advanced tools and skills, you are now equipped to apply them to your own systematic review, allowing you to draw more robust, nuanced, and generalizable conclusions. 

<br>

**Looking ahead**

In the final module, you will learn how to effectively present the results of your meta-analysis to diverse audiences, including researchers, practitioners, and policymakers. The module will cover best practices for translating statistical findings into clear, actionable messages that can inform policy and practice. You will also explore how to create dynamic, reproducible reports using R Markdown, integrating text, code, and visualizations to ensure transparency and replicability in your work.

<br>


-
## Module 5 - Quiz 

This quiz is designed to help you review and reinforce the key concepts covered in the first module. Take your time to read each question carefully, and apply the knowledge you’ve gained from the lectures and hands-on activities. Remember, the quiz is meant to support your learning, so it’s a great way to identify areas you may want to revisit before moving on.

All the best, and enjoy testing your understanding!

[**Begin your Module 5 Quiz Now**](https://tassitano-lab.shinyapps.io/SystematicReviewQuiz/)

<br>


**Kindly click this link below to provide feedback to improve this module**

[**Click here to provide feedback**](https://surveys.illinois.edu/sec/26435143)



Thank you for taking time to provide your feedback to improve the course. See you on the next module. 

