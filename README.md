# Applied Statistics

This repository contains solutions for a series of statistical problems and a project involving the **PlantGrowth dataset**. The tasks cover topics such as permutations and combinations, normal distribution analysis, t-tests, and ANOVA. Additionally, the repository includes a project focusing on data analysis and statistical testing with the **PlantGrowth dataset**.

## Contents

1. [Task 1: Permutations and Combinations](#task-1-permutations-and-combinations)
2. [Task 2: Numpy's Normal Distribution](#task-2-numpys-normal-distribution)
3. [Task 3: t-Test Calculation](#task-3-t-test-calculation)
4. [Task 4: ANOVA](#task-4-anova)
5. [PlantGrowth Dataset Project](#plantgrowth-dataset-project)

---

## Task 1: Permutations and Combinations

### Problem Overview:
We have twelve cups: six with tea first and six with milk first. A person claims they can tell which six cups had the milk in first by taste. We need to calculate the probability of them guessing the correct six cups and the probability of them making at most one error. Finally, we analyze if accepting two errors is reasonable.

---

## Task 2: Numpy's Normal Distribution

### Problem Overview:
We assess whether `numpy.random.normal()` generates values that follow a normal distribution. To do this, we generate a sample of 100,000 values with a mean of 10.0 and a standard deviation of 3.0, and then test for normality using the Shapiro-Wilk test.

---

## Task 3: t-Test Calculation

### Problem Overview:
We are given two datasets (before and after exercise) containing resting heart rates for patients. We need to calculate the t-statistic for the paired sample t-test to compare the means before and after the exercise program.

---

## Task 4: ANOVA

### Problem Overview:
We will perform a one-way ANOVA test on three samples, each generated from a normal distribution with slightly different means. The goal is to estimate the probability of committing a Type II error (failing to reject the null hypothesis) when there is actually a difference between the means.

---

## PlantGrowth Dataset Project

### Problem Overview:
In this project, we will perform **t-tests** and **ANOVA** on the **PlantGrowth dataset**, which contains data on plant growth under different treatment conditions. The goal is to determine if there are significant differences in plant growth based on the treatment groups (control, treatment 1, and treatment 2).

### Steps:

1. **Download and Save the Dataset**: First, you need to download the dataset from a reliable source and save it to your repository.

2. **Describe the Dataset**:
   - The dataset contains information about the growth of plants under three different treatment groups: `ctrl` (control), `trt1` (treatment 1), and `trt2` (treatment 2).
   - It includes two columns: `weight` (the growth measurement of the plant) and `group` (the treatment group assigned to the plant).


   
3. **What is a t-test?**
- A **t-test** is used to compare the means of two groups to determine if there is a statistically significant difference between them.
- **Assumptions** for a t-test include:
  - The data is normally distributed in each group.
  - The variances of the two groups are equal (for an independent t-test).
  - The samples are independent of each other.

4. **Perform a t-test**:
- We will perform a **two-sample t-test** to compare the two treatment groups `trt1` and `trt2` to determine if there is a significant difference between the means of these two groups.

5. **Perform ANOVA**:
- We will also perform a **one-way ANOVA** to compare all three treatment groups (`ctrl`, `trt1`, and `trt2`) and test if there is a significant difference in plant growth between them.

6. **Why ANOVA and not several t-tests?**
- **ANOVA** is preferred when comparing more than two groups because:
  - Conducting multiple t-tests increases the chance of Type I error (false positives).
  - ANOVA controls the overall error rate while testing for differences between multiple groups simultaneously.

---

## Conclusion

Each of these tasks demonstrates a fundamental statistical technique in Python, from calculating probabilities in combinations to performing ANOVA and t-tests. Additionally, the **PlantGrowth dataset project** allows us to apply these techniques to real-world data analysis, providing a comprehensive approach to statistical reasoning and hypothesis testing.

### Dependencies:
To execute the code for these tasks, you will need the following Python libraries:
- `numpy`
- `scipy`
- `matplotlib`
- `pandas`

These libraries can be installed using the following command:

