# Helmholtz-energy
a modification to DoSPT in order to calculate Helmholtz energy
DoSPT is useful tool to calculate entropy, especially the entropy of organic system or materials containing organic particles. 
However, it does not support calculation of Helmoltz energy. 
Though entropy times temperature can be used instead in many occasions, we just want to make it more rigorous.
Here is a modification to the thermodynamic function of DoSPT. 
Just copy this thermodynamics.f90 to the src directory and then compile it following the DoSPT guide, nothing special to do.
