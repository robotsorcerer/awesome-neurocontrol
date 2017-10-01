# Machine Learning-based Control

A curated list of resources dedicated to theory and applications of machine learning to Control Theory and Engineering (Emphasis on Large Scale Control and Deep Learning)

Maintainers - [Olalekan Ogunmolu](https://ecs.utdallas.edu/~opo140030), Bashir Jafari, [Nick Gans](https://www.utdallas.edu/~ngans), James Davidson

## Table of Contents
- [Papers and Codes](#papers-and-codes)
	- [Continuous Action Reinforcement Learning for Control-Affine Systems with Unknown Dynamics](#faustCont)
	- [Preference-balancing Motion Planning under Stochastic Disturbances](#prefbal)
	-	[Adaptive Human-Inspired Compliant Contact Primitives to Perform Surface-Surface Contact under Uncertainty](#humanContact)
	-	[Learning Potential Functions from Human Demonstrations with Encapsulated Dynamic and Compliant Behaviors](#motionGen)
	-	[Learning Stable Non-Linear Dynamical Systems with Gaussian Mixture Models](#seds)
	-	[Learning Control Lyapunov Function to Ensure Stability of Dynamical System-based Robot Reaching Motions](#clfdm)
	-	[A Dynamical System Approach to Realtime Obstacle Avoidance](#obstAvoid)
	- [FeUdal Networks for Hierarchical Reinforcement Learning](#feudal-networks-for-hierarchical-reinforcement-learning)
	- [Optnet: Differentiable Optimization as a Layer in Neural Networks](#optnet-differentiable-optimization-as-a-layer-in-neural-networks)
	- [qpth: A fast and differentiable Quadratic Programming solver for PyTorch](#qpth-a-fast-and-differentiable-quadratic-programming-solver-for-pytorch)
	- [How hard is it to cross the room? - Training (Recurrent) Neural Networks to steer a UAV](#how-hard-is-it-to-cross-the-room)
	- [Neural Episodic Control](#neural-episodic-control)
	- [Inferring and Executing Programs for Visual Reasoning](#jcjohnson)
	- [Dynamical Systems approach to Learn Robot Motions](#dynamical-robot-motions)
	- [Learning representations by backpropagating errors](#learning-representations-by-backpropagating-errors)

- [Foundational Papers on Modern Machine Learning](#foundational-papers-on-modern-machine-learning)
	- [Course on Information Theory, Pattern Recognition, and Neural Networks](#DavidMackay)
	- [Approximation by Superpositions of a Sigmoidal Function. Approximation Theory and Its Applications](#approximation-by-superpositions-of-a-sigmoidal-function.-approximation-theory-and-its-applications)
	- [On the approximate realization of continuous mappings by neural networks.](#on-the-approximate-realization-of-continuous-mappings-by-neural-networks).
	- [Parallel networks that learn to pronounce English text. Complex Systems](#parallel-networks-that-learn-to-pronounce-english-text.-complex-systems)


<a id="papers-and-codes"></a>
## Papers and Codes
<a id="dynamical-robot-motions)"></a>
*  [Dynamical Systems approach to Learn Robot Motions](http://lasa.epfl.ch/sourcecode/#1)
	* Ecole Polytechnique Federale de Lausanne, LASA Laboratory

<a id="faustCont"></a>
* [Continuous Action Reinforcement Learning for Control-Affine Systems
	with Unknown Dynamics](#http://cs.unm.edu/~afaust/afaustStochPlanIcra15.pdf)
		* Aleksandra Faust
		* Institution Affiliation: University of Minnesota

<a id="prefbal"></a>
* [Preference-balancing Motion Planning under Stochastic Disturbances](#http://cs.unm.edu/~afaust/afaustStochPlanIcra15.pdf)
		* Aleksandra Faust
		* Institution Affiliation: University of Minnesota

<a id="humanContact"></a>
 *	[Adaptive Human-Inspired Compliant Contact Primitives to Perform Surface-Surface Contact under Uncertainty](#http://ijr.sagepub.com/content/early/2016/07/06/0278364916648389)
		* Authors: S.M. Khansari-Zadeh, E. Klingbeil, and O. Khatib (2016)
		* Institution: Stanford
		* Journal: The International Journal of Robotics Research

<a id="motionGen"></a>
 *	[Learning Potential Functions from Human Demonstrations with Encapsulated Dynamic and Compliant Behaviors](#http://link.springer.com/article/10.1007%2Fs10514-015-9528-y)
		* Authors: S.M. Khansari-Zadeh and O. Khatib (2015)
		* Institution: Stanford
		* Journal: Autonomous Robots.

<a id="seds"></a>
 *	[Learning Stable Non-Linear Dynamical Systems with Gaussian Mixture Models](#http://infoscience.epfl.ch/record/166322/files/Khansari_Billard_TRO11_1.pdf)
	* Institution: Stanford
	* Authors: S.M. Khansari-Zadeh and A. Billard (2011), L,
	* Journal: IEEE Transaction on Robotics, vol. 27, num 5, p. 943-957.

<a id="clfdm"></a>
 *	[Learning Control Lyapunov Function to Ensure Stability of Dynamical System-based Robot Reaching Motions](#http://lasa.epfl.ch/publications/uploadedFiles/Khansari_Billard_RAS2014.pdf)
		* Institution: Stanford
		* Authors: S.M. Khansari-Zadeh and A. Billard (2014),
		* Journal: Robotics and Autonomous Systems, vol. 62, num 6, p. 752-765.

<a id="obstAvoid"></a>
 * 	[A Dynamical System Approach to Realtime Obstacle Avoidance](#http://lasa.epfl.ch/publications/uploadedFiles/Khansari_Billard_AR12.pdf)
		* Authors: S.M. Khansari-Zadeh and A. Billard (2012),
		* Journal: Autonomous Robots, vol. 32, num 4, p. 433-454.

<a id="feudal-networks-for-hierarchical-reinforcement-learning"></a>
* [FeUdal Networks for Hierarchical Reinforcement Learning](https://arxiv.org/abs/1703.01161)
	* Authors: Alexander Sasha Vezhnevets, Simon Osindero, Tom Schaul, Nicolas Heess, Max Jaderberg, David Silver, Koray Kavukcuoglu
	* Institution: Google

<a id="optnet-differentiable-optimization-as-a-layer-in-neural-networks"></a>
* [Optnet: Differentiable Optimization as a Layer in Neural Networks](https://arxiv.org/abs/1703.00443)
	* [Code](https://github.com/locuslab/optnet)
	* Authors:  Brandon Amos and J. Zico Kolter. (3/2017).
	* Institution Affiliation: CMU

* [Primal-Dual Interior Methods](http://www.seas.ucla.edu/~vandenbe/ee236a/lectures/mpc.pdf)
	* Vanderberghe, UCLA

<a name="qpth-a-fast-and-differentiable-quadratic-programming-solver-for-pytorch"></a>
* [qpth: A fast and differentiable Quadratic Programming solver for PyTorch](https://github.com/locuslab/qpth)
	* [Code](https://github.com/locuslab/qpth)
	* Authors:  Brandon Amos and J. Zico Kolter. (3/2017).
	* Institution Affiliation: CMU

<a name="how-hard-is-it-to-cross-the-room"></a>
* [How hard is it to cross the room? - Training (Recurrent) Neural Networks to steer a UAV](https://arxiv.org/pdf/1702.07600.pdf)
	* Authors: Klaas Kelchtermans and Tinne Tuytelaars. (3/2017).
	* Institution Affiliation: KU Leuven

<a id="neural-episodic-control"></a>
* [Neural Episodic Control](https://arxiv.org/abs/1703.01988)
	* Authors: Alexander Pritzel, Benigno Uria, Sriram Srinivasan, Adrià Puigdomènech, Oriol Vinyals, Demis Hassabis, Daan Wierstra, Charles Blundell
	* Google/DeepMind

<a id="jcjohnson"></a>
*	[Inferring and Executing Programs for Visual Reasoning](https://arxiv.org/abs/1705.03633)
	* Authors: Justin C. Johnson, Bharath Hariharan, Laurens van der Maaten, Judy Hoffman, Li Fei-Fei, C. Lawrence Zitnick, Ross Girshick

### Foundational Papers on Modern Machine Learning
<a id="DavidMackay"></a>
* [Course on Information Theory, Pattern Recognition, and Neural Networks](http://videolectures.net/mackay_course_16/)
	* Author: Sir David MacKay
	* Institution Affiliation: University of Cambridge

<a id="approximation-by-superpositions-of-a-sigmoidal-function.-approximation-theory-and-its-applications"></a>
* [Approximation by Superpositions of a Sigmoidal Function. Approximation Theory and Its Applications](http://deeplearning.cs.cmu.edu/pdfs/Cybenko.pdf)
	* Author: Cybenko, G. (1993).
	* Institution Affiliation: University of Illinois

<a id="on-the-approximate-realization-of-continuous-mappings-by-neural-networks"></a>
* [On the approximate realization of continuous mappings by neural networks.](http://www.sciencedirect.com/science/article/pii/0893608089900038)
	* Author: Ken-Ichi Funahashi, 5/1988
	* Institution Affiliation: CMU

<a id="parallel-networks-that-learn-to-pronounce-english-text.-complex-systems"></a>
* [Parallel networks that learn to pronounce English text. Complex Systems](http://cs.union.edu/~rieffelj/classes/2011-12/csc320/readings/Sejnowski-speech-1987.pdf)
	* Sejnowski, T. J., & Rosenberg, C. R. (1987).
	* Institution Affiliation: Johns Hopkins University/Princeton University

<a id="parallel-networks-that-learn-to-pronounce-english-text.-complex-systems"></a>
* [Learning representations by backpropagating errors](http://www.iro.umontreal.ca/~vincentp/ift3395/lectures/backprop_old.pdf).
	* Rumelhart, D. E., & Hinton, G. E. (1986).
	* Institution Affiliation: UToronto
