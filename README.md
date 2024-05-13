# Sonar Benchmarks Scores

The goal of this repository is to centralize the ground truths of popular SAST Benchmarks.
By ground truths, we mean what should be detected or not detected by a SAST product.
The ground truths correspond to the Sonar AppSec team's perspective on the issues that should be detected or not detected. We acknowledge that we may have made mistakes, so if you come across any misclassifications, please don't hesitate to report them.
The ground truths contain all kinds of security issues, even the incidentals (issues that were not expected to be highlighted by the author of the SAST benchmarks).

By contributing this content, we hope that the SAST market will raise its game and deliver better SAST analyzers.

In this repository, you will also find how Sonar scores on the SAST benchmarks.

In each directory corresponding to a benchmark, you will find:

* metadata to identify the benchmark (name, code URL)
* a ground-truth.json file containing the list of expected issues
* a file "sonar-score.json" showing the TPR (True Positive Rate) and FDR (False Detection Rate) of the Sonar solution on the benchmark
