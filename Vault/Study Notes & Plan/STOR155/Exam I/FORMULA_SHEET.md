# 📐 STOR 155 MIDTERM 1 - FORMULA SHEET

## DESCRIPTIVE STATISTICS

### Measures of Center
```
Mean (x̄):
x̄ = (1/n) Σ xᵢ = (x₁ + x₂ + ... + xₙ)/n

Median:
- Sort data smallest to largest
- If n odd: middle value
- If n even: average of two middle values
```

### Measures of Spread
```
Sample Variance (s²):
s² = [1/(n-1)] Σ(xᵢ - x̄)²

⚠️ CRITICAL: Divide by (n-1), NOT n!

Sample Standard Deviation (s):
s = √s²

Interquartile Range (IQR):
IQR = Q3 - Q1
```

### Quartiles
```
Q1 = 25th percentile (median of lower half)
Q2 = 50th percentile (median)
Q3 = 75th percentile (median of upper half)
```

### Outlier Detection
```
A value x is an outlier if:

x < Q1 - 1.5 × IQR  (lower outlier)
    OR
x > Q3 + 1.5 × IQR  (upper outlier)
```

## CORRELATION

### Correlation Coefficient (r)
```
r = [1/(n-1)] Σ[(xᵢ - x̄)/sₓ × (yᵢ - ȳ)/sᵧ]

Where:
- x̄, ȳ = sample means
- sₓ, sᵧ = sample standard deviations
```

### Properties of r
```
Range: -1 ≤ r ≤ 1

Sign:
r > 0: positive linear relationship
r < 0: negative linear relationship
r = 0: no linear relationship

Strength:
|r| close to 1: strong
|r| close to 0: weak
```

## LINEAR REGRESSION

### Regression Line Equation
```
ŷ = b₀ + b₁x

Where:
- ŷ = predicted value of y
- b₀ = y-intercept
- b₁ = slope
```

### Computing the Regression Line
```
Slope:     b₁ = r × (sᵧ / sₓ)

Intercept: b₀ = ȳ - b₁x̄
```

### Residual
```
Residual = Observed - Predicted = yᵢ - ŷᵢ

Positive residual → Model UNDERESTIMATED
Negative residual → Model OVERESTIMATED
```

### Coefficient of Determination (r²)
```
r² = (correlation coefficient)²

Interpretation: % of variation in Y explained by the line
```

### Interpreting Slope and Intercept
```
Slope (b₁): "For each 1-unit increase in X,
            Y changes by b₁ units"

Intercept (b₀): "When X = 0, we predict Y = b₀"
                ⚠️ May not be meaningful!
```

### Interpolation vs Extrapolation
```
Interpolation: x within data range → TRUSTWORTHY ✓
Extrapolation: x outside data range → UNTRUSTWORTHY ✗
```

---

## PROBABILITY

### Basic Rules
```
Sample Space: S = all possible outcomes

0 ≤ P(A) ≤ 1 for any event A
P(S) = 1
P(∅) = 0
```

### Complement Rule
```
P(Aᶜ) = 1 - P(A)

Where Aᶜ = "not A"
```

### Addition Rule (General)
```
P(A or B) = P(A) + P(B) - P(A and B)
```

### Addition Rule (Mutually Exclusive)
```
If A and B cannot both occur:
P(A or B) = P(A) + P(B)
```

### Equally Likely Outcomes
```
P(A) = (# favorable outcomes) / (# total outcomes)
```

## TRANSFORMATIONS

### Adding/Subtracting Constant c
```
If Y = X + c:
- Mean shifts: ȳ = x̄ + c
- Median shifts: median_y = median_x + c
- SD unchanged: s_y = s_x
- Variance unchanged: s²_y = s²_x
- Shape unchanged
```

### Multiplying/Dividing by Constant c
```
If Y = c × X:
- Mean scales: ȳ = c × x̄
- Median scales: median_y = c × median_x
- SD scales: s_y = |c| × s_x
- Variance scales: s²_y = c² × s²_x
- Shape unchanged
```

## RELATIONSHIPS BETWEEN STATISTICS

### Skewness and Center
```
Right-skewed: Mean > Median
Left-skewed: Mean < Median
Symmetric: Mean ≈ Median
```

### Five-Number Summary
```
Minimum, Q1, Median, Q3, Maximum

Used for boxplots
```

## QUICK REFERENCE

### When to use what?

**Measure of Center:**
- Symmetric data → Mean
- Skewed data → Median
- With outliers → Median

**Measure of Spread:**
- Symmetric data → Standard Deviation
- Skewed data → IQR
- With outliers → IQR

**Sampling Method:**
- Equal representation → Stratified
- Large population convenience → Cluster
- No special structure → Simple Random

**Study Type:**
- Need causation → Experiment
- Causation impossible/unethical → Observational
- Just exploring → Observational

---

## COMMON FORMULAS TO MEMORIZE

```
✓ x̄ = Σxᵢ / n
✓ s² = Σ(xᵢ - x̄)² / (n-1)  ⚠️ Note: n-1
✓ s = √s²
✓ IQR = Q3 - Q1
✓ Outliers: Q1 - 1.5×IQR or Q3 + 1.5×IQR
✓ r = [1/(n-1)]Σ[(xᵢ-x̄)/sₓ × (yᵢ-ȳ)/sᵧ]
✓ P(Aᶜ) = 1 - P(A)
✓ P(A or B) = P(A) + P(B) - P(A and B)
```

---

**💡 PRO TIP:** Practice calculating these by hand on the homework problems until you can do them without referring to this sheet!