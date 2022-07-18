## Uncertainty calibration for group-equivariant Bayesian CNNs in radio galaxy classification.

*Unlike standard neural networks, which provide a point-wise prediction for each test sample, Bayesian neural networks provide a posterior probability distribution. This probability distribution can then be used to quantify the relative uncertainty/confidence with which each prediction is being made. However, the calibration of these uncertainties can be improved/degraded by making changes to the neural network model. In this project the student will investigate whether the introduction of different types of equivariance to isometries of the 2-d Euclidean group (i.e. the image plane) in the convolutional layers of a CNN affects the calibration of uncertainties when making predictions of radio galaxy classification in astrophysics. This project is suited to a student with a background in physics, maths or computer science. Existing experience with deep learning models is useful but not essential. The project will run in Python, using the PyTorch deep-learning library.*

---

### Work Plan

1. Literature review on group equivariant NNs, Bayesian CNNs, uncertainty calibration, and their existing applications in astrophysics;
2. Adapt models from arXiv:2102.08252 to output epistemic uncertainty values;
3. Adapt models from arXiv:2102.08252 to output aleatoric uncertainty values;
4. Evaluate the ECE and UCE for all models in arXiv:2102.08252;
5. Examine differences in ECE/UCE for different types of equivariance and compare to model performance;
6. Discuss and explain results.

#### Potential publications

* [MNRAS (or similar) astronomy paper on uncertainty calibration in FR classification](https://www.overleaf.com/4756255635rdcxgzpvbkbq)
* NIPS (or similar) workshop paper on uncertainty calibration as a function of equivariance

#### Useful Links

* [MiraBest PyTorch dataset](https://zenodo.org/record/4288837#.YtUMsS1Q00o)
* [NIPS Conference Papers](https://papers.nips.cc)
