# STOR 155 MIDTERM 1 - COMPLETE MASTERY GUIDE
**Exam Date: February 10, 2026 | Topics 1-8 (through Basic Probability)**

---

## 📋 TABLE OF CONTENTS
1. [Basics of Data](#1-basics-of-data)
2. [Data Collection & Sampling](#2-data-collection--sampling)
3. [Experiments](#3-experiments)
4. [Numerical Data Analysis](#4-numerical-data-analysis)
5. [Categorical Data Analysis](#5-categorical-data-analysis)
6. [Correlation](#6-correlation)
7. [Basic Probability](#7-basic-probability)
8. [Practice Problems](#8-practice-problems)
9. [Common Mistakes to Avoid](#9-common-mistakes)

---

## 1. BASICS OF DATA

### 🎯 Core Concepts

#### **Variables and Data Types**

**VARIABLE**: A characteristic/attribute that can take different values across observations

**Two Main Categories:**

1. **NUMERICAL (Quantitative)**
   - Can perform arithmetic operations
   - Has units of measurement
   - **Discrete**: Countable values (e.g., number of siblings: 0, 1, 2, 3...)
   - **Continuous**: Can take any value in a range (e.g., height: 5.7 ft, 5.75 ft, 5.752 ft...)

2. **CATEGORICAL (Qualitative)**
   - Describes qualities/categories
   - Cannot perform arithmetic operations
   - **Nominal**: No natural order (e.g., eye color: blue, brown, green)
   - **Ordinal**: Has natural order (e.g., education level: high school, bachelor's, master's, PhD)

#### **Critical Understanding:**
- Numbers can be categorical! (e.g., zip codes, jersey numbers)
- Test: Can you calculate the average? If meaningless → categorical
- Example: Average of zip codes 27514 and 27516 = 27515 ← MEANINGLESS!

#### **Key Terminology**

- **Population**: The ENTIRE group you want to study/make conclusions about
- **Sample**: A SUBSET of the population
- **Parameter**: A number describing the POPULATION (usually unknown)
- **Statistic**: A number describing the SAMPLE (what we calculate)

**Memory Aid**: 
- **P**arameter → **P**opulation (both start with P)
- **S**tatistic → **S**ample (both start with S)

---

## 2. DATA COLLECTION & SAMPLING

### 🎯 Three Sources of Data

#### 1. **Anecdotes**
- Individual stories or single cases
- ❌ **BAD for scientific inquiry**
- Cannot generalize from one or few cases
- Example: "My grandmother smoked and lived to 100, so smoking is fine"

#### 2. **Observational Studies**
- **PASSIVE data collection**
- Observe without influencing responses
- ✅ Good for exploring relationships
- ❌ **CANNOT establish causation**
- Why? **Confounding variables**

#### 3. **Experiments**
- **ACTIVE data collection**
- Deliberately influence responses with treatment
- ✅ **ONLY method to establish causation**
- ✅ Can control for confounding variables

### 🔑 Critical Concept: CAUSATION vs CORRELATION

**Confounding Variable**: A factor OTHER than your explanatory variable that might affect your response variable

**Example: Ice Cream and Drowning**
- Observational study finds: ↑ ice cream sales = ↑ drowning deaths
- Can we conclude ice cream CAUSES drowning? **NO!**
- Confounding variable: **TEMPERATURE**
  - Hot days → more ice cream sales
  - Hot days → more swimming → more drowning
  
**TO ESTABLISH CAUSATION, YOU MUST:**
1. Use an experiment (random assignment)
2. Control for confounding variables
3. Have proper experimental design

### 📊 Sampling Methods

#### **Why Sample?**
- Census = survey entire population
  - Usually too expensive, time-consuming, or impossible
- Sample = survey part of population
  - Make "educated guesses" about population

#### **The Golden Rule: RANDOM SELECTION**

**Good Sampling Methods (all involve randomness):**

1. **Simple Random Sample (SRS)**
   - Every member has equal chance of selection
   - Like "drawing names from a hat"
   - Example: Randomly select 100 student ID numbers

2. **Stratified Sampling**
   - Divide population into strata (homogeneous groups)
   - Take SRS from EACH stratum
   - Use when you believe a characteristic substantially influences results
   - Example: Stratify by gender, then SRS from each
   - **Goal**: Ensure all important subgroups are represented

3. **Cluster Sampling**
   - Divide population into clusters (heterogeneous groups)
   - Use SRS to select WHICH clusters
   - Survey EVERYONE in selected clusters
   - Use for convenience with large populations
   - **Goal**: Clusters should be "mini-populations" (diverse)
   - Example: Randomly select 5 schools, survey all students in those schools

4. **Multistage Sampling**
   - Cluster sampling + SRS within clusters
   - Use when clusters are too large to survey entirely
   - Example: Randomly select schools, then randomly select students within those schools

#### **Bad Sampling Methods (BIASED):**

1. **Convenience Sampling**
   - Sample only easy-to-reach participants
   - Example: Survey people walking by in the quad
   - ❌ Only represents people who walk in quad

2. **Voluntary Response**
   - People choose to participate
   - Example: Online polls, call-in surveys
   - ❌ Only represents people with strong opinions (and free time)

3. **Non-response Bias**
   - Planned sample is good, but most people don't respond
   - ❌ Resulting sample ≠ planned sample

#### **Key Comparison: Stratified vs Cluster**

| Feature | Stratified | Cluster |
|---------|-----------|---------|
| Groups are... | Homogeneous (similar within) | Heterogeneous (diverse within) |
| Sample from... | ALL groups | SOME groups (randomly selected) |
| Goal | Ensure representation | Convenience for large populations |
| Example groups | Age brackets, gender | Schools, neighborhoods |

### ⚠️ Other Sources of Bias

**Wording Effects:**
- "Buy" vs "obtain" cigarettes → Different responses!
- "Assistance to poor" vs "welfare" → Same program, different support!

**Framing Effects:**
- Open-ended vs closed-ended questions
- Order of questions matters
- Multiple choice vs ranking can yield different results

---

## 3. EXPERIMENTS

### 🎯 Four Principles of Experimental Design

#### 1. **CONTROL**
- Assign participants to MULTIPLE treatment groups
- At least one group should be **control** (no treatment)
- Purpose: Account for confounding variables
- **Treatment** = explanatory variable you're manipulating

#### 2. **RANDOMIZE**
- Assign subjects RANDOMLY to treatment groups
- Purpose: Reduce bias, balance out unknown confounding variables
- How: Coin flip, random number generator, etc.

**Special Case: Matched Pairs**
- Use "similar" subjects, put one in control, one in treatment
- **BEST matched pairs**: Identical twins!
- Still randomly assign which twin gets which treatment

#### 3. **REPLICATE**
- Test on MULTIPLE subjects
- More subjects = better!
- Must be **repeatable** by other scientists
- **If not repeatable → not believable!**

#### 4. **BLOCK**
- "Experimental equivalent of stratifying"
- **Blocking variable**: Characteristic likely to influence outcomes
  - NOT an explanatory variable
  - NOT what you're testing
- Break subjects into blocks BEFORE random assignment
- Then randomly assign within each block

**Example: Testing therapies on survival**
- Blocking variable: Gender (drugs interact with hormones differently)
- Process:
  1. Separate subjects into Men and Women blocks
  2. Within Men: randomly assign to Therapy 1, 2, or 3
  3. Within Women: randomly assign to Therapy 1, 2, or 3
  4. Compare survival rates

#### **Practice Problem**
*A study tests light level and air quality on corn growth. Researcher believes soil acidity might affect results differently, so ensures varying soil acidity levels are equally represented in each group.*

- How many explanatory variables? **2** (light, air quality)
- How many blocking variables? **1** (soil acidity)
- How many response variables? **1** (corn growth rate)

**Answer: (B)** ✓

### 🎯 Eliminating Bias in Experiments

**Placebo**: Fake treatment (sugar pill)
- Controls for placebo effect

**Placebo Effect**: People improve just because they think they're being treated

**Blinding**: Subjects don't know which treatment they receive
- Prevents placebo effect
- Prevents subjects from changing behavior

**Double-Blind**: NEITHER subjects NOR researchers know who got what
- Prevents researcher bias in measuring outcomes

### 🎯 Experiments vs Observational Studies: The Matrix

|  | Random Assignment | No Random Assignment |
|---|---|---|
| **Random Sampling** | ✅✅ IDEAL EXPERIMENT<br>→ Causal conclusion<br>→ Generalize to population | ❌ Observational Study<br>→ Correlation only<br>→ Generalize to population |
| **No Random Sampling** | ⚠️ Common Experiment<br>→ Causal conclusion<br>→ Generalize ONLY to sample | ❌❌ BAD Observational<br>→ Correlation only<br>→ Cannot generalize |

**Key Takeaways:**
- Random assignment → Causation
- Random sampling → Generalizability
- Observational studies NEVER establish causation (confounding variables!)

---

## 4. NUMERICAL DATA ANALYSIS

### 🎯 Visualizing Distributions: Histograms

**Histogram**: Shows distribution of ONE numerical variable

**Key Features:**
1. **Bins** (classes/ranges) on x-axis
   - Equal width, no gaps, no overlap
   - Must cover all data
   - Choice of bin width matters!

2. **Frequency or Relative Frequency** on y-axis
   - Frequency = count
   - Relative Frequency = count/n (always sums to 1)

3. **Bars are adjacent** (no gaps)
   - Unlike bar plots for categorical data

**Shape DOES NOT change** when using frequency vs relative frequency!

#### **Choosing Bins**
- Too narrow → Too many gaps, can't see shape
- Too wide → Too few bins, lose detail
- Multiple valid choices exist!
- **Goal**: See the overall pattern/shape

### 🎯 Describing Distributions: SOCS

Always describe distributions using these four features:

#### **S - SHAPE**

**Modality (peaks):**
- Unimodal: 1 peak
- Bimodal: 2 peaks  
- Multimodal: 3+ peaks
- Uniform: No peaks (flat)

**Symmetry:**
- **Symmetric**: Mirror image on both sides
  - Mean ≈ Median
- **Right-skewed** (positive skew):
  - Long tail to the RIGHT
  - Peak on LEFT
  - Mean > Median
- **Left-skewed** (negative skew):
  - Long tail to the LEFT
  - Peak on RIGHT
  - Mean < Median

**⚠️ WATCH OUT!**
- "Right-skew" → tail on right, NOT peak on right!
- "Left-skew" → tail on left, NOT peak on left!

#### **O - OUTLIERS**
- Data values FAR from the rest
- Look for bars of height 1 with empty space
- Can dramatically affect mean and standard deviation
- Less effect on median and IQR

#### **C - CENTER**
Three measures:

1. **Mean** (average): x̄ = (sum of all values) / n
   - Notation: x̄ = (1/n)Σxᵢ
   - **Sensitive to outliers**
   - Use for symmetric data

2. **Median**: Middle value when sorted
   - If n odd: middle value
   - If n even: average of two middle values
   - **Robust to outliers**  
   - Use for skewed data
   - Also called **50th percentile**

3. **Mode**: Most frequent value
   - Can be local (within a region)
   - Less commonly used as measure of center

**Relationship in Skewed Data:**
- Right-skew: Mean > Median
- Left-skew: Mean < Median
- Symmetric: Mean ≈ Median

#### **S - SPREAD**
How spread out is the data?

**Three measures:**

1. **Variance** (s²)
   - Formula: s² = [1/(n-1)] Σ(xᵢ - x̄)²
   - ⚠️ **Divide by n-1, NOT n!**
   - Units: (original units)²
   - "Average squared distance from mean"

2. **Standard Deviation** (s)
   - Formula: s = √(variance) = √s²
   - Units: same as original data
   - "Typical distance from mean"
   - **Sensitive to outliers**

3. **Interquartile Range** (IQR)
   - Formula: IQR = Q3 - Q1
   - "Range of middle 50% of data"
   - **Robust to outliers**

### 🎯 Quartiles and Percentiles

**Percentile**: The value that is greater than or equal to p% of data

**xᵗʰ percentile = value ≥ x% of data values**

**Important Percentiles:**
- Q1 (1st quartile) = 25th percentile
  - ≥ 25% of data
  - Median of bottom half

- Median = 50th percentile
  - ≥ 50% of data

- Q3 (3rd quartile) = 75th percentile
  - ≥ 75% of data
  - Median of top half

**⚠️ Finding Quartiles when n is ODD:**

Two methods (both acceptable):

**Inclusive Method**: Include median in both halves
- Data: 1, 3, 3, 3, **4**, 4, 5, 6, 7
- Lower half: 1, 3, 3, 3, 4 → Q1 = 3
- Upper half: 4, 4, 5, 6, 7 → Q3 = 5
- IQR = 5 - 3 = 2

**Exclusive Method**: Exclude median from both halves
- Data: 1, 3, 3, 3, **4**, 4, 5, 6, 7
- Lower half: 1, 3, 3, 3 → Q1 = 3 (avg of 3 and 3)
- Upper half: 4, 5, 6, 7 → Q3 = 5.5 (avg of 5 and 6)
- IQR = 5.5 - 3 = 2.5

**When n is EVEN**: Only one method - split in middle!

### 🎯 Identifying Outliers: IQR Criterion

**An outlier is any value where:**
- xᵢ < Q1 - 1.5 × IQR  (outliers on low end)
- **OR**
- xᵢ > Q3 + 1.5 × IQR  (outliers on high end)

**Example with birthday party ages:**
Data: 1, 3, 3, 3, 4, 4, 5, 6, 7, 64

Q1 = 3, Q3 = 6, IQR = 3

Lower fence: 3 - 1.5(3) = 3 - 4.5 = -1.5
- Anything < -1.5 is an outlier
- No values here (can't have negative age)

Upper fence: 6 + 1.5(3) = 6 + 4.5 = 10.5
- Anything > 10.5 is an outlier
- 64 > 10.5 ✓ → **64 is an outlier**

### 🎯 Five-Number Summary and Boxplots

**Five-Number Summary:**
1. Minimum (non-outlier)
2. Q1
3. Median
4. Q3
5. Maximum (non-outlier)

**Boxplot Components:**
- **Box**: From Q1 to Q3
- **Line in box**: Median
- **Whiskers**: Extend to min/max non-outliers
- **Dots**: Individual outliers beyond whiskers

**Boxplot for birthday party (with 64-year-old):**
```
    o                              o
    |------[==|===]------|    •
    1      3  4  6       7    64
```
- Box from Q1=3 to Q3=6
- Median=4 line in box
- Left whisker to min=1
- Right whisker to max non-outlier=7
- Outlier 64 shown as dot

### 🎯 Properties of Mean, Median, Variance, SD

**Mean:**
- ✓ Uses all data
- ✗ Very sensitive to outliers
- ✗ Affected by extreme values

**Median:**
- ✓ Robust to outliers
- ✗ Doesn't use all data
- ✓ Good for skewed distributions

**Variance and Standard Deviation:**
- Both sensitive to outliers
- Higher values → more spread out
- SD in same units as original data
- Variance in squared units

**Effects of Transformations:**

If you add/subtract a constant to all values:
- Mean shifts by that constant
- Median shifts by that constant
- Variance and SD: **NO CHANGE**
- Shape: **NO CHANGE**

If you multiply/divide all values by a constant c:
- Mean multiplied/divided by c
- Median multiplied/divided by c
- SD multiplied/divided by |c|
- Variance multiplied/divided by c²
- Shape: **NO CHANGE**

---

## 5. CATEGORICAL DATA ANALYSIS

### 🎯 Contingency Tables

**Contingency Table**: Shows aggregate data for TWO categorical variables combined

**Example from your notes:**
```
                    homeownership
           rent    mortgage    own     Total
app_type
individual  3496    3839      1170     8505
joint       362     950       183      1495
Total       3858    4789      1353     10000
```

### 🎯 Computing Proportions

**You can compute proportions using ANY combination of cells!**

**Total Proportions** (using full sample):
- % of ALL applicants who rent: 3858/10000 = 0.3858 = 38.58%

**Row Proportions** (within each row):
- % of INDIVIDUAL applicants who rent: 3496/8505 ≈ 0.41 = 41%
- % of JOINT applicants who rent: 362/1495 ≈ 0.24 = 24%

**Column Proportions** (within each column):
- % of RENTERS who are individual: 3496/3858 ≈ 0.91 = 91%
- % of RENTERS who are joint: 362/3858 ≈ 0.09 = 9%

**Key Insight:**
- Row proportions answer: "Given the row category, what % have each column category?"
- Column proportions answer: "Given the column category, what % have each row category?"

**Comparing proportions helps identify relationships!**
- 41% of individual applicants rent
- 24% of joint applicants rent
- Suggests individual applicants rent more often!

### 🎯 Visualizing Categorical Data

#### **Bar Plots**
- Display frequencies (or proportions) for ONE categorical variable
- Categories on x-axis
- Heights show frequency/proportion
- **Gaps between bars** (standard convention)

**Bar Plot vs Histogram:**
| Feature | Bar Plot | Histogram |
|---------|----------|-----------|
| Data type | Categorical | Numerical |
| X-axis | Categories (any order) | Number line (ordered) |
| Bars | Gaps between | Adjacent (no gaps) |
| Bin choice | Fixed by categories | Flexible |

#### **Pie Charts**
- Show parts of a whole
- Visually distinct
- ❌ **Hard to see relative sizes accurately**
- ✅ **Bar plots are better for accurate comparison**

#### **Side-by-Side Plots**
- Use categorical variable to split numerical data
- Create separate plots for each category
- Can use boxplots, histograms, etc.
- Shows how **categorical variable influences numerical variable**
- **Categorical = EXPLANATORY, Numerical = RESPONSE**

**Example: Income by population change**
- Categorical: gain vs no gain
- Numerical: median income
- Side-by-side boxplots show income distribution for each group

---

## 6. CORRELATION

### 🎯 Measuring Linear Association

**Correlation (r)**: Measures strength and direction of LINEAR relationship between two numerical variables

**Formula:**
```
r = (1/(n-1)) Σ[(xᵢ - x̄)/sₓ × (yᵢ - ȳ)/sᵧ]
```

**Computation Steps:**
1. Find x̄ and ȳ (sample means)
2. Find sₓ and sᵧ (sample standard deviations)
   - ⚠️ Use SAMPLE variance: divide by n-1!
3. For each point (xᵢ, yᵢ):
   - Compute (xᵢ - x̄)/sₓ  [standardized x]
   - Compute (yᵢ - ȳ)/sᵧ  [standardized y]
   - Multiply them together
4. Sum all products
5. Divide by (n-1)

### 🎯 Properties of Correlation

#### **1. Range: -1 ≤ r ≤ 1**
- r = +1: Perfect positive linear relationship
- r = -1: Perfect negative linear relationship
- r = 0: No linear relationship
- |r| close to 1: Strong linear relationship
- |r| close to 0: Weak linear relationship

#### **2. Sign Meaning**
- **Positive (r > 0)**: 
  - As x increases, y TENDS TO increase
  - Positive linear relationship
  
- **Negative (r < 0)**:
  - As x increases, y TENDS TO decrease
  - Negative linear relationship

#### **3. Correlation is INVARIANT under:**
- **Translation**: Adding/subtracting constant to x or y
  - Doesn't change r
  
- **Scaling**: Multiplying/dividing x or y by constant
  - Doesn't change r
  
- **Swapping x and y**:
  - r(x,y) = r(y,x)
  - Correlation is symmetric

#### **4. Correlation measures ONLY LINEAR relationships**
⚠️ **CRITICAL**: r can be near 0 even with strong NON-LINEAR relationship!

**Example: Parabola**
```
y = x² has perfect relationship, but r ≈ 0!
```
- Quadrants balance out:
  - Quadrant 1 (+,+): positive products
  - Quadrant 4 (+,-): negative products
  - They cancel!

**Moral: ALWAYS plot your data!**

### 🎯 Outliers and Correlation

**Outliers can DRASTICALLY change r!**

**Example from notes:**
- Without outliers: r = 0.48 (moderate positive)
- With one outlier: r = 0.99 (strong positive)
- Different outlier: r = -0.95 (strong negative!)

**r is NOT robust to outliers!**

### 🎯 Interpreting Correlation

**What correlation tells you:**
✓ Strength of LINEAR association
✓ Direction of relationship
✓ How points cluster around a line

**What correlation does NOT tell you:**
✗ Causation (correlation ≠ causation!)
✗ Non-linear relationships
✗ Actual rate of change (slope)
✗ Whether relationship is meaningful

**Example: Heights of couples**
- r = 0.565
- Interpretation: "As women's height increases, men's height TENDS TO increase"
- ⚠️ NOT causative! Women's height doesn't CAUSE men's height
- Both influenced by genetics, nutrition, etc.

### 🎯 Perfect Correlation (r = ±1)

**r = 1** when all points fall EXACTLY on a line with positive slope
- Can write equation: y = mx + b where m > 0
- Example: If women always dated men exactly 3 inches taller
  - Men's height = Women's height + 3
  - r = 1 (perfect positive correlation)

**r = -1** when all points fall EXACTLY on a line with negative slope
- Can write equation: y = mx + b where m < 0

### 🎯 Correlation and Transformations

**If all y-values smaller by constant c:**
- Scatterplot shifts down
- Interpretation changes
- r value: **UNCHANGED**

**If heights in cm instead of inches:**
- Both axes rescaled
- r value: **UNCHANGED**

**Remember: Correlation is invariant under translation and scaling!**

---

## 7. LINEAR REGRESSION

### 🎯 What is Regression?

**Regression line**: Describes how a response variable Y changes with respect to an explanatory variable X

**Key Difference from Correlation:**
- Correlation: Order of x and y doesn't matter (r(x,y) = r(y,x))
- Regression: **ORDER MATTERS!** Which variable is X (explanatory) and Y (response) changes the line

### 🎯 The Least-Squares Regression Line

**Equation of a Line:**
```
ŷ = b₀ + b₁x

Where:
- ŷ (y-hat) = PREDICTED value of y
- b₀ = y-intercept (value of y when x = 0)
- b₁ = slope (change in y for each 1-unit increase in x)
```

**Computing the Line:**
```
b₁ = r × (sᵧ / sₓ)

b₀ = ȳ - b₁x̄
```

**Where:**
- r = correlation coefficient
- sₓ, sᵧ = sample standard deviations of x and y
- x̄, ȳ = sample means of x and y

**Example Calculation:**
Given: x̄ = 7, ȳ = 5, sₓ = 4, sᵧ = 2, r = 0.85

```
b₁ = 0.85 × (2/4) = 0.85 × 0.5 = 0.425
b₀ = 5 - 0.425(7) = 5 - 2.975 = 2.025

Regression Line: ŷ = 2.025 + 0.425x
```

### 🎯 Interpreting Slope and Intercept

**Slope Interpretation:**
- "For each increase of 1 [unit of x], we predict [y] to change by b₁ [units of y]"
- Example: If ŷ = 122.9 - 11.1x (golf putts vs distance)
  - "For each 1-meter increase in distance, we predict the golfer makes 11.1 fewer putts"

**Y-Intercept Interpretation:**
- "When x = 0, we predict y = b₀"
- ⚠️ Often doesn't make practical sense! (e.g., "at 0 meters from hole, golfer makes 122.9 putts")
- May be an extrapolation error

### 🎯 Residuals

**Definition:**
```
Residual = Observed - Predicted = yᵢ - ŷᵢ
```

**Interpretation:**
- **Positive residual**: Model UNDERESTIMATES y (actual > predicted)
- **Negative residual**: Model OVERESTIMATES y (actual < predicted)
- **Residual = 0**: Perfect prediction

**Example:**
- Observed: y = 34 points
- Predicted: ŷ = 33.67 points
- Residual = 34 - 33.67 = 0.33 → Model underestimated by 0.33 points

### 🎯 r² (Coefficient of Determination)

**What r² tells you:**
```
r² = percentage of variation in Y explained by the regression line
```

**Calculation:**
- Just square the correlation coefficient!
- r = 0.8056 → r² = 0.649 → **64.9% of variation explained**

**Interpretation Scale:**
| r | r² | Strength |
|---|-----|----------|
| ±0.3 | 0.09 | Weak (9% explained) |
| ±0.5 | 0.25 | Moderate (25% explained) |
| ±0.7 | 0.49 | Moderately Strong (49% explained) |
| ±0.9 | 0.81 | Strong (81% explained) |

**Rule of Thumb:**
- Use **r²** to describe STRENGTH of linear relationship
- Use **r** to describe DIRECTION (positive vs negative)

### 🎯 Extrapolation vs Interpolation

**Interpolation**: Predicting y for x-values WITHIN the range of your data
- ✅ **TRUSTWORTHY**

**Extrapolation**: Predicting y for x-values OUTSIDE the range of your data
- ❌ **UNTRUSTWORTHY** - can give absurd results!

**Example:**
- Data: x ranges from 3 to 7 meters
- Predicting at x = 4.5? → **Interpolation** (within range) ✅
- Predicting at x = 0? → **Extrapolation** (outside range) ❌
- Predicting at x = 15? → **Extrapolation** (outside range) ❌

**Classic Extrapolation Error:**
- Beer/BAC study: x (beers) from 1-9
- Line: ŷ = -0.0127 + 0.018x
- At x = 0: ŷ = -0.0127 → **Negative BAC is impossible!**

### 🎯 Residual Plots

**Why use residual plots?**
- Check if linear model is appropriate
- Identify patterns that suggest problems

**Ideal Residual Plot:**
- Points scattered **randomly** around horizontal line at 0
- **No pattern**
- Constant spread (same vertical scatter throughout)

**Problem Patterns:**

1. **Curved/U-shaped pattern:**
   - Indicates **nonlinear relationship**
   - Linear regression is NOT appropriate

2. **Fan/funnel shape:**
   - Spread increases or decreases across x
   - Called **heteroskedasticity**
   - Violates constant variance assumption

3. **Pattern visible:**
   - Any systematic pattern = problem
   - Model is missing something

### 🎯 Outliers and Influential Points

**Outliers can dramatically affect regression!**

**Types of influential points:**
1. **High leverage point**: Extreme x-value (far from x̄)
2. **Influential point**: Removing it substantially changes the regression line

**Effect:** A single outlier can:
- Change slope from positive to negative
- Dramatically increase or decrease r

### 🎯 Regression Practice Problem (from exam)

**Given:** Steelers data
- x̄ = 324.35 yards, sₓ = 77.23 yards
- ȳ = 24.8 points, sᵧ = 8.53 points
- r = 0.8056

**Find the regression line:**
```
b₁ = r × (sᵧ/sₓ) = 0.8056 × (8.53/77.23) = 0.8056 × 0.1104 = 0.08898

b₀ = ȳ - b₁x̄ = 24.8 - 0.08898(324.35) = 24.8 - 28.86 = -4.06

Line: ŷ = -4.06 + 0.08898x
```

**Check prediction for (424, 34):**
```
ŷ = -4.06 + 0.08898(424) = -4.06 + 37.73 = 33.67

Residual = 34 - 33.67 = 0.33 (positive → underestimate)
```

**What % of variation is explained?**
```
r² = (0.8056)² = 0.649 = 64.9%
```

### 🎯 Key Regression Formulas to Memorize

```
Slope:           b₁ = r × (sᵧ/sₓ)
Intercept:       b₀ = ȳ - b₁x̄
Regression line: ŷ = b₀ + b₁x
Residual:        e = y - ŷ
R-squared:       r² = (correlation)²
```

---

## 8. BASIC PROBABILITY

### 🎯 Fundamental Concepts

**Random Experiment**: Process with uncertain outcome
- Example: Flip coin, roll die, draw card

**Outcome**: A possible result of random experiment
- Example: Heads, 5, Ace of Spades

**Sample Space (S)**: Set of ALL possible outcomes
- Example: Coin flip S = {H, T}
- Example: Die roll S = {1, 2, 3, 4, 5, 6}

**Event**: A set of outcomes (subset of sample space)
- Example: Rolling even number = {2, 4, 6}
- Example: Getting heads = {H}

### 🎯 Probability Rules

#### **Basic Properties**
1. **0 ≤ P(A) ≤ 1** for any event A
2. **P(S) = 1** (something must happen)
3. **P(∅) = 0** (impossible event has probability 0)

#### **For Equally Likely Outcomes**
```
P(A) = (# of outcomes in A) / (# of outcomes in S)
```

**Example: Fair die**
- P(rolling 3) = 1/6
- P(rolling even) = 3/6 = 1/2
- P(rolling 7) = 0/6 = 0

### 🎯 Complement Rule

**Complement of A** (written Aᶜ or A'): All outcomes NOT in A

**Complement Rule:**
```
P(Aᶜ) = 1 - P(A)
```

**Example:**
- P(not rolling 6) = 1 - P(rolling 6) = 1 - 1/6 = 5/6

**Why useful?** Sometimes easier to find P(not A) than P(A)!

### 🎯 Addition Rules

#### **General Addition Rule**
```
P(A or B) = P(A) + P(B) - P(A and B)
```

**Why subtract P(A and B)?**
- When we add P(A) + P(B), we count overlap twice
- Must subtract overlap once

#### **Mutually Exclusive Events**
- A and B are mutually exclusive if they CANNOT both happen
- P(A and B) = 0

**Addition Rule for Mutually Exclusive:**
```
P(A or B) = P(A) + P(B)
```

**Example: Drawing one card**
- A = drawing Ace = 4/52
- B = drawing King = 4/52
- Mutually exclusive (can't be both Ace AND King)
- P(Ace or King) = 4/52 + 4/52 = 8/52 = 2/13

**Example: NOT mutually exclusive**
- A = drawing Ace = 4/52
- B = drawing Spade = 13/52
- NOT mutually exclusive (Ace of Spades!)
- P(A and B) = 1/52
- P(Ace or Spade) = 4/52 + 13/52 - 1/52 = 16/52 = 4/13

### 🎯 Multiplication Rules (Coming in later topics)

**Independent events:**
```
P(A and B) = P(A) × P(B)
```

**Dependent events (conditional probability):**
```
P(A and B) = P(A) × P(B|A)
```

---

## 8. PRACTICE PROBLEMS

### Problem Set 1: Data Types

**1.** Classify each variable as numerical (discrete/continuous) or categorical (nominal/ordinal):

a) Temperature in Fahrenheit
b) Letter grade (A, B, C, D, F)  
c) Number of pets owned
d) Social Security Number
e) Movie rating (1-5 stars)
f) Height in inches
g) Zip code
h) Time to complete exam

<details>
<summary>Click for answers</summary>

a) Numerical - Continuous (can be 72.5°F)
b) Categorical - Ordinal (A > B > C > D > F)
c) Numerical - Discrete (0, 1, 2, 3... pets)
d) Categorical - Nominal (numbers are identifiers, not amounts)
e) Could be either! 
   - If treated as categories: Categorical - Ordinal
   - If averaging ratings: Numerical - Discrete
