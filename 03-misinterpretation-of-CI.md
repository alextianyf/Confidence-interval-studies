# ⚠️ Common Misinterpretations of Confidence Intervals (CI)

### ❌ 1. “There’s a 95% probability that the true mean is inside this interval.”

✅ **Correction**:  
The true mean is a fixed value — it's either inside or outside the interval.  
A 95% CI means that **if you repeated the experiment 100 times**, about **95 intervals would contain the true mean**.

> ✅ The confidence is in the **method**, not in a single interval.

---

### ❌ 2. “The sample mean is always at the center of the confidence interval.”

✅ **Correction**:  
Only true for **symmetric intervals** like those from t- or z-distributions.  
For **asymmetric intervals** (e.g., from bootstrapping), the sample mean may not be centered.

---

### ❌ 3. “95% of the data fall inside the 95% confidence interval.”

✅ **Correction**:  
The CI is about the **uncertainty of a statistic** (like the mean), **not the spread of raw data**.  
Individual data points can lie far outside the interval.

> CI ≠ data range  
> CI = range for the estimated **parameter**

---

### ❌ 4. “Once calculated, there’s a 95% chance the true mean is in this interval.”

✅ **Correction**:  
After computing the CI, there's **no probability left** — the interval **either contains** the true value or not.  
The 95% refers to the **success rate of the procedure over repeated sampling**.

---

### ❌ 5. “A wider CI means my estimate is more accurate.”

✅ **Correction**:  
A **narrower CI** usually reflects **greater precision** (e.g., larger sample size).  
A **wider CI** can mean more uncertainty, not better accuracy.

> Accuracy = how close to the true value  
> Precision = how tight the estimate range is

---

### ✅ Recommended Interpretation

> “We used a method that gives correct intervals 95% of the time.  
> Based on our sample, we estimate that the true population mean lies between A and B.”

---