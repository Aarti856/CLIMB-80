# Benchmark Questions — CLIMB-80

80 university-level mathematics problems sourced from MIT OpenCourseWare, spanning three domains and three difficulty levels. The full machine-readable dataset is available in `benchmark_questions.csv` in this folder.

## Problem Distribution

| Subject | Easy | Medium | Hard | Total |
|---|---|---|---|---|
| Calculus | 10 | 10 | 7 | 27 |
| Probability | 9 | 10 | 7 | 26 |
| Linear Algebra | 9 | 10 | 8 | 27 |
| **Total** | **28** | **30** | **22** | **80** |

All problems were sourced from MIT OpenCourseWare and selected to test analytical reasoning and multi-step problem-solving rather than factual recall. Difficulty classification was performed manually based on the number of reasoning steps required, conceptual complexity, and the mathematical maturity expected of a university-level student.

---

## Calculus

### Easy (10 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Basic Differentiation | Problem Set: Unit 1: Differentiation 1E-1a Find the derivative of the following polynomial. a) x¹⁰ + 3x⁵ + 2x³ + 4. | f'(x) = 10x⁹ + 15x⁴ + 6x² | MIT OpenCourseWare |
| 2 | Basic Differentiation ; Critical Points | Find the points (x, y) of the graph y = x³ + x² − x + 2 at which the slope of the tangent line is horizontal. | 1/3, 49/27) and (−1, 3) | MIT OpenCourseWare |
| 3 | Limits & Continuity | Calculate the following limit if it exists: lim_{x→0} 4/(x−1). | -4 | MIT OpenCourseWare |
| 4 | Limits & Continuity | Calculate the limit: lim(x→2) (x − 2)/(x² − 4). | 1/4 | MIT OpenCourseWare |
| 5 | Chain Rule | Find the derivative of f(x) = (x² + 2)² using two methods | f'(x) = 4x³ + 8x | MIT OpenCourseWare |
| 6 | Exponential & Logarithmic Derivatives | Calculate the derivative of f(x) = xe^x. | f'(x) = (x + 1)eˣ | MIT OpenCourseWare |
| 7 | Definite Integrals ; Fundamental Theorem of Calculus | Find the area under one arch of sin x, i.e., evaluate ∫₀^π sin x dx. | 2 | MIT OpenCourseWare |
| 8 | Indefinite Integration; Polynomials | Compute the indefinite integral ∫(2x⁴ + 3x² + x + 8) dx. | (2/5)x⁵ + x³ + x²/2 + 8x + C | MIT OpenCourseWare |
| 9 | Areas Between Curves | Find the area under the curve y = 1 − x² (the region between the curve and the x-axis) in two ways. | 4/3 | MIT OpenCourseWare |
| 10 | Infinite Series — Geometric Series | Problem Set: Unit 7: Infinite Series 7A-1a Does the series 1 + 1/4 + 1/16 + 1/64 + … + 1/4ⁿ + … converge or diverge? If it converges, find its sum. | Coverage, sum:4/3 | MIT OpenCourseWare |

