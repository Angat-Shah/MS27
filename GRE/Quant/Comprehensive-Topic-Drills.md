# GRE Quantitative Reasoning: Comprehensive Coursework Topic Drills

This drill set covers essential topics from the **GRE Quantitative Coursework Syllabus (Phases 1, 2, and 3)** that complement Practice Sets 1–3. It ensures 100% comprehensive coverage across every quantitative subtopic—including Normal Distribution, 3-Set Venn Diagrams, Work/Rate, Relative Speed, Mixture Problems, Compound Interest, 3D Geometry (Cylinders & Solids), and Advanced Coordinate Geometry.

---

## Question Format Guidelines
* **Quantitative Comparison (QC):**
  * `[A]` Quantity A is greater.
  * `[B]` Quantity B is greater.
  * `[C]` The two quantities are equal.
  * `[D]` The relationship cannot be determined from the information given.
* **Geometric Figures:** Figures are **NOT** necessarily drawn to scale. Do not assume angles or segment lengths based on appearance unless explicitly stated or in coordinate geometry.

---

## Table of Contents
- [Topic 1: Advanced Number Properties & Divisibility (Drills 1–3)](#topic-1)
- [Topic 2: Absolute Value Inequalities & Functions (Drills 4–5)](#topic-2)
- [Topic 3: Sequences & Series (Drills 6–7)](#topic-3)
- [Topic 4: Advanced Word Problems (Rate, Work, Mixtures, Interest) (Drills 8–11)](#topic-4)
- [Topic 5: Statistics & Normal Distribution (Drills 12–14)](#topic-5)
- [Topic 6: Counting, Combinatorics & 3-Set Venn Diagrams (Drills 15–17)](#topic-6)
- [Topic 7: 3D Solids, Polygons & Coordinate Geometry (Drills 18–20)](#topic-7)

---

<a id="topic-1"></a><a id="topic-1-advanced-number-properties-divisibility-drills-13"></a><a id="topic-1-advanced-number-properties-divisibility-drills-1-3"></a>
## Topic 1: Advanced Number Properties & Divisibility (Drills 1–3)

### Drill 1: Total Divisors Formula
How many positive divisors does the integer $n = 720$ have?

- [A] $24$
- [B] $28$
- [C] $30$
- [D] $32$
- [E] $36$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] $30$**
>
> **Step-by-Step Solution:**
> 1. Find the prime factorization of $720$:
>    $$720 = 72 \times 10 = (8 \times 9) \times (2 \times 5) = 2^3 \times 3^2 \times 2^1 \times 5^1 = 2^4 \times 3^2 \times 5^1$$
> 2. The formula for the total number of positive divisors of $n = p_1^{a} p_2^{b} p_3^{c}$ is:
>    $$\text{Number of Divisors} = (a + 1)(b + 1)(c + 1)$$
> 3. Substitute the exponents:
>    $$\text{Divisors} = (4 + 1)(2 + 1)(1 + 1) = 5 \times 3 \times 2 = 30$$

</details>

---

### Drill 2: Remainder Arithmetic (QC)
When the positive integer $n$ is divided by $7$, the remainder is $5$.

| Quantity A | Quantity B |
| :---: | :---: |
| The remainder when $3n + 4$ is divided by $7$ | $5$ |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] The two quantities are equal.**
>
> **Step-by-Step Solution:**
> 1. Express $n$ using modular arithmetic or algebraic quotient form:
>    $$n = 7k + 5 \quad (k \in \mathbb{Z}_{\ge 0})$$
> 2. Substitute into $3n + 4$:
>    $$3n + 4 = 3(7k + 5) + 4 = 21k + 15 + 4 = 21k + 19$$
> 3. Rewrite $21k + 19$ in terms of multiples of $7$:
>    $$21k + 19 = 21k + 14 + 5 = 7(3k + 2) + 5$$
> 4. Since $7(3k + 2)$ is completely divisible by $7$, the remainder is $5$.
> 5. Both Quantity A and Quantity B equal $5$. The two quantities are equal.

</details>

---

### Drill 3: Trailing Zeros in Factorials
What is the number of trailing zeros in the decimal expansion of $100!$?

- [A] $20$
- [B] $22$
- [C] $24$
- [D] $25$
- [E] $28$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] $24$**
>
> **Step-by-Step Solution:**
> 1. Each trailing zero in a decimal representation corresponds to a factor of $10 = 2 \times 5$.
> 2. In $100!$, factors of $2$ are far more abundant than factors of $5$. Therefore, the number of trailing zeros equals the highest power of $5$ dividing $100!$.
> 3. Apply Legendre's formula:
>    $$E_5(100!) = \left\lfloor\frac{100}{5}\right\rfloor + \left\lfloor\frac{100}{25}\right\rfloor + \left\lfloor\frac{100}{125}\right\rfloor = 20 + 4 + 0 = 24$$
> 4. There are $24$ trailing zeros.

</details>

---

<a id="topic-2"></a><a id="topic-2-absolute-value-inequalities-functions-drills-45"></a><a id="topic-2-absolute-value-inequalities-functions-drills-4-5"></a>
## Topic 2: Absolute Value Inequalities & Functions (Drills 4–5)

### Drill 4: Absolute Value Range (Select All)
Which of the following values of $x$ satisfy the inequality $|2x - 5| \le 9$?  
*Indicate all such values.*

- [A] $-3$
- [B] $-2$
- [C] $0$
- [D] $5$
- [E] $7$
- [F] $8$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answers:** **[B] $-2$, [C] $0$, [D] $5$, [E] $7$**
>
> **Step-by-Step Solution:**
> 1. Unfold the absolute value inequality $|u| \le a \iff -a \le u \le a$:
>    $$-9 \le 2x - 5 \le 9$$
> 2. Add $5$ to all three parts:
>    $$-4 \le 2x \le 14$$
> 3. Divide by $2$:
>    $$-2 \le x \le 7$$
> 4. Evaluate each choice against the interval $[-2, 7]$:
>    - [A] $-3 < -2$ (False)
>    - [B] $-2 \in [-2, 7]$ (True)
>    - [C] $0 \in [-2, 7]$ (True)
>    - [D] $5 \in [-2, 7]$ (True)
>    - [E] $7 \in [-2, 7]$ (True)
>    - [F] $8 > 7$ (False)

</details>

---

### Drill 5: Symmetric Composite Function (QC)
Let $f(x) = x^2 - 4x + 7$.

| Quantity A | Quantity B |
| :---: | :---: |
| $f(2 - t)$ | $f(2 + t)$ |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] The two quantities are equal.**
>
> **Step-by-Step Solution:**
> 1. Rewrite $f(x)$ by completing the square:
>    $$f(x) = (x^2 - 4x + 4) + 3 = (x - 2)^2 + 3$$
> 2. Evaluate **Quantity A**:
>    $$f(2 - t) = ((2 - t) - 2)^2 + 3 = (-t)^2 + 3 = t^2 + 3$$
> 3. Evaluate **Quantity B**:
>    $$f(2 + t) = ((2 + t) - 2)^2 + 3 = (t)^2 + 3 = t^2 + 3$$
> 4. Both quantities simplify to $t^2 + 3$ for any real number $t$. The two quantities are equal.

</details>

---

<a id="topic-3"></a><a id="topic-3-sequences-series-drills-67"></a><a id="topic-3-sequences-series-drills-6-7"></a>
## Topic 3: Sequences & Series (Drills 6–7)

### Drill 6: Arithmetic Series Sum
An arithmetic sequence has a first term $a_1 = 7$ and a common difference $d = 4$. What is the sum of the first $30$ terms of this sequence?

- [A] $1,860$
- [B] $1,950$
- [C] $2,010$
- [D] $2,120$
- [E] $2,250$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] $1,950$**
>
> **Step-by-Step Solution:**
> 1. The $n$th term of an arithmetic sequence is $a_n = a_1 + (n - 1)d$:
>    $$a_{30} = 7 + (29)(4) = 7 + 116 = 123$$
> 2. The sum of $n$ terms is given by $S_n = \frac{n}{2}(a_1 + a_n)$:
>    $$S_{30} = \frac{30}{2}(7 + 123) = 15 \times 130 = 1,950$$

</details>

---

### Drill 7: Infinite Geometric Series (Numeric Entry)
The first term of an infinite geometric series is $a_1 = 18$, and the common ratio is $r = -\frac{1}{3}$. What is the sum of the series?

*Give your answer as a fraction or decimal.*

$$\frac{\boxed{\phantom{000}}}{\boxed{\phantom{000}}}$$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **$\dfrac{27}{2}$** (or $13.5$)
>
> **Step-by-Step Solution:**
> 1. For $|r| < 1$, the sum of an infinite geometric series is:
>    $$S_\infty = \frac{a_1}{1 - r}$$
> 2. Substitute $a_1 = 18$ and $r = -\frac{1}{3}$:
>    $$S_\infty = \frac{18}{1 - \left(-\frac{1}{3}\right)} = \frac{18}{1 + \frac{1}{3}} = \frac{18}{\frac{4}{3}} = 18 \times \frac{3}{4} = \frac{54}{4} = \frac{27}{2} = 13.5$$

</details>

---

<a id="topic-4"></a><a id="topic-4-advanced-word-problems-rate-work-mixtures-interest-drills-811"></a><a id="topic-4-advanced-word-problems-rate-work-mixtures-interest-drills-8-11"></a>
## Topic 4: Advanced Word Problems (Rate, Work, Mixtures, Interest) (Drills 8–11)

### Drill 8: Round-Trip Average Speed (Harmonic Mean)
A driver travels from Town A to Town B at an average speed of $40\text{ miles per hour}$, and immediately returns from Town B to Town A along the exact same route at an average speed of $60\text{ miles per hour}$. What is the average speed for the entire round trip in miles per hour?

- [A] $48$
- [B] $49$
- [C] $50$
- [D] $52$
- [E] $54$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[A] $48$**
>
> **Step-by-Step Solution:**
> 1. Let the one-way distance between Town A and Town B be $d\text{ miles}$.
> 2. Time going: $t_1 = \frac{d}{40}\text{ hours}$.
> 3. Time returning: $t_2 = \frac{d}{60}\text{ hours}$.
> 4. Total round-trip distance $= 2d$. Total time $= t_1 + t_2 = \frac{d}{40} + \frac{d}{60} = \frac{3d + 2d}{120} = \frac{5d}{120} = \frac{d}{24}$.
> 5. Average speed:
>    $$\text{Average Speed} = \frac{\text{Total Distance}}{\text{Total Time}} = \frac{2d}{\frac{d}{24}} = 2 \times 24 = 48\text{ mph}$$
> *(Note: A common trap is simply averaging $(40+60)/2 = 50$, which ignores that more time is spent driving at the slower speed).*

</details>

---

### Drill 9: Combined Work with Leaking Tank
Pipe A can fill an empty reservoir in $6\text{ hours}$, and Pipe B can fill it in $8\text{ hours}$. A drain at the bottom can empty a full reservoir in $12\text{ hours}$. If both pipes and the drain are opened simultaneously when the reservoir is empty, how many hours will it take to fill the reservoir?

- [A] $4.0$
- [B] $4.8$
- [C] $5.2$
- [D] $5.6$
- [E] $6.0$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] $4.8$**
>
> **Step-by-Step Solution:**
> 1. Express each hourly rate:
>    $$\text{Rate}(A) = +\frac{1}{6}, \quad \text{Rate}(B) = +\frac{1}{8}, \quad \text{Rate}(\text{Drain}) = -\frac{1}{12}$$
> 2. Combined net hourly rate:
>    $$\text{Net Rate} = \frac{1}{6} + \frac{1}{8} - \frac{1}{12} = \frac{4 + 3 - 2}{24} = \frac{5}{24}\text{ reservoirs/hour}$$
> 3. Time to fill $1$ complete reservoir:
>    $$\text{Time} = \frac{1}{\text{Net Rate}} = \frac{24}{5} = 4.8\text{ hours}$$

</details>

---

### Drill 10: Solution Mixture Concentration
How many liters of pure water must be added to $40\text{ liters}$ of an $80\%$ acid solution to dilute it into a $50\%$ acid solution?

- [A] $20$
- [B] $24$
- [C] $25$
- [D] $30$
- [E] $32$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] $24$**
>
> **Step-by-Step Solution:**
> 1. The amount of pure acid in the initial solution is:
>    $$\text{Acid} = 0.80 \times 40 = 32\text{ liters}$$
> 2. Let $w$ be the volume of pure water added. Pure water contains $0\%$ acid.
> 3. The new total volume is $40 + w$ liters. Set the acid concentration equal to $50\%$:
>    $$\frac{32}{40 + w} = 0.50 = \frac{1}{2}$$
> 4. Cross-multiply:
>    $$40 + w = 64 \implies w = 24\text{ liters}$$

