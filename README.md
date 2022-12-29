# HMMC-project

In this project, we use work on the article "Mirauta B, Nicolas P, Richard H. Parseq: reconstruction of microbial transcription landscape from RNA-Seq read counts using state-space models. Bioinformatics. 2014 May 15;30(10):1409-16. doi: 10.1093/bioinformatics/btu042" (https://pubmed.ncbi.nlm.nih.gov/24470570/). 

We have three objectives: 
- Creating a model allowing us to generate data as modelled in the paper. 
- Implementing a boostrap filter on those data. 
- Using PMMH do perform bayesian inference on a subset of parameters.

We rely a lot on the "particles" package developed by N. Chopin (see https://github.com/nchopin/particles); although in some cases we have to adapt it to our needs.