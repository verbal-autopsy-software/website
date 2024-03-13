---
title: "Tree-informed Bayesian multi-source domain adaptation: cross-population probabilistic cause-of-death assignment using verbal autopsy"
date: 2024-02-23
publishDate:
authors: ["Zhenke Wu", "Zehang R Li", "Irena Chen", "Mengbing Li"]
publication_types: ["2"]
abstract: "Determining causes of deaths (CODs) occurred outside of civil registration and vital statistics systems is challenging. A technique called verbal autopsy (VA) is widely adopted to gather information on deaths in practice. A VA consists of interviewing relatives of a deceased person about symptoms of the deceased in the period leading to the death, often resulting in multivariate binary responses. While statistical methods have been devised for estimating the cause-specific mortality fractions (CSMFs) for a study population, continued expansion of VA to new populations (or “domains”) necessitates approaches that recognize between-domain differences while capitalizing on potential similarities. In this article, we propose such a domain-adaptive method that integrates external between-domain similarity information encoded by a prespecified rooted weighted tree. Given a cause, we use latent class models to characterize the conditional distributions of the responses that may vary by domain. We specify a logistic stick-breaking Gaussian diffusion process prior along the tree for class mixing weights with node-specific spike-and-slab priors to pool information between the domains in a data-driven way. The posterior inference is conducted via a scalable variational Bayes algorithm. Simulation studies show that the domain adaptation enabled by the proposed method improves CSMF estimation and individual COD assignment. We also illustrate and evaluate the method using a validation dataset. The article concludes with a discussion of limitations and future directions."
featured: false
publication: "https://academic.oup.com/biostatistics/advance-article/doi/10.1093/biostatistics/kxae005/7613451"
url_pdf: "https://academic.oup.com/biostatistics/advance-article-pdf/doi/10.1093/biostatistics/kxae005/56750250/kxae005.pdf"
doi: "https://doi.org/10.1093/biostatistics/kxae005"
---
