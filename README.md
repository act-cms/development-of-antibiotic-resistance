Lesson/Module Title
===================

This module uses Python to get students to understand how mutations occur. 
It models both spontaneous and selection-dependent mutations and compares them to the historic experiments from [Luria and Delbruck] (https://pubmed.ncbi.nlm.nih.gov/17247100/).
Students directly compare the two models and use them to explain the experimental results. This module is based on Chapter 1 of the [Quantitative Biosciences textbook](https://press.princeton.edu/books/paperback/9780691181516/quantitative-biosciences?srsltid=AfmBOorplxUR0YGsrXwPBzlCj40s24hxJBXU1ei6syqPu4AZ9OgwOEDR) by Joshua Weitz. 

The module was written for an undergraduate sophomore-junior level Genetic Analysis course, but can be used in other courses, such as Advanced Genetics, Microbiology, Microbial Genetics, and Bioinformatics

## Lesson/Module Contents

Provide a brief overview of the structure of your module or lesson as an
enumerated list below:

1. Introduction to distributions
    * Directory: `01_Introduction-to-distributions`
    * Description: This lesson introduces the concepts of spontaneous and acquired mutations and generates datasets that fit different distributions (uniform, normal, binomial, and Poisson). 
    * Time: 1 hour
2. Simulation of the Luria-Delbruck experiment
    * Directory: `02_Simulation-of-Luria-Delbruck-experiment`
    * Description: This lesson provides the results of the LD experiment and models a culture of bacteria containing both mutant and wild-type genotypes.
    * Time: 0.5 hours
3. Selection-dependent mutations
    * Directory: `03_Selection-dependent-mutation-model`
    * Description: This lesson explains the distribution of mutants assuming a Lamarckian ('acquired' or selection-dependent) model for the appearance of mutations. It then provides an estimate for the lambda value of the Poisson distribution as well as its confidence intervals.
    * Time: 1.5 hours
4. Modeling the growth of mutants
    * Directory: `04_Modeling-the-growth-of-mutants`
    * Description: In this lesson, students write a program to simulate multiple cultures of bacteria (similar to the Luria-Delbruck experiment) over one generation. 
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
    * Description: The lesson puts together all prior work to get students to simulate the time of mutation appearance and the time of selection. Students then compare the variance produced by the Lamarckian and the Darwinian models and compare them to the experimental results from Luria and Delbruck. 
    * Time: 1 hour




