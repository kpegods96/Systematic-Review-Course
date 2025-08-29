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

•	Explain the key concepts, assumptions, and statistical models (Random and fixed effect models) used in meta-analysis.

•	Import, clean, and structure data for meta-analysis in R.

•	Calculate common effect size measures (e.g., mean differences, odds ratios, risk ratios) from raw data or summary statistics.

•	Conduct meta-analysis using both random and fixed effect models and interpret their results.

•	Quantify and interpret heterogeneity using statistical measures such as Cochran’s Q, I², and Tau².




## Lesson 4.1: Introduction to Meta-Analysis

o	Key concepts: effect sizes, heterogeneity, and bias

o	When to conduct a meta-analysis

o	Standardized mean differences, odds ratios, and risk ratios

o	Using the esc package to compute effect sizes


## Lesson 4.2: Fixed-Effect vs. Random-Effects Models

o	Understanding heterogeneity (Cochran’s Q, I²)

o	Running meta-analysis using the metafor package


