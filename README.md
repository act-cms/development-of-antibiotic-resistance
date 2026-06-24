Development of antibiotic resistance
===================

This module uses Python to get students to understand how mutations occur. 
It models both spontaneous and selection-dependent mutations and compares them to the historic experiments from [Luria and Delbrück](https://pubmed.ncbi.nlm.nih.gov/17247100/).
Students directly compare the two models and use them to explain the experimental results. This module is based on Chapter 1 of the [Quantitative Biosciences textbook](https://press.princeton.edu/books/paperback/9780691181516/quantitative-biosciences?srsltid=AfmBOorplxUR0YGsrXwPBzlCj40s24hxJBXU1ei6syqPu4AZ9OgwOEDR) by Joshua S Weitz. 

The module was written for an undergraduate sophomore-junior level Genetic Analysis course, but can be used in other courses, such as Advanced Genetics, Microbiology, Microbial Genetics, and Bioinformatics

## Lesson Learning Outcomes
At the end of this lesson, students will be able to...
1. Use Python to simulate stochastic biological processes and analyze experimental data.
2. Apply probability distributions and computational models to investigate the origins of antibiotic resistance in bacterial populations.
3. Evaluate competing scientific hypotheses by comparing model predictions with experimental observations.
4. Estimate biological parameters from data and interpret uncertainty in model-based inferences.
5. Explain how mutation timing and natural selection interact to shape evolutionary outcomes in microbial populations.

## Cyberinfrastructure skills
Before beginning this lesson, students are expected to have basic Python and Jupyter Notebook skills and/or have completed the following module available on the ACT-CMS Portal: 

- [Introduction to Programming for Molecular Scientists](https://act-cms.molssi.org/portal/lessons/foundational-intro-python/)

## Content prerequisites
Before beginning this lesson, students are expected to be familiar with the following topics: 
- Mutation basics
- Effects of mutations on organismal fitness
- Statistical concepts, including probability, probability distributions, sampling distributions, and confidence intervals.

## Resources
The following resources may be relevant to the students and can be assigned as homework prior to class: 
- [MolSSI Workshop: Python Scripting for Computational Molecular Sciences](https://education.molssi.org/python_scripting_cms/)
- [Probability](https://online.stat.psu.edu/stat500/Lesson02)
- [Probability Distributions](https://online.stat.psu.edu/stat500/Lesson03)
- [Sampling Distributions](https://online.stat.psu.edu/stat500/Lesson04)
- [Confidence Intervals](https://online.stat.psu.edu/stat500/Lesson05)

## Lesson/Module Contents

Lesson overview:

1. Introduction to distributions
    * Directory: `01_Introduction-to-distributions`
    * Description: This lesson introduces the concepts of spontaneous and acquired mutations and generates datasets that fit different distributions (uniform, normal, binomial, and Poisson). 
    * Time: 1 hour
2. Simulation of the Luria-Delbrück experiment
    * Directory: `02_Simulation-of-Luria-Delbrück-experiment`
    * Description: This lesson provides the results of the LD experiment and models a culture of bacteria containing both mutant and wild-type genotypes.
    * Time: 0.5 hours
3. Selection-dependent mutations
    * Directory: `03_Selection-dependent-mutation-model`
    * Description: This lesson explains the distribution of mutants assuming a Lamarckian ('acquired' or selection-dependent) model for the appearance of mutations. It then provides an estimate for the lambda value of the Poisson distribution as well as its confidence intervals.
    * Time: 1.5 hours
4. Modeling the growth of mutants
    * Directory: `04_Modeling-the-growth-of-mutants`
    * Description: In this lesson, students write a program to simulate multiple cultures of bacteria (similar to the Luria-Delbrück experiment) over one generation. 
    * Time: 1 hours
5. Spontaneous mutations
    * Directory: `05_Spontaneous-mutations`
    * Description: This lesson explains the distribution of mutants assuming Darwinian (spontaneous) model for the appearance of mutations. The lesson is fully theoretical, meaning that students do not need to code. 
    * Time: 0.5 hours
6. From observations to estimates
    * Directory: `06_From-observations-to-estimates`
    * Description: Students will leverage the coding skills they have acquired in prior lessons to estimate the mutation rate using either the probability of zero or the mean as a proxy. They will then simulate a bacterial culture and perform a 'grid search' of values to obtain the best estimate for the mutation rate.
    * Time: 1 hour
7. Timing of mutation appearance
    * Directory: `07_Timing-of-mutation-appearance`
    * Description: The lesson puts together all prior work to get students to simulate the time of mutation appearance and the time of selection. Students then compare the variance produced by the Lamarckian and the Darwinian models and compare them to the experimental results from Luria and Delbrück. 
    * Time: 1 hour


## References

[Weitz, Joshua S. Quantitative Biosciences : Dynamics across Cells, Organisms, and Populations. First edition., Princeton University Press, 2024](https://press.princeton.edu/books/hardcover/9780691181509/quantitative-biosciences)



