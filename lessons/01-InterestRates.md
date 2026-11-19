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

## Part (A): Future value 

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


## Part(b) - Effective Interest Rates 

Effective annual interest rates:

$$r_{\text{eff}} = \left(1+\frac{r}{n}\right)^{n-1}$$

Given a nominal interest rate of 3%:

**Compounded annually:**

$$r_{\text{eff}} = (1+0.03)^1-1 =0.03 = 3%

**Compounded monthly:**

$$r_{\text{eff}}= (1+0.03)^1-1=3\% = 0.030416 = 3.0416\%$$

**Compounded semi-annually:**

$$r_{\text{eff}} = \left(1+\frac{0.03}{2}\right)^2-1 = 0.030225 = 3.0225\%$$

**Compounded continuously:**

$$r_{\text{eff}}= e^{0003}-1= 0.030455 = 3.0455\%$$

Continous compounding produces the highest effective annual interest rate whereas annual compounding produces the least. 

## Part(c): Inflation adjusted interest rates 

Given an inflation rate of 2%, real interest rates formula 

$$r_{\text{real}}=\frac{r_{\text{eff}}-r_{\text{inf}}}{1+r_{\text{inf}}}$$

**Compounded annually:**

$$r_{\text{real}}=\frac{0.0-0.02}{1.02}= 0.009804 = 0.9804%$$

**Compounded monthly:**

$$r_{\text{real}}=\frac{(1+o.03/12)^{12}-1-0.02}{1.02}\approx 0.010212 = 1.0212%$$

**Compounded semi-annually:**

$$r_{\text{real}}=\frac{0.030225-0.02}{1.02}\approx 0.010025= 1.0025%$$

**Compounded continuously:**

$$r_\{text{real}}=\frac{e^{0.003}-1-0.02}{1.02}\approx 0.010250 = 1.0250\%$$

All interest rates are positive meaning that investment purchasing power increases despite inflation.

##Exercise 1(d)- Time required for investment growth

An initial investment of £700 earns 3% nominal interest rate compounded semi-annually. We calculate the time required for the balance to reach £1000.

Compound interest rate:

$$1000=700\left(1+\frac{0.03}{2}right)^{2T}$$

Dividing by 700:

$$\frac{1000}{700}=(1.015)^{2T}$$

Taking natural logartims:

$$\ln\left(\frac{1000}{700}\right)=2T\ln(1.015)$$

Rearranging:

$$T=\frac{\ln(1000/700)}{2\ln(1.015)}$$

$$T=\approx 11.98\text{years}$$

Therefore, the investment reaches £1000 in approximately 12 years. 





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

$$0.0149< r < 0.0251$$

The approximation is accurate within 0.01 percentage points when the nominal interest rate lies strictly between 1.49% and 2.51%. 



## Spreadsheet


[Download the Interest Rate Calculator](../spreadsheets/Lesson%201%20.xlsx)

The Excel spreadsheet is an interactive interest rate calculator demonstrating how different compounding frequencies affect investment growth. Users can modify the initial investment (B3), annual interest rate (B4), investment period (B5) and inflation rate (B6). The spreadsheet automatically calculates future values, effective annual interest rates, inflation-adjusted returns and the time required to reach a target balance. This illustrates the relationship between compounding, inflation and the time value of money. 
