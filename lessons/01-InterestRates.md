# 1. Interest rates

[Back to contents](../README.md)

## Summary
**1.1 Interest Rates** 

Interest is the money earned on savings or charged on loans. The principle P is the intial amount invested or borrowed. Interest rates could be compounded in different ways, which ultimately affects the accumulated value of an investment over time. The main formulas are presented below.

**Annual compounding:**

$$P(1+r)^T$$

**Compounding n times yearly:**

$$P(1+\frac{r}{n})^{nT}$$

**Effective annual interest rate:**

$$r_{\mathrm{eff}} = \left(1+\frac{r}{n}\right)^n-1$$

Where P is the principal, r is the annual interest rate, t is time in years and n is the number of compounding periods per year.

**1.2 Variable Interest Rates**

Interest rates do no aways remain constant and may change over time. A variable interest rate is represented by r(t).

**Accumulated value with a continuously varying interest rate is:**

$$P(t)= P(0)e^{\int_0^t r(u)\, du}$$

**Average compounded interest rate:**

$$\bar{r}(t)=\frac{1}{t}\int_0^t r(u)\, du$$

**1.3 Inflation**
Inflation is the increase in the general price level, reducing purchasing power of money. Nominal interest rate is the rate without adjusting for inflation whereas real interest rates is adjusted.

**Real interest rate:**
$$r_{\mathrm{real}}=\frac{r-r_{\mathrm{inf}}}{1=r_{\mathrm{inf}}}$$


## My example

**Question:**

An individual invests £5000 into a savings account offering a nominal annual interest rate of 6% for 3 years.

Calculate the accumulated value if the interest is compounded:

1.Annually

2.Monthly 

**Solution:**

**1. Annual compounding**

$$A=P(t)= P(0)e^{\int_0^t r(u)\, du}$$

$$A = 5000(1.06)^{3} =5,955.08$$ 

**2.Monthly compounding**

$$A=P(1+\frac{r}{n})^{nT}$$

$$A=5000(1+\frac{0.06}{12})^{36}$$ = 5983.40


## Solved exercises

### Exercise 1.x (from Exercise Sheet 1)

Question, then your solution.

## Spreadsheet

[01-InterestRates.xlsx](../spreadsheets/01-InterestRates.xlsx): what it
does, which cells to change and what to look at.