### Medium (10 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Implicit Differentiation | Problem Set: Unit 1: Differentiation 1F-3 Find dy/dx for y = x^(1/n) by implicit differentiation. | dy/dx = (1/n)x^(1/n − 1) | MIT OpenCourseWare |
| 2 | Higher Derivatives | Problem Set: Unit 1: Differentiation 1G-1a Calculate y'' for f(x) = 3x² + 2x + 4√x. | y'' = 6 − x^(−3/2) | MIT OpenCourseWare |
| 3 | Linear Approximation (Linearization) | Problem Set: Unit 2: Applications of Differentiation 2A-1 Find the linearization of f(x) = √(a + bx) at x = 0 (where a > 0, and a and b are constants), using the derivative, and also by using the basic approximation formulas | √a + (b / 2√a)·x | MIT OpenCourseWare |
| 4 | Max-Min Problems | Problem Set: Unit 2: Applications of Differentiation 2C-1 Cut four identical squares of side x out of the corners of a 12 × 12 inch piece of cardboard and fold the sides up to make a box without a top. Find the size of the corner square that maximizes the volume of the box. | x = 2 inches | MIT OpenCourseWare |
| 5 | Related Rates | Problem Set: Unit 2: Applications of Differentiation 2E-4 Sand is pouring onto a conical pile at a rate of 12 m³/min, in such a way that the diameter of the base is always 3/2 the height. Find the rate at which the height is increasing when the pile is 2 m tall. | 16/3π m/min | MIT OpenCourseWare |
| 6 | Definite Integrals | Problem Set: Unit 3: Integration3C-2a Calculate the definite integral ∫₀² √(3x + 5) dx. | (2/9)(11^(3/2) − 5^(3/2)) | MIT OpenCourseWare |
| 7 | Differential Equations, Separation of Variables | Problem Set: Unit 3: Integration 3F-2a Solve the differential equation dy/dx = 4xy with the initial condition y(1) = 3. Find y(3). | y(3) =3e¹⁶ | MIT OpenCourseWare |
| 8 | Areas Between Curves | Problem Set: Unit 4: Applications of Integration 4A-4 Find the area between y = sin x and y = cos x from one crossing to the next | 2√2 | MIT OpenCourseWare |
| 9 | Trigonometric Integrals | Problem Set: Unit 5: Integration Techniques 5C-1 Evaluate ∫ sin²(x) dx. | x/2 − sin(2x)/4 + C | MIT OpenCourseWare |
| 10 | L Hospital's Rule | Problem Set: Unit 6: Additional Topics 6A-1a Find the limit: lim(x→0) sin(3x)/x. | 3 | MIT OpenCourseWare |

### Hard (7 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Max and MIn | Problem Set: Unit 2: Applications of Differentiation 2C-4 The U.S. Postal Service accepts boxes whose length plus girth equals at most 108 inches. What are the dimensions of the accepted box of largest volume, and what is its volume in cubic feet? ("Length" is the longest dimension and "girth" is the perimeter of the perpendicular face. Note: the best shape for the face is a square.) | Dimensions: 36 in × 18 in × 18 in; Volume = 6.75 cubic feet | MIT OpenCourseWare |
| 2 | Related Rates | Problem Set: Unit 2: Applications of Differentiation 2E-7 A trough is filled with water at a rate of 1 cubic meter per second. The trough has a trapezoidal cross-section with a lower base of half a meter, one-meter sides opening outward at 45° from the base, and a length of 4 meters. What is the rate at which the water level h is rising when h is one half meter? | dh/dt = 1/6 meters per second | MIT OpenCourseWare |
| 3 | Definite Integrals | Problem Set: Unit 3: Integration 3C-3a Calculate the definite integral ∫₁² x dx/(x² + 1). | (1/2)ln(5/2) | MIT OpenCourseWare |
| 4 | Volumes of Revolution, Disk Method | Problem Set: Unit 4: Applications of Integration 4B-1a Find the volume of the solid of revolution generated by rotating the region bounded by y = 1 − x², y = 0 around the x-axis. | 16π/15 | MIT OpenCourseWare |
| 5 | Integration by Partial Fractions | Problem Set: Unit 5: Integration Techniques 5E-1 Evaluate the integral ∫ dx / ((x − 2)(x + 3)). | (1/5)ln\|x − 2\| − (1/5)ln\|x + 3\| + C | MIT OpenCourseWare |
| 6 | Integration by Parts | Problem Set: Unit 5: Integration Techniques 5F-2a Evaluate ∫ x eˣ dx. | xeˣ − eˣ + C | MIT OpenCourseWare |
| 7 | Infinite Series | Problem Set: Unit 7: Infinite Series 7A-4b Find the sum of the series Σ(n=1 to ∞) 1/(n(n+2)) by first finding the partial sum Sₘ. | 3/4 | MIT OpenCourseWare |

