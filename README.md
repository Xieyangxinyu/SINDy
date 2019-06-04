# Alone the SINDy Frontier

## SAMSI Undergraduate Modeling Workshop, May 2019

### Dr. John Nardini, Allison Duprey, Fanuel Sisay, Natasha Stewart, and Yangxinyu Xie

Goal
-----------------------------------------------------------------------------------------
This study investigates the integration of Lasso into the SINDy algorithm and make comparison with Ridge. In this study, we make inferences on the differential equation of the logistic time series

<p align="center"><img src="https://rawgit.com/Xieyangxinyu/SINDy/master/svgs/f155d18cc82673c19e4763093e636d6f.svg?invert_in_darkmode" align=middle width=221.60527125pt height=37.72265145pt/></p>

Mathematical Background
-----------------------------------------------------------------------------------------
For an introduction of subset selection and shrinkage method, we recommend a brief overview [Yangxinyu's Notes on Regression] or a more thorough discussion in [Chapter 3, Hastie, Tibshirani and Friedman (2009)].

For the details of SINDy algorithm, we refer the reader to [Brunton, Proctor, and Kutz (2016)] and [Mangan, Kutz, Brunton and Proctor (2017)].

For the algorithm of Relaxed Lasso, we refer the reader to [Meinshausen (2007)]

Results & Discussion
-----------------------------------------------------------------------------------------
From our experiments, we see that fast-converging Lasso shows an advantage of lower time complexity. We also studied some relationship between the model performance/accuracy noise, data quality as well as starting library. For full results and discussion, please view [Duprey, Sisay, Stewart, and Xie (2019)].

Acknowledgement
-----------------------------------------------------------------------------------------
Many thanks to SAMSI for organizing this workshop, special thanks to Thomas Gehrmann, Dr. Mansoor Haider and Dr. David Banks.

Many thanks to SAMSI workshop mentors and especially our project mentor Dr. John Nardini.

References
-----------------------------------------------------------------------------------------
  - Brunton, S. L., Proctor, J. L., & Kutz, J. N. (2016). Discovering governing equations from data by sparse identification of nonlinear dynamical systems. Proceedings of the National Academy of Sciences, 113(15), 3932-3937.
  - Boyd, S. P., & Vandenberghe, L. (2018). Convex optimization. Meinshausen, N. (2007). Relaxed lasso. Computational Statistics & Data Analysis, 52(1), 374-393.
  - Hastie, T., Tibshirani, R., & Friedman, J. (2009). The elements of statistical learning: Data mining, inference, and prediction (Second ed.). New York, NY: Springer New York. doi:10.1007/978-0-387-84858-7
  - Kutner, M. H. (2005). Applied linear statistical models (5th ed.). Boston: McGraw-Hill Irwin.
  - Mangan, N., Brunton, S., Proctor, J. and Kutz, J. (2016). Inferring Biological Networks by Sparse Identification of Nonlinear Dynamics. IEEE Transactions on Molecular, Biological and Multi-Scale Communications, 2(1), pp.52-63.
  - Mangan, N. M., Kutz, J. N., Brunton, S. L., & Proctor, J. L. (2017). Model selection for dynamical systems via sparse regression and information criteria. Proceedings of the Royal Society A: Mathematical, Physical and Engineering Sciences, 473(2204), 20170009.
  - Scikit-Learn: Machine learning in Python - scikit-learn 0.16.1 documentation. Retrieved from https://scikit-learn.org/
  
   [Yangxinyu's Notes on Regression]: <https://github.com/Xieyangxinyu/Xieyangxinyu.github.io/raw/master/File/Notes\%20on\%20Regression.pdf}{Notes on Regression>
   [Chapter 3, Hastie, Tibshirani and Friedman (2009)]: <https://web.stanford.edu/~hastie/ElemStatLearn/>
   [Brunton, Proctor, and Kutz (2016)]: <https://www.pnas.org/content/113/15/3932>
   [Mangan, Kutz, Brunton and Proctor (2017)]: <https://arxiv.org/abs/1701.01773>
   [Meinshausen (2007)]: <https://www.sciencedirect.com/science/article/pii/S0167947306004956>
   [Duprey, Sisay, Stewart, and Xie (2019)]: <https://github.com/Xieyangxinyu/SINDy/blob/master/ODE_Sampling_Group_Final%20Presentation.pdf>
