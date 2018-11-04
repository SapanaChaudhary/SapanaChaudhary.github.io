---
title: "Projects"
permalink: /portfolio/
author_profile: true
---  

## Reinforcement Learning

<details>
<summary>Smoother Imitation with Lipschitz Costs</summary>

<ul>
  <li>With Akshat Dave, Balaraman Ravindran</li>
  <li>Accepted for Poster Presentation at NIPS DRL Symposium 2017</li>
  <li>Generative Adversarial Imitation Learning (GAIL) presents a specific approach to the task of imitating an expert by jointly modelling the environment’s reinforcement signal and the imitating agent’s policy. GAIL provides state-of-the-art results in imitating complex behaviours in large, high dimensional environments. However, the algorithm often suffers from instability during the training and high variance in the returns and the trajectories. In this work, we propose a GAIL-like framework for learning smoother imitation and achieving consistently meaningful learning gradients. The learned policyachieves better performance than the existing methods in terms of closeness to the expert trajectories and the value of the true returns. We propose metrics to evaluate for the better imitation of the expert and the smoothness of the learned policies. We empirically evaluate the algorithm on simulated continuous control tasks from MuJoCo.</li>
</ul>
</details>

<details>
<summary>On the Analysis of Lipschitz Smoothness of Costs for Learning Smooth Policies</summary>

<ul>
  <li>With Akshat Dave, Balaraman Ravindran</li>
  <li>In continuous control using Reinforcement Learning (RL), learning a smooth policy is
crucial and the cost function plays an important role in deciding the quality of the
learned policy. In this work, we formalize the idea that a smooth cost function results in
learning a smooth policy. We discuss the smoothness of the policy with respect to the
inputs, unlike the previous works where it has been discussed with respect to the
parameters. Through a simple 2D continuous control task, we demonstrate how
Lipschitz continuous cost leads to learning a smooth policy. Further, for the task of
imitation learning, we propose a way to enforce Lipschitz smoothness on the modelled
cost. We demonstrate how our proposed framework outperforms the state-of-the-art, in
terms of not only smoothness of the policy but also in achieving better imitation. We
introduce novel metrics, using policy Jacobians, to assess the smoothness of the
learned policies.</li>
</ul>  
</details>

<details>
<summary>Variance Reduction in Policy Gradients through Smooth Costs</summary>  

<ul>
  <li>Advised Vaibhav Nayel, with Balaraman Ravindran</li>
  <li>In reinforcement learning (RL), the standard likelihood ratio policy gradients suffer from high variance, and have no generalization property. Variance reduction of the policy gradients can be achieved by either discounting the rewards or function approximating the Q-value function. In RL, the reward function is fixed. So, agent goes with the assumption that the designed reward function suits the environment/application the best, and estimate the above mentioned Q- values. However, for the tasks like imitation learning (IL) using inverse reinforcement learning (IRL), the reward function is estimated from the expert demonstrations. For high dimensional tasks, no assumption is made on the form of the reward function (like rewards being linear combination of feature vectors), and neural networks are used to model the non-linear rewards. The modelling of reward function in this manner can itself induce a lot of variance in the policy gradient estimates. So, the question considered in this work is: ‘Does having a smooth reward function lead to a significant reduction of variance in policy gradient estimates in imitation learning?’. 
</li>
</ul>  

</details>

<details>
<summary>Learning Domain-Invariant Policies in RL</summary>

<ul>
  <li>Advised Nived Narayanan, with Balaraman Ravindran</li>
  <li>The main idea of the work is to obtain an agent policy, through imitation learning, that performs well not just in the domain from which expert demonstrations came, but also in other similar domains. The domain invariant imitation is achieved by first learning the domain invariant features and using Generative Adversarial Imitation Learning on top of these to obtain the agent policy. The experiments are run in TORCS. </li>
</ul>  

</details>
-----------------------------------------------------------------------------------

## Optimization

<details>
<summary>Analyzing and Quantifying Missing Modes in GANs</summary>

<ul>
  <li>With Rahul Vallivel, Mitesh Khapra, Balaraman Ravindran</li>
  <li>In this work, we analyse various issues with the Generative Adversarial Network (GAN)
  architecture, training, the loss function and the training algorithm. We run an
  exploratory set of experiments on mixture of Gaussians, MNIST and CelebA to
  understand what goes wrong and why. We concentrate specifically on the problem of
  missing modes in generative densities modelled by GANs. We observe that a difference
  in loss function of GANs leads to
    <ul>
      <li>Different learning rates that need to be used for model training</li>
      <li>Difference in the amount of true distribution that can be recovered</li>
      <li>We also run experiments to measure input covariate shift in GANs, using gradient
    of the discriminator with respect to the inputs to quantify the same</li>
    </ul>
  </li>
</ul>  
</details>

<details>
<summary>Localization in Cellular Networks</summary> 

<ul>
  <li> With Radha Krishna Ganti </li>
  <li> The problem of mobile user localization in wireless cellular networks has received
considerable attention in the cellular communications community. This is mainly because
localization finds applications in commercial services and network optimization, to name
a few . Before we go on to describe the localization problem, let us quickly introduce
what cellular networks are. Our main contributions in this part of the work are as follows : 
    <ul> 
      <li> We briefly discuss the effect of non-line-of-sight (NLOS) on the localization procedure, and leave inclusion of NLOS in our set of algorithms as a future work.</li>
      <li> We first understand the nature of the problem by studying Maximum Likelihood Estimate
