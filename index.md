# A Framework to Evaluate the Quality of Differentially Private Synthetic Data

Recent advances in generating synthetic data that allow to add principled ways of protecting privacy – such as Differential Privacy – are a crucial step in sharing statistical information in a privacy preserving way. But while the focus has been on privacy guarantees, the resulting private synthetic data is only useful if it still carries statistical information from the original data. To further optimise the inherent trade-off between data privacy and data quality, it is necessary to think closely about the latter. What is it that data analysts want? Acknowledging that data quality is a subjective concept, we develop a framework to evaluate the quality of differentially private synthetic data from an applied researcher’s perspective. Data quality can be measured along two dimensions. First, quality of synthetic data can be evaluated against training data or against an underlying population. Second, the quality of synthetic data depends on general similarity of distributions or specific tasks such as inference or prediction. It is clear that accommodating all goals at once is a formidable challenge.
We invite the academic community to jointly advance the privacy-quality frontier.

You can find our working paper [here](https://arxiv.org/pdf/2004.07740.pdf).

# Assessing the Utility of Synthetic Data

Building on scenarios that describe applied researchers’ main data related obstacles, we suggest two different ’disciplines’ in which a differentially private data synthesizer should perform well: **resulting synthetic data needs to be useful at different levels of privacy guarantees** and also at **different training set sizes**. On this homepage we plan to keep track of the performance of differentially private data synthesizers.

The code for the utility suite is work in progress and we will include this on this page as soon as possible.

# About Us

*   [Christian Arnold](http://christianarnold.org)
*   [Marcel Neunhoeffer](http://marcel-neunhoeffer.com)