f) Numerical - Continuous (can be 70.5 inches)
g) Categorical - Nominal (27514 vs 27516 ≠ meaningful difference)
h) Numerical - Continuous (can be 45.3 minutes)
</details>

---

### Problem Set 2: Sampling Methods

**2.** Identify the sampling method used:

a) A researcher wants to study UNC students. They randomly select 5 dorms and survey ALL students in those dorms.

b) A company surveys every 10th customer who enters the store.

c) To study American voting preferences, researchers randomly select 100 Democrats, 100 Republicans, and 100 Independents.

d) A local news station asks viewers to call in with their opinion on a new law.

e) A researcher randomly selects 20 student ID numbers from a list of all students.

<details>
<summary>Click for answers</summary>

a) **Cluster sampling** (randomly select clusters, survey everyone in those clusters)

b) **Systematic sampling** (every kth individual - not covered in detail but is a valid method)

c) **Stratified sampling** (divide into strata by political party, SRS from each)

d) **Voluntary response** - BIASED! Only people with strong opinions call in

e) **Simple random sample** (SRS)
</details>

---

### Problem Set 3: Experiment Design

**3.** A study tests whether a new study method improves test scores. Researchers:
- Recruit 100 students
- Randomly assign 50 to new method, 50 to traditional method
- Both groups study for same amount of time
- All take the same test
- Researchers grading the tests don't know which method students used

