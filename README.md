# Numerical-Optimization-Experiment-Linear_Search-GLL_Search-Newton_Method-Conjugate_Gradients-etc
Numerical Optimization Methods Experiment, including line search, GLL search, modified Cholesky decomposition, damped Newton method, quasi-Newton method, conjugate gradient method, and common test functions such as Extended Rosenbrock.

# Experiment Description
experiment1：<br />
<img src="https://github.com/user-attachments/assets/ba5e4a85-d728-49a7-aa34-4872551e64d2" width="400" /><br />
experiment2：<br />
<img src="https://github.com/user-attachments/assets/38b7c7cd-52a5-493b-8810-36961974e4c7" width="450" /><br />
### File Description:

- `damped_newton.py`: Damped Newton method, search criterion can be specified;
- `quasi_newton.py`: Quasi-Newton method, L-BFGS;
- `conjugate_gradients.py`: Conjugate gradient method, PRP+ and FR;
- `linear_search.py`: Monotone line search with strong Wolfe conditions;
- `GLL_linear_search.py`: GLL search;
- `utils.py`: Cholesky decomposition;
- `main.py`: Test functions and commands used in the first experiment. Automatic differentiation is used for the test functions in this part; manual differentiation is recommended for large-scale problems;
- `variably_dimensioned_function.py`, `discrete_boundary_function.py`, `extended_rosenbrock_function.py`: Three test functions used in the second experiment, manually differentiated;
- `More-Testing.pdf`: *Testing unconstrained optimization software*: Contains more test examples.



# Reference：
高立.数值最优化方法[M]. 北京,北京大学出版社,2014.8.<br />
刘浩洋, 户将, 李勇锋, 文再文.最优化计算方法[M].北京，高等教育出版社, 2023  <br />
Moré J J, Garbow B S, Hillstrom K E. Testing unconstrained optimization software[J]. ACM transactions on mathematical software (TOMS), 1981, 7(1): 17-41.
