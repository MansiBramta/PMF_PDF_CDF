# Understanding PMF, PDF, and CDF

This repository contains the examples, mathematical explanations, and Python implementations used to understand three fundamental concepts in probability:

* **Probability Mass Function (PMF)**
* **Probability Density Function (PDF)**
* **Cumulative Distribution Function (CDF)**

These concepts are essential for understanding probability distributions and form an important foundation for **Statistics, Data Science, and Machine Learning**.

---

## About This Repository

Probability can be represented differently depending on whether a random variable is **discrete** or **continuous**.

In this repository, I explore:

* How probability works for discrete random variables using **PMF**
* How probability works for continuous random variables using **PDF**
* How cumulative probability is represented using **CDF**
* The mathematical relationship between these concepts
* Practical probability calculations using examples
* Python implementations for better visualization and understanding

---

## Topics Covered

### 1. Random Variables

Understanding the difference between:

* **Discrete Random Variables**
* **Continuous Random Variables**

---

### 2. Probability Mass Function (PMF)

A PMF is used to describe the probability distribution of a **discrete random variable**.

It assigns a probability to every possible value of the random variable.

The repository includes examples such as a fair six-sided die and demonstrates how probabilities are represented for discrete outcomes.

---

### 3. Probability Density Function (PDF)

A PDF is used to describe the distribution of a **continuous random variable**.

For continuous variables:

* The probability of a single exact value is zero
* Probability is calculated over an interval
* The probability is represented by the area under the density curve

Mathematically:

$$
P(a \leq X \leq b)=\int_a^b f(x)\,dx
$$

---

### 4. Cumulative Distribution Function (CDF)

The CDF represents the probability that a random variable is less than or equal to a particular value.

$$
F(x)=P(X\leq x)
$$

The repository demonstrates how CDF works for both:

* Discrete random variables
* Continuous random variables

---

## 🔗 PMF vs PDF vs CDF

| Concept | Random Variable       | Meaning                              |
| ------- | --------------------- | ------------------------------------ |
| **PMF** | Discrete              | Probability of a specific value      |
| **PDF** | Continuous            | Probability density                  |
| **CDF** | Discrete & Continuous | Cumulative probability up to a value |

---

## Python Implementation

This repository also includes Python examples for working with probability concepts.

The implementations help demonstrate and visualize:

* PMF
* PDF
* CDF
* Probability calculations
* Discrete probability distributions
* Continuous probability distributions

---

## Tools Used

* **Python**
* **NumPy**
* **Matplotlib**

---

## Learning Objectives

After working through this repository, you should understand:

* The difference between discrete and continuous random variables
* When to use PMF and PDF
* Why PDF does not represent the probability of an exact value
* How probability is calculated over an interval for continuous variables
* How CDF represents cumulative probability
* The relationship between PMF, PDF, and CDF

---

## Why This Topic Matters

PMF, PDF, and CDF are fundamental concepts that appear throughout:

* Probability Theory
* Statistics
* Data Analysis
* Machine Learning
* Statistical Modeling

A strong understanding of these concepts makes it easier to learn probability distributions and more advanced statistical concepts used in Data Science and Machine Learning.

---

## Author

**Mansi Bramta**

MSc Mathematics | Aspiring Data Scientist

---

⭐ *This repository is part of my learning journey in Probability, Statistics, Data Science, and Machine Learning.*


