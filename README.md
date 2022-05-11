### Incorporate all stats from A levels and Uni + ask masters stats people for their notes and make a full 0 to hero stats course. Spick and spam, with all the questions, exercises and every thing fully + beautifully explained.

# Statistics For Business

This repository contains a full course on the statistics that are used in a business environment. Before we get busy with the codes, understanding the fundamentals is crucial when performing analytics and interpreting results. The good news is however, the course is produced in a way that someone who has never studied statistics can learn from the course and make it to the end successfully. We begin by looking at the course structure so the course is easy to navigate, incase you are required to only learn or revise a certain topic.

I hope you enjoy this course just as much as I have enjoyed making it and teaching it to colleagues and students just like you.

## Course Structure

- Section 1: Distributions
  - Continuous Vs Discrete data. 
  - What is a distribution?
  - Mean, Median, Mode.
  - Standard Deviation.
  - Normal Distribution.
  - Skewness.
  
- Section 2: Central Limit Theorem
  - Populations and Samples.
  - Sampling Distributions
  - Central Limit Theorem.
  - Z-Score

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

<p align="center"> <img width="1500" src= "/Pics_S/s101.png"> </p>

### What Is A Distribution

**Distribution:** In probability theory and statistics, a probability distribution is the mathematical function that gives the probabilities of occurrence of different possible outcomes for an experiment. It is a mathematical description of a random phenomenon in terms of its sample space and the probabilities of events (subsets of the sample space).

For instance, if X is used to denote the outcome of a coin toss ("the experiment"), then the probability distribution of X would take the value 0.5 (1 in 2 or 1/2) for X = heads, and 0.5 for X = tails (assuming that the coin is fair). Therefore, the probability of getting a head (or tail) on the next toss is 0.5 (1/2 or 50%). [4]

If we had a group of people and their ages, a probability distirbution will give us the probability of selecting a person at random of a given age. For example, what is the probability of the next person being 36 years old? A probability distribution will allow us to answer such quesions.

The diagram below shows us a discrete distribution and a continuous distribution: [5]

<p align="center"> <img width="1500" src= "/Pics_S/s2.jpg"> </p>

**Note:** For continuous distributions, the probability is found as an area under the curve. The total area under the curve is 100%, and we are unable to find the probability of a single line as the area of a line is negligable.

### Mean, Median and Mode

**Mean:** The "mean" is the "average". To find the mean, we must add up all the numbers and divide by the total number of numbers that exist. 

**Median:** The "median" is the middle value in our dataset. To find the median, we must first order our dataset in numerical order, and then find the middle number. If the number of values we have is even, we take the average of the two values that are in the middle.

**Mode:** The "mode" is the value that occurs most often. If there is no repeated number in our dataset, then the mode does not exist.

The formulas for mean, median, mode, variance and standard deviation are given in the table below: [11]

<p align="center"> <img width="400" src= "/Pics_S/F1.png"> </p>

We will revisit the mean, median and mode in the following topics which will make our understanding clearer by observing diagrams and examples.

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

### Normal Distribution

In statistics, a Normal Distribution (also known as Gaussian, Gauss, bell curves or Laplace–Gauss distribution) is a type of continuous probability distribution for a real-valued random variable [8]. In a Normal Distribution, data is symmetrically distributed with no skew. When plotted on a graph, the data follows a bell shape, with most values clustering around a central region and tapering off as they go further away from the center. [9]

The diagram below gives the Normal Distribution curve

<p align="center"> <img width="1500" src= "/Pics_S/ND.png"> </p>

From the above, we observe that 68.2% of the population lies within one standard deviation (± 1σ), 95.4% of the population lies within two standard deviations (± 2σ), and 99.6% of the population lies within three standard deviations (± 3σ).

The general form of probability density function is 

<p align="center"> <img width="750" src= "/Pics_S/NDPDF.png"> </p>

Properties of the Normal Distributions:

- The mean, median and mode are exactly the same.
- The distribution is symmetric about the mean—half the values fall below the mean and half above the mean.
- The distribution can be described by two values: the mean and the standard deviation.

The below diagrams show the Normal Distribution with different means, the Normal Distribution with different standard deviations, and the Normal Distribution with different means and standard deviations: [9]

<p align="center"> <img width="500" src= "/Pics_S/NDM.png"> </p>

<p align="center"> <img width="500" src= "/Pics_S/NDSD.png"> </p>

<p align="center"> <img width="500" src= "/Pics_S/NDMSD.png"> </p>

### Skewness

**Skewness:** Skewness is a measure of the asymmetry of the probability distribution of a real-valued random variable about its mean. The skewness value can be positive, zero, negative, or undefined. For a unimodal distribution, negative skew commonly indicates that the tail is on the left side of the distribution, and positive skew indicates that the tail is on the right. [10]

