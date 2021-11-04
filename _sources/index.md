# Recommenders

````{margin}
```sh
pip install recommenders
```
<a class="github-button" href="https://github.com/microsoft/genalog" data-icon="octicon-star" style="margin:auto" data-size="large" data-show-count="false" aria-label="Star us microsoft/genalog on GitHub">Star Us</a><script async defer src="https://buttons.github.io/buttons.js"></script>
````
This repository contains examples and best practices for building recommendation systems, provided as Jupyter notebooks. The examples detail our learnings on five key tasks:

- [Prepare Data](examples/01_prepare_data): Preparing and loading data for each recommender algorithm
- [Model](examples/00_quick_start): Building models using various classical and deep learning recommender algorithms such as Alternating Least Squares ([ALS](https://spark.apache.org/docs/latest/api/python/_modules/pyspark/ml/recommendation.html#ALS)) or eXtreme Deep Factorization Machines ([xDeepFM](https://arxiv.org/abs/1803.05170)).
- [Evaluate](examples/03_evaluate): Evaluating algorithms with offline metrics
- [Model Select and Optimize](examples/04_model_select_and_optimize): Tuning and optimizing hyperparameters for recommender models
- [Operationalize](examples/05_operationalize): Operationalizing models in a production environment on Azure

Several utilities are provided in [recommenders](recommenders) to support common tasks such as loading datasets in the format expected by different algorithms, evaluating model outputs, and splitting training/test data. Implementations of several state-of-the-art algorithms are included for self-study and customization in your own applications. See the [recommenders documentation](https://readthedocs.org/projects/microsoft-recommenders/).

For a more detailed overview of the repository, please see the documents on the [wiki page](https://github.com/microsoft/recommenders/wiki/Documents-and-Presentations).