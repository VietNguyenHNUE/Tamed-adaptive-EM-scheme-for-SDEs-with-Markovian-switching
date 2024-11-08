This is the simulation results that we used to support our theoretical theorem in the paper "Uniform in time convergence of a tamed-adaptive Euler-Maruyama scheme for SDEs with Markovian switching, under non-Lipschitz conditions" (see https://vjol.info.vn/index.php/DHSPHN-KHTN/article/view/83092) for more details.
The code is not very technical, we basically calculate the discretized value of the tamed-adaptive E-M scheme to approximate the solution of the SDEwMS, which was presented quite clearly in our paper.
To see the convergence rate, we use the Monte-Carlo method to approximate the Expectation value of the error. This idea is shown through the function MSE that we mentioned in Section 4 of the paper.