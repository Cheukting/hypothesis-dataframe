# Using Pandas stratgies in Hypothesis

Do you test your data pipeline? Do you use Hypothesis? In this workshop, we will use Hypothesis - a property-based testing framework to generate Pandas DataFrame for your tests, without involving any real data.

In this workshop, we will first go through the basics of hypothesis and what is property-based testing. After that, we will introduce the strategies for Pandas objects - available via the extras in Hypothesis. We will have a glimpse of what the strategies are doing to generate the testing object, including Pandas Series and DataFrames. In the end, we will apply what we learn in real testing applications - testing a data pipeline that involves DataFrames.

---

## Installation

[Creating a new enviroment](https://docs.python.org/3/library/venv.html) is highly recommended. Recommended version of Python is 3.11. Install all the requirements at [requirements.txt](requirements.txt)

## Outline

1. [Introduction and basic use of Hypothesis exercises](01_Hypothesis_basics.ipynb)
2. [Deep dive into Pandas strategies](02_Hypotheses_with_pandas.ipynb)
3. [Do it yourself - apply property-based testing to data pipelines](03_final_project.ipynb)

## Prerequisits

No prior knowledge of property-based testing or hypothesis is required. However, we assume the attendee has experience using Pandas and has a basic understanding of Pandas objects. Knowledge about Numpy array and typing would also be beneficial in understanding the Pandas Strategies.

## Goal

We hope the attendee will learn about property-based testing and see how it can benefit their work involved data - especially those that use Pandas. After the workshop, attendees should be able to understand how the Pandas strategies in Hypothesis works and to use Hypotheses to test codes that involve Pandas Series or DataFrame input.