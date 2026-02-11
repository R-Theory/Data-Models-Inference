# 🎓 MIDTERM 1 PRACTICE QUIZ
**Time limit: 75 minutes (simulate exam conditions)**

---

## SECTION 1: MULTIPLE CHOICE (2 points each)

### Question 1
Which of the following is a numerical discrete variable?
- A) Temperature in degrees Celsius
- B) Number of students in a classroom  
- C) Height of a building
- D) Time to run a mile

<details>
<summary>Click for answer</summary>
**Answer: B** - Number of students is countable (discrete numerical)
- A, C, D are continuous (can take any value in a range)
</details>

---

### Question 2
A researcher wants to study employee satisfaction at a large company. She randomly selects 10 departments and surveys ALL employees in those departments. What sampling method is this?
- A) Simple Random Sample
- B) Stratified Sampling
- C) Cluster Sampling
- D) Convenience Sampling

<details>
<summary>Click for answer</summary>
**Answer: C** - Cluster Sampling
- Randomly selects SOME groups (departments) 
- Surveys EVERYONE in selected groups
</details>

---

### Question 3
An observational study finds that people who drink coffee have lower rates of heart disease. What can we conclude?
- A) Coffee prevents heart disease
- B) Coffee causes lower heart disease rates
- C) People with lower heart disease rates tend to drink more coffee
- D) Coffee is associated with lower heart disease rates, but we cannot establish causation

<details>
<summary>Click for answer</summary>
**Answer: D** - Observational studies CANNOT establish causation
- Could be confounding variables (exercise, diet, genetics, etc.)
- Correlation ≠ Causation
</details>

---

### Question 4
Which of these is NOT a principle of experimental design?
- A) Control
- B) Randomize
- C) Stratify
- D) Replicate

<details>
<summary>Click for answer</summary>
**Answer: C** - Stratify is a sampling method, not an experimental design principle
- The 4 principles are: Control, Randomize, Replicate, Block
</details>

---

### Question 5
A distribution has mean = 75 and median = 80. What is the shape?
- A) Right-skewed
- B) Left-skewed
- C) Symmetric
- D) Cannot determine from this information

<details>
<summary>Click for answer</summary>
**Answer: B** - Left-skewed
- Mean < Median indicates left-skew (tail on left pulls mean down)
</details>

---

### Question 6
Which measure of spread is most affected by outliers?
- A) Range
- B) Interquartile Range
- C) Standard Deviation
- D) Both A and C

<details>
<summary>Click for answer</summary>
**Answer: D** - Both range and standard deviation
- Range uses min and max (extreme values!)
- SD uses all values, outliers have large squared deviations
- IQR is robust (uses middle 50%)
</details>

---

### Question 7
If correlation r = 0, what can we conclude?
- A) There is no relationship between the variables
- B) There is no linear relationship between the variables
- C) The variables are independent
- D) One variable does not affect the other

<details>
<summary>Click for answer</summary>
**Answer: B** - No LINEAR relationship
- Could still have strong nonlinear relationship (e.g., parabola)
- Never confuse "no linear relationship" with "no relationship"
</details>

---

### Question 8
What happens to the correlation if we add 5 to every x-value?
- A) Correlation increases by 5
- B) Correlation decreases by 5
- C) Correlation stays the same
- D) Cannot determine without more information

<details>
<summary>Click for answer</summary>
**Answer: C** - Correlation is invariant under translation
- Adding/subtracting constants doesn't change correlation
</details>

---

### Question 9
Events A and B are mutually exclusive. P(A) = 0.3 and P(B) = 0.4. What is P(A or B)?
- A) 0.12
- B) 0.58
- C) 0.70
- D) 1.00

<details>
<summary>Click for answer</summary>
**Answer: C** - 0.70
- Mutually exclusive means P(A and B) = 0
- P(A or B) = P(A) + P(B) = 0.3 + 0.4 = 0.7
</details>

---

