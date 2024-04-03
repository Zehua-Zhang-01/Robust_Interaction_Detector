# Robust_Interaction_Detector
Code and explanations for Robust Interaction Detector (https://doi.org/10.1016/j.spasta.2024.100814)

Robust Interaction Detector is a further test of 'Robust Geographical Detector' (RGD). Given the scenario of factor's interaction in geographical detector, can we still guarantee the growth of statistical association between variables with the increase of number of statistical groups?🤔

We are using the same 'change point detection' optimization algorithm in RGD to determine statistical groups that can show the maximum statistical association between variables. For optimization strategies, it is impossible to optimize two research targets at the same time. Thus, we make a change point detection on one variable, then the other. 

💻There is nothing changed in algorithms from RGD to RID, and we may use the code displayed in the RGD session.  