</details>

---

### Drill 11: Compound Interest Compounded Semiannually (QC)
An initial principal $P = \$10,000$ is invested for $2\text{ years}$ at an annual interest rate of $6\%$.

| Quantity A | Quantity B |
| :---: | :---: |
| The total interest earned with semiannual compounding | The total interest earned with annual compounding |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[A] Quantity A is greater.**
>
> **Step-by-Step Solution:**
> 1. For compound interest, compounding more frequently within each year always yields a strictly higher effective annual rate because previously accrued interest earns additional interest sooner:
>    $$\left(1 + \frac{r}{n}\right)^{nt}$$
> 2. **Semiannual ($n = 2$):**
>    $$A_A = 10,000 \left(1 + \frac{0.06}{2}\right)^{2 \times 2} = 10,000(1.03)^4 \approx 10,000(1.1255) = \$11,255.09$$
>    $$\text{Interest}_A = \$1,255.09$$
> 3. **Annual ($n = 1$):**
>    $$A_B = 10,000 (1 + 0.06)^2 = 10,000(1.1236) = \$11,236.00$$
>    $$\text{Interest}_B = \$1,236.00$$
> 4. $\$1,255.09 > \$1,236.00 \implies \text{Quantity A is greater}$.

</details>

---

<a id="topic-5"></a><a id="topic-5-statistics-normal-distribution-drills-1214"></a><a id="topic-5-statistics-normal-distribution-drills-12-14"></a>
## Topic 5: Statistics & Normal Distribution (Drills 12–14)

