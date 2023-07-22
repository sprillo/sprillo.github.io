## About

I am a fourth year PhD student in the department of Electrical Engineering and Computer Science at UC Berkeley, advised by [Yun S. Song](http://people.eecs.berkeley.edu/~yss/) and [Nir Yosef](https://niryosef.wordpress.com/group/).
Broadly speaking, I work on mathematical and computational biology.
More specifically, I am interested in statistical phylogenetics and its intersection with single-cell biology.
Two key areas I am interested in are protein evolution and cancer evolution.
Methodologically, my work is themed around finding clever tradeoffs between computational efficiency and statistical efficiency (or accuracy) when analyzing large biological datasets.
Indeed, many biological datasets have reached a point where they are too large to analyze with conventional methods, and more clever, scalable methods are needed.
Here, by 'clever' we mean that the increased scalability comes at a small cost of accuracy.
The best example of this is my work on 'CherryML' for rate matrix estimation, where we developed a method that is _thousands_ of times faster than the state-of-the-art, while being only two times less statistically efficient (rather than thousands, which would be trivially achievable by subsampling the dataset).

## Publications

**Sebastian Prillo**, Yun Deng, Pierre Boyeau, Xingyu Li, Po-Yen Chen, Yun S. Song [CherryML: scalable maximum likelihood estimation of phylogenetic models](https://rdcu.be/dfGuF), *Nature Methods 2023* [Code](https://github.com/songlab-cal/CherryML)

Khalil Ouardini, Romain Lopez, Matthew G Jones, **Sebastian Prillo**, Richard Zhang, Michael I Jordan, Nir Yosef [Reconstructing unobserved cellular states from paired single-cell lineage tracing and transcriptomics data](https://www.biorxiv.org/content/10.1101/2021.05.28.446021v1), *ICML 2021 Workshop in Computational Biology, Oral presentation*

**Sebastian Prillo**<sup>\*</sup>, Julian Eisenschlos<sup>\*</sup> [SoftSort: A Continuous Relaxation for the argsort Operator](https://arxiv.org/abs/2006.16038), *ICML 2020* [Code](https://github.com/sprillo/softsort)

**Sebastian Prillo** [An elementary view on factorization machines](https://dl.acm.org/doi/abs/10.1145/3109859.3109892), *RecSys 2017*

[\*] Equal contribution
