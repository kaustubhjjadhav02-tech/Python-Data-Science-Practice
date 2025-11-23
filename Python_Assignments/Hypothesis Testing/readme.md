# 🧪 Hypothesis Testing – Operating Cost Analysis

## **Background**
Bombay Hospitality Ltd. operates a franchise model for producing exotic Norwegian dinners across New England.  
According to the cost model, the weekly operating cost for a franchise is given by:

\[
W = \$1,000 + 5X
\]

where **X** represents the number of units produced in a week.

Recent feedback from franchise owners suggests that their actual weekly operating costs are **higher** than what the model predicts. This assignment aims to investigate that claim using hypothesis testing.

---

## **Objective**
To determine whether there is statistically significant evidence that the true weekly operating cost is **higher** than the cost predicted by the existing model.

---

## **Data Provided**
- Theoretical cost model:  
  **W = $1,000 + 5X**
- Sample of **25 restaurants** with a mean weekly cost of **Rs. 3,050**
- Number of units produced (X) follows a normal distribution with:
  - Mean (μ) = 600 units  
  - Standard deviation (σ) = 25 units  

---

## **Assignment Tasks**

### **1. State the Hypotheses**
- **Null Hypothesis (H₀):** The weekly operating cost is **not higher** than the model predicts.  
- **Alternative Hypothesis (H₁):** The weekly operating cost is **higher** than the model predicts.

---

### **2. Calculate the Test Statistic**
Use the Z-statistic formula:

\[
z = \frac{\bar{x} - \mu}{\frac{\sigma}{\sqrt{n}}}
\]

Where:
- \(\bar{x}\) = Sample mean weekly cost = **Rs. 3,050**
- μ = Theoretical mean cost from model  
  (For X = 600: W = 1,000 + 5 × 600)
- σ = 5 × 25 units
- n = 25 restaurants

---

### **3. Determine the Probability**
- Use α = **0.05** (5% significance level)
- Compare the calculated z-value with the critical value.

---

### **4. Make a Decision**
- Reject or fail to reject the null hypothesis based on comparison with critical z-value.  
- Determine whether there is enough evidence to support the owners’ claim.

---

### **5. Conclusion**
Based on the hypothesis test results, conclude whether the weekly operating costs are **significantly higher** than the model suggests.

---

## **Submission Guidelines**
- Submit a **Python file/notebook** showing all steps of the hypothesis testing process.
- Include:
  - Calculations for **test statistic**
  - **Critical value**
  - **Final conclusion**

---

## **Deliverables**
- Complete Python implementation of hypothesis testing  
- Documentation of results and interpretation  
- Final conclusion summarizing the statistical findings
  