### Question 10
The 75th percentile of a dataset is 90. What does this mean?
- A) 75% of the data values are less than 90
- B) 75% of the data values are greater than or equal to 90
- C) 75% of the data values equal 90
- D) 75% of the data values are less than or equal to 90

<details>
<summary>Click for answer</summary>
**Answer: D** - 75% are ≤ 90
- The 75th percentile is the value that is greater than or equal to 75% of the data
- Equivalently, 75% of data is less than or equal to that value
</details>

---

## SECTION 2: SHORT ANSWER (5 points each)

### Question 11
Data: 3, 5, 7, 9, 11, 13, 100

a) Calculate the mean
b) Calculate the median
c) Is there an outlier? Show your work using the IQR criterion.

<details>
<summary>Click for answer</summary>

a) **Mean**: (3+5+7+9+11+13+100)/7 = 148/7 = **21.14**

b) **Median**: Middle value when sorted = **9**

c) **Outlier check**:
- Q1 = median of lower half {3,5,7} = **5**
- Q3 = median of upper half {11,13,100} = **13**
- IQR = 13 - 5 = **8**
- Lower fence: 5 - 1.5(8) = 5 - 12 = **-7**
- Upper fence: 13 + 1.5(8) = 13 + 12 = **25**
- 100 > 25, so **100 is an outlier** ✓
</details>

---

### Question 12
A study wants to test if a new teaching method improves test scores. Researchers:
- Recruit 200 students
- Randomly assign 100 to new method, 100 to traditional
- Give same final exam to both groups

a) Is this an experiment or observational study? Why?
b) What is the explanatory variable?
c) What is the response variable?
d) Can this study establish causation? Why or why not?

<details>
<summary>Click for answer</summary>

a) **Experiment** - Researchers actively assigned the treatment (teaching method)

b) **Explanatory variable**: Teaching method (new vs traditional)

c) **Response variable**: Test score

d) **YES, can establish causation** because:
- Random assignment to treatment groups
- Controls for confounding variables through randomization
- This is a properly designed experiment
</details>

---

### Question 13
Describe the sampling method:

"A researcher wants to survey college students about campus dining. She divides students into four groups: Freshmen, Sophomores, Juniors, and Seniors. She then randomly selects 50 students from each group."

What sampling method is this? Explain why this method was chosen.

<details>
<summary>Click for answer</summary>

**Stratified Sampling**

Why this method:
- Population divided into strata (class year)
- Simple random sample taken from EACH stratum
- Ensures all class years are represented
- Class year might affect dining preferences, so we want to ensure each group is represented proportionally
</details>

---

### Question 14
Two variables have correlation r = 0.85.

a) Describe the relationship in words.
b) If all x-values were multiplied by 2, what would the new correlation be?
c) Can we conclude that changes in x CAUSE changes in y? Why or why not?

<details>
<summary>Click for answer</summary>

a) **Strong positive linear relationship** - As x increases, y tends to increase, and points cluster closely around a line with positive slope

b) **Still 0.85** - Correlation is invariant under scaling (multiplying/dividing by constants)

c) **NO** - Correlation alone cannot establish causation. We would need a properly designed experiment with random assignment to establish causal relationship.
</details>

---

### Question 15
Given: Data: 12, 15, 18, 20, 22, 25, 28

Calculate the sample variance. Show all steps.

<details>
<summary>Click for answer</summary>

**Steps:**

1. Calculate mean:
   x̄ = (12+15+18+20+22+25+28)/7 = 140/7 = **20**

2. Calculate deviations from mean:
   (12-20) = -8
   (15-20) = -5
   (18-20) = -2
   (20-20) = 0
   (22-20) = 2
   (25-20) = 5
   (28-20) = 8

3. Square the deviations:
   64, 25, 4, 0, 4, 25, 64

4. Sum squared deviations:
   64+25+4+0+4+25+64 = **186**

5. Divide by (n-1):
   s² = 186/(7-1) = 186/6 = **31**

**Answer: s² = 31**
</details>

---

## SECTION 3: FREE RESPONSE (10 points each)

### Question 16
A researcher wants to study the relationship between hours of sleep and test performance.

