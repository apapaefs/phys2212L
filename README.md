# phys2212L
Code for graphing for PHYS 2212L (Physics II Laboratory) @ Kennesaw State University

# Experiment 7: RLC Circuits
## Instructions

Click below to launch the repository in jupyter lab: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/apapaefs/phys2212L/HEAD)

Once the repository is open (it will take a while), in the file browser, double click ```RLC_resonance_fit.ipynb```. This will open the jupyter notebook.

First enter the parameters of the experiment at:

```
##################
# the parameters
# R and RL in Ohm
# L in Henry
# C in Farad
#################
```

To enter your experimental data, use the ```X``` and ```Y``` arrays below:

```
########################################################
# Your measurements go here: X is the frequency in Hz, #
# Y is the voltage across the resistor in Ohm          #
########################################################
```

Now execute the notebook either by pressing SHIFT+ENTER in all cells, or by pressing the "run" button at the top.

You should now have several parameters printed, as well as several calculations using the fit, e.g.:

```
theoretical f0= 919.0 Hz
Input data:
[ 410.2  510.2  610.2  710.2  810.2  860.2  910.2  960.2 1010.  1110.
 1210.  1310.  1410. ]
[0.481 0.671 0.926 1.249 1.547 1.622 1.63  1.581 1.504 1.319 1.154 1.018
 0.91 ]


R(fitted)= 999.4 Ohm
V_S(fitted)= 1.66 V
R_L(fitted)= 17.03 Ohm
L(fitted)= 0.309 H
C(fitted)= 9.956e-08 F
f1(from fit)= 683.0 Hz
f2(from fit)= 1210.0 Hz
BW(from fit)= 523.0 Hz
f0(from fit)= 907.0 Hz
```

There should be a RLC_resonance.fit.pdf file with the plot in the file explorer on the left. (Click on the directory again and it will appear).

You can right-click on the file and click "Download" to download it to your computer. 