The below diagram illustrates positive, symmetrical and negative skewness respectively. [10]

<p align="center"> <img width="1000" src= "/Pics_S/SKEW.png"> </p>

### Exercise: The Clothing Store

We are in the new product development team that develops clothing styles for our company depending on company priorities and industry trends. The company has decided to develop a seperate clothing line called "Big and Tall", where we cater for those who are extremely tall. We have been asked by management to illustrate its viability using visuals, as a short statistical analysis.

We have the following information available to us:

- Mens heights have an average of 69.1 inches (175.5 cm) and a standard deviation of 2.9 inches (7.4 cm).
- Womens heights have an average of 63.7 inches (161.8 cm) and a standard deviation of 2.7 inches (6.9 cm).

Here is what's required:

- A normal distribution of 1000 observations for heights of men in the US to generate a distribution.
- A normal distribution of 1000 observations for heights of women in the US to generate a distribution.
- Identify the minimum height of the 2.2% of the tallest people in our population.

To perfrom this short analysis, we will be using the NORM.INV function in Excel.

**Note:** I have used Google sheets for this exercise as Google sheets are available to everyone, free of charge but you can use Microsoft Excel too if you prefer.

We will use the NORM.INV() function combined with RAND() in Excel. The standard form looks like:

```
Round(NORM.INV(RAND(),μ,σ,1))

Where: μ is the population mean
       σ is the standard deviation
```

In the spreadsheet attached, we will be using the below formulas to generate 1000 observations from our normal distribution:

```
- NORM.INV(RAND(), 69.1, 2.9)
- NORM.INV(RAND(), 63.7, 2.7)
```

From the normal distribution diagram above, we observe that the top 2.2% lies after the 2nd standard deviation. Therefore, in order to identify the minimum height, we simply need to perform the below calculation:

```
Minimum height of top 2.2% of men = 69.1 + 2*(2.9) = 74.9 inches
Minimum height of top 2.2% of women = 63.7 + 2*(2.7) = 69.1 inches
```

# Section 2: Central Limit Theorem

We will first discuss the difference between a population and a sample. Below is a diagram that illustrates this: [13]

<p align="center"> <img width="750" src= "/Pics_S/sample.png"> </p>

**Population:** A population is the entire group that we wish to draw conclusions about. [12]

The population has parameters (**N**,**μ**,**σ**)

where: 

- **N** is the population size
- **μ** is the population mean
- **σ** is the standard deviation
       
**Sample:** A sample is the specific group that we will collect data from. The size of the sample is always less than the total size of the population, as it is a subset of the population. [12]

The sample has parameters (**n**,**xˉ**,**s**)

where:

- **n** is the sample size
- **xˉ** (x bar) is the sample mean
- **s** is the sample standard deviation



# References

[1](https://www.mathsisfun.com/data/data-discrete-continuous.html). Maths Is Fun: Discrete and Continuous Data.

[2](https://www.bbc.co.uk/bitesize/guides/zvybkqt/revision/5). Bitesize: Collecting and recording data

[3](https://www.g2.com/articles/discrete-vs-continuous-data). G2: Discrete vs Continuous Data – What’s the Difference?

[4](https://en.wikipedia.org/wiki/Probability_distribution). Wikipedia: Probability Distribution

[5](https://twitter.com/statsatoz/status/964159304067633153?lang=zh-Hant). Twitter post: @statsatoz – Statistics A-Z

[6](https://en.wikipedia.org/wiki/Standard_deviation). Wikipedia: Standard Deviation

[7](https://www.investopedia.com/terms/v/variance.asp#:~:text=In%20statistics%2C%20variance%20measures%20variability,values%20in%20the%20data%20set.). Investopedia: Variance

[8](https://en.wikipedia.org/wiki/Normal_distribution). Wikipedia: Normal distribution

[9](https://www.scribbr.com/statistics/normal-distribution/#:~:text=Height%2C%20birth%20weight%2C%20reading%20ability,designed%20for%20normally%20distributed%20populations.). Scribbr: Normal Distribution | Examples, Formulas, & Uses

[10](https://en.wikipedia.org/wiki/Skewness). Wikipedia: Skewness

[11](https://www.cuemath.com/basic-statistics-formula/). CUEMATH: Basic Statistics Formula

[12](https://www.scribbr.com/methodology/population-vs-sample/#:~:text=A%20population%20is%20the%20entire,t%20always%20refer%20to%20people.). Scribbr: Population vs. Sample | Definitions, Differences & Examples

[13](https://www.omniconvert.com/what-is/sample-size/). Omniconvert:What is ... Sample size
