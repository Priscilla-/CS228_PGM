![Hits](https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fgithub.com%2FSKKSaikia%2FCS228_PGM)

# [CS:228 - Probabilistic Graphical Models](https://cs.stanford.edu/~ermon/cs228/index.html)

PGM ! PGM ! PGM ! One of the most interesting class yet challenging at Stanford is CS228. Graphical Models ahoi!, There's also an online preview of the course, [here](http://scpd.stanford.edu/search/publicCourseSearchDetails.do?method=load&courseId=11761) or [here](https://mvideos.stanford.edu/Previews) , only  the overview lecture though. The course heavily follows Daphne Koller's book [Probabilistic Graphical Models: Principles and Techniques by Daphne Koller and Nir Friedman.](https://github.com/SKKSaikia/CS228_PGM/blob/master/Probabilistic%20Graphical%20Models%20-%20Principles%20and%20Techniques.pdf), and There's also an online version of "Probabilistic Graphical Models" on [Coursera](https://www.coursera.org/specializations/probabilistic-graphical-models). I [completed](https://www.coursera.org/account/accomplishments/specialization/R63SHPRXHBC8) the [online](https://github.com/liang456/Stanford-Probabilistic-Graphical-Models-Coursera) [version](https://github.com/kuo000/stanford-pgm) as a freshman, and here I take CS228 again. I got [enrolled](https://github.com/SKKSaikia/CS228_PGM/blob/master/gradescope.PNG) on Gradescope, though I am not taking the course in person. Maintain the honor code, keep learning. This is exciting!

<img src="https://github.com/SKKSaikia/CS228_PGM/blob/master/cs228.PNG">

<p align="justify"> Probabilistic graphical models are a powerful framework for representing complex domains using probability distributions, with numerous applications in machine learning, computer vision, natural language processing and computational biology. Graphical models bring together graph theory and probability theory, and provide a flexible framework for modeling large collections of random variables with complex interactions. This course will provide a comprehensive survey of the topic, introducing the key formalisms and main techniques used to construct them, make predictions, and support decision-making under uncertainty.</p>

The aim of this course is to develop the knowledge and skills necessary to design, implement and apply these models to solve real problems. The course will cover: 
- (1) Bayesian networks, undirected graphical models and their temporal extensions
- (2) exact and approximate inference methods
- (3) estimation of the parameters and the structure of graphical models.

BOOK : [Probabilistic Graphical Models: Principles and Techniques by Daphne Koller and Nir Friedman.](https://github.com/SKKSaikia/CS228_PGM/blob/master/Probabilistic%20Graphical%20Models%20-%20Principles%20and%20Techniques.pdf)

𓄆 <b>Important Books : </b><br/>
𓊖 [Modeling and Reasoning with Bayesian](https://github.com/SKKSaikia/CS228_PGM/blob/master/Modeling%20and%20Reasoning%20with%20Bayesian.pdf) <br/>
𓊖 [Information Theory, Inference, and Learning Algorithms](https://github.com/SKKSaikia/CS228_PGM/blob/master/books/Information%20Theory%2C%20Inference%2C%20and%20Learning%20Algorithms%20by%20David%20J.%20C.%20Mackay.pdf) <br/>
𓊖 [Machine Learning A Probabilistic Perspective](https://doc.lagout.org/science/Artificial%20Intelligence/Machine%20learning/Machine%20Learning_%20A%20Probabilistic%20Perspective%20%5BMurphy%202012-08-24%5D.pdf) <br/>
𓊖 [Bayesian Reasoning and Machine Learning by David Barber](https://github.com/SKKSaikia/CS228_PGM/blob/master/books/Bayesian%20Reasoning%20and%20Machine%20Learning%20by%20David%20Barber.pdf) <br/>
𓊖 [Graphical models, exponential families, and variational inference](https://github.com/SKKSaikia/CS228_PGM/blob/master/Graphical%20models%2C%20exponential%20families%2C%20and%20variational%20inference%20by%20Martin%20J.%20Wainwright%20and%20Michael%20I.%20Jordan.pdf) <br/>

<b> Homework (70%) + Final Exam (30%) </b>| Homework - Theoretical + Programming | Topics in [book](https://github.com/SKKSaikia/CS228_PGM/blob/master/book.PNG)

# [Homeworks](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw)

- [Homework 1](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/hw1.pdf) : [Programming](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw/hw1)
- [Homework 2](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/hw2.pdf) : [Programming](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw/hw2)
- [Homework 3](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/hw3.pdf) : [Programming](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw/hw3)
- [Homework 4](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/hw4.pdf) : [Programming](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw/hw4)
- [Homework 5](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/hw5.pdf) : [Programming](https://github.com/SKKSaikia/CS228_PGM/tree/master/hw/hw5)

# [COURSE](https://ermongroup.github.io/cs228-notes/)

<h2><b> ♞ PRELIMINARIES </b></h2>

- [Introduction](https://ermongroup.github.io/cs228-notes/preliminaries/introduction/): What is probabilistic graphical modeling? Overview of the course. <br/>
- [Review of probability theory](https://ermongroup.github.io/cs228-notes/preliminaries/probabilityreview/): Probability distributions. Conditional probability. Random variables (under construction). <br/>
- [Examples of real-world applications](https://ermongroup.github.io/cs228-notes/preliminaries/applications/): Image denoising. RNA structure prediction. Syntactic analysis of sentences. Optical character recognition (under construction). <br/>

<h2><b> ♞ REPRESENTATION </b></h2>

- [Bayesian networks](https://ermongroup.github.io/cs228-notes/representation/directed/): Definitions. Representations via directed graphs. Independencies in directed models. <br/>
- [Markov random fields](https://ermongroup.github.io/cs228-notes/representation/undirected/): Undirected vs directed models. Independencies in undirected models. Conditional random fields. <br/>

<h2><b> ♞ INFERENCE </b></h2>

- [Variable elimination](https://ermongroup.github.io/cs228-notes/inference/ve/): The inference problem. Variable elimination. Complexity of inference. <br/>
- [Belief propagation](https://ermongroup.github.io/cs228-notes/inference/jt/): The junction tree algorithm. Exact inference in arbitrary graphs. Loopy Belief Propagation. <br/>
- [MAP inference](https://ermongroup.github.io/cs228-notes/inference/map/): Max-sum message passing. Graphcuts. Linear programming relaxations. Dual decomposition. <br/>
- [Sampling-based inference](https://ermongroup.github.io/cs228-notes/inference/sampling/): Monte-Carlo sampling. Importance sampling. Markov Chain Monte-Carlo. Applications in inference. <br/>
- [Variational inference](https://ermongroup.github.io/cs228-notes/inference/variational/): Variational lower bounds. Mean Field. Marginal polytope and its relaxations. <br/>

<h2><b> ♞ LEARNING </b></h2>

- [Learning in directed models](https://ermongroup.github.io/cs228-notes/learning/directed/): Maximum likelihood estimation. Learning theory basics. Maximum likelihood estimators for Bayesian networks. <br/>
- [Learning in undirected models](https://ermongroup.github.io/cs228-notes/learning/undirected/): Exponential families. Maximum likelihood estimation with gradient descent. Learning in CRFs <br/>
- [Learning in latent variable models](https://ermongroup.github.io/cs228-notes/learning/latent/): Latent variable models. Gaussian mixture models. Expectation maximization. <br/>
- [Bayesian learning](https://ermongroup.github.io/cs228-notes/learning/bayesianlearning/): Bayesian paradigm. Conjugate priors. Examples (under construction). <br/>
- [Structure learning](https://ermongroup.github.io/cs228-notes/learning/structLearn/): Chow-Liu algorithm. Akaike information criterion. Bayesian information criterion. Bayesian structure learning (under construction). <br/>

<h2><b> ♞ BRINGING IT ALL TOGETHER </b></h2>

- [The variational autoencoder](https://ermongroup.github.io/cs228-notes/extras/vae/): Deep generative models. The reparametrization trick. Learning latent visual representations. <br/>
- [List of further readings](https://ermongroup.github.io/cs228-notes/extras/readings/): Structured support vector machines. Bayesian non-parametrics. <br/>


유 [PGM - Max Planck Institute for Intelligent Systems - Christopher Bishop](https://www.youtube.com/watch?v=ju1Grt2hdko&list=PLL0GjJzXhAWTRiW_ynFswMaiLSa0hjCZ3) | [CMU - PGM](https://www.youtube.com/watch?v=lcVJ_zsynMc&list=PLI3nIOD-p5aoXrOzTd1P6CcLavu9rNtC-) | [Probabilistic Graphical Models Tutorial — Part 1](https://blog.statsbot.co/probabilistic-graphical-models-tutorial-and-solutions-e4f1d72af189) | [Understanding Probabilistic Graphical Models Intuitively](https://medium.com/@neerajsharma_28983/intuitive-guide-to-probability-graphical-models-be81150da7a) | [CMU - PGM - website](http://www.cs.cmu.edu/~epxing/Class/10708-14/lecture.html) | [PGM](https://cedar.buffalo.edu/~srihari/CSE674/) | [libDAI](https://staff.fnwi.uva.nl/j.m.mooij/libDAI/) | [OpenGM](http://hciweb2.iwr.uni-heidelberg.de/opengm/)

# FINAL EXAM

[2016 Final](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/final16_with_sols.pdf) , [2009 Final](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/CS228%20WINTER%202009%20FINAL%20SOLUTION%20(1)%20Using%20...%20-%20Stanford%20AI%20Lab.pdf) , [2008 Final](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/final-08.pdf) , [2007 Final](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/final040407.pdf), [2006 Final](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/final-06.pdf) | My Solution - [HOMEWORKS](https://github.com/SKKSaikia/CS228_PGM/blob/master/hw/SOLUTION.MD) , [EXAMS](https://github.com/SKKSaikia/CS228_PGM/blob/master/exam/SOLUTION.MD)