## Probability

### Easy (9 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | binomial probability | (a) Count the number of ways to get exactly 3 heads in 10 flips of a coin. (b) For a fair coin, what is the probability of exactly 3 heads in 10 flips? | (a) 10c3 (b) 0.117 | MIT OpenCourseWare |
| 2 | Inclusion–Exclusion Principle | A band consists of singers and guitar players: 7 people sing, 4 play guitar, 2 do both How many people are in the band? | 9 | MIT OpenCourseWare |
| 3 | Rule of Product / Permutations | There are 5 Competitors in an Olympics 100m final.How many ways can gold, silver, and bronze be awarded? | 60 ways (5 × 4 × 3 = 60) | MIT OpenCourseWare |
| 4 | Sample Spaces and Coin Tosses | You flip a fair coin 3 times, determine the probability of the below events. Assume all sequences are equally likely. (a) Three heads: HHH (b) The sequence head, tail, head: HTH (c) Any sequence with 2 heads and 1 tail (d) Any sequence where the number of heads is greater than or equal to the number of tails | 1/8, 1/8, 3/8, 1/2 | MIT OpenCourseWare |
| 5 | Weighted Probability Distributions | Bob has a peculiar pair of four-sided dice. When he rolls the dice, the probability of any particular outcome is proportional to the sum of the results of each die. All outcomes that result in a particular sum are equally likely. (a) What is the probability of the sum being even? (b) What is the probability of Bob rolling a 2 and a 3, in any order? | 1/2, 1/8 | MIT OpenCourseWare |
| 6 | Permutations and Sample Spaces | The hats of n persons are thrown into a box. The persons then pick up their hats at random (i.e., so that every assignment of the hats to the persons is equally likely). What is the probability that (a) every person gets his or her hat back? | 1/n! | MIT OpenCourseWare |
| 7 |  | Roll two dice and consider the following events • 𝐴 = ‘first die is 3’ • 𝐵 = ‘sum is 6’ • 𝐶 = ‘sum is 7’ 𝐴 is independent of (a) 𝐵 and 𝐶 (b) 𝐵 alone (c) 𝐶 alone (d) Neither 𝐵 or 𝐶. | c | MIT OpenCourseWare |
| 8 |  | Ignoring leap days, the days of the year can be numbered 1 to 365. Assume that birthdays are equally likely to fall on any day of the year. Consider a group of 𝑛 people, of which you are not a member. An element of the sample space 𝑆 will be a sequence of 𝑛 birthdays (one for each person). (a) Define the probability function 𝑃 for 𝑆. (This will depend on 𝑛.) | 1/365 to power n | MIT OpenCourseWare |
| 9 | Variance | Suppose 𝑋 is a discrete random variable, True or False: If Var(𝑋) = 0 then 𝑋 is constant. Solution: True. If 𝑋 can take more than one value with positive probability, than Var(𝑋) will be a sum of positive terms. So, 𝑋 is constant if and only if Var(𝑋) = 0. | TRUE | MIT OpenCourseWare |

