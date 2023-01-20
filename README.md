# Coordinate Descent (CD)

This is a (actively updated) paper list of **Coordinate Descent (CD)**, aka *Alternative Optimization*, which has an interesting relationship with *Expectation Maximization* (from an optimization viewpoint).

Note that sometimes CD is named as *coordinatewise minimization*/*coordinate relaxation* and **Block Coordinate Descent (BCD)** is a generalization of CD, which is suitable for parallelized and distributed computing.

* Hildreth, C., 1957. A quadratic programming procedure. Naval Research Logistics Quarterly, 4(1), pp.79-85. [ [Notes](https://onlinelibrary.wiley.com/doi/10.1002/nav.3800040410) from the original author for an erratum ]
  * "One could look for the most effective one, that one which maximizes the gradient (w.r.t. one component), at each stage".
  * "Another modification that might be worth considering would be to draw random numbers at each stage to determine the sequence in which the elementary operators would be applied."
  * Hildreth, C., 1954. Point estimates of ordinates of concave functions. Journal of the American Statistical Association, 49(267), pp.598-619.
  * Freund, R.J., 1956. The introduction of risk into a programming model. Econometrica: Journal of the Econometric Society, pp.253-263.
* d'Esopo, D.A., 1959. A convex programming procedure. Naval Research Logistics Quarterly, 6(1), pp.33-42. [ Stanford Research Institue ]
  * "Coordinate minimization transformation"
* Zadeh, N., 1970. Note—A note on the cyclic coordinate ascent Method. Management Science, 16(9), pp.642-644. [ University of California, Berkeley ]
* Powell, M.J., 1973. On search directions for minimization algorithms. Mathematical Programming, 4(1), pp.193-201. [ Atomic Energy Research Establishment ]
* Luo, Z.Q. and Tseng, P., 1992. On the convergence of the coordinate descent method for convex differentiable minimization. Journal of Optimization Theory and Applications, 72(1), pp.7-35. [ McMaster University + Massachusetts Institute of Technology ]
* Tseng, P. and Yun, S., 2009. A coordinate gradient descent method for nonsmooth separable minimization. Mathematical Programming, 117(1), pp.387-423. [ University of Washington ]
* Nesterov, Y., 2012. Efficiency of coordinate descent methods on huge-scale optimization problems. SIAM Journal on Optimization, 22(2), pp.341-362.
  * "The main advantage of these methods is the simplicity of each iteration, both in generating the search direction and in performing the update of variables. However, very soon it became clear that the coordinate descent methods can be criticized in several aspects."
* Shi, H.J.M., Tu, S., Xu, Y. and Yin, W., 2016. A primer on coordinate descent algorithms. arXiv preprint arXiv:1610.00040. [ Northwestern University + University of California, Los Angeles ]
* Richtárik, P. and Takáč, M., 2016. Distributed coordinate descent method for learning with big data. Journal of Machine Learning Research, 17(1), pp.2657-2681. [ University of Edinburgh + Lehigh University ]

******* *** *******

* Moré, J.J., Garbow, B.S. and Hillstrom, K.E., 1981. Testing unconstrained optimization software. ACM Transactions on Mathematical Software, 7(1), pp.17-41.
  * "Almost all of the test functions have appeared in the optimization literature are nonlinear least squares."
