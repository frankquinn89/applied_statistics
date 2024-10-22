# Applied Statistics
---------------------------------
# Tasks 

## Task 1: Permutations and Combinations
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

Would you accept two errors? Explain.

---------------------------------

## Task 2: Numpy's Normal Distribution

In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

------------------------------

# Project

# PlantGrowth Dataset

- **Variables**:
  - **weight**: Numeric variable representing the weight of the plants (in grams).
  - **group**: Factor variable indicating the treatment group to which the plant belongs. It has three levels:
    - `ctrl`: Control group
    - `trt1`: Treatment 1
    - `trt2`: Treatment 2

## Content

- The dataset contains measurements of plant weights that have been subjected to different growth treatments. The goal is often to compare the effects of these treatments on plant growth.

## Size

- The dataset typically consists of **30 observations** (plants), with **10 plants** in each treatment group.

## Purpose

- Used for analysis of variance (ANOVA) to examine if there are statistically significant differences in plant weights between the treatment groups.

## Example Use

- You can use this dataset to perform ANOVA, visualize the weight distribution among groups, and draw conclusions about the effects of the treatments.

This dataset is useful for educational purposes in statistics and data analysis.