### Medium (10 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Distinct Outcomes | Consider the following experiment. Roll a 20-sided die (D20) 9 times. What is the probability that all 9 rolls are distinct.For this experiment, how would you define the sample space, probability function, and event? Compute the probability that all rolls (in one trial of 9 rolls) are distinct. | 0.119 | MIT OpenCourseWare |
| 2 | Inclusion–Exclusion Principle | Supposes a class has 50 students: 20 male (M), 25 brown-eyed (B) For a randomly chosen student, what is the range of possible values for 𝑝 = 𝑃 (𝑀 ∪ 𝐵)? (a) 𝑝 ≤ 0.4 (b) 0.4 ≤ 𝑝 ≤ 0.5 (c) 0.4 ≤ 𝑝 ≤ 0.9 (d) 0.5 ≤ 𝑝 ≤ 0.9 (e) 0.5 ≤ 𝑝 | (d) 0.5 ≤ 𝑝 ≤ 0.9 | MIT OpenCourseWare |
| 3 | Conditional Probability | For this problem assume that puppies are equally probable to be male or female. Likewise for kittens. Be sure to carefully justify your answers. (a) Our dog Layla had two puppies. The older puppy is female. What is the probability that both puppies are female?(b) Our cat Ariel had two kittens. At least one of them is male. What is the probability that both kittens are males? | (a) 1/2 (b) 1/3 | MIT OpenCourseWare |
| 4 | Conditional Probability and Bayes' Theorem | The local widget factory is having a blowout widget sale. Everything must go, old and new. The factory has 500 old widgets, and 1500 new widgets in stock. The problem is that 15% of the old widgets are defective, and 5% of the new ones are defective as well. You can assume that widgets are selected at random when an order comes in. You are the first customer since the sale was announced. (a) You flip a fair coin once to decide whether to buy old or new widgets. You order two widgets of the same type, chosen based on the outcome of the coin toss. What is the probability that they will both be defective? (b) Given that both widgets turn out to be defective, what is the probability that they were old widgets? | 0.0125, 0.8965 | MIT OpenCourseWare |
| 5 | Bayes' Theorem | Most mornings, Victor checks the weather report before deciding whether to carry an umbrella. If the forecast is “rain,” the probability of actually having rain that day is 80%. On the other hand, if the forecast is “no rain,” the probability of it actually raining is equal to 10%. During fall and winter the forecast is “rain” 70% of the time and during summer and spring it is 20%. (a) One day, Victor missed the forecast and it rained. What is the probability that the forecast was “rain” if it was during the winter? What is the probability that the forecast was “rain” if it was during the summer? | 2/3 | MIT OpenCourseWare |
| 6 | Bayes' Theorem | A device has a sensor connected to an alarming system. The sensor triggers with probability 0.95 if dangerous conditions exist in a given day and with probability 0.005 if conditions are normal during the day. Days with dangerous conditions occur with probability 0.005. Given the above: (a) What is the probability of false alarm, i.e. the probability that conditions are normal when the alarm system triggers? | 0.5116 | MIT OpenCourseWare |
| 7 | Expected Value and Variance | Let X1 and X2 be independent and identically distributed random variables with common mean value m and common variance σ2 . (a) Find the mean value and variance of Y1 = X1 + X2 | 2σ2, | MIT OpenCourseWare |
| 8 | Conditional Probability | (a) Roll three dice. Find the probability that there are at least two sixes given that there is at least one six. (b) Find the conditional probability that a standard poker hand has at least 3 aces given that it has at least 2. | (1 − p0 − p1)/(1 − p0), (p3 + p4)/(p2 + p3 + p4) | MIT OpenCourseWare |
| 9 | Negative Binomial Distribution | Consider an infinite sequence of independent tosses of a coin that comes up heads with probability 1/3. Let X be such that the third heads occurs on the Xth toss. u8 (a) Compute P[X = 9]. (b) Compute E[X]. | (1/3)2(2/3)6(1/3) 2, 9 | MIT OpenCourseWare |
| 10 | Poisson Distribution | Suppose X is Poissonian random variable with parameter λ1 = 1, Y is an independent Poissonian random variable with λ2 = 2, and Z is a Poissonian random variable with parameter λ3 = 3. Assume X and Y and Z are independent and compute the following: (a) P{X + Y + Z = 8} | e power-6 * 6 power 8/ 8! | MIT OpenCourseWare |