(MLE) formulation of the problem. Formulated this way, the problem of localization
in wireless cellular networks, is a clear inverse problem. We first observe that the loss
surface of MLE objective is indeed non-convex, making the optimization procedure diffi-
cult. We then look at how the problem can be converted into a convex problem, through
semi-definite program (SDP) relaxation. We note that the different SDP relaxations act
as different regularizations to the problem and result in different solutions.
We then go on to compare the performance of non-convex optimization of the MLE
objective using two optimization algorithms : Levenberg Marquardt and trust region
optimization.</li>
      <li>We also exploit the geometry of the problem to obtain faster algorithms.</li>
   </li>
</ul>  

</details>

<details>
<summary>Spectrum Cartography using Wireless Cellular Data</summary>

<ul>
  <li> With Radha Krishna Ganti</li>
  <li> Project Page: <a href="https://sapanachaudhary.github.io/Power-Spectrum-Cartography/" style="color: #FA8072"> Power Spectrum Cartography</a></li>
  <li> Power Spectrum cartography is the process of contructing
a map showing received signal strength over a given geographical area. RSSI data is extracted from the raw GSM data. We then use an empirical model of the environment to first localize users roughly. Next, we use an interpolation technique
on RSSI along with localized locations to obtain the spectrum cartographical maps. To perform this task, we had to start with raw physical layer data provided by Bharat
Sanchar Nigam Limited (BSNL). </li>
</ul>  

</details>

<details>
<summary>James-Stein Estimator</summary>

<ul>
  <li>With Vaishnavi Adella, Sai Charan Thoutam</li>
  <li>Project Page: <a href="https://sapanachaudhary.github.io/Biased-Estimation-for-Channel-Estimation/" style="color: #FA8072">Biased Estimator for Channel Estimation</a></li>
  <li>Studied JS-Estimator to perform biased estimation for orthogonal frequency division
multiplexing in the Wireless Communications course.</li>
</ul>  
</details>

<details>
<summary>Report on 'Constrained convex minimization via model based excessive gap'</summary>
<ul>
  <li> </li>
  <li> </li>
</ul>  


As a part of Term Paper Presentation in the course on Algorithms for Convex Optimization,
reviewed paper on ”Constrained convex minimization via model-based excessive gap (NIPS
2014)”

</details>

<details>
<summary>Natural Gradient Descent for Neural Networks</summary>

<ul>
  <li> Project Page: <a href="https://sapanachaudhary.github.io/On-Natural-Gradients/" style="color: #FA8072">Lab talk on natural gradient descent for neural networks</a></li>
  <li> </li>
</ul>  

</details>

-----------------------------------------------------------------------------------

## Machine Learning

<details>
<summary>Multi-class classification of 100 class data</summary> 

<ul>
  <li> Project Page: <a href="https://sapanachaudhary.github.io/Multi-Class-Classification/" style="color: #FA8072">Multi Class Classification</a></li>
  <li> This project was done as a part of course on Introduction to Machine Learning. The train data
provided corresponded to a 100 class classification problem. We had to perform the
classification task resulting in the best mean F1-measure for the 100 classes.</li>
</ul>  

</details>

-----------------------------------------------------------------------------------

## Systems
  
<details>
<summary>Automatic Vehicle Speed Reduction using GPS</summary>

<ul>
  <li> With Divya BM, Meghana M, Rajehwari B</li>
  <li> <a href="https://github.com/SapanaChaudhary/SapanaChaudhary.github.io/blob/master/files/adaptive_vehicle_speed_monitoring.pdf" style="color: #FA8072">Project Report</a></li>
  <li> Achieving automatic vehicle speed monitoring and control with minimum add-ons ensures that the size and the
cost of the vehicle does not increase significantly. In this paper,
GPS has been used to achieve speed determination and speed
control based on the current vehicle location. The entire
geographical region has been divided into finite sized cells for
speed assignment. The system can be implemented in a variety
of vehicles right from auto rickshaw, taxis to the luxurious
SUVs. Also, the idea can be extended to dynamically change
the speed-limit of a cell based on the traffic density in the cell.</li>
</ul>  

</details>

<details>
<summary>RFID based Localization</summary> 

<ul>
  <li> With Meghana M, Srinivas A</li>
  <li> <a href="https://github.com/SapanaChaudhary/SapanaChaudhary.github.io/blob/master/files/inteliigent_hospital_emergency.pdf" style="color: #FA8072">Project Report</a></li>
  <li> In large hospitals handling emergencies on a day-to-
day basis, it is very important to locate and ensure the
availability of medical specialists in a timely manner. This is
especially significant in situations where doctors will have to
keep the mobile phones in ‘switch-off’ state in a few patient-
sensitive areas. In this paper, an RFID based system has been
developed to determine the location of medical specialists
inside the hospital and also to make automatic annunciations
only to the required locations. The RFID based application
developed in this work and the associated database for a
structured storage of entities aid in easy and efficient
functioning of the overall system. The system developed is very
robust and flexible enough to handle changing environment.</li>
</ul>  

</details>

<details>
<summary>Wireless Energy Meter Module Development</summary> 

<ul>
  <li>With Anushree Singh, Venkatesh Vadde</li>
  <li>Energy meters that can send their readings wirelessly to a centralised meter can be of great
use; in developing analytics for the energy consumption by heavy duty appliances in a given
area. We can plot energy usage to identify places for conservation.
In our project we have developed an Arduino based Energy Meter modules that would
transmit the ‘on’ and ‘off’ state of an appliance to the central meter. The active state of the
device is measured using a Current Transformer Sensor.</li>
</ul>  
</details>
  
<details>
<summary>WiFi Channel Modelling</summary> 

<ul>
  <li> With Kishan PB, Sthanuthan Ramakrishnan </li>
  <li> We collected WiFI AP data from two shopping areas in Bangalore and wrote matlab codes to generate channel models.</li>
</ul>  

</details>
