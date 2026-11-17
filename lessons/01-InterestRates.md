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

### Exercise 1: Compound interest 

**Source:** Week 1 Tutorial, Exercise 1 

**Problem:** A £700 investment earns 3% nominal annual interest. Calculate its future value under different compounding frequencies. 

**Solution:**

###Part (A): Future value 

**General compound interest formula:** 

$$A=P\left(+\frac{r}{m}\right)^{mt}$$

Where P = 700, r= 0.03, t = 3, and m is the number of compounding periods per year.

**Annually:**

$$A=700(1+0.03)^3$$= 764.91

**Monthly:**

$$A=700(1+\frac{0.03}{12})^{36}$$= 765.89

**Semi-annually:**

$$A=700(1+\frac{0.03}{2})^{6}$$= 765.41

**Continuously:**

$$A=700e^{0.03\times3}$$= 765.92



**Source:** Week 1 Tutorial, Exercise 2 

**Question:** Assuming an inflation rate of 2%, determine the range of nominal interest rates for which the approximate real interest rate is accurate to within 0.001 percentage points. 

**Solution:**

Exact real interest rate:

$$r_{\mathrm{real}}=\frac{1+r}{1+i}-1$$

Approx real interest rate:

$$r_{\mathrm{real}}\approx r-i$$

Given an inflation rate of i= 0.02, the required accuracy is:

$$|r_{\mathrm{rea}}-(r=i)<0.0001$$

Substituting the exact formula:

$$\left|\frac{1+r}{1.02}-1-(r-0.02)\right|<00001$$

$$\frac{0.02|0.02-r|}{1.02}<0.0001$$

$$|0.02-r|<0.0051$$

$$-0.0051<0.02-r<0.0051$$

$$0.0149<r<0.0251$$

The approximation is accurate within 0.01 percentage points when the nominal interest rate lies strictly between 1.49% and 2.51%. 









…

## Spreadsheet

[01-InterestRates.xlsx](../spreadsheets/01-InterestRates.xlsx): what it
does, which cells to change and what to look at.