**Study A**: She surveys 500 students, asking them to report average sleep hours and their most recent test score. She finds students who sleep more have higher test scores (r = 0.65).

**Study B**: She recruits 100 students and randomly assigns 50 to sleep 8 hours before the test and 50 to sleep 6 hours. She finds the 8-hour group scored significantly higher.

a) Identify the type of study for Study A and Study B
b) Can Study A establish that more sleep CAUSES better performance? Why or why not?
c) Can Study B establish that more sleep CAUSES better performance? Why or why not?
d) Name two possible confounding variables in Study A
e) What is one advantage of Study A over Study B?

<details>
<summary>Click for answer</summary>

a) 
- **Study A**: Observational study (passive data collection)
- **Study B**: Experiment (active manipulation of sleep)

b) **NO** - Observational study cannot establish causation
- Could be confounding variables affecting both sleep and performance
- Correlation does not imply causation

c) **YES** - Randomized experiment can establish causation
- Random assignment controls for confounding variables
- Direct manipulation of explanatory variable (sleep)
- Proper experimental design

d) **Possible confounding variables** (any 2):
- Study habits (good students study more AND sleep more)
- Stress levels (less stressed → better sleep AND better performance)
- Overall health
- Course difficulty
- Prior knowledge/ability
- Time management skills

e) **Advantages of Study A** (any 1):
- Larger sample size (500 vs 100) → better generalizability
- More realistic (natural sleep patterns, not manipulated)
- Less expensive and easier to conduct
- No ethical concerns about sleep deprivation
</details>

---

### Question 17
The following data shows ages of 10 people at a family reunion:
**5, 8, 12, 15, 18, 22, 28, 35, 42, 87**

a) Create a five-number summary
b) Draw a properly labeled boxplot
c) Describe the shape of the distribution
d) Calculate the mean and median. Do they support your answer to part (c)?
e) Which measure of center is more appropriate here? Why?

<details>
<summary>Click for answer</summary>

a) **Five-number summary**:
- Minimum: **5**
- Q1: (12+15)/2 = **13.5**
- Median: (18+22)/2 = **20**
- Q3: (35+42)/2 = **38.5**
- Maximum: **87**

Check for outliers:
- IQR = 38.5 - 13.5 = 25
- Lower fence: 13.5 - 1.5(25) = -24 (no outliers here)
- Upper fence: 38.5 + 1.5(25) = 76
- 87 > 76, so 87 is an outlier

**Corrected five-number summary**:
Min=5, Q1=13.5, Median=20, Q3=38.5, Max (non-outlier)=42

b) **Boxplot**:
```
        [====|====]--------o
        |    |    |        •
        5   13.5  20  38.5 42   87
             Q1   M   Q3
```

c) **Shape**: RIGHT-SKEWED
- Long tail to the right
- One outlier on the high end (87)

d) **Mean and Median**:
- Mean = (5+8+12+15+18+22+28+35+42+87)/10 = 272/10 = **27.2**
- Median = **20** (calculated above)
- Mean > Median ✓
- **YES**, this supports right-skewed shape

e) **Median is more appropriate**
- Distribution is skewed
- There's an outlier (87)
- Median is robust to outliers and better represents typical value
- Mean (27.2) is pulled up by outlier, doesn't represent most people well
</details>

---

## 📊 SCORING GUIDE

**Section 1** (20 points): _____ / 20
**Section 2** (25 points): _____ / 25  
**Section 3** (20 points): _____ / 20

**TOTAL**: _____ / 65 points

**Grading Scale:**
- A (90-100%): 59-65 points - You're ready!
- B (80-89%): 52-58 points - Review missed topics
- C (70-79%): 46-51 points - More practice needed
- D (60-69%): 39-45 points - Serious review required
- F (<60%): <39 points - Start over with study guide

---

**After completing quiz:** 
1. Check all answers
2. Calculate your score
3. For any mistakes, review that topic in the main study guide
4. Retake until you get 90%+ 

**You've got this! 💪**