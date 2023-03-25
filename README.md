## Parameter Estimation using Metropolis-Hastings Algorithm (MCMC) 

Actual model
$$ \frac{d{\alpha}}{dt} = (K_1 + K_2 \alpha^m)(\alpha_{max} - \alpha)^n $$
where $\alpha$ is the degree-of-cure (between 0 and 1), $\alpha_{max} = 0.9$ is the maximum
degree-of-cure achieved in an isothermal scan. m, n are kinetic exponents
(unknowns), K1; K2 are the unknown kinetic parameters, described based of:
$$ K_i = A_i \exp(-E_i/RT) $$
where A_i and E_i are the frequency factors and activation energy. R is the universal gas constant
and T is the temperature (in Kelvin). 
The initial degree-of-cure ( $\alpha$ at time = 59.02002
seconds) is 0:01.

#### Problem
Using the MCMC algorithm and the experimental data given, compute
the K_i parameters for Equation (3) and visualize the uncertainty about
the response by taking several samples.