Repository for the parallelization of the Metropolis-Hastings Markov Chain Monte-Carlo method. 

Parallelization implemented in Python version 3.8 using the native multiprocessing library. 

Code then benchmarked and analyzed to compare results of multiproccessed implementations. 
Loglinear models created using R and Rstudio to further analyze code behavior, and to make predictions of possible timing outcomes. 

Sequential Metropolis-Hastings implementation courtosy of Joseph Moukarzel:
https://gist.github.com/Joseph94m
https://gist.github.com/Joseph94m/00f102e1e838433c1ec21536b3bea003#file-dummy-code-and-mh-py

How to run:
	mcmc_mp.py:
		created with Python version 3.8
		run script in python 3.8

	pmcmc_analysis.r:
		created in Rstudio v 1.2.5
		using R v 3.5.1


System specifications for timing data:
	AMD Ryzen 9 3900x 12-Core Processor 3.79GHz
	16gb ddr4 RAM
	64 bit Windows 10 Professional 