a) What is the explanatory variable?
b) What is the response variable?
c) Is this an experiment or observational study?
d) What type of blinding is used?
e) Can we establish causation?

<details>
<summary>Click for answers</summary>

a) Explanatory: **Study method** (new vs traditional)
b) Response: **Test score**
c) **Experiment** (researchers actively assigned the treatment)
d) **Single-blind** (students know their method, graders don't)
   - Would be double-blind if students also didn't know which method they had
e) **YES** - This is a well-designed randomized experiment!
</details>

---

### Problem Set 4: Numerical Summaries

**4.** Given data: 2, 3, 3, 5, 6, 7, 8, 12

Calculate:
a) Mean
b) Median
c) Q1 and Q3 (use exclusive method)
d) IQR
e) Are there any outliers?
f) Variance
g) Standard deviation

<details>
<summary>Click for answers</summary>

a) **Mean**: x̄ = (2+3+3+5+6+7+8+12)/8 = 46/8 = 5.75

b) **Median**: n=8 (even), so average middle two
   - Sorted: 2, 3, 3, 5, | 6, 7, 8, 12
   - Median = (5+6)/2 = 5.5

c) **Q1 and Q3** (exclusive method):
   - Lower half (first 4): 2, 3, 3, 5
   - Q1 = (3+3)/2 = 3
   - Upper half (last 4): 6, 7, 8, 12
   - Q3 = (7+8)/2 = 7.5

