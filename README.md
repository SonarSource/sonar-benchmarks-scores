# Sonar Benchmarks Scores

In this repository, Sonar shares the ground truths (list of expected issues) of popular SAST Benchmarks.
We also share how Sonar scores on these SAST Benchmarks.

In each directory corresponding to a benchmark, you will find:
* metadata to identify the benchmark (name, code URL)
* a ground-truth.json file containing the list of expected issues
* a file "sonar-score.json" showing the TPR (True Positive Rate) and FDR (False Detection Rate) of the Sonar solution on the benchmark