### Drill 12: Standard Deviation Shift vs. Scale (QC)
Let $S = \{x_1, x_2, \dots, x_n\}$ be a set of numbers with standard deviation $\sigma > 0$.  
Set $T$ is formed by multiplying each number in $S$ by $2$ and then adding $5$.  
Set $U$ is formed by multiplying each number in $S$ by $3$ and then subtracting $10$.

| Quantity A | Quantity B |
| :---: | :---: |
| The standard deviation of set $T$ | The standard deviation of set $U$ |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] Quantity B is greater.**
>
> **Step-by-Step Solution:**
> 1. Adding or subtracting a constant $c$ to every element in a dataset shifts the entire distribution along the axis without altering the distance between points, leaving the standard deviation unchanged:
>    $$\text{SD}(X + c) = \text{SD}(X)$$
> 2. Multiplying every element by a constant factor $k$ scales all distances by $|k|$:
>    $$\text{SD}(kX + c) = |k| \cdot \text{SD}(X)$$
> 3. For Set $T$: $\text{SD}(T) = 2\sigma$.
> 4. For Set $U$: $\text{SD}(U) = 3\sigma$.
> 5. Since $\sigma > 0$, $3\sigma > 2\sigma$. Therefore, Quantity B is greater.

</details>

---

### Drill 13: Normal Distribution 68-95-99.7 Rule
The scores on a standardized test are normally distributed with a mean of $500$ and a standard deviation of $100$. Approximately what percentage of test takers scored between $400$ and $700$?