d) **IQR** = Q3 - Q1 = 7.5 - 3 = 4.5

e) **Outliers**:
   - Lower fence: 3 - 1.5(4.5) = 3 - 6.75 = -3.75
   - Upper fence: 7.5 + 1.5(4.5) = 7.5 + 6.75 = 14.25
   - All values between -3.75 and 14.25
   - **No outliers**

f) **Variance**:
   - s² = [1/(n-1)] Σ(xᵢ - x̄)²
   - Deviations: -3.75, -2.75, -2.75, -0.75, 0.25, 1.25, 2.25, 6.25
   - Squared: 14.06, 7.56, 7.56, 0.56, 0.06, 1.56, 5.06, 39.06
   - Sum: 75.5
   - s² = 75.5/7 ≈ **10.79**

g) **Standard deviation**: s = √10.79 ≈ **3.28**
</details>

---

### Problem Set 5: Correlation

**5.** True or False:

a) If r = 0.9, then as x increases, y increases.
b) Correlation can be greater than 1.
c) If all points lie exactly on the line y = -2x + 5, then r = 1.
d) Adding 10 to every x-value will change the correlation.
e) Correlation measures how strong any relationship is between x and y.

<details>
<summary>Click for answers</summary>

a) **TRUE** - Positive correlation means positive linear relationship

