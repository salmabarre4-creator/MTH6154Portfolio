## Lesson 2- Present value 

[Back to contents](../README.md)

## Lecture notes:

### 1.3 Inflation

Inflation reduces the purchasing power of money. The real interest rate measures returns after accounting for inflation.

$$r_{\text{real}}=\frac{r_{\text{eff}}-r_{\text{inf}}}{1+r_{\text{inf}}}$$

For small rates:

$$r_{\text{real}}\approx r_{\text{eff}}-r_{\text{inf}}$$

### 1.4 Present value analysis:

Present value measures the current worth of future payments, discounted at an interest rate.

**Single payment:**

$$PV=\frac{V}{(1+r)^T}$$

**Multiple payments:**

$$PV=\sum_{i=1}^{n}\frac{a_i}{(1+r)^{t_i}}$$

**Discount factor:**

Annual: $D(T)=(1+r^(-T)$

Continuous: $D(T)=e^{-rT}$

Two cash-low streams are equivalent when their present values are equal. 

## 1.5 Rates of Return 

The rate of return measures investment probability.

$$R=\left(\frac{P_{\text{final}}}{P}\right)^{1/T}-1$$

**Internal rate of return (IRR):**

The rate at which then present value of future payments equals the initial investment.

$$P\sum_{i=1}^{n}\frac{a_i}{(1+r)^{t_i}}$$


## Example question:

### Question:

A student wants to save for a £5000 holiday in 4 years. A savings account offers an annual interest rare of 5%, compounded annually.

How much should the student invest today to have £5000 in 4 years?

### Solution:

$$PV={\frac{FV}{{1+i}^n}}$$

Where:
FV = 5000 (future value)
i = 0.05 (interest rate)
n = 4 (number of years)

### Substituting: 

$$PV={\frac{5000}{{1.05}^4}}$$
$$PV = £4113.51$$

The student needs to invest approximately £4113.51 today to accumulate £5000 in 4 years.


## Week 2- Exercise 1: Internal Rate of Return (IRR)

## Question: 

An initial investment of £1000 generates payments of £500 at the end of Year 2 and £750 at the end of Year 4. Calculate the internal rate of return (IRR). 


## Solution:

$$1000={\frac{500}{{1+i}^{2}}}+{\frac{750}{{1+i}^{4}}}$$

### let $$x=(1+i)^2$$

$$1000={\frac{500}{x}}+{\frac{750}{1+i}}$$

$$1000{x}^{2}=500{x}+{750}$$

$$4{x}^{2}-2{x}-3=0$$

$$x={\frac{2\pm\sqrt{52}}{8}}$$

$$x=1.15139$$

$$i=7.31%$$


## Week 2- Exercise 2: Comparing Present Values 

### Question:

After graduation, you receive two job offers for three years,

### Company A:

- £65,000 at the end of Year 1
-  £75,000 at the end of Year 2
-  £115,000 at the end of Year 3

### Company B:

- £15,000 signing bonus immediately
- £79,000 at the end of each of the three years

Determine which company offers the better deal at an intersect rate of 3.75%, compounded:

i) Annually 

ii) Continously

### Solution:

### part i) 

$$PV={\frac{FV}{{1+i}^{n}}}$$

$${PVa= {\frac{65000}{1.0375}} + {\frac{75000}{{1.0375}^2}} + {\frac{115000}{{1.0375}^3}}}$$

$$PVa = £235,302.31$$

$$PVb= 15000 + {\frac{79000}{1.0375}} + {\frac{79000}{{1.0375}^2}} + {\frac{79000}{{1.0375}^3}}$$ 













