# Workshop Summary

There is a long history of algorithmic development for solving inverse problems arising in sensing and imaging systems and beyond. Examples include medical and computational imaging, compressive sensing, as well as community detection in networks. Until recently, most algorithms for solving inverse problems in the imaging and network sciences were based on static signal models derived from physics or intuition, such as wavelets or sparse representations.

Today, the best performing approaches for the aforementioned image reconstruction and sensing problems are based on deep learning, which learn various elements of the method including i) signal representations,  ii) stepsizes and parameters of iterative algorithms, iii) regularizers, and iv) entire inverse functions. For example, it has recently been shown that solving a variety of inverse problems by transforming an iterative, physics-based algorithm into a deep network whose parameters can be learned from training data, offers faster convergence and/or a better quality solution. Moreover, even with very little or no learning, deep neural networks enable superior performance for classical linear inverse problems such as denoising and compressive sensing. Motivated by those success stories, researchers are redesigning traditional imaging and sensing systems. 

However, the field is mostly wide open with a range of theoretical and practical questions unanswered. In particular, deep-neural network based approaches often lack the guarantees of the traditional physics based methods, and while typically superior can make drastic reconstruction errors, such as fantasizing a tumor in an MRI reconstruction.

This workshop aims at bringing together theoreticians and practitioners in order to chart out recent advances and discuss new directions in deep neural network based approaches for solving inverse problems in the imaging and network sciences.


# Schedule

| Time | Event |
| --- | --- |
||Morning session|
| 8:30 - 8:40 | Opening Remarks |
| 8:40 - 9:10 | [Lenka Zdeborova](http://artax.karlin.mff.cuni.cz/~zdebl9am/): *The spiked matrix model with generative priors * |
| 9:10 - 9:40 | Qiu, Wei, Yang: *Robust One-Bit Recovery via ReLU Generative Networks: Improved Statistical Rate and Global Landscape Analysis* |
| 9:40 - 10:30 | Coffee Break |
||Pre-lunch session|
| 10:30 - 11:00 | [Laura Waller](http://www.laurawaller.com/): *Computational microscopy in scattering media* |
| 11:00 - 11:30 | [Guillermo Sapiro](https://ece.duke.edu/faculty/guillermo-sapiro): *Basis Decomposition of Deep Learning* |
| 11:30 - 12:00 | Hoyer, Sohl-Dickstein, Greydanus: 	Neural Reparameterization Improves Structural Optimization|
| 12:00 - 2:00 | Lunch Break |
||Post-lunch session|
| 2:00 - 2:30 | [Raquel Urtasun](http://www.cs.toronto.edu/~urtasun/) |
| 2:30 - 3:00 | [Josh Batson](https://twitter.com/thebasepoint?lang=en): *Blind Denoising, Self-Supervision, and Implicit Inverse Problems* |
| 3:00 - 3:30 | [Venkat Chandrasekaran](http://users.cms.caltech.edu/~venkatc/): *Learning Regularizers from Data* |
| 3:30 - 4:15 | Break and Posters |
||Afternoon session|
| 4:15 - 6:00 | Poster Session | 


<!---
# Confirmed Speakers

- [Guillermo Sapiro](https://ece.duke.edu/faculty/guillermo-sapiro) (Duke)
- [Lenka Zdeborova](http://artax.karlin.mff.cuni.cz/~zdebl9am/) (CEA Saclay)
- [Laura Waller](http://www.laurawaller.com/) (UC Berkeley)
- [Michael Unser](http://bigwww.epfl.ch/unser/) (EPFL)
- [Raquel Urtasun](http://www.cs.toronto.edu/~urtasun/) (University of Toronto)
- [Josh Batson](https://twitter.com/thebasepoint?lang=en) (Chan-Zuckerberg Biohub)
- [Venkat Chandrasekaran](http://users.cms.caltech.edu/~venkatc/) (Caltech)
-->


# Call for Papers and Submission Instructions
We invite researchers to submit anonymous extended abstracts of up to 4 pages (excluding references) which will be considered for contributed talks and posters. No specific formatting is required. Authors may use the NeurIPS style file, or any other style as long as it has standard font size (11pt) and margins (1in).

Submission at [openreview](https://openreview.net/group?id=NeurIPS.cc/2019/Workshop/Deep_Inverse) open now until the submission deadline on ~~September 9~~ September 13.

We invite works on inverse problems in the imaging sciences and new developments in non-Euclidean domains such as graphs, including contributions on the development of new architectures for natural signal priors (for examples GANs, non adversarially trained generators, unlearned neural networks, and combinations thereof), theoretical foundations (including rigorous recovery guarantees, provable convergence, and bounds on representation errors), and applications in imaging and beyond. We especially encourage submissions in the following areas:

- **Learned generative models for solving inverse problems:** Recent years have seen great advances in generative modeling for a variety of signals, in particular images. The corresponding priors, when enforced in reconstruction algorithms, enable lower sample complexity and higher robustness to noise than conventional approaches. In this workshop, we discuss progress and research directions in generative models for finding solutions to inverse problems efficiently and accurately.

- **Un-trained models for solving inverse problems:** Even without any learning, deep neural networks have been shown to be effective models through the so-called deep image priors, suggesting that deep neural networks are inherently good at representing natural images or more generally, signals. In this workshop, we will discuss progress and research directions in the understanding of the inductive bias brought by deep architectures and by gradient-descent optimization.

- **Learning to solve inverse problems end-to-end:** Neural networks applied to inverse problems yield impressive results. Trained on large amounts of training data they are often able to run faster and yield more accurate results than existing methods. However, those advances come at the cost of a lack of recovery guarantees, require large amounts of training data, and can sometimes lead to undesirable behaviour, such as hypothesizing parts of an image from training data. We encourage contributions on methods and algorithms for learning to solve inverse problems and contributions that explore application scenarios, for example in computational imaging.

- **Inverse problems beyond Euclidean data:** Deep networks are emerging as a powerful tool to solve inverse problems on data with an underlying graph or manifold structure such as social networks  or surfaces in computer graphics. We highly welcome contributions on solving inverse problems in geometric deep learning.

# Important Dates
- Submission Deadline: ~~September 9th~~ Extended until September 13th, 2019.
- Notification: October 1st, 2019
- Workshop: Friday, December 13, 2019.

# Organizers
- [Reinhard Heckel](http://www.reinhardheckel.com/) (TUM)
- [Paul Hand](http://khoury.northeastern.edu/home/hand/) (Northeastern)
- [Richard Baraniuk](http://richb.rice.edu/) (Rice University)
- [Joan Bruna](https://cims.nyu.edu/~bruna/) (NYU)
- [Alex Dimakis](https://users.ece.utexas.edu/~dimakis/) (UT Austin)
- [Deanna Needell](https://www.math.ucla.edu/~deanna/) (UCLA)

Please email [neurips2019inverse@gmail.com](mailto:neurips2019inverse@gmail.com) with any questions.