b) **FALSE** - Correlation always between -1 and 1

c) **FALSE** - The slope is negative, so r = -1 (not +1)

d) **FALSE** - Correlation is invariant under translation

e) **FALSE** - Correlation measures only LINEAR relationships
</details>

---

## 9. COMMON MISTAKES TO AVOID

### ❌ Mistake 1: Variance denominator
**WRONG**: s² = Σ(xᵢ - x̄)² / n
**RIGHT**: s² = Σ(xᵢ - x̄)² / (n-1)

**Divide by n-1 for SAMPLE variance!**

---

### ❌ Mistake 2: Quartile computation
When computing Q1 and Q3 with odd n:
- **Be consistent** with inclusive vs exclusive method
- **Both are acceptable**
- Your answer must match your chosen method

---

### ❌ Mistake 3: Skewness direction
**WRONG**: "Right-skewed means peak on right"
**RIGHT**: "Right-skewed means TAIL on right, peak on LEFT"

The skew refers to the TAIL, not the peak!

---

### ❌ Mistake 4: Correlation = Causation
**NEVER say**: "Higher x CAUSES higher y" based only on correlation

**ALWAYS say**: "Higher x is ASSOCIATED WITH higher y"

Causation requires a properly designed experiment!

---

### ❌ Mistake 5: Outlier criteria
**WRONG**: "Outliers are values far from the mean"
**RIGHT**: Use IQR criterion:
- Outliers < Q1 - 1.5×IQR
- Outliers > Q3 + 1.5×IQR