### Hard (7 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Discrete Random Variables & Expected Value | You roll two fair (6-sided) dice. If the sum of the dice is greater than 9, you win $100. If the sum is 9 or less you get to roll again. On the second roll, if your sum of dice is greater than 9, you win $50, otherwise you win nothing. Let 𝑋 be the random variable of how much money you win by playing this game. (a) Construct a probability model for 𝑋, i.e. make a probability table.(b) What is the expected amount you will win playing the game? | (b) 23.61 | MIT OpenCourseWare |
| 2 | Maximum Likelihood Estimation (MLE) | The Pareto distribution is used in economics modeling. To keep it simple we’ll use the Pareto distribution that takes values 𝑥 ≥ 1 and has pdf 𝑓(𝑥 ∣ 𝜃) = 𝜃𝑥−𝜃−1 for 𝑥 ≥ 1. It’s defined whenever 𝜃 > 0. Assume 𝑥1, … , 𝑥𝑛 are 𝑛 independent samples from a Pareto(𝜃) distribution, find the maximum likelihood estimate of 𝜃. | pic | MIT OpenCourseWare |
| 3 | Bayes' Theorem | A certain medical condition exists in 1% of the population. A screening test for the condition has a 4% false positive rate and a 0% false negative rate. (a) What are the odds that a random person has the condition?(b) Suppose a random person tests positive for the condition. What are the odds they have the condition? | 1/99, 1/4 | MIT OpenCourseWare |
| 4 | Hypothesis Testing | Jerry wants to brag to his non-MIT colleagues about how smart MIT students are. To give himself credibility, he decides to run a statistical test comparing the IQ scores of MIT students and Harvard students. He collects IQ scores from 11 MIT students. The data has a sample mean of 115, with a sample standard deviation of 8. He then collects IQ scores from 11 Harvard students. Their scores have a sample mean of 110, with a sample standard deviation of 6. (a) Which test should he run to compare the IQ scores from the two schools? What assumptions will he need to make? What are the null and alternative hypotheses?(b) Run the test with a significance level of 𝛼 = 0.05. Should Jerry reject the null hypothesis or not? (In this problem there is some arithmetic. You will want to use √100/11 ≈ √9 = 3.) | pic | MIT OpenCourseWare |
| 5 | Binomial Distribution & Normal Approximation | MIT has decided to form a new Department of Statistics and Probability. In a vote for the new head of this department, suppose 50% of the MIT population supports Sarah, 20% supports So Hee, and the remaining 30% is split evenly among Jerry, Jen, Alessandre and Gabe. (a) A poll asks 100 random people whom they support. Estimate the probability that at least 45% of those polled support Sarah | 0.84 | MIT OpenCourseWare |
| 6 | Statistical Power | You independently draw 100 data points from a N(𝜇, 1) distribution, where 𝜇 is unknown. Suppose you test the null hypothesis 𝐻0 ∶ 𝜇 = 0 against the alternative hypothesis 𝐻𝐴 ∶ 𝜇 ≠ 0 using a significance level of 𝛼 = 0.05. What is the power of the test for the alternative 𝐻𝐴 ∶ 𝜇 = 0.4? | 0.98 | MIT OpenCourseWare |
| 7 | Bayesian Inference | A random process produces outcomes labeled 𝐴, 𝐵 and 𝐶 with probabilities 𝜃/2, 𝜃/2, 1 − 𝜃 respectively. Here 𝜃 is an unknown parameter with value between 0 and 1. You want to know the value of 𝜃. Before running any experiments you have a prior pdf for 𝜃 of 𝑓(𝜃) = 3𝜃2. You then run the process five times producing data 𝐴, 𝐵, 𝐶, 𝐴, 𝐵. Find the posterior probability density for 𝜃. | 56 | MIT OpenCourseWare |

## Linear Algebra

