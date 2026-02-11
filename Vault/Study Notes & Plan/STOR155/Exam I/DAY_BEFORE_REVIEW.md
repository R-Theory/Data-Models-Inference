# 🎯 MIDTERM 1: DAY BEFORE EXAM - RAPID REVIEW

## ⚡ LIGHTNING CONCEPTS (Know These Cold!)

### DATA TYPES
- **Numerical**: Can do math → Discrete (countable) or Continuous (any value)
- **Categorical**: Categories → Nominal (no order) or Ordinal (has order)
- ⚠️ Numbers can be categorical! (Zip codes, jersey numbers)

### SAMPLING
| Method | Description | When to Use |
|--------|-------------|-------------|
| SRS | Random from whole population | Default, simple |
| Stratified | Divide into groups, SRS from EACH | Ensure representation |
| Cluster | Divide into clusters, sample SOME clusters entirely | Large populations, convenience |
| Multistage | Cluster + SRS within clusters | Very large populations |

**BAD SAMPLING** (Biased): Convenience, Voluntary Response, Non-Response

### EXPERIMENTS VS OBSERVATIONAL
| Feature | Experiment | Observational |
|---------|-----------|---------------|
| Method | **ACTIVE** manipulation | **PASSIVE** observation |
| Causation? | ✅ YES | ❌ NO |
| Random assignment? | Yes | No |
| Confounding? | Controlled | Major problem |

**4 PRINCIPLES OF EXPERIMENTS:**
1. **Control** - Multiple treatment groups
2. **Randomize** - Random assignment to groups
3. **Replicate** - Multiple subjects, repeatable
4. **Block** - Group by characteristics before randomizing

### DESCRIBING DISTRIBUTIONS (SOCS)
**S**hape:
- Modality: Unimodal, bimodal, multimodal, uniform
- Symmetry: Symmetric, right-skew (tail right), left-skew (tail left)

**O**utliers: Far from rest, use IQR criterion

**C**enter: Mean (sensitive to outliers) or Median (robust)

**S**pread: SD/Variance (sensitive) or IQR (robust)

### KEY RELATIONSHIPS
```
Right-skew: Mean > Median
Left-skew: Mean < Median
Symmetric: Mean ≈ Median
```

### OUTLIER DETECTION
```
Outlier if:
x < Q1 - 1.5×IQR  OR  x > Q3 + 1.5×IQR
```

### CORRELATION
- **Range**: -1 ≤ r ≤ 1
- **r = 1**: Perfect positive linear
- **r = -1**: Perfect negative linear
- **r = 0**: No linear relationship (⚠️ could still have nonlinear!)
- **Properties**: 
  - Invariant under translation (add/subtract constant)
  - Invariant under scaling (multiply/divide constant)
  - Symmetric: r(x,y) = r(y,x)
  - ⚠️ Sensitive to outliers
  - ⚠️ Measures ONLY linear relationships

### PROBABILITY BASICS
```
P(Aᶜ) = 1 - P(A)

P(A or B) = P(A) + P(B) - P(A and B)

If mutually exclusive: P(A or B) = P(A) + P(B)
```

---

## ❌ TOP 10 MISTAKES TO AVOID

1. **Using n instead of n-1** in variance formula
2. **Confusing stratified and cluster sampling**
3. **Saying "correlation = causation"** - NEVER!
4. **Wrong skew direction** - Skew points to TAIL not peak
5. **Thinking r is a percentage** - It's not!
6. **Forgetting outliers affect mean/SD** - Use median/IQR with outliers
7. **Claiming observational studies show causation** - They don't!
8. **Thinking r=0 means no relationship** - Could be nonlinear!
9. **Using wrong outlier criterion** - Must use IQR method
10. **Confusing blocking variable with explanatory variable**

---

## 🔥 LAST-MINUTE DRILL

**Without looking at your notes, answer:**

1. What's the sample variance formula? ⟹ s² = Σ(xᵢ-x̄)²/(n-1)
2. What makes data right-skewed? ⟹ Long tail on right, mean > median
3. How do you identify outliers? ⟹ < Q1-1.5×IQR or > Q3+1.5×IQR
4. Can observational studies prove causation? ⟹ NO!
5. What does r = -0.9 mean? ⟹ Strong negative linear relationship
6. What happens to SD if you add 10 to all values? ⟹ No change
7. What's the complement rule? ⟹ P(Aᶜ) = 1 - P(A)
8. Stratified vs cluster sampling? ⟹ Stratified: sample from ALL groups; Cluster: sample SOME groups
9. What are the 4 experimental design principles? ⟹ Control, Randomize, Replicate, Block
10. When is correlation exactly 1? ⟹ All points on line with positive slope

**If you got all 10 right without checking: YOU'RE READY! 💪**
**If you missed any: Review that topic now!**

---

## 📋 FINAL CHECKLIST

□ Can calculate mean, median, Q1, Q3, IQR by hand
□ Know variance formula (with n-1!)
□ Can identify outliers using IQR criterion
□ Can describe distribution shape completely
□ Know all sampling methods and when to use them
□ Understand experiment vs observational study
□ Know why only experiments show causation
□ Can list 4 principles of experimental design
□ Understand correlation properties (range, invariance)
□ Know correlation ≠ causation
□ Can apply complement rule and addition rule
□ Know when addition rule simplifies (mutually exclusive)
□ Understand how outliers affect different statistics
□ Can create and interpret contingency tables
□ Can compute row/column proportions

---

## 🚀 EXAM DAY STRATEGY

**1. Read questions carefully**
- "Experiment" vs "Observational study" - one word changes everything
- "Mean" vs "Median" - different formulas
- "Sample" vs "Population" - affects interpretation

**2. Show all work**
- Partial credit is real!
- Write formulas first, then substitute
- Label your answers clearly

**3. Check reasonableness**
- Is correlation between -1 and 1?
- Is probability between 0 and 1?
- Do percentages add to 100%?
- Are units correct?

**4. Time management**
- Don't get stuck on one problem
- Do easy ones first
- Come back to hard ones
- Leave 5 minutes to check

**5. Trust your preparation**
- You've studied the material
- You know this!
- Breathe and focus

---

**You've got this! Now get some rest and ace that exam! 🎯🔥**