---

### ❌ Mistake 6: Interpreting r
**WRONG**: "r = 0.7 means a 70% relationship"
**RIGHT**: "r = 0.7 indicates a moderately strong positive linear relationship"

Correlation is NOT a percentage!

---

### ❌ Mistake 7: Stratified vs Cluster
**Stratified**: 
- Homogeneous groups
- Sample from ALL groups

**Cluster**:
- Heterogeneous groups  
- Sample from SOME groups

Don't confuse these!

---

### ❌ Mistake 8: Observational studies
**WRONG**: "This observational study shows smoking causes cancer"
**RIGHT**: "This observational study shows smoking is associated with higher cancer rates"

Observational studies NEVER establish causation!

---

### ❌ Mistake 9: Nonlinear relationships
Just because r ≈ 0 doesn't mean no relationship!
- Could be strong nonlinear relationship
- **Always plot your data!**

---

### ❌ Mistake 10: Blocking vs Explanatory variable
**Blocking variable**: 
- Might influence results
- NOT what you're testing
- Use to separate groups before randomization

**Explanatory variable**:
- What you're actively manipulating
- The treatment itself

---

## 🎯 EXAM STRATEGY TIPS

### Before the Exam:
1. ✅ Review ALL homework problems
2. ✅ Redo practice problems without looking at answers
3. ✅ Make formula sheet (if allowed)
4. ✅ Understand CONCEPTS, not just formulas
5. ✅ Practice identifying when to use each method

