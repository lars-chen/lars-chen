### Hello! I'm Lars Chen.


- I’m a recent MSc graduate at the Bernstein Center for Computational Neuroscience (BCCN), where I explored the application of machine learning and causal inference in clinical neuroimaging.
- My research focuses on leveraging deep learning and structural causal models to generate counterfactual brain images, improving personalized treatment analysis for neurological disorders.
- I did my master's thesis with Prof. Dr. Kerstin Ritter at Charité Universitätsmedizin, where I developed a model using causal inference to simulate treatment effects on 3D brain MRI data.

_______________________________________________________________________________________________________________________________________

### Highlighted Projects

#### [3D Neuroimaging Counterfactuals with Deep Structural Causal Models](https://github.com/lars-chen/3dscm)

<img src="https://github.com/user-attachments/assets/ccb8489c-c96c-4edd-8b18-fffae8719c8a" width="400"/>

This repository extends Deep Structural Causal Models (DSCMs) to 3D neuroimaging by generating a synthetic 3D MRI dataset via a diffusion model conditioned on ground‑truth SCM covariates and implementing lightweight 3D CNNs for causal inference. The 3D DSCM produces anatomically coherent counterfactuals that reflect interventions on variables in the causal graph, providing a benchmark for evaluating counterfactual validity in high‑dimensional data. 



#### [Fair Image Generation using  β‑intact-VAE](https://github.com/lars-chen/conv-beta-iVAE)

<img src="https://github.com/lars-chen/conv-beta-iVAE/blob/main/Images/t_age.png" width="400"/>

A convolutional adaptation of the β‑Intact‑VAE (Wu et al. 2021) for reducing spurious correlations in counterfactual image generation. Trained on the CelebA dataset, this model learns a prognostic score sufficient for treatment effect estimation and, by enforcing overlap between control and treatment distributions, yields fairer facial image counterfactuals under limited covariate overlap. 

 
#### [Safe Reinforcement Learning: High Dimensional MuJoCo Environments with Barrier Certificates](https://lars-chen.github.io/rl-blog/learning-barrier-certificates/) 

Mujoco Gym Environment      |  Observation Dimension    | Action Dimension
:-------------------------:|:-------------------------:|:-------------------------:
Pendulum                  						   		 |         3                                   |     1
Cartpole               								       |         4                                   |     1
<span style="color:green"> ***Double Inverted Pendulum***  </span>           | <span style="color:green">***11***</span>         |     1
<span style="color:green"> ***Hopper***                    </span>           | <span style="color:green">***11***</span>         | <span style="color:green">*3*</span>


Blog post on “Learning Barrier Certificates for High‑Dimensional MuJoCo Environments,” based on the Luo & Ma (2021) paper. 


#### [MCTS and Mini-Max Agents for Connect-4](https://github.com/lars-chen/MCTS_Connect4)

Developed as part of the Computational Neuroscience MSc coursework at BCCN Berlin, this project provides Python implementations of both MiniMax and Monte Carlo Tree Search agents adapted for Connect‑4. Includes profiling scripts, optional Numba acceleration, and a suite of tests to benchmark decision‑making performance in deterministic game settings.
