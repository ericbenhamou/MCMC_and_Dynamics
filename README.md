# MCMC_and_Dynamics

Practice with MCMC methods and dynamics (Langevin, Hamiltonian, etc.)

For now I'll put up a few random scripts, but later I'd like to get some common
code up for quickly testing different algorithms and problem cases.

- `standard_mcmc`: "Standard" or basic MCMC methods, mostly to get my feet wet
  in this. (Keep the file name like this since I reference it in [my BAIR blog
  post][1].)

- `hmc`: Hamiltonian Monte Carlo.

- `bnn`: Bayesian Neural Networks

Note: I adjusted the `bnn` directory so that I can more extensively test Tianqi
Chen's code with more random seeds. See the bash script there. **TODO**: get a
plotting script set up for that!

[1]:http://bair.berkeley.edu/blog/2017/08/02/minibatch-metropolis-hastings/