### During the Exam:
1. ✅ **Read carefully** - watch for "observational" vs "experiment"
2. ✅ **Show your work** - partial credit!
3. ✅ **Check units** - does your answer make sense?
4. ✅ **Use process of elimination** on multiple choice
5. ✅ **Budget your time** - don't get stuck on one problem

### Key Formulas to Memorize:
```
Mean: x̄ = (1/n)Σxᵢ

Variance: s² = [1/(n-1)]Σ(xᵢ - x̄)²

Standard Deviation: s = √s²

IQR: Q3 - Q1

Outlier Criteria: 
  < Q1 - 1.5×IQR  or  > Q3 + 1.5×IQR

Correlation: r = [1/(n-1)]Σ[(xᵢ-x̄)/sₓ × (yᵢ-ȳ)/sᵧ]

Complement Rule: P(Aᶜ) = 1 - P(A)

Addition Rule: P(A or B) = P(A) + P(B) - P(A and B)
```

---

## 🚀 FINAL CHECKLIST

Before you say "I'm ready," make sure you can:

- [ ] Identify variable types without hesitation
- [ ] Distinguish experiments from observational studies
- [ ] List and explain all 4 principles of experimental design
- [ ] Identify all types of sampling methods from descriptions
- [ ] Explain why observational studies can't establish causation
- [ ] Calculate mean, median, variance, SD by hand
- [ ] Find Q1, Q3, IQR correctly (both methods)
- [ ] Identify outliers using IQR criterion
- [ ] Describe distribution shape (skewness, modality)
- [ ] Draw and interpret boxplots
- [ ] Compute proportions from contingency tables
- [ ] Calculate and interpret correlation
- [ ] List all properties of correlation
- [ ] Explain why r can be 0 with strong relationship
- [ ] Apply basic probability rules
- [ ] Use complement rule and addition rule

---

**YOU'VE GOT THIS! 💪**

Review this guide section by section. Work through the practice problems. 
Test yourself without looking at answers. You're aiming for 100% mastery,
and with dedicated practice, you'll get there!

Good luck on your exam! 🎯
