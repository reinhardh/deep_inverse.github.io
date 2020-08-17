# Workshop Summary

Learning-based methods, and in particular deep neural networks, have emerged as highly successful and universal tools for image and signal recovery and restoration. They achieve state-of-the-art results on tasks ranging from image denoising, image compression, and image reconstruction from few and noisy measurements. They are starting to be used in important imaging technologies, for example in GEs newest computational tomography scanners and in the newest generation of the iPhone.

The field has a range of theoretical and practical questions that remain unanswered. In particular, learning and neural network-based approaches often lack the guarantees of traditional physics-based methods. Further, while superior on average, learning-based methods can make drastic reconstruction errors, such as hallucinating a tumor in an MRI reconstruction or turning a pixelated picture of Obama into a white male.

This virtual workshop aims at bringing together theoreticians and practitioners in order to chart out recent advances and discuss new directions in deep neural network-based approaches for solving inverse problems in the imaging sciences and beyond.

<!---
# Schedule

| Time | Event |
| --- | --- |
||Morning session|
| 8:30 - 8:40 | Opening Remarks |
| 8:40 - 9:10 | [Lenka Zdeborova](http://artax.karlin.mff.cuni.cz/~zdebl9am/): *The spiked matrix model with generative priors* |
| 9:10 - 9:40 | [Shuang Qiu, Xiaohan Wei, Zhuoran Yang](): *Robust One-Bit Recovery via ReLU Generative Networks: Improved Statistical Rate and Global Landscape Analysis* |
| 9:40 - 10:30 | Coffee Break |
||Pre-lunch session|
| 10:30 - 11:00 | [Laura Waller](http://www.laurawaller.com/): *Computational microscopy in scattering media* |
| 11:00 - 11:30 | [Mahdi Soltanolkotabi](https://viterbi-web.usc.edu/~soltanol/): *Denoising via Early Stopping* |
| 11:30 - 12:00 | [Stephan Hoyer, Jascha Sohl-Dickstein, Sam Greydanus](): *Neural Reparameterization Improves Structural Optimization* |
| 12:00 - 2:00 | Lunch Break |
||Post-lunch session|
| 2:00 - 2:30 | [Piotr Indyk](https://people.csail.mit.edu/indyk/): *Learning-Based Low-Rank Approximations* |
| 2:30 - 3:00 | [Josh Batson](https://twitter.com/thebasepoint?lang=en): *Blind Denoising, Self-Supervision, and Implicit Inverse Problems* |
| 3:00 - 3:30 | [Venkat Chandrasekaran](http://users.cms.caltech.edu/~venkatc/): *Learning Regularizers from Data* |
| 3:30 - 4:15 | Break and Posters |
||Afternoon session|
| 4:15 - 6:00 | Poster Session | 

# Accepted Papers

- Neural reparameterization improves structural optimization  
*Stephan Hoyer, Jascha Sohl-Dickstein, Sam Greydanus*

- Robust One-Bit Recovery via ReLU Generative Networks: Improved Statistical Rate and Global Landscape Analysis  
*Shuang Qiu, Xiaohan Wei, Zhuoran Yang*

- Extreme Few-view CT Reconstruction using Deep Inference  
*Hyojin Kim, Rushil Anirudh, K. Aditya Mohan, Kyle Champley*

- Improving Limited Angle CT Reconstruction with a Robust GAN Prior  
*Rushil Anirudh, Hyojin Kim, Jayaraman J. Thiagarajan, K. Aditya Mohan, Kyle Champley*

- A Hybrid Architecture for On-Device Compressive Machine Learning  
*Yang Li, Thomas Strohmer*

- Generative Models for Low-Dimensional Video Representation and Compressive Sensing  
*Rakib Hyder, M. Salman Asif*

- PatchDIP Exploiting Patch Redundancy in Deep Image Prior for Denoising  
*Muhammad Asim, Fahad Shamshad, Ali Ahmed*

- Auto-encoders for compressed sensing  
*Pei Peng, Shirin Jalali, Xin Yuan*

- Compressed Sensing and Overparametrized Networks: Overfitting Peaks in a Model of Misparametrized Sparse Regression in the Interpolation Limit  
*Partha P Mitra*

- Lower Bounds for Compressed Sensing with Generative Models  
*Akshay Kamath, Sushrut Karmalkar, Eric Price*

- Y-net: A Physics-constrained and Semi-supervised Learning Approach to the Phase Problem in Computational Electron Imaging  
*Nouamane Laanait, Junqi Yin, Albina Borisevich*

- Unsupervised Deep Basis Pursuit: Learning inverse problems without ground-truth data  
*Jonathan I. Tamir, Stella X. Yu, Michael Lustig*

- AlgoNet: $C^\infty$ Smooth Algorithmic Neural Networks for Solving Inverse Problems  
*Felix Petersen, Christian Borgelt, Oliver Deussen*

- Retrieving Signals with Deep Complex Extractors  
*Chiheb Trabelsi, Olexa Bilaniuk, Ousmane Dia, Ying Zhang, Mirco Ravanelli, Jonathan Binas, Negar Rostamzadeh, Christopher J Pal*

- Unrolled, model-based networks for lensless imaging  
*Kristina Monakhova, Joshua Yurtsever, Grace Kuo, Nick Antipa, Kyrollos Yanny, Laura Waller*

- GAN priors for Bayesian inference  
*Dhruv V. Patel, Assad A. Oberai*

- Learning Network Parameters in the ReLU Model  
*Arya Mazumdar, Ankit Singh Rawat*

- Learned imaging with constraints and uncertainty quantification  
*Felix J. Herrmann, Ali Siahkoohi, Gabrio Rizzuti*

- Generative Inpainting Network Applications on Seismic Image Compression and Non-Uniform Sampling  
*Xiaoyang Rebecca Li, Nikolaos Mitsakos, Ping Lu, Yuan Xiao, Cheng Zhan, Xing Zhao*

- Exploring Properties of the Deep Image Prior  
*Andreas Kattamis, Adrian Weller*

- Learning-Based Low-Rank Approximations  
*Piotr Indyk, Ali Vakilian, Yang Yuan*

- Sample Complexity Lower Bounds for Compressive Sensing with Generative Models  
*Zhaoqiang Liu, Jonathan Scarlett*

- Energy Dissipation with Plug-and-Play Priors  
*Hendrik Sommerhoff, Andreas Kolb, Michael Moeller*

- Precise asymptotics for phase retrieval and compressed sensing with random generative priors  
*Benjamin Aubin, Bruno Loureiro, Antoine Baker, Florent Krzakala, Lenka Zdeborova*

- Learning to Recover Sparse Signals  
*Sichen Zhong, Yue Zhao, Jianshu Chen*

- Subsampled Fourier Ptychography via Pretrained Invertible and Untrained Network Priors  
*Fahad Shamshad, Asif Hanif, Ali Ahmed*

- Learning to Solve Linear Inverse Problems in Imaging with Neumann Networks  
*Davis Gilton, Greg Ongie, Rebecca Willett*

- Robust and interpretable blind image denoising via bias-free convolutional neural networks  
*Zahra Kadkhodaie, Sreyas Mohan, Eero P. Simoncelli, Carlos Fernandez-Granda*

- Phase Retrieval using Untrained Neural Network Priors  
*Gauri Jagatap, Chinmay Hegde* 

- A GAN based solver of black-box inverse problems  
*Michael Gillhofer, Hubert Ramsauer, Johannes Brandstetter, Sepp Hochreiter*

- Co-Generation with GANs using AIS based HMC  
*Tiantian Fang, Alexander G. Schwing*

- Memory-efficient Learning for Large-scale Computational Imaging  
*Michael Kellman, Jon Tamir, Emrah Bostan, Michael Lustig, Laura Waller*

- Gradient-Based Neural DAG Learning  
*Sébastien Lachapelle, Philippe Brouillard, Tristan Deleu, Simon Lacoste-Julien*

- Low Shot Learning with Untrained Neural Networks for Imaging Inverse Problems  
*Oscar Leong, Wesam Sakla*

-->


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

We invite researchers to submit anonymous papers of up to 4 pages (excluding references and appendices) which will be considered for contributed workshop papers. No specific formatting is required. Authors are encouraged to use NeurIPS style file, but they may use any other style as long as it has standard font size (11pt) and margins (1in).

Submission at openreview will soon be open until the until the submission deadline on October 2, 2020.

We welcome all submission in the intersection of inverse problems and deep learning including contributions related to robustness and biases, neural network architectures, regularization, optimization methods, datasets, theoretical foundations (including rigorous recovery guarantees, provable convergence, and bounds on representation errors),  untrained methods, generative models, end-to-end methods, and applications in imaging, time series, and beyond. We especially encourage submissions related to the following questions:

- Deep learning based approaches can make drastic reconstruction errors and may introduce biases. How common are such issues, can such reconstruction difficulties be alleviated, and if yes, how? 

- Deep learning based approaches often lack the guarantees of the traditional physics based methods. What theoretical results are necessary and possible?

- Untrained neural networks such as the deep image prior have shown that neural networks alone, without any learning, can give excellent reconstruction performance. How important is training on the target distribution for imaging performance and is it possible to achieve state-of-the art performance without training?

# Important Dates
- Submission Deadline: October 2th, 2020.
- Notification: October 23st, 2020.
- Workshop: Friday December 11th or Saturday December 12th, 2020.

# Organizers
- [Reinhard Heckel](http://www.reinhardheckel.com/) (TUM)
- [Paul Hand](http://khoury.northeastern.edu/home/hand/) (Northeastern)
- [Richard Baraniuk](http://richb.rice.edu/) (Rice University)
- [Soheil Feizi](https://www.cs.umd.edu/~sfeizi/) (UMD)
- [Lenka Zdeborova](http://artax.karlin.mff.cuni.cz/~zdebl9am/) (CEA/SACLAY)

Please email [deepinverse@gmail.com](mailto:deepinverse@gmail.com) with any questions.
