# multidimensional-incertitude-dropout
Use of dropout to have uncertainties with neural networks, case of a multidimensional output

I try to compute incertitude when using neural networks, using concrete dropout of Gal et al. 
The article of Sigrid Kedyana was a great help for me, see https://blogs.rstudio.com/tensorflow/posts/2018-11-12-uncertainty_estimates_dropout/.
In this article, the output to be predicted is of dimension one. I am willing to use concretze dropout, but for multidimensional output. 
Here, I juste take the same example than Sigrid Kedyana, and try to extend it to a 2-dimensional output.
