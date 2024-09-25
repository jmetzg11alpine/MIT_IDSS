# Statistics for Data Science

# Inference 
Summaries about the population from a sample of the data

# Probability Distribution
Describes the values that a random variable can take, along with the probabilities of those values. Discrete (probability mass function) and Continuous (probability density function) random variables. 

Bernoulli distribution (trails = 1) - binary distribution (many Bernoulli trails, number of success on the x-axis and probability on the y-axis)

binary distribution = PMF probability mass function, CDF cumulative distribution function

uniform distribution - discrete uniform distribution like a dice, continuous uniform distribution like temperature (where there is a min and max)

# Normal Distribution
The μ and the standard deviation is σ. - population parameters
x̄ and s - sample populaiton

68%/95%/99% = 1, 2 3 stds, μ ± σ, μ ± 2σ, μ ± 3σ

Standard nomral: μ=0, σ=1  

Z = (X−μ) / σ, gives you the Z score

Z score describes how many standard deviations a sample is from the mean


# Sampling Distribution 
Simple Random Sampling - each individual has equal chance of being selected 

Controlled Random Sampling - there are subgroups or strata

the mean of x̄ = μ

the Standard Error = σ / √n (The standard error of x̄), tells how accurately it reflects the true population mean. The true mean will vary by the SE. 

SE is the varitity of the sample mean if we were to take more samples

# Central Limit Theorem
The sampling distribution of the sample means will approach normal distribution as the sample size gets bigger, no matter what the shape of the population distribution is.

Sample size > 30 

all samples come from same distribution, random and not correlated

# Estimation 
info from the sample can use to make inference about a population parameter, 

point estimation a single point

interval estimage with a confidence interval

Point estimation doesn't take into account the distribution, t distibution when the population distribution is not know

# Hypothesis Testing 

Type 1 error - When we reject the null hypothesis when it is actually true.

Type 2 error - When we fail to reject the null hypothesis when it is actually false.

Level of Significance (type 1 error)= probability of reject the null hypothesis when it is true, fixed before hypothesis test. Does not change

Z = (x̄ - μ) / σ/√n

p-value = probability of seeing these results from the sample data, likelihood of the H0 being True. Changes with the data

Acceptance or Rejection Region = area under the curve 

One-tail = rejection on one side. Ha: μ > 20

Two-tailed = the parameter is not equal. Ha μ != 20