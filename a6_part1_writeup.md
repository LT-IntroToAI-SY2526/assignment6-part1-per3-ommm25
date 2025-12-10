# Assignment 6 Part 1 - Writeup

**Name:** _______________  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**
The R^2 score tells you about the variance as in how close it is to the actual score. If it is close to 1.00 that means its is highly accurate and as it goes down towards 0 it gets less and less accurate. 




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**
MSE means how accurate/far the model predicts the values . I think teh errors are squared to eliminate negative values from being the value since you cannot have negative values when you square a value.




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**

I would trust it a litte bit to a certain extent, the maximum hours in the dataset is 9 hours. When you make predictions outside the range of the training data values are often inaccurate due to variables correlating too much/too little to the actual number so at one point it becomes unnaccuate.




---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
The relatinship between hours studied and test scores is strong, it is linear as seen in the graph and it is positive not negative.



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Mental state
2. Hours slept that day
3. Nutrition prior to the test (brain fog if you don't eat)


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**

We split it so that we can compare both datasets, the real one versus the training one. After that is out of the way we then compare both datasets to compare how accurat ethe training one is compared to the actual testing data. If we trained and tested on the same data the progrm would just memorize it instead of predicting it.




---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**
The most challenging part was starting the code from scratch so what I did towards the end is just find differences in values and recognized what code does what and copy and pasted it with different values since all you need to do is understand the code from other assignments but with different values.




---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**




---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
