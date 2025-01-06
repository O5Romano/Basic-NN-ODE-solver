# Basic-NN-ODE-solver

My simple implementation of a feedforward neural network that approximates the solution of the differential equation (with an initial condition) formulated in the following form: dy/dx=g(x,y). It may look like overkill for such a task; however, trying to find the solution when y is the variable—for example, instead of g(x,y)=exp(x), using g(x,y)=y—proves to be significantly more difficult for a neural network to train (even now it still cannot solve many equations).
