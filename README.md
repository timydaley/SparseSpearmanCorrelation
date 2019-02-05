# SparseSpearmanCorrelation

I've run into difficulties in computing the Spearman correlation coefficient in R.  Any function involving apply or a variant thereof will convert the sparse matrix first to a regular matrix, followed by the application of apply.  This creates difficulties for extremely large matrices.  My objective here is to develop an efficient method of computing the Spearman correlation coefficient for large and sparse matrices.
