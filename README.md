# CPSC 340: Machine Learning and Data Mining (2021W1)

### Course documents

* [syllabus](docs/syllabus.md)
* [homework submission instructions](docs/submissionInstructions.pdf)
* [textbooks and online resources](docs/resources.md)
* [CPSC 340 vs. CPSC 330 vs. CPSC 440](docs/340_330_440.md)

### Schedule

Note: In the timetable below, the textbook codes (such as "AI:AMA") are defined [here](docs/resources.md#textbooks).

| Date           | Slides         | Related Readings and Links    | Homework and Notes    |
| -------------- | -------------- | ----------------------------- | ------------ |
| Wed Sep 8      | [Motivation and Syllabus](lectures/L1.pdf)                                                                                                              | [What is Machine Learning?](https://www.youtube.com/watch?v=OokV2AX4TKg) [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)<br>[Rise of the Machines](http://www.economist.com/news/briefing/21650526-artificial-intelligence-scares-peopleexcessively-so-rise-machines) [Talking Machine Episode 1](https://www.thetalkingmachines.com/episodes/hello-world)       |   |
| Fri Sep 10      | [Exploratory Data Analysis](lectures/L2.pdf)      | [Gotta Catch'em all](http://datagenetics.com/blog/april32016/index.html) [Why Not to Trust Statistics](https://mathwithbaddrawings.com/2016/07/13/why-not-to-trust-statistics/)<br>[Visualization Types](http://guides.library.duke.edu/datavis/vis_types) [Google Chart Gallery](https://developers.google.com/chart/interactive/docs/gallery?hl=en) [Other Tools](http://selection.datavisualization.ch/)    |     |
| Mon Sep 13      | [Decision Trees](lectures/L3.pdf)        | [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1), [Decision Trees](https://en.wikipedia.org/wiki/Decision_tree_learning) [Entropy](https://en.wikipedia.org/wiki/Entropy_(information_theory))<br>AI:AMA 18.2-3, ESL: 9.2, ML:APP 16.2     | [Big-O Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/bigO.pdf)
| Wed Sep 15     | [Fundamentals of Learning](lectures/L4.pdf)        | [7 Steps of Machine Learning](https://www.youtube.com/watch?v=nKW8Ndu7Mjw) [IID](https://en.wikipedia.org/wiki/Independent_and_identically_distributed_random_variables) [Cross-validation](https://en.wikipedia.org/wiki/Cross-validation_(statistics)) [Bias-variance](https://en.wikipedia.org/wiki/Bias%E2%80%93variance_tradeoff) [No Free Lunch](http://dml.cs.byu.edu/~cgc/docs/mldm_tools/Reading/LCG.pdf)<br>AI: AMA 18.4-5, ESL 7.1-7.4, 7.10, ML:APP 1.4, 6.5                                                                                                                                                          | [Course Notation Guide](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/notation.pdf)<br>                                                                                                                                                                                                     |
| Fri Sep 17     | [Probabilistic Classifiers](lectures/L5.pdf)                                                                                                            | [Conditional probability](https://en.wikipedia.org/wiki/Conditional_probability) ([demo](http://setosa.io/ev/conditional-probability/)) [Naive Bayes](https://en.wikipedia.org/wiki/Naive_Bayes_classifier) [Probabilities and Battleship](http://datagenetics.com/blog/december32011/index.html)<br>ESL 4.3, ML: APP 2.2, 3.5, 4.1-4.2                                                                                                                                                                                                                                                                                           | Assignment 1 due<br>[Probability Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/probability.pdf) [Probability Slides](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/probabilitySlides.pdf)                                                                                            |
| Mon Sep 20     | [Non-Parametric Models](lectures/L6.pdf)                                                                                                                | [K-nearest neighbours](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm) [Decision Theory for Darts](http://www.datagenetics.com/blog/january12012/index.html) [Norms](https://en.wikipedia.org/wiki/Norm_(mathematics))<br>AI: AMA 18.8, ESL 13.3, ML:APP 1.4     |   |
| Wed Sep 22     | [Ensemble Methods](lectures/L7.pdf)                                                                                                                     | [Ensemble Methods](https://en.wikipedia.org/wiki/Ensemble_learning) [Random Forests](https://en.wikipedia.org/wiki/Random_forest) [Empirical Study](http://jmlr.org/papers/volume15/delgado14a/delgado14a.pdf) [Kinect](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/BodyPartRecognition.pdf)<br>AI: AMA 18.10, ESL: 7.11, 8.2, 15, 16.3, ML: APP 6.2.1, 16.2.5, 16.6                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                             |
| Fri Sep 24     | [Clustering](lectures/L8.pdf)                                                                                                                           | [Clustering](https://en.wikipedia.org/wiki/Cluster_analysis) [K-means clustering](https://en.wikipedia.org/wiki/K-means_clustering) ([demo](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)) [K-Means++](http://ilpubs.stanford.edu:8090/778/1/2006-13.pdf) ([demo](https://www.youtube.com/watch?v=BIQDlmZDuf8))<br>IDM 8.1-8.2, ESL: 14.3                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                             |
| Mon Sep 27<br> | [More Clustering](lectures/L9.pdf)                                                                                                                      | [DBSCAN](https://en.wikipedia.org/wiki/DBSCAN) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/dbscan.mov), [demo](https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)) [Hierarchical Clustering](https://en.wikipedia.org/wiki/Hierarchical_clustering) [Phylogenetic Trees](https://en.wikipedia.org/wiki/Phylogenetic_tree)<br>IDM 8.4    |
| Wed Sep 29<br> | [Outlier Detection](lectures/L10.pdf)                                                                                                                   | [Empirical Study](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0152173)<br>IDM 8.3, ESL 14.3.12, ML:APP 25.5  | Assignment 2 due   |
| Fri Oct 1<br> | [Least Squares](lectures/L12.pdf)                                                                                                                       | [Linear Regression](http://datagenetics.com/blog/august12013/index.html) ([demo](http://setosa.io/ev/ordinary-least-squares-regression/), [2D data](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linear.mp4), [2D video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linear2.mp4)) [Least Squares](https://en.wikipedia.org/wiki/Ordinary_least_squares) [Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) [Partial Derivative](https://en.wikipedia.org/wiki/Partial_derivative) [Gradient](https://en.wikipedia.org/wiki/Gradient)<br>ESL 3.1-2, ML:APP 7.1-3, AI:AMA 18.6<br> |  |
| Mon Oct 4<br>  | [Nonlinear Regression](lectures/L13.pdf)                                                                                                                | [Why should one learn machine learning from scratch?](https://www.quora.com/Why-should-one-learn-machine-learning-from-scratch-rather-than-just-learning-to-use-the-available-libraries) [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) [Matrix Differentiation](https://atmos.washington.edu/~dennis/MatrixCalculus.pdf) [Fluid Simulation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.726.8764&rep=rep1&type=pdf) ([video](https://www.youtube.com/watch?v=kGB7Wd9CudA))<br>ESL 5.1, 6.3                                                                   | [Linear Algebra Notes](https://www.cs.ubc.ca/~schmidtm/Documents/2009_Notes_LinearAlgebra.pdf)<br>[Linear/Quadratic Gradients](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/linearQuadraticGradients.pdf)                                                                                  |
| Wed Oct 6<br>  | [Gradient Descent](lectures/L14.pdf)  | [Gradient Descent](https://en.wikipedia.org/wiki/Gradient_descent) [Convex Functions](https://en.wikipedia.org/wiki/Convex_function)    |        |
| Fri Oct 8<br> | [Finding Similar Items](lectures/L11.pdf)<br>(Bonus Lecture)                                                                                            | [MMD Chapter 3](http://infolab.stanford.edu/~ullman/mmds/ch3.pdf) |    |
| Mon Oct 11   | | THANKSGIVING - NO CLASS | |
| Wed Oct 13 <br>  | [Robust Regression](lectures/L15.pdf)                                                                                                                   | ML:APP 7.4    |     |
| Fri Oct 15<br>  | [Feature Selection](lectures/L16.pdf)                                                                                                                   | [Genome-Wide Association Studies](https://en.wikipedia.org/wiki/Genome-wide_association_study) [AIC](https://en.wikipedia.org/wiki/Akaike_information_criterion), [BIC](https://en.wikipedia.org/wiki/Bayesian_information_criterion)<br>ESL 3.3 , 7.5-7   |  Assignment 3 due         |
| Mon Oct 18<br> | [Regularization](lectures/L17.pdf)    | ESL 3.4., ML:APP 7.5, AI:AMA 18.4  |                                                                                                                                                                                                                                                                          |
| Wed Oct 20<br> | [More Regularization](lectures/L18.pdf)                                                                                                                 | [RBF video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/rbf.mp4) [RBF and Regularization video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/rbf2.mp4)<br>ESL 6.7, ML:APP 13.3-4     |   |
| Thu Oct 21<br> |  | MIDTERM (6:00-7:30pm) | |
| Fri Oct 22<br> | [Linear Classifiers](lectures/L19.pdf)                                                                                                                  | [Perceptron](https://en.wikipedia.org/wiki/Perceptron)<br>ESL 4.5, ML:APP 8.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                                             |
| Mon Oct 25<br> | [More Linear Classifiers](lectures/L20.pdf)                                                                                                             | [Support Vector Machines](https://en.wikipedia.org/wiki/Support_vector_machine)<br>ESL 4.4, 12.1-2, ML:APP 8.1-3, 9.5 14.5, AI:AMA 18.9  |   |
| Wed Oct 27<br> | [Feature Engineering](lectures/L21.pdf)    | [Gmail Priority Inbox](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36955.pdf)  |   |
| Fri Oct 29<br> | [Convolutions](lectures/L22.pdf)      |    |      |
| Mon Nov 1<br> | [Kernel Trick](lectures/L23.pdf)                                                                                                                        | ESL 12.3, ML:APP 14.1-4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                             |
| Wed Nov 3<br> | [Stochastic Gradient](lectures/L24.pdf)                                                                                                                 | [Stochastic Gradient](https://en.wikipedia.org/wiki/Stochastic_gradient_descent)<br>ML:APP 8.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                                             |
| Fri Nov 5<br>  | [Boosting](lectures/L25.pdf)                                                                                                                            | [AdaBoost](https://en.wikipedia.org/wiki/AdaBoost) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/adaBoost.mp4)) [XGBoost](https://xgboost.readthedocs.io/en/latest/tutorials/model.html) ([video](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/regressionBoost.mp4))<br>ML:APP 16.4     | Assignment 4 due<br>[Max and Argmax Notes](https://www.cs.ubc.ca/~schmidtm/Courses/Notes/max.pdf)                                                                                                                                                                                           |
| Mon Nov 8<br>  | [MLE and MAP](lectures/L26.pdf) | [Maximum Likelihood Estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation)<br>ML:APP 9.3-4  |   |
| Wed Nov 10<br>  | [Principal Component Analysis](lectures/L27.pdf)          | [Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis)<br>ESL 14.5, IDM B.1, ML:APP 12.2  |        |
| Fri Nov 12 | | MIDTERM BREAK - NO CLASS | | 
| Mon Nov 15 | | MIDTERM BREAK - NO CLASS | |
| Wed Nov 17<br>  | [More PCA](lectures/L28.pdf)                                                                                                                            | [Making Sense of PCA](https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues) [SVD](https://en.wikipedia.org/wiki/Singular_value_decomposition) [Eigenfaces](https://en.wikipedia.org/wiki/Eigenface)   |   |
| Fri Nov 19<br> | [Sparse Matrix Factorization](lectures/L29.pdf)                                                                                                         | [Non-Negative Matrix Factorization](https://en.wikipedia.org/wiki/Non-negative_matrix_factorization) ([original](http://www.nature.com/nature/journal/v401/n6755/abs/401788a0.html) - access from UBC)<br>ESL 14.6, ML: APP 13.8  |    |
| Mon Nov 22<br> | [Recommender Systems](lectures/L30.pdf)                                                                                                                 | [Recommender Systems](https://en.wikipedia.org/wiki/Recommender_system) [Netflix Prize](https://en.wikipedia.org/wiki/Netflix_Prize)  |   |
| Wed Nov 24<br> | [Multi-Dimensional Scaling](lectures/L31.pdf)                                                                                                           | [Nonlinear Dimensionality Reduction](https://en.wikipedia.org/wiki/Nonlinear_dimensionality_reduction) [t-SNE demo](http://distill.pub/2016/misread-tsne/)<br>ESL 14.8-9, IDM B.2    |  Assignment 5 due |
| Fri Nov 26<br> | [Deep Learning](lectures/L32.pdf)                                                                                                                       | [Google Video](https://www.youtube.com/watch?v=bHvf7Tagt18) [What is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) [Interactive Guide](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks)<br>ML:APP 16.5, ESL 11.1-4, AI: AMA 18.7    |       |
| Mon Nov 29<br> | [More Deep Learning](lectures/L33.pdf)                                                                                                                  | [Fortune Article](http://fortune.com/ai-artificial-intelligence-deep-machine-learning/) [Deep Learning References](https://github.com/ChristosChristofidis/awesome-deep-learning) [Alchemy](https://www.youtube.com/watch?v=Qi1Yry33TQE&feature=youtu.be&t=3m)<br>ML:APP 28.3, ESL 11.5   |       |
| Wed Dec 1<br> | [Convolutional Neural Networks](lectures/L34.pdf)                                                                                                       | [Convolutional Neural Networks](https://en.wikipedia.org/wiki/Convolutional_neural_network)<br>ML:APP 28.4, ESL 11.7   | |
| Fri Dec 3<br> | Bonus lecture | [Semi-Supervised Learning](https://en.wikipedia.org/wiki/Semi-supervised_learning) [Label Propagation at Google](https://ai.googleblog.com/2016/10/graph-powered-machine-learning-at-google.html)<br>[AlexNet](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)  |    |
| Mon Dec 6<br> | Bonus lecture   | [PageRank Slides](http://www.stat.cmu.edu/~ryantibs/datamining/lectures/03-pr.pdf) [PageRank Math/Code](https://uu.diva-portal.org/smash/get/diva2:536076/FULLTEXT01.pdf), ESL 14.10, AI: AMA 22.3<br>[Non-convex](https://arxiv.org/pdf/1309.5549.pdf) [PL Inequality](https://arxiv.org/abs/1608.04636)     | Assignment 6 due      |