### Easy (9 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Linear Combinations and Dependence | Find a combination x₁w₁ + x₂w₂ + x₃w₃ that gives the zero vector where w₁=[1,2,3], w₂=[4,5,6], w₃=[7,8,9]. Are these vectors independent or dependent? | w₁ − 2w₂ + w₃ = 0. The vectors are dependent and lie in a plane. | MIT OpenCourseWare |
| 2 | Permutation matrices | (a) Find a 3 by 3 permutation matrix with P 3 = I (but not P = I). (b) Find a 4 by 4 permutation Pwith P4 = I. | Correct Answer: P = [[0,0,1],[1,0,0],[0,1,0]], cycling rows so P³ = I. (b) Let P be the block diagonal matrix with 1 and P on the diagonal: P = ( 0 P ). Since P 3 = I, also P3 = I. So P4 = P<>I. | MIT OpenCourseWare |
| 3 | Symmetric matrices and subspaces | Problem 18: True or false (check addition or give a counterexample): (a) The symmetric matrices in M (with AT = A) form a subspace. (b) The skew-symmetric matrices in M (with AT = −A) form a subspace. (c) The unsymmetric matrices in M (with AT<>A) form a subspace. | (a) True: AT = A and BT = B lead to (A + B)T = AT + BT = A + B. (b) True: AT = −A and BT = −B lead to (A + B)T = AT + BT = −A − B = −(A + B). 1 1 (c) False: ( 0 0 ) + ( 1 1 ) = ( 1 1 ). | MIT OpenCourseWare |
| 4 | Rank and Invertibility | Suppose A and B are n by n matrices, and AB = I. Prove from rank(AB) ≤ rank(A) that the rank of A is n. So A is invertible and B must be its two-sided inverse (Section 2.5). Therefore BA = I (which is not so obvious!). | n = rank(I) = rank(AB) ≤ rank(A) ≤ n, so rank(A) = n and A is invertible. | MIT OpenCourseWare |
| 5 | Markov Matrices and Steady State | Start with u₀=(1,0). Multiply repeatedly by Markov matrix A=[[0.8,0.3],[0.2,0.7]]. Find u₁, u₂, u₃ and state what property all four vectors share. | u₁=[0.8,0.2], u₂=[0.7,0.3], u₃=[0.65,0.35]. All vectors have components that sum to one. | MIT OpenCourseWare |
| 6 | Projection Matrices | If P 2 = P show that (I − P )2 = I − P . When P projects onto the column space of A, I − P projects onto the . | (I−P)² = I−2P+P² = I−P. I−P projects onto the left nullspace of A. | MIT OpenCourseWare |
| 7 | Determinants and Singular Matrices | If the entries in every row of A add to zero, solve Ax = 0 to prove det A = 0. If those entries add to one, show that det(A − I) = 0. Does this mean det A = I? | Rows summing to zero means x=(1,1,...,1) solves Ax=0 so det A=0. Rows of A−I sum to zero so det(A−I)=0. | MIT OpenCourseWare |
| 8 | Matrix Inverse | Suppose you solve Ax=b for three special right sides: Ax₁=[1,0,0], Ax₂=[0,1,0], Ax₃=[0,0,1]. If x₁, x₂, x₃ are columns of matrix X, what is AX? | AX = I. X is the inverse of A. | MIT OpenCourseWare |
| 9 | Singular Matrices and Elimination | Problem Set 1 Section 2.5, Problem 7 If A has row 1 + row 2 = row 3, show that A is not invertible by: (a) explaining why Ax=(1,0,0) cannot have a solution, (b) finding which right sides (b₁,b₂,b₃) might allow a solution, (c) stating what happens to row 3 during elimination. | (a) A₁·x+A₂·x=A₃·x means 1+0=0 — contradiction. (b) b₁+b₂=b₃ must hold. (c) Row 3 becomes zero during elimination. | MIT OpenCourseWare |