- [A] $68\%$
- [B] $81.5\%$
- [C] $84\%$
- [D] $95\%$
- [E] $97.5\%$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] $81.5\%$**
>
> **Step-by-Step Solution:**
> 1. Calculate the $z$-scores for the boundary points:
>    $$z_1 = \frac{400 - 500}{100} = -1$$
>    $$z_2 = \frac{700 - 500}{100} = +2$$
> 2. By the empirical rule (68-95-99.7):
>    - From $z = -1$ to $z = 0$ contains $\frac{68\%}{2} = 34\%$.
>    - From $z = 0$ to $z = +2$ contains $\frac{95\%}{2} = 47.5\%$.
> 3. Sum the probabilities across both intervals:
>    $$\text{Percentage} = 34\% + 47.5\% = 81.5\%$$

</details>

---

### Drill 14: Combined Mean with Unequal Subgroups
Class A contains $20$ students with a mean exam score of $85$. Class B contains $30$ students with a mean exam score of $75$. What is the overall mean score of the combined $50$ students?

- [A] $78$
- [B] $79$
- [C] $80$
- [D] $81$
- [E] $82$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] $79$**
>
> **Step-by-Step Solution:**
> 1. Compute total scores for each class:
>    $$\text{Sum}_A = 20 \times 85 = 1,700$$
>    $$\text{Sum}_B = 30 \times 75 = 2,250$$
> 2. Total combined sum $= 1,700 + 2,250 = 3,950$.
> 3. Total number of students $= 20 + 30 = 50$.
> 4. Combined mean:
>    $$\text{Mean} = \frac{3,950}{50} = 79$$

