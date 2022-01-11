---
permalink: /software/
title: "Software"
---


## HiddenSemiMarkov

[HiddenSemiMarkov](https://lasy.github.io/HiddenSemiMarkov/) is an R package for specifying hidden semi-Markov models, simulating sequences, fitting models to specific observation sequences and predicting the sequence of hidden states from observation sequences. It is especially designed to model multivariate sequences with frequent (non-random) missing data. The probabilities of missing data may be state- or variable-dependent and specified manually or learned from observation sequences. This package was developed and used for [Labeling self-tracked menstrual health records with hidden semi-Markov models](https://ieeexplore.ieee.org/document/9531515).

To install the latest version from GitHub:

```r
library(devtools)
devtools::install_github("lasy/HiddenSemiMarkov")
```


## alto

[alto](https://lasy.github.io/alto/) is an R package for aligning topics across a collection of LDA models. The package also contains functions to visualize the alignments and associated diagnostics scores. The methods are described in [Multiscale Analysis of Count Data through Topic Alignment](https://arxiv.org/abs/2109.05541)

To install the latest version from GitHub:


```r
library(devtools)
devtools::install_github("lasy/alto")
```


## cpass

[cpass](https://lasy.github.io/cpass/) is an R package for the application of the C-PASS (Carolina Premenstrual Assessment Scoring System) procedure for the diagnosis of PMDD (Pre-Menstrual Dysphoric Disorder) and MRMD (Menstrually Related Mood Disorder).
The C-PASS procedure is described in ["Toward the Reliable Diagnosis of DSM-5 Premenstrual Dysphoric Disorder: The Carolina Premenstrual Assessment Scoring System (C-PASS)"](https://ajp.psychiatryonline.org/doi/full/10.1176/appi.ajp.2016.15121510) (2016) by Eisenlohr-Moul _et al._

To install the latest version from GitHub:

```r
library(devtools)
devtools::install_github("lasy/cpass")
```

If you believe that you may have PMDD (e.g., feel very depressed or have suicidal thoughts before/around your period), get help. For example, [IAPMD](https://iapmd.org) has a lot of resources, such as the self-screening tool, peer-support groups, and can help you find a healthcare professional. Get help now.
