## Codes for Semi-Supervised Sparse Representation based Classificatin (S3RC), Version 1.0

### Please refer to our following paper for algorithm details:
> Yuan Gao, Jiayi Ma, and Alan L. Yuille,
> Semi-Supervised Sparse Representation Based Classification for Face Recognition with Insufficient Labeled Samples,
> IEEE Transactions on Image Processing, 2017. In Press.

### Usage:
- run `S3RC_single_labeled_sample.m` to start the demo for Face Recognition with insufficient labeled samples;
- run `S3RC_insufficient_labeled_samples.m` to start the demo for Face Recognition with single labeled sample per person.
- The demo codes needs `L1_homotopy_v2.0` toobox to solve the L1 minimization problem (already included), which can be acquired from http://www.ece.ucr.edu/~sasif/homotopy/.

### Features:
- This release implements the vanilla version of our S3RC algorithm, i.e., our main contribution on the gallery dictionary learning with the basic ESRC variation dictionary.
- In order to combine more advanced variation dictionary, e.g., S3RC-SVDL, S3RC-RADL, or your own variation dictionary learning, just replace the variation dictionary `V` in `S3RC_single_labeled_sample.m` or `S3RC_insufficient_labeled_samples.m`.

### Contacts
For questions about the code or the paper, feel free to contact me by Ethan.Y.Gao@gmail.com.