### PhD Projects

#### Neural Networks can learn how Bacteria move and coordinate  
Chemotaxis is the ability of bacteria to direct multicellular motion along chemical gradients [1]. This phenomenon is central to environmental, medical and agricultural processes. For this project, I trained Neural Networks that *learn* Chemotactic PDEs, and when integrated, can reproduce and predict bacterial density profiles. This has been done in the following cases:
  * Black-box PDE models
  * Gray-box PDE models (Closures)
  * Partial information - second order models  
  
And with many kinds of datasets:
  * Data from PDE simulations 
  * Data from Monte-Carlo simulations (agent-based model)
  * Sparse, Noisy experimental data

<img src="NNPDE1.gif" width="400"/>

**Fig.1** : The Data-driven PDE is able to reproduce the bacteria density profiles beyond the training set and predict new trajectories. 

<img src="1.PNG" width="400"/>

**Fig.2** : Data-driven PDEs can be trained on experimental data. Here the Neural Network 'learns' and reproduces what is seen in the microscope. 


[1]  [Bhattacharjee et al., 2020](https://www.sciencedirect.com/science/article/pii/S0006349521004276)

#### Programming Dynamic Catalysts with Bayesian Optimization
Improved catalytic performance can lead to breakthroughs in sustainability, such as low-cost solar and wind power. However, catalysts are naturally limited by the [Sabatier principle](https://en.wikipedia.org/wiki/Sabatier_principle). By imposing a (appropriately tuned) electrodynamic oscillation on the surface, the Sabatier principle can be overcome. I used **advanced numerical methods** and **machine learning** to tune such catalysts. Improved catalytic performance can have significant impact on **sustainability**, sustainabilsuch as low-cost solar and wind power [2].
 * Root-finding accelerated by up to 150% using the a Variational Approach.
 * Pseudo-arclength continuation used to explore the parameter space.
 * Bayesian Optimization emloyed to optimize reactor performance/reaction rates.

<img src="dyncat.gif" width="200"/>

**Fig.3** : Dynamic Catalysts act like a molecular 'pump' overcoming the limitations of static catalysis.

https://user-images.githubusercontent.com/19255413/149025012-5646acd7-e3b4-4f45-adb3-63bdcaa6945e.mov



**Fig.4** : Bayesian Optimization 'sculpts' a complex forcing function to optimize the reactor's performance. 

[2] [Ardagh et al., 2020](https://pubs.rsc.org/en/content/articlelanding/2020/sc/c9sc06140a)


* Bayesian Continuation for Bayesian Optimization

A research 'by-product' of Dynamic Catalysis: Initializing Black-box simulations using Machine Learning surrogate models. 

* Investigating the response of Circadian Rhythmicity to drugs


* Directed Graph Embeddings
* Neural Network Pathologies
* Machine Learning for PDEs with Complex Geometries






