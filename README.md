# The Power of Plots

## Summary (with links to my code and results)

What good is data without a good plot to visually sum up the story?

Use Python (Pandas) and Matplotlib to analyze real-world situations and create scatter plots and a bar graph to visualize a [comparison](Images/drug_efficacy_comparison.png) and [results](Images/tumor_metastatic_survival_plots.png) of this clinical study.  At the end of your [code](pymaceuticals.ipynb) (snippet below) include a written description of three observable trends based on the data analysis.

![Code Snippet](Images/SEM.png)

## Pymaceuticals Inc 

![Laboratory](Images/Laboratory.jpg)

While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've since joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, CA. Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. In their most recent efforts, they've since begun screening for potential treatments to squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As their Chief Data Analyst, you've been given access to the complete data from their most recent animal study. In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. Your objective is to analyze the data to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

To do this you are tasked with:

* Creating a scatter plot that shows how the tumor volume changes over time for each treatment.
* Creating a scatter plot that shows how the number of [metastatic](https://en.wikipedia.org/wiki/Metastasis) (cancer spreading) sites changes over time for each treatment.
* Creating a scatter plot that shows the number of mice still alive through the course of treatment (Survival Rate)
* Creating a bar graph that compares the total % tumor volume change for each drug across the full 45 days.

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must use the Matplotlib library.
* You must include a written description of three observable trends based on the data.
* You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, X and Y Axis Limits, etc.
* Your scatter plots should include [error bars](https://en.wikipedia.org/wiki/Error_bar) to allow the company to account for variability between mice. You may want to look into [`pandas.DataFrame.sem`](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.sem.html) for ideas on how to calculate this.
* Remember when making your plots, certain aesthetics aid in clearly communicating the information!
  * Your legends should not be overlaid on top of any data.
  * Your bar graph should indicate tumor growth as red and tumor reduction as green.
    It should also include a label with the percentage change for each bar. You may want to consult this [tutorial](http://composition.al/blog/2015/11/29/a-better-way-to-add-labels-to-bar-charts-with-matplotlib/) for relevant code snippets.

## Hints and Considerations

* Be warned: this is very challenging. Be patient with yourself as you trudge through these tasks. They will take time and there is no shame in fumbling along the way. Data visualization is equal parts exploration, equal parts resolution. This task _will_ require you to refer to documentation and Stack Overflow for hacked solutions to problems you'll experience along the way.