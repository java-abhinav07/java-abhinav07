---
title: "Rethinking Neural Networks with Benford's Law"
collection: publications
permalink: /publication/rbl
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2021-12-12
venue: 'Neurips 2021, Machine Learning for Physics'
paperurl: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_99.pdf'
citation: "Sahu, S. K., <b>Java, A.</b>, Shaikh, A., & Kilcher, Y. (2021). Rethinking Neural Networks With Benford's Law. arXiv preprint arXiv:2102.03313."
poster: 'https://ml4physicalsciences.github.io/2021/files/NeurIPS_ML4PS_2021_99_poster.png'
image: "../images/rbl.png"
---
In this work, we address the following question: Is the distribution of the Neural Network parameters related to the network's generalization capability? To that end, we first define a metric, MLH (Model Enthalpy), that measures the closeness of a set of numbers to Benford's Law. Second, we use MLH as an alternative to Validation Accuracy for Early Stopping and provide experimental evidence that even if the optimal size of the validation set is known beforehand, the peak test accuracy attained is lower than early stopping with MLH i.e. not using a validation set at all. <br>
This work was done with my [research group](https://github.com/The-Learning-Machines).