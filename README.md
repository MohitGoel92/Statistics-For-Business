# Statistics For Business

This repository contains a full course on the statistics that are used in a business environment. Before we get busy with the codes, understanding the fundamentals is crucial when performing analytics and interpreting results. The good news is however, the course is produced in a way that someone who has never studied statistics can learn from the course and make it to the end successfully. We begin by looking at the course structure so the course is easy to navigate, incase you are required to only learn or revise a certain topic.

I hope you enjoy this course just as much as I have enjoyed making it and teaching it to colleagues and students just like you.

## Course Structure

- Section 1: Distributions
  - Continuous Vs Discrete data. 
  - What is a distribution?
  - Standard Deviation.
  - Normal Distribution.
  - Skewness.
  - Mean, Median, Mode.
  - Correlation

- Section 2: Central Limit Theorem
- Section 3: Hypothesis Testing and Statistical Significance

# Section 1: Distribution

In this section, we will be covering the below:

- Continuous Vs Discrete date.
- What is a distribution?
- Standard Deviation.
- Normal Distribution.
- Skewness.
- Mean, Median, Mode.

### Continuous Vs Discrete

**Continuous:** Continuous data is measured, or in other words, it is data that can take any value. Examples include time, height and weight. Because continuous data can take any value, there are an infinite number of possible outcomes. [1][2]

**Discrete:** Discrete data is counted. For example, the number of customers who bought different items, the number of computers in each department, and the number of items you buy at the grocery store each week. [1][3]

The diagram below visually depicts the difference between these two data types: [3]

<p align="center"> <img width="2000" src= "/Pics_S/s101.png"> </p>

### What Is A Distribution

**Distribution:** In probability theory and statistics, a probability distribution is the mathematical function that gives the probabilities of occurrence of different possible outcomes for an experiment. It is a mathematical description of a random phenomenon in terms of its sample space and the probabilities of events (subsets of the sample space).

For instance, if X is used to denote the outcome of a coin toss ("the experiment"), then the probability distribution of X would take the value 0.5 (1 in 2 or 1/2) for X = heads, and 0.5 for X = tails (assuming that the coin is fair). Therefore, the probability of getting a head (or tail) on the next toss is 0.5 (1/2 or 50%). [4]

If we had a group of people and their ages, a probability distirbution will give us the probability of selecting a person at random of a given age. For example, what is the probability of the next person being 36 years old? A probability distribution will allow us to answer such quesions.

The diagram below shows us a discrete distribution and a continuous distribution: [5]

<p align="center"> <img width="2000" src= "/Pics_S/s2.jpg"> </p>

**Note:** For continuous distributions, the probability is found as an area under the curve. The total area under the curve is 100%, and we are unable to find the probability of a single line as the area of a line is negligable.

### Standard Deviation

**Variance:** The term variance refers to a statistical measurement of the spread between numbers in a data set. More specifically, variance measures how far each number in the set is from the mean and thus from every other number in the set. Variance is often depicted by this symbol sigma squared: σ^2. The square root of the variance is the standard deviation. [7]

**Standard Deviation:** The standard deviation is a measure of the amount of variation or dispersion of a set of values. A low standard deviation indicates that the values tend to be close to the mean (also called the expected value) of the set, while a high standard deviation indicates that the values are spread out over a wider range. The standard deviation is often depicted by the symbol sigma: σ [6]

Example: Let's say we have data for a population, which includes the salaries of five people, they are: £60,000, £70,0000, £72,500, £85,000 and £93,000.

The average (or population mean, μ) is given by:

μ = (60000 + 70000 + 72500 + 85000 + 93000)/5 = £76,100

The variance (or population variance, σ^2) is given by:

σ^2 = ((60000-76100)^2 + (70000-76100)^2 + ... + (93000-76100)^2))/5 = 134,840,000

The standard deviation (or population standard deviation, σ) is given by:

σ = sqrt(variance) = sqrt(((60000-76100)^2 + (70000-76100)^2 + ... + (93000-76100)^2))/5) =  £11,612



# References

[1](https://www.mathsisfun.com/data/data-discrete-continuous.html). Maths Is Fun: Discrete and Continuous Data.

[2](https://www.bbc.co.uk/bitesize/guides/zvybkqt/revision/5). Bitesize: Collecting and recording data

[3](https://www.g2.com/articles/discrete-vs-continuous-data). G2: Discrete vs Continuous Data – What’s the Difference?

[4](https://en.wikipedia.org/wiki/Probability_distribution). Wikipedia: Probability Distribution

[5](https://twitter.com/statsatoz/status/964159304067633153?lang=zh-Hant). Twitter post: @statsatoz – Statistics A-Z

[6](https://en.wikipedia.org/wiki/Standard_deviation). Wikipedia: Standard Deviation

[7] (https://www.investopedia.com/terms/v/variance.asp#:~:text=In%20statistics%2C%20variance%20measures%20variability,values%20in%20the%20data%20set.). Investopedia: Variance
