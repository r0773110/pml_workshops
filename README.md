# Workshops by the Probabilistic Mechanics Laboratory
Welcome to the PML Workshop repository. We use this repository to disseminate the results of our research and make them accessible to the broader scientific community.

The repository consists of the following Jupyter Notebooks:

### [1_simple_logistic_regression.ipynb](https://github.com/PML-UCF/pml_workshops/blob/main/1_simple_logistic_regression.ipynb):
- euler_example is a complete code implementation including the EulerIntegratorCell class, creation and training of the model as well as prediction on test data
- euler_save_training trains the imported model on training data and saves the model weights 
- euler_predict_only loads the model weights and predicts on test data
- model contains the EulerIntegratorCell class, the Normalization layer and the create_model function

### [2_PINN_sciann_Burgers.ipynb](https://github.com/PML-UCF/pml_workshops/blob/main/2_PINN_sciann_Burgers.ipynb):
- runge_kutta_example is a complete implementation of a Runge-Kutta integrator including model training and prediction 
- runge_kutta_save_training trains the trainable coefficients on the training data and saves the model weights
- runge_kutts_predict_only loads the saved model weights and predicts on test data
- model contains the RungeKuttaIntegratorCell class and the create_model function


### [3_hybrid_PINN.ipynb](https://github.com/PML-UCF/pml_workshops/blob/main/3_hybrid_PINN.ipynb):
- runge_kutta_example is a complete implementation of a Runge-Kutta integrator including model training and prediction 
- runge_kutta_save_training trains the trainable coefficients on the training data and saves the model weights
- runge_kutts_predict_only loads the saved model weights and predicts on test data
- model contains the RungeKuttaIntegratorCell class and the create_model function


## Further reading
- R. G. Nascimento and F. A. C. Viana, "[Cumulative damage modeling with recurrent neural networks](https://arc.aiaa.org/doi/full/10.2514/1.J059250)," AIAA Journal, Online First, 13 pages, 2020. (DOI: 10.2514/1.J059250).

- A. Dourado and F. A. C. Viana, "[Physics-informed neural networks for missing physics estimation in cumulative damage models: a case study in corrosion fatigue](https://asmedigitalcollection.asme.org/computingengineering/article-abstract/doi/10.1115/1.4047173/1083614/Physics-informed-neural-networks-for-missing)," ASME Journal of Computing and Information Science in Engineering, Vol. 20 (6), 10 pages, 2020. (DOI: 10.1115/1.4047173).

- Y. A. Yucesan and F. A. C. Viana, "[A physics-informed neural network for wind turbine main bearing fatigue](http://www.phmsociety.org/node/2736)," International Journal of Prognostics and Health Management, Vol. 11 (1), 2020. (ISSN: 2153-2648).
