---
title: "Experiment--1 :Basic Math & Stao Operations in R"
author: "prudhwi.inmca2025@saintgits.org"
date: '2022-04-11'
output:
  html_document: default
  word_document: default
  pdf_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## <u> **Aim** </u>

Execute basic mathematical; and statistical operations in R

## <u>**Algorithm**</u>

**Step1:** Create `R code` chunks

**Step2:** Write math expressions

**Step3:** Run the chunk codes

**Step4:** Report the results

## [**R-code**]{.underline}
_In this experiment basic mathematical operations will be tested using R_

```{r addition}
# addition
a=10;
b=125;
total=a+b;
total;
```
```{r subtraction}
x=425;
y=345;
x-y;
```
```{r MULTIPLICATION}
a1=34;
a2=5.4;
s=prod(a1,a2);
paste0("Product of ",a1," and ",a2, " is ",s);
```
```{r division}
c=32;
d=6;
qu=c/d;
qu;
```
```{r reminder}
rem=c%%d;
rem;
```
```{r flooring operation}
r=32;
s=2;
d=r%/%s;
d;
```
```{r power operations}
a=5;
b=5^2;
b;

```
```{r power operations in array}
v=1:10;
v^10;
```
```{r scalar multiplication on array}
ar=c(1,5,7,9,21);
5*ar;
```
```{r vector multiplication}
br=c(1,4,1,2,8);
ar;br;ar*br;
```
```{r round down a number}
floor(3.1427)
```
```{r round up a number}
ceiling(.6879)
```
```{r factorial of a number}
factorial(10)
```
To find $nCr=\frac{n!}{r!(n-r)!}$
```{r combination}
choose(5,3)
```
Permutation can be found using :$^n P_r=n\times(n-1) \times \cdots \times (n-r+1)$
```{r permutation}
prod(10:(10-4+1))
```



## [**Result**]{.underline}



