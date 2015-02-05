JADE
====

current package url: https://github.com/jade-package/JADE

----


JADE packages surface hopping code, which is a a semi-classical approximation. 
It has been primarily used for simulations of ultrafast processes (femtosecond to picosecond time scale) in photoexcited molecules.

Newton-X uses the trajectory surface hopping method, a semi-classical approximation in which the nuclei are treated classically by Newtonian dynamics, while the electrons are treated as a quantum subsystem via a local approximation of the Time-dependent Schrödinger Equation. Nonadiabatic effects (the spread of the nuclear wave packet between several states) are recovered by a stochastic algorithm, which allows individual trajectories to change between different potential energy states during the dynamics.

an on-the-fly surface hopping code for nonadiabatic molecular dynamics of poly-atomic systems

This JADE code has been interfaced with Gaussian, Gamess, Turbomole.
the popular TDDFT/TDA has been interfaced, TDHF/CIS is also possible.
ADC(2)/CC2 is also interfaced with Turbomole.
the interface with the semi-emperical MNDO code is also implemented in this release.

The Langevin Dynamics is implemented now.


Some of the code is still in progress or in testing stage, which would be updated later, if possible.
addtional interface to Molpro, Q-CHEM et al., spin orbital coupling, ONIOM/QM/MM feature, force field based dynamics.



This code is mainly developed by Prof. Dr. Zhenggang Lan and co-workers at QIBEBT, Qingdao, China, in recent years.





