# fly-supplementary

## Quantitative Analysis of Predictive Performance

![model](./figures/confusion_matrix.png)

In order to analyze the prediction errors of our model, we compare the
confusion matrices of the prediction results, as shown in figure.
We observe that most wrongly-predicted samples are classified into
neighboring stages, within the correct stage ranges. In particular, for deep learning models trained using our proposed low-shot learning methods, the number of samples that are categorized into wrong stage ranges is fewer than the baseline. It indicates that the data-level deep low-shot learning step effectively incorporates information from samples with stage range labels and improves the performance of precise stage prediction.


