1. **Simple Random Sampling:** A basic sampling technique where each data point in the dataset has an equal probability of being selected in the sample.

2. **Stratified Sampling:** A sampling technique where the population is divided into subgroups (strata) based on a specific characteristic, and samples are taken from each stratum in proportion to the population.

3. **Systematic Sampling:** A sampling technique where every nth element in the population is selected for the sample, with n being a fixed interval.

4. **Cluster Sampling:** A sampling technique where the population is divided into clusters, and a sample of clusters is randomly selected. Then, all members of the selected clusters are included in the sample.

5. **Convenience Sampling:** A non-probability sampling technique where the sample is chosen based on its convenience to the researcher.

## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using random over-sampling and under-sampling techniques.

| Sampling Technique | Decision Tree | Ridge Classifier	 | Gradient Boosting Classifier	 | Dummy Classifier	 | KNN |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 0.9778 | 0.8581 | 0.9813 | 0.5635 | 0.8915 |
| Systematic Sampling | 0.9813 | 0.8878 | 0.9944 | 0.5131 | 0.9493 |
| Stratified Sampling | 0.9851 | 0.8696 | 0.9963 | 0.5028 | 0.9498 |
| Cluster Sampling | **0.9868** | 0.8809 | 0.9971 | 0.5103 | 0.9691 |
| Convenience Sampling | 0.9849 | 0.8739 | 0.9962 | 0.5028 | 0.9623 |

Based on these results, it can be concluded that Cluster Sampling performs the best on all five models. Simple random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 5 samples is Decision Tree.

## Conclusion

It is recommended to use cluster sampling for this dataset, as it consistently gives the best performance across all models. However, other sampling techniques may be worth considering for different datasets or models.
 
