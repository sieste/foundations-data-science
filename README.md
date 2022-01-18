# Foundations of Data Science: A Bibliography

This bibliography is a collection of foundational papers and review papers of subfields of Mathematics and Computer Science that build the modern foundations of Data Science. This site is work in progress, and as such this collection is necessarily opinionated and incomplete. Contributions in the form of Issues and Pull Requests are welcome.


## General

- https://www.inferentialthinking.com/chapters/intro This is the textbook for the Foundations of Data Science class at UC Berkeley.
- <data8.org> UC Berkeley Foundations of Data Science Course
- <https://www.cs.cornell.edu/jeh/book.pdf> Foundations of Data Science, by Avrim Blum, John Hopcroft, and Ravindran Kannan (2018) 466 pages


## Interpretations of Probability

- **Review paper**: Hájek, Alan, "Interpretations of Probability", The Stanford Encyclopedia of Philosophy (Fall 2019 Edition), Edward N. Zalta (ed.), URL = <https://plato.stanford.edu/archives/fall2019/entries/probability-interpret/>.
- **Paper** R. A. Fisher (1922) On the mathematical foundations of theoretical statistics [RSS](https://royalsocietypublishing.org/doi/10.1098/rsta.1922.0009)
- **Book** Kolmogorov (1933): Foundations of the theory of probability [kolmogorov.com](http://kolmogorov.com/Foundations.html)
- **Paper** Jaynes ET (1968): Prior probabilities [bayes.wustl.edu](https://bayes.wustl.edu/etj/articles/prior.pdf)
- **Paper** Berger JO, Sellke T (1985): Testing a Point Null Hypothesis: The Irreconcilability of P Values and Evidence [JASA](https://www.tandfonline.com/doi/abs/10.1080/01621459.1987.10478397) (on the p-value controversy)
- **Book** Jaynes ET (1995): Probability Theory: The Logic of Science [bayes.wustl.edu](https://bayes.wustl.edu/etj/prob/book.pdf)


## Important Algorithms

- **Paper** Dempster AP, Laird NM, Rubin DB (1977): Maximum likelihood from incomplete data via the EM algorithm [JRSS-B](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/j.2517-6161.1977.tb01600.x) (Expectation-maximisation algorithm)
- **Paper** Hastings WK (1970): Monte Carlo Sampling Methods Using Markov Chains and Their Applications [Biometrika](https://www.jstor.org/stable/2334940) (Markov Chain Monte Carlo)
- **Paper** Geman S, Geman D (1984): Stochastic Relaxation, Gibbs Distributions, and the Bayesian Restoration of Images [IEEE Transactions](https://ieeexplore.ieee.org/document/4767596) (Gibbs sampling)
- **Paper** Hartigan and Wong (1979): Algorithm AS 136: A k-means clustering algorithm [JSTOR](https://www.jstor.org/stable/2346830)


## Linear modelling

- **Review paper** Hocking RR (1983): Developments in Linear Regression Methodology: 1959–l982 [Technometrics](https://www.tandfonline.com/doi/abs/10.1080/00401706.1983.10487871)
- **Review paper** Hocking RR (1976): The Analysis and Selection of Variables in Linear Regression [JSTOR](https://www.jstor.org/stable/2529336)
- **Paper** Nelder JA, Wedderburn RWM (1972): Generalized Linear Models
 [JRSS-A](https://rss.onlinelibrary.wiley.com/doi/abs/10.2307/2344614)
- **Review paper** Holan SH et al. (2010): The ARMA alphabet soup: A tour of ARMA model variants [Statistics Surveys](https://projecteuclid.org/journals/statistics-surveys/volume-4/issue-none/The-ARMA-alphabet-soup--A-tour-of-ARMA-model/10.1214/09-SS060.full)
- **Paper** Pearson K (1901): On lines and planes of closest fit to systems of points in space [Journal](https://www.tandfonline.com/doi/abs/10.1080/14786440109462720) (Principal Components Analysis)


## Model selection

- **Paper** Wilks, SS (1938) "The Large-Sample Distribution of the Likelihood Ratio for Testing Composite Hypotheses" [Ann. Math. Stat.](https://dx.doi.org/10.1214/aoms/1177732360) (Likelihood ratio test)
- **Paper** Neyman J, Pearson ES (1933) "IX. On the problem of the most efficient tests of statistical hypotheses" [Phil. Trans. Roy. Soc. A](https://royalsocietypublishing.org/doi/10.1098/rsta.1933.0009) (Neyman-Pearson Theorem)
- **Paper** Akaike, H (1974), "A new look at the statistical model identification" [IEEE Transactions on Automatic Control](https://ieeexplore.ieee.org/document/1100705) (Akaike information criterion)
- **Paper** Stone, M (1974) "Cross‐validatory choice and assessment of statistical predictions" [JRSS-B](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/j.2517-6161.1974.tb00994.x) (cross validation)


## Data visualisation

- **Book** Tufte E.: The Visual Display of Quantitative Information [Aesthetics and Technique in Data Graphical Design (Chapter 9)](https://webspace.science.uu.nl/~telea001/uploads/VACourse/Tufte01-2.pdf)
- **Paper** Wickham H (2007): A Layered Grammar of Graphics [Journal of Computational and Graphical Statistics](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2009.07098)


## Data analysis

- **Paper** Good IJ (1983): The Philosophy of Exploratory Data Analysis [Philosophy of Science](https://www.journals.uchicago.edu/doi/abs/10.1086/289110)
- **Paper** Wickham H. (2001): The Split-Apply-Combine Strategy for Data Analysis [J Stat Soft](https://www.jstatsoft.org/article/view/v040i01)
- **Paper** McKinney, W (2011): "pandas: A foundational python library for data analysis and statistics." [pdf](https://www.dlr.de/sc/portaldata/15/resources/dokumente/pyhpc2011/submissions/pyhpc2011_submission_9.pdf)
- **Paper** Wickham H. (2014): Tidy data [J Stat Soft](https://www.jstatsoft.org/article/view/v059i10)
- **Paper** Broman KW, Woo KH (2018): Data Organization in Spreadsheets [The American Statistician](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989)


## Natural language processing

- **Review paper** Cambria E, White B (2014): Jumping NLP Curves: A Review of Natural Language Processing Research [IEEE Computational Intelligence Magazine](https://ieeexplore.ieee.org/abstract/document/6786458)
- **Paper** Blei DM, Ng AY, Jordan MI (2003): Latent Dirichlet Allocation [pdf](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf)


## Artificial Neural Networks

- **Paper** Rosenblatt F (1958): The perceptron: A probabilistic model for information storage and organization in the brain. [pdf](https://www.neural-networks.io/papers/1958-the-perceptron:-a-probabilistic-model-for-information-storage-and-organization-in-the-brain.pdf)
- **Paper** Werbos P (1990): Backpropagation Through Time: What It Does and How to Do It
[Journal](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=58337) (early review paper)
- **Paper** Hochreiter S, Schmidhuber J (1997): Long short-term memory, Neural Computation. [pdf](https://www.neural-networks.io/papers/1958-the-perceptron:-a-probabilistic-model-for-information-storage-and-organization-in-the-brain.pdf)


## Reservoir Computing
- **Paper** Jaeger H (2010): The echo state approach to analysing and training recurrent neural networks-with an
erratum note, German National Research Center for Information Technology GMD Technical Report. [pdf](https://www.ai.rug.nl/minds/uploads/EchoStatesTechRep.pdf)
- **Review** Jaeger H (2007): Echo state Networks [Scholarpedia](http://www.scholarpedia.org/article/Echo_state_network), 2(9):2330.


## Gaussian processes

- **Book** Rasmussen CE, Williams CKI (2006): Gaussian Processes for Machine Learning [gaussianprocess.org](http://www.gaussianprocess.org/gpml/)
- **Paper** Williams CKI, Rasmussen CE (1996): Gaussian processes for regression.  [Advances in Neural Information Processing Systems](http://publications.aston.ac.uk/id/eprint/651/)
- **Paper** Damianou A, Lawrence ND (2013): Deep Gaussian Processes [Proceedings of the Sixteenth International Conference on Artificial Intelligence and Statistics](http://proceedings.mlr.press/v31/damianou13a)
- **Paper** Williams CKI, Barber D (1998): Bayesian classification with Gaussian processes [IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/abstract/document/735807)


## Theory of computation

- **Paper** Turing, AM (1936): On Computable Numbers, with an Application to the Entscheidungsproblem [Proc. London Math. Soc.](https://londmathsoc.onlinelibrary.wiley.com/doi/abs/10.1112/plms/s2-42.1.230) [(correction 1937)](https://londmathsoc.onlinelibrary.wiley.com/doi/abs/10.1112/plms/s2-43.6.544) (proof of the decision problem)
- **Paper** McCarthy J (1960): Recursive Functions of Symbolic Expressions and Their Computation by Machine [stanford.edu](http://www-formal.stanford.edu/jmc/recursive.html)


## Causal Inference

- **Review paper** Pearl J (2003): Statistics and causal inference: A review. [Test](https://link.springer.com/article/10.1007/BF02595718)


## Information theory

- **Book** MacKay DJ (2003): Information theory, inference and learning algorithms. [inference.org.uk](http://www.inference.org.uk/mackay/itila/)
- **Paper** Kullback S, Leibler RA (1951): On Information and sufficiency [JSTOR](https://www.jstor.org/stable/2236703)
- **Paper** Jaynes ET (1957): Information Theory and Statistical Mechanics [aps.org](https://journals.aps.org/pr/abstract/10.1103/PhysRev.106.620)


## Literate programming

- **Paper** Knuth (1984): Literate Programming [literateprogramming.com/](http://www.literateprogramming.com/knuthweb.pdf)
- **Paper** Perkel JM (2018): Why Jupyter is data scientists' computational notebook of choice [nature.com](https://www.nature.com/articles/d41586-018-07196-1/)
- **Book** Xie Y, Dervieux C, Riederer E (2022): R Markdown Cookbook [bookdown.org](https://bookdown.org/yihui/rmarkdown-cookbook/)


## Graphical models

- **Review paper** Smyth (1997): Belief networks, hidden Markov models, and Markov random fields: A unifying view [Pattern Recognition Letters](https://doi.org/10.1016/S0167-8655(97)01050-7)


## Monte Carlo methods

- **Review paper** MacKay (1998): Introduction to Monte Carlo methods [Learning in Graphical Models](https://link.springer.com/chapter/10.1007/978-94-011-5014-9_7) [pdf](http://www.cs.cmu.edu/afs/cs.cmu.edu/Web/People/motionplanning/papers/sbp_papers/kalman/intro_montecarlo.pdf)

