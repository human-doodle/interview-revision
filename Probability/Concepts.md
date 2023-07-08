## Markov Chain:
A Markov chain is a mathematical concept used to study systems that change over time. It involves a sequence of events or states where the probability of transitioning from one state to another depends only on the current state and not on the history of how you got there.

Markov chains have a wide range of applications in various fields. Here are a few examples:

1. Natural Language Processing: Markov chains are used in language modeling and text generation tasks. They can be used to predict the next word in a sentence based on the current word or to generate new sentences that resemble a given text. For instance, auto-complete suggestions on your smartphone or computer often utilize Markov chains.
2. Finance and Economics: Markov chains are employed in analyzing financial markets and economic models. They can help predict stock prices, market trends, and economic indicators. By modeling the behavior of market conditions, investors and economists can make informed decisions about investments and economic policies.
3. Simulation and Modeling: Markov chains are useful in simulating and modeling various systems. They can simulate complex systems by representing different states and the probabilities of transitioning between those states. For example, they can be used to model the movement of particles, the spread of diseases, or the behavior of customers in a queue.
4. Machine Learning: Hidden Markov Models (HMMs), a type of Markov chain, are used in speech recognition, gesture recognition, and other pattern recognition tasks. HMMs are particularly useful when the underlying process or sequence of events is not directly observable, but only the resulting outputs or observations are available.
5. Web Ranking Algorithms: Markov chains are utilized in web ranking algorithms like Google's PageRank. In these algorithms, web pages are treated as states, and the transitions between pages are based on links. By analyzing the structure of the web and the probabilities of transitions, these algorithms determine the importance and relevance of web pages.

So,  Markov chains are a way to understand and predict how things change over time. Imagine you have a system that can be in different states, like a weather system with states such as sunny, cloudy, or rainy.

A Markov chain helps us figure out the probability of moving from one state to another. For example, if it's sunny today, there might be a 70% chance it will be sunny tomorrow, a 20% chance it will be cloudy, and a 10% chance it will be rainy.


## Law of Large Numbers:

The Law of Large Numbers is a fundamental principle in probability theory and statistics. It states that as the number of independent, identically distributed (i.i.d.) random variables increases, the sample average or arithmetic mean of these variables will converge to the expected value or population mean.

In simpler terms, the Law of Large Numbers tells us that if we repeatedly perform an experiment with a random outcome and calculate the average of the observed values, this average will approach the expected or true average of the underlying distribution as the number of trials increases.

The Law of Large Numbers is based on the assumption of independence and identical distribution of the random variables. This means that each random variable is unrelated to the others and follows the same probability distribution.

The Law of Large Numbers is a fundamental concept in statistics and has significant implications for data analysis and inference. It allows us to make reliable conclusions about population parameters based on observed sample averages. The larger the sample size, the more confidence we have in the sample mean being a good estimate of the population mean.

It's important to note that the Law of Large Numbers does not imply that individual observations will necessarily be close to the population mean. It is concerned with the behavior of the average over a large number of observations.

Example:
Let's consider flipping a fair coin. Each time we flip the coin, we have a 50% chance of getting a head (H) and a 50% chance of getting a tail (T). Our goal is to estimate the true probability of getting a head.

Suppose we start flipping the coin and record the outcomes: H, T, H, H, T. If we calculate the average of these outcomes, we get (1+0+1+1+0)/5 = 0.6.

Now, let's increase the number of coin flips to 50. We flip the coin 50 times and record the outcomes: H, H, T, T, H, T, H, H, T, ..., resulting in a series of heads and tails. The average of these outcomes may be different, such as 0.52.

If we continue this process and flip the coin 500 times, 5,000 times, or even more, we will observe that the average of the outcomes tends to get closer to the true probability of 0.5, which is the expected value for a fair coin. This demonstrates the Law of Large Numbers in action.

As the number of coin flips (trials) increases, the average of the observed outcomes (proportion of heads) approaches the expected value or true probability of 0.5. This convergence happens with increasing probability as the number of trials gets larger.

The Law of Large Numbers assures us that with a sufficiently large number of trials, our estimate of the true probability becomes more accurate and reliable.

It's important to note that in practice, due to randomness, there may be fluctuations and the observed average may not exactly equal the expected value. However, as the number of trials increases, the average will tend to be closer to the expected value.



## Central Limit Theorem:

awesome video: https://www.youtube.com/watch?v=zeJD6dqJ5lo

It states that when we take many random samples from a population, the distribution of the sample means or sums tends to follow a bell-shaped curve, known as a normal distribution, even if the individual observations themselves don't have a normal distribution.

Formally, the Central Limit Theorem (CLT) can be defined as follows:

Let X1, X2, X3, ... be a sequence of independent and identically distributed (i.i.d.) random variables with a common distribution having a finite mean μ and a finite variance σ^2. Let S_n = X1 + X2 + ... + Xn represent the sum of the first n random variables, and let X̄_n = S_n / n represent the sample mean.

The Central Limit Theorem states that as n approaches infinity, the distribution of X̄_n approaches a normal distribution with mean μ and variance σ^2/n. In other words:

X̄_n ~ N(μ, σ^2/n)

This implies that regardless of the shape of the original distribution of the X_i random variables, as the sample size increases, the distribution of the sample mean becomes increasingly close to a normal distribution.

The Central Limit Theorem has several important implications in statistics:

a) Sampling Distributions: It explains why the sampling distribution of the mean tends to be approximately normal, even when the population distribution is not.

b) Confidence Intervals: It justifies the use of the normal distribution as an approximation when constructing confidence intervals for population parameters based on sample means.

c) Hypothesis Testing: It enables the use of parametric tests, such as the t-test, even when the population distribution is unknown or non-normal, as long as the sample size is large enough.







