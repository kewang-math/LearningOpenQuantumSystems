# LearningOpenQuantumSystems
## Guide to Codes
For example, for exp 25.4
* Learning algorithm: main2_runfmin.m
  * Optimization: runfminunc.m
  * Exact Solution: gen_mea_data2.m
  * Objective function value \phi and gradient: gradPhilsq2.m
* Initial Guess of \theta: genTheta.m
  * generate theta based on the distribution: gen_theta.m
* Generate initial density operator and observables: gen_rho.m, genManyA.m
* Separate \theta to Hamiltonian part and dissipative part: theta2tensor2.m
  * recover it: theta2vector2.m
* Draw Graphs based on the optimization outputs: Graphs.m

For exp 25.2
* Learning algorithm: main2_runfmin.m -> genManyA.m
  * Optimization: runfminunc.m
  * Exact Solution: gen_mea_data2.m ->
  * Objective function value \phi and gradient: gradPhilsq2.m
    * number of 2-local observables:
* Initial Guess of \theta: genTheta.m
  * generate theta based on the distribution: gen_theta.m
* Generate initial density operator and observables: gen_rho.m, genManyA.m
* Separate \theta to Hamiltonian part and dissipative part: theta2tensor2.m
  * recover it: theta2vector2.m
* Draw Graphs based on the optimization outputs: Graphs.m

Similarly, for exp 25.3
* Learning algorithm: main2_runfmin.m -> genManyA.m
  * Optimization: runfminunc.m
  * Exact Solution: gen_mea_data2.m ->
  * Objective function value \phi and gradient: gradPhilsq2.m
    * number of 2-local observables:
* Initial Guess of \theta: genTheta.m
  * generate theta based on the distribution: gen_theta.m
* Generate initial density operator and observables: gen_rho.m, genManyA.m
* Separate \theta to Hamiltonian part and dissipative part: theta2tensor2.m
  * recover it: theta2vector2.m
* Draw Graphs based on the optimization outputs: Graphs.m

For Fig2: Exp 19, to check the difference between first order and second order Euler methods
* Main program: SimulationValidation.m
  * Tools: gen_rho.m, genManyA.m
  * First Order Euler: semiEuler.m
    * theta2tensor.m
  * Second Order Euler: gen_mea_data1.m

  
