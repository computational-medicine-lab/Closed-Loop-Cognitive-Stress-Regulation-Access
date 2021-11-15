
# Instructions for use

**main.slx** is the main simulation file. There exist results for six simulated profiles. The model parameters required for environmental stimuli forcing function are found as **AMP.mat, N.mat, PHA.mat,** and **R.mat** data files. While running the simulation, use the corresponding model parameters on the `stimuli generator` block. For each subject, x_0 and alpha values should be updated in the `human brain` block. For each subject, initial values for x_0 and alpha veps_guess should be updated in the `KF` sub-block and `Bayesian Filter` block. In.fis and Ex.fis are associated with the inhibitory and excitatory fuzzy control systems, respectively that are used for closing the loop. Input "open-loop" will be zero to reflect the open-loop results.

For the new control design, please replace the whole controller block and use the designed block to take the estimated stress state from the "Bayesian filter" block and generate the required control signal.

# Citation

If you are using our work please cite the following papers:

Fekri Azgomi H, Wickramasuriya D.S., and Faghih R.T., “**State-Space Modeling and Fuzzy Feedback Control of Cognitive Stress**,” *The Annual International Conference of the IEEE Engineering in Medicine and Biology Society, Berlin, Germany, 2019.*


Fekri Azgomi H, Cajigas I, and Faghih R.T., “**Closed-Loop Cognitive Stress Regulation Using Fuzzy Control in Wearable-Machine Interface Architectures,**” *IEEE Access, 2021.*

**Bibtex**
```

@inproceedings{azgomi2019state,
title={State-space modeling and fuzzy feedback control of cognitive stress},
author={Azgomi, Hamid Fekri and Wickramasuriya, Dilranjan S and Faghih, Rose T},
booktitle={2019 41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC)},
pages={6327--6330},
year={2019},
organization={IEEE}
}

@article{azgomi2021closed,
title={Closed-Loop Cognitive Stress Regulation Using Fuzzy Control in Wearable-Machine Interface Architectures},
author={Azgomi, Hamid Fekri and Cajigas, Iahn and Faghih, Rose T},
journal={IEEE Access},
volume={9},
pages={106202--106219},
year={2021},
publisher={IEEE}
}
```
