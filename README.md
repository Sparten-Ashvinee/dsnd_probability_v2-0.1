Python library for statistics

Both Binomial and Gaussian (Normal) distributions are fundamental concepts in statistics and probability theory. They serve different purposes and are used to model different types of data.

The Binomial Distribution is a discrete probability distribution that models the number of successes in a fixed number of independent trials, each with the same probability of success.

Key Characteristics:
Discrete Distribution: The Binomial distribution is discrete, meaning it deals with distinct or separate values (e.g., 0, 1, 2, ...).

Parameters:

𝑛
n: The number of trials.
𝑝
p: The probability of success on any given trial.
Probability Mass Function (PMF): The probability of getting exactly 
𝑘
k successes in 
𝑛
n independent trials is given by:

𝑃
(
𝑋
=
𝑘
)
=
(
𝑛
𝑘
)
𝑝
𝑘
(
1
−
𝑝
)
𝑛
−
𝑘
P(X=k)=( 
k
n
​
 )p 
k
 (1−p) 
n−k
 
where:

(
𝑛
𝑘
)
=
𝑛
!
𝑘
!
(
𝑛
−
𝑘
)
!
( 
k
n
​
 )= 
k!(n−k)!
n!
​
  is the binomial coefficient.
𝑋
X is a random variable representing the number of successes.
Mean and Variance:

Mean: 
𝜇
=
𝑛
𝑝
μ=np
Variance: 
𝜎
2
=
𝑛
𝑝
(
1
−
𝑝
)
σ 
2
 =np(1−p)
