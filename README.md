📊 Simulation of Statistical Distributions
This repository contains simulation scripts and examples for various statistical distributions. The simulations are implemented in [R/Python], and each script explores the properties, visualization, and summary statistics of the respective distribution.

📁 Structure
Each directory or file focuses on a specific distribution. The general structure includes:

Theoretical properties

Random simulation

Plots (Histogram, Density, QQ plot)

Moments (Mean, Variance, Skewness, Kurtosis)

Applications or scenarios where the distribution is used

🧮 Distributions Covered
🔹 1. Normal Distribution
Symmetric, bell-shaped

Parameters: Mean (μ), Standard Deviation (σ)

Used in CLT, measurement errors, natural phenomena

Python: np.random.normal(loc, scale, size)

🔹 2. Bernoulli Distribution
Binary outcome (0/1)

Parameter: Probability of success (p)

Use: Modeling binary outcomes like yes/no, success/failure

Python: np.random.binomial(1, p, n)

🔹 3. Binomial Distribution
Number of successes in fixed n independent Bernoulli trials

Parameters: n, p

Python: np.random.binomial(n, p, size)

🔹 4. Poisson Distribution
Count of events in fixed interval (time/space)

Parameter: λ (rate)

Python: np.random.poisson(lam, size)

🔹 5. Exponential Distribution
Time between events in a Poisson process

Parameter: λ (rate)

Memoryless property

Python: np.random.exponential(scale=1/lambda, size)

🔹 6. Uniform Distribution
Equal probability across interval [a, b]

Continuous or discrete

Python: np.random.uniform(low=a, high=b, size=n)

🔹 7. Gamma Distribution
Generalization of Exponential, often used for waiting times

Parameters: shape (k), rate (λ)

Python: np.random.gamma(shape, scale=1/rate, size)

🔹 8. Beta Distribution
Continuous distribution on [0, 1]

Parameters: α, β

Common in Bayesian inference

Python: np.random.beta(a, b, size)

🔹 9. Chi-Square Distribution
Special case of Gamma (shape = df/2, rate = 1/2)

Used in hypothesis testing and confidence intervals

Python: np.random.chisquare(df, size)

🔹 10. t-Distribution
Heavy-tailed alternative to Normal

Parameter: degrees of freedom (df)

Python: np.random.standard_t(df, size)

📊 Visualization
All distributions are visualized with:

Histograms

Kernel Density Estimation (KDE)

QQ plots (for normality assessment)

Empirical vs. Theoretical comparison

📈 Moment Calculation
Each script calculates:

Mean

Variance

Skewness

Kurtosis

Comparison with theoretical values

🧪 Simulations
Simulations help understand:

Law of Large Numbers (LLN)

Central Limit Theorem (CLT)

Convergence properties

Tail behavior

