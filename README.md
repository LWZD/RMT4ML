# RMT4ML
This repository contains [`MATLAB`](https://www.mathworks.com/products/matlab.html) and [`Python`](https://www.python.org/) codes for visualizing random matrix theory results and their applications to machine learning, in [Random Matrix Theory for Machine Learning](https://zhenyu-liao.github.io/pdf/RMT4ML.pdf).

In each subfolder (named after the corresponding section) there are:

* a `.html` file containing the [`MATLAB`](https://www.mathworks.com/products/matlab.html) or [IPython Notebook](https://ipython.org/notebook.html) demos
* a `.m` or `.ipynb` source file

* Chapter 1 Introduction
* Chapter 2 Random Matrix Theory
	* Section 2.1 Fundamental objects
	* Section 2.2 Foundational random matrix results
		* Section 2.2.1 Key lemma and identities: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.2/html/lemma_plots.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.2/lemma_plots.ipynb)
		* Section 2.2.2 The Marcenko-Pastur and semicircle laws: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.2/html/MP_and_SC.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.2/MP_and_SC.ipynb)
		* Section 2.2.3 Large sample covariance matrices and generalized semicircles: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.2/html/SCM_and_DSC.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.2/SCM_and_DSC.ipynb)
	* Section 2.3 Advanced spectrum considerations for sample covariances: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.3/html/advanced_spectrum.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.3/advanced_spectrum.ipynb)
	* Section 2.4 Preliminaries on statistical inference
		* Section 2.4.1 Linear eigenvalue statistics: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.4/html/linear_eig_stats.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.4/linear_eig_stats.ipynb)
		* Section 2.4.2 Eigenvector projections and subspace methods: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.4/html/eigenvec_proj.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.4/eigenvec_proj.ipynb)
	* Section 2.5 Spiked model: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/2.5/html/spiked_models.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/2.5/spiked_models.ipynb)
	* Section 2.6 Information-plus-noise, deformed Wigner, and other models
	* Section 2.7 Beyond vectors of independent entries: concentration of measure in RMT
	* Section 2.8 Concluding remarks
	* Section 2.9 Exercises
* Chapter 3 Statistical Inference in Linear Models
	* Section 3.1 Detection and estimation in information-plus-noise models
		* Section 3.1.1 GLRT asymptotics: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.1/html/GLRT.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.1/GLRT.ipynb)
		* Section 3.1.2 Linear and Quadratic Discriminant Analysis: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.1/html/LDA.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.1/LDA.ipynb)
		* Section 3.1.1 Subspace methods: the G-MUSIC algorithm: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.1/html/GMUSIC.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.1/GMUSIC.ipynb)
	* Section 3.2 Covariance matrix distance estimation: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.2/html/cov_distance_estimation.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.2/cov_distance_estimation.ipynb)
	* Section 3.3 M-estimator of scatter: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.3/html/M_estim_of_scatter.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.3/M_estim_of_scatter.ipynb)
	* Section 3.4 Concluding remarks
	* Section 3.5 Practical course material: 
		* The Wasserstein distance estimation: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.5/html/Wasserstein_dist.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.5/Wasserstein_dist.ipynb)
		* Robust portfolio optimization via Tyler estimator: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/3.5/html/robust_portfolio.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/3.5/robust_portfolio.ipynb)
* Chapter 4 Kernel Methods
	* Section 4.1 Basic setting
	* Section 4.2 Distance and inner-product random kernel matrices
		* Section 4.2.1 Main intuitions 
		* Section 4.2.2 Main results: distance random kernel matrices: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.2/html/dist_kernel.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.2/dist_kernel.ipynb)
		* Section 4.2.3 Motivations: alpha-beta random kernel matrices 
		* Section 4.2.4 Main results: alpha-beta random kernel matrices: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.2/html/alpha_beta_kernel.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.2/alpha_beta_kernel.ipynb)
	* Section 4.3 Properly scaling kernel model: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.3/html/proper_scale_kernel.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.3/proper_scale_kernel.ipynb)
	* Section 4.4 Implications to kernel methods
		* Section 4.4.1 Application to kernel spectral clustering: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.4/html/kernel_spectral_clustering.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.4/kernel_spectral_clustering.ipynb)
		* Section 4.4.2 Application to semi-supervised kernel learning: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.4/html/semi_supervised_kernel.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.4/semi_supervised_kernel.ipynb)
		* Section 4.4.3 Application to kernel ridge regression: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.4/html/kernel_ridge.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.4/kernel_ridge.ipynb)
		* Section 4.4.4 Summary of Section 4.4
	* Section 4.5 Concluding remarks
	* Section 4.6 Practical course material
		* Complexity-performance trade-off in spectral clustering with sparse kernel: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.6/html/sparse_clustering.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.6/sparse_clustering.ipynb)
		* Towards transfer learning with kernel regression: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/4.6/html/transfer.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/4.6/transfer.ipynb)
* Chapter 5 Large Neural Networks
	* Section 5.1 Random neural networks
		* Section 5.1.1 Regression with random neural networks: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/5.1/html/random_NN.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/5.1/random_NN.ipynb)
		* Section 5.1.2 Delving deeper into limiting kernels: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/5.1/html/random_feature_GMM.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/5.1/random_feature_GMM.ipynb)
	* Section 5.2 Gradient descent dynamics in learning linear neural nets: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/5.2/html/grad_descent_dynamics.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/5.2/grad_descent_dynamics.ipynb)
	* Section 5.3 Recurrent neural nets: echo-state networks: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/5.3/html/ESN.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/5.3/ENS.ipynb)
	* Section 5.4 Concluding remarks
	* Section 5.5 Practical course material: performance of large dimensional random Fourier features: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/5.5/html/random_Fourier.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/5.5/html/random_Fourier.ipynb)
* Chapter 6 Large Dimensional Convex Optimization
	* Section 6.1 Generalized linear classifier: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/6.1/html/empirical_risk_min.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/6.1/empirical_risk_min.ipynb)
	* Section 6.2 Large dimensional support vector machines
	* Section 6.3 Concluding remarks
	* Section 6.4 Practical course material: phase retrieval: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/6.4/html/phase_retrieval.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/6.4/phase_retrieval.ipynb)
* Chapter 7 Community Detection on Graphs
	* Section 7.1 Community detection in dense graphs
		* Section 7.1.1 The stochastic block model: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/7.1/html/SBM.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/7.1/SBM.ipynb)
		* Section 7.1.2 The degree-correlated stochastic block model: 
		[Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/7.1/html/DCSBM.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/7.1/DCSBM.ipynb)
	* Section 7.2 From dense to sparse graphs: a different approach:
	[Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/7.2/html/sparse_graph.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/7.2/sparse_graph.ipynb)
	* Section 7.3 Concluding remarks
	* Section 7.4 Practical course material: asymptotic Gaussian fluctuations of the SBM dominant eigenvector
* Chapter 8 Universality and Real Data: [Matlab code](https://htmlpreview.github.io/?https://github.com/Zhenyu-LIAO/RMT4ML/blob/master/8/html/RMT_universality.html) and [Python code](https://nbviewer.jupyter.org/github/Zhenyu-LIAO/RMT4ML/blob/master/8/RMT_universality.ipynb)