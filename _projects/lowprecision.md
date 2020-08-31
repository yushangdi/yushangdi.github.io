---
title: "Low Precision Training in Distributed ML Systems "
collection: publications
permalink: /publication/lowprecision
excerpt: 'The behavior of low-precision training in distributed computing environments. '
course: "CS 6787 Advanced Machine Learning Systems"
prof: "Christopher De Sa"
courseurl: "http://www.cs.cornell.edu/courses/cs6787/2018fa/"
profurl: "http://www.cs.cornell.edu/~cdesa/"
paperurl: '../files/low_precision.pdf'
---
Distributed computing and low-precision numerical representation are two techniques used to speed up computation-intensive machine learning tasks. They have been widely investigated in systemic and algorithmic scope, respectively. However, how we can effectively combine these two techniques has not been well understood in prior arts. In this paper, we aim to empirically investigate the effectiveness of employing low-precision training in both centralized and decentralized architectures, with a combined consideration on both system efficiency and statistical performance.

We select two representative machine learning tasks: logistic regression on MNIST by training a linear classifier and image classification on CIFAR-10 by training a 16-layer VGG network. We make the following observations: 1) For both convex and non-convex problems, aggressively quantizing the communication rarely affect the statistical performance while can largely reduce the communication overhead (up to 87.5%). 2) In non-convex problem, training with extremely low precision can no
longer achieve state-of-the-art performance. These conclusions can be reference for applying low-precision training in modern systems in the future.

[Download paper here](../files/low_precision.pdf)
<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
