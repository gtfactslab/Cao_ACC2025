<h1>Cao_ACC2025</h1>

This code supplements the ACC 2025 submission "Safe and Performant Control via Efficient Overapproximation of the Reachable Set Probability Distribution" by Michael E. Cao and Samuel Coogan.

<h2>Abstract</h2>

We consider a nonlinear system subject to an unknown state-dependent disturbance input and assume availability of state-dependent upper and lower bounds on the disturbance that hold with any user-prescribed probability available from, e.g., Gaussian Process estimation. Using methods from mixed monotone systems theory, we then propose an efficient technique for overbounding the probabilistic reachable set of the system for any prescribed probability. Next, we consider a reach-avoid control synthesis problem and propose using a weighted sum of reachability quantiles as the control objective in order to balance safety and performance. We show via a case study of a kinematic bicycle vehicle model that this approach generally outperforms using a single fixed probability bound. 

<h2>Notes on Repository</h2>

This repository assumes you have IPOPT installed, as well as the `immrax` library which can be found [here](https://github.com/gtfactslab/immrax). The scripts contained within this repository can be used to reproduce the results from the paper. 

For reference:

* The Monte Carlo case study can be reproduced via the `kinbike_distribution_montecarlo.ipynb` jupyter notebook
* The MPC case study can be reproduced via the `kinbike_distribution_mpc.ipynb` jupyter notebook