</details>

---

<a id="topic-6"></a><a id="topic-6-counting-combinatorics-3-set-venn-diagrams-drills-1517"></a><a id="topic-6-counting-combinatorics-3-set-venn-diagrams-drills-15-17"></a>
## Topic 6: Counting, Combinatorics & 3-Set Venn Diagrams (Drills 15–17)

### Drill 15: 3-Set Venn Diagram (Overlapping Sets)
In a survey of $120$ college freshmen:
- $65$ take Calculus
- $50$ take Physics
- $40$ take Chemistry
- $25$ take Calculus and Physics
- $20$ take Calculus and Chemistry
- $15$ take Physics and Chemistry
- $8$ take all three subjects

How many freshmen in the survey take none of these three subjects?

- [A] $12$
- [B] $15$
- [C] $17$
- [D] $20$
- [E] $23$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] $17$**
>
> **Step-by-Step Solution:**
> 1. Use the Principle of Inclusion-Exclusion for three sets:
>    $$|A \cup B \cup C| = \sum |A| - \sum |A \cap B| + |A \cap B \cap C|$$
> 2. Substitute the given values:
>    $$|A \cup B \cup C| = (65 + 50 + 40) - (25 + 20 + 15) + 8$$
>    $$|A \cup B \cup C| = 155 - 60 + 8 = 103$$
> 3. The number taking none of these subjects is the complement:
>    $$\text{None} = \text{Total} - |A \cup B \cup C| = 120 - 103 = 17$$

</details>

---

### Drill 16: Circular Permutations (QC)
A committee of $6$ delegates sits around a circular round table. Two seatings are considered identical if each person has the same neighbors on their left and right.

| Quantity A | Quantity B |
| :---: | :---: |
| The number of distinct circular seating arrangements of the $6$ delegates | $120$ |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] The two quantities are equal.**
>
> **Step-by-Step Solution:**
> 1. The formula for the number of circular permutations of $n$ distinct objects is:
>    $$P_{\text{circle}} = (n - 1)!$$
> 2. For $n = 6$ delegates:
>    $$P_{\text{circle}} = (6 - 1)! = 5! = 5 \times 4 \times 3 \times 2 \times 1 = 120$$
> 3. Quantity A $= 120$, and Quantity B $= 120$. Both quantities are equal.

</details>

---

### Drill 17: Committee Selection with Subgroup Constraints
A research council consists of $5$ mathematicians and $6$ computer scientists. A project committee of $4$ members is to be formed. How many different committees can be formed that contain at least $2$ mathematicians?

- [A] $180$
- [B] $205$
- [C] $215$
- [D] $240$
- [E] $330$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] $215$**
>
> **Step-by-Step Solution:**
> 1. Partition the selection into mutually exclusive cases satisfying \"at least $2$ mathematicians\":
>    - **Case 1: Exactly 2 mathematicians and 2 computer scientists**
>      $$\binom{5}{2} \times \binom{6}{2} = 10 \times 15 = 150$$
>    - **Case 2: Exactly 3 mathematicians and 1 computer scientist**
>      $$\binom{5}{3} \times \binom{6}{1} = 10 \times 6 = 60$$
>    - **Case 3: All 4 mathematicians and 0 computer scientists**
>      $$\binom{5}{4} \times \binom{6}{0} = 5 \times 1 = 5$$
> 2. Sum the valid cases:
>    $$\text{Total} = 150 + 60 + 5 = 215$$

</details>

---

<a id="topic-7"></a><a id="topic-7-3d-solids-polygons-coordinate-geometry-drills-1820"></a><a id="topic-7-3d-solids-polygons-coordinate-geometry-drills-18-20"></a>
## Topic 7: 3D Solids, Polygons & Coordinate Geometry (Drills 18–20)

### Drill 18: Cylinder Volume vs. Surface Area (QC)
Right circular cylinder $C$ has radius $r = 3$ and height $h = 4$.

| Quantity A | Quantity B |
| :---: | :---: |
| The volume of cylinder $C$ | The total surface area of cylinder $C$ |

- [A] Quantity A is greater.
- [B] Quantity B is greater.
- [C] The two quantities are equal.
- [D] The relationship cannot be determined from the information given.

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[B] Quantity B is greater.**
>
> **Step-by-Step Solution:**
> 1. Compute **Quantity A** (Volume of Cylinder):
>    $$V = \pi r^2 h = \pi (3^2)(4) = 36\pi$$
> 2. Compute **Quantity B** (Total Surface Area of Cylinder):
>    $$\text{Total Surface Area} = 2\pi r h + 2\pi r^2 = 2\pi(3)(4) + 2\pi(3^2) = 24\pi + 18\pi = 42\pi$$
> 3. Comparing numerical values:
>    $$36\pi < 42\pi \implies \text{Quantity B is greater}$$

</details>

---

### Drill 19: Sum of Interior Angles in a Polygon
A regular polygon has interior angles that each measure $144^\circ$. How many sides does the polygon have?

- [A] $8$
- [B] $9$
- [C] $10$
- [D] $12$
- [E] $15$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **[C] $10$**
>
> **Step-by-Step Solution:**
> 1. In any regular polygon, the sum of an interior angle and an exterior angle at each vertex is $180^\circ$:
>    $$\text{Exterior Angle} = 180^\circ - 144^\circ = 36^\circ$$
> 2. The sum of all exterior angles for any convex polygon is always $360^\circ$:
>    $$n \times 36^\circ = 360^\circ \implies n = \frac{360^\circ}{36^\circ} = 10$$
> 3. The polygon has $10$ sides (a decagon).

</details>

---

### Drill 20: Perpendicular Lines in Coordinate Geometry (Numeric Entry)
In the $xy$-plane, line $L_1$ has equation $3x - 4y = 12$. Line $L_2$ is perpendicular to line $L_1$. What is the slope of line $L_2$?

*Give your answer as a fraction.*

$$\frac{\boxed{\phantom{000}}}{\boxed{\phantom{000}}}$$

<details>
<summary><b>View Answer & Explanation</b></summary>

> **Correct Answer:** **$-\dfrac{4}{3}$**
>
> **Step-by-Step Solution:**
> 1. Convert equation $L_1$ to slope-intercept form $y = mx + b$:
>    $$3x - 4y = 12 \implies 4y = 3x - 12 \implies y = \frac{3}{4}x - 3$$
> 2. The slope of $L_1$ is $m_1 = \frac{3}{4}$.
> 3. Two non-vertical lines are perpendicular if and only if their slopes are negative reciprocals:
>    $$m_1 \cdot m_2 = -1 \implies m_2 = -\frac{1}{m_1} = -\frac{1}{3/4} = -\frac{4}{3}$$

</details>
