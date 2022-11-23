- <img src="https://latex.codecogs.com/gif.latex?O_t=\text { Onset event at time bin } t " /> 
- <img src="https://latex.codecogs.com/gif.latex?s=\text { sensor reading }  " /> 
- <img src="https://latex.codecogs.com/gif.latex?P(s | O_t )=\text { Probability of a sensor reading value when sleep onset is observed at a time bin } t " />
# Datasets from experiments

Three Datasets are collected from enumerated process list:

1)
From Example 4.1 in Dalen and Ruscio (2016)
* dimeg_input_exp_data.csv 

We consider the 3 state model presented in Di Meglio
et al. (2009), which was calibrated in Di Meglio et al.
(2010b), for reproducing the slugging regime present in
a real oil well located in the North Sea. 

y ∈ R := n
Bottom-riser pressure, [bar] ,
u ∈ R := n
Topside choke  [1]

2)
From Example 4.1 in Dalen and Ruscio (2019)
* dsrv_input_exp_data.csv

A Continuous
time fifth order nonlinear SSM, x˙ = DSRV(x, u),
with measurement Eq., y = x5, where DSRV.m is a
m-file function found in the Marine Systems Simulator
toolbox (Fossen and Perez (2004)). We will consider
the following SISO control case:
yk ∈ R := n
Pitch angle, [deg]
uk ∈ R := n
Stern angle, [deg]

3)
From Example 4.2 in Dalen and Ruscio (2019)
* miss_input_exp_data.csv

Consider a rocket, i.e. the continuous time sixth order
nonlinear SSM, x˙ = rocket(x, u), with measurement
where miss.m is a MATLAB m-file
function found in App. E. The m-file implementation
is based on the nonlinear SSM in Eqs. (40) and (44)
in Mracek and Cloutier (1997).
We will consider the following SISO control case:
yk ∈ R := n
Angle of attack, [deg]
uk ∈ R := n
Rudder angle, [deg]

References:

Dalen and Ruscio (2016):  https://www.mic-journal.no/PDF/2016/MIC-2016-1-4.pdf

Dalen and Ruscio (2019):  https://www.mic-journal.no/PDF/2019/MIC-2019-4-2.pdf