### Medium (10 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | Systems of Equations and Singular Systems | Three planes can fail to have an intersection point even if no planes are parallel. Find a third equation that cannot be solved together with x+y+z=0 and x−2y−z=1 | Row 3 must be a linear combination of rows 1 and 2 but right-hand side must violate that relation. Example: 2x+5y+4z=1. | MIT OpenCourseWare |
| 2 | LU Factorization | Compute L and U for A=[[a,a,a,a],[a,b,b,b],[a,b,c,c],[a,b,c,d]]. Find four conditions on a,b,c,d for four pivots. | Pivots are a, b−a, c−b, d−c. Conditions: a≠0, b≠a, c≠b, d≠c. | MIT OpenCourseWare |
| 3 | Null Space Analysis | How is the nullspace N(C) related to N(A) and N(B) if C=[A;B]? | N(C) = N(A) ∩ N(B). Cx=0 if and only if Ax=0 and Bx=0 simultaneously. | MIT OpenCourseWare |
| 4 | Orthogonal Projection | A is the 4×4 identity with last column removed (4×3). Project b=(1,2,3,4) onto column space of A. Find projection matrix P and the projection. | P=[[1,0,0,0],[0,1,0,0],[0,0,1,0],[0,0,0,0]]. Projection of b=(1,2,3,0). | MIT OpenCourseWare |
| 5 | Least Squares and Normal Equations | Write E=‖Ax−b‖² as a sum of four squares. Find ∂E/∂C=0 and ∂E/∂D=0 and divide by 2 to get normal equations AᵀAx̂=Aᵀb for the least squares line through points (0,0),(1,8),(3,8),(4,20). | Normal equations: 4C+8D=36 and 8C+26D=112. | MIT OpenCourseWare |
| 6 | Eigenvalues and Positive Definiteness | Problem Set 8 Problem 6. (§6.4,#7) 1 b (a) Find a symmetric matrix that has a negative eigenvalue. b 1 (b) How do you know it must have a negative pivot? (c) How do you know it can’t have two negative eigenvalues? | Take b>1. Eigenvalues are 1±b so one is negative. det=1−b² <0 so one pivot must be negative. c) The product of the eigenvalues equals the determinant, which is negative in this case. Two negative numbers cannothave a negativeproduct | MIT OpenCourseWare |
| 7 | Cholesky Factorization | Problem Set 9 Section 6.5, Problem 26 Find the Cholesky factorization C (upper triangular) for A=[[1,1,1],[1,2,2],[1,2,7]] | C=[[1,1,1],[0,1,1],[0,0,√5]]. | MIT OpenCourseWare |
| 8 | Rank Factorization COL × ROW | Problem Set 3 Section 3.3, Problem 25 Every m×n matrix of rank r reduces to (m×r)(r×n). Write the 3×4 matrix A = [[1,1,2,4],[1,2,2,5],[1,3,2,6]] as the product of pivot columns times first r rows of R | A = [[1,1],[1,2],[1,3]] × [[1,0,2,3],[0,1,0,1]]. Pivot columns of A multiplied by first 2 rows of R. | MIT OpenCourseWare |
| 9 | Fundamental Subspaces and Orthogonality | Problem Set 5 Section 4.1, Problem 9 If AᵀAx=0 then Ax=0. Reason: Ax is in the nullspace of Aᵀ and also in the column space of A and those spaces are orthogonal. Conclusion: AᵀA has the same nullspace as A. Complete the reasoning and fill in the blanks to prove this key fact. | Ax is in the nullspace of Aᵀ AND in the column space of A. Those spaces are orthogonal. Therefore Ax=0. So AᵀA has the same nullspace as A. | MIT OpenCourseWare |
| 10 | Determinants and Row Operations | Problem Set 6 Section 5.1, Problem 18 Use row operations to show that the 3×3 Vandermonde determinant is: det([[1,a,a²],[1,b,b²],[1,c,c²]]) = (b−a)(c−a)(c−b) | Subtract row 1 from rows 2 and 3, then factor (b−a) from row 2 and (c−a) from row 3. After one more elimination step: det = (b−a)(c−a)(c−b). | MIT OpenCourseWare |

### Hard (8 questions)

| Question No. | Subtopic | Problem Statement | Correct Answer | Source |
|---|---|---|---|---|
| 1 | LU Factorization Uniqueness | Problem Set 2 Section 2.6, Problem 18 If A=LDU and also A=L₁D₁U₁, derive L₁⁻¹LD=D₁U₁U⁻¹ and use it to prove uniqueness: L=L₁, D=D₁, U=U₁. | Left side is lower triangular, right side upper triangular, so both are diagonal. Since both have diagonal 1s they equal I, giving L=L₁, U=U₁, D=D₁. | MIT OpenCourseWare |
| 2 | Rank and Solution Existence | Problem Set 3 Section 3.4, Problem 25 Write down all relations between r, m, n if Ax=b has: (a) no solution for some b, (b) infinitely many solutions for every b, (c) exactly one solution for some b no solution for other b, (d) exactly one solution for every b. | (a) The system has less than full row rank: r<m. (b) The system has full row rank, and less than full column rank: m = r<n. (c) The system has full column rank, and less than full row rank: n = r<m. (d) The systemhasfull row and column rank(i.e., is invertible): n = r = m. | MIT OpenCourseWare |
| 3 | Gram-Schmidt Orthogonalization | Problem Set 6 Section 4.4, Problem 18 Find orthonormal vectors A, B, C by Gram-Schmidt from a=(1,−1,0,0), b=(0,1,−1,0), c=(0,0,1,−1). Show {A,B,C} is a basis for vectors perpendicular to d=(1,1,1,1). | A=(1/√2)(1,−1,0,0), B=(1/√6)(1,1,−2,0), C=(1/2√3)(1,1,1,−3). All three are perpendicular to d and span the 3-dimensional subspace. | MIT OpenCourseWare |
| 4 | Matrix Exponential and Diagonalization | Problem Set 8 Section 6.3, Problem 24 Write A=[[1,3],[0,0]] as SΛS⁻¹. Find matrix exponential eᴬᵗ by multiplying SeΛᵗS⁻¹. Verify eᴬᵗ and its derivative at t=0 | Λ=[[1,0],[0,3]], S=[[-1/2,1/2],[0,1]]. eᴬᵗ=[[eᵗ, (3e³ᵗ−eᵗ)/2],[0,e³ᵗ]]. At t=0 gives I; derivative at t=0 gives A. | MIT OpenCourseWare |
| 5 | Jordan Form and Matrix Similarity | Problem Set 10 Section 6.6, Problem 12 Compare JM with MK for Jordan matrices J and K. If JM=MK show M is not invertible, proving J is not similar to K | Setting JM=MK forces specific entries of M to zero making the second row or fourth row dependent, so M is always singular and J cannot be similar to K. | MIT OpenCourseWare |
| 6 | Singular Value Decomposition | Problem Set 10 Section 6.7, Problem 4 Find eigenvalues and unit eigenvectors of AᵀA and AAᵀ for Fibonacci matrix A=[[1,1],[1,0]]. Construct the full SVD and verify A=UΣVᵀ. | Eigenvalues (3±√5)/2. Singular values σ=(1±√5)/2. Full SVD constructed from these eigenvectors and verified. | MIT OpenCourseWare |
| 7 | Positive Definite Matrices | Problem Set 9 Section 6.5, Problem 33 When A and B are symmetric positive definite, AB might not be symmetric. Prove its eigenvalues are still positive by starting from ABx=λx and taking dot products with Bx. | ABx)ᵀBx=(Bx)ᵀA(Bx)=λxᵀBx. Since B positive definite xᵀBx>0 and A positive definite means (Bx)ᵀA(Bx)>0, so λ>0. | MIT OpenCourseWare |
| 8 | Jordan Form and Nilpotent Matrices | Problem Set 10 Section 6.6, Problem 22 If an n×n matrix A has all eigenvalues λ=0, prove that Aⁿ is the zero matrix. | Each Jordan block Jᵢ of size nᵢ satisfies Jᵢⁿⁱ=0 since there is no diagonal nᵢ diagonals above the main diagonal. Since all blocks satisfy Jᵢⁿ=0 and Aⁿ is similar to a block diagonal matrix with these blocks, Aⁿ=0. Alternatively by Cayley-Hamilton: all eigenvalues zero means characteristic polynomial is xⁿ so Aⁿ=0. | MIT OpenCourseWare |